### Lecture 22 – Computer Crimes, Cyber Offences and PECA 2016 (Summary)

#### 1. What Is Computer Crime and Why It’s Growing
- **Computer crime**: unlawful activity where a computer/digital device is a **tool**, **target**, or **storage medium** for the offence.
- Growth drivers:
  - Digital assets (banking, e‑commerce, fintech, crypto) are everywhere.
  - Automation (botnets, exploit kits, ransomware‑as‑a‑service).
  - Human weakness (phishing, social engineering, weak passwords).
  - Low risk, high reward: anonymity, cross‑border attacks, slow enforcement.
  - Technology (social media, AI, IoT, crypto) evolves faster than law.

#### 2. Evolution & Categories of Cybercrime
- From simple viruses/worms and basic hacking in the 1980s–2000s to:
  - Targeted data breaches, RaaS, AI‑based social engineering, deepfakes.
  - IoT and cloud/API attacks, state‑sponsored operations, zero‑day markets.
- Major categories:
  - **Unauthorized access & hacking** (password attacks, SQLi, XSS, session hijacking, privilege escalation).
  - **Data crimes** (theft, copying, alteration, leaks).
  - **Malware & ransomware**.
  - **Online fraud & financial crime** (phishing, scams, crypto fraud).
  - **Identity theft & impersonation** (CNIC/SIM/email/social accounts).
  - **Harassment, cyberstalking & blackmail**.
  - **Content offences** (revenge porn, CSAM, hate & extremist content).
  - **Cyber terrorism & critical infrastructure attacks**.
  - **Social engineering crimes** (deepfakes, AI voice calls, WhatsApp/OTP scams).

#### 3. Technical Attack Lifecycle & Footprinting
- **Footprinting / OSINT**:
  - Collect domain, IP, DNS, tech stack, leaked creds, employee info, public repos/docs.
  - **Passive** (no direct contact) vs **active** (scans/probes).
  - Goals: understand security posture, narrow focus, map networks, find vulnerabilities.
- Other core attacks:
  - Password attacks, MITM, network sniffing, web attacks, malware/ransomware, identity theft.

#### 4. Harmful Online Content, Hate Speech & Fake News
- Illegal/harmful content is persistent and amplified online; victims lose control after leaks.
- **Hate speech**: attacks on groups (religion, ethnicity, sect, nationality, race) ⇒ can spark real‑world violence.
- **Defamation**: false accusations, edited screenshots, rumours → reputational damage.
- **Fake news/misinformation**: altered media, fake breaking news, wrong info about exams/jobs → panic, mistrust.

#### 5. Jurisdiction & International Issues
- Cybercrime is **borderless**: victim, attacker, servers, and payments often in different countries.
- Legal questions:
  - Which country’s law applies? Where was the offence “committed”? Where is harm felt?
  - Extradition requires treaties and dual criminality; platforms might not cooperate.
  - Attacker anonymity (VPN/TOR/crypto) and conflicting privacy laws complicate investigations.

#### 6. PECA 2016 – Pakistan’s Cybercrime Law
- Purpose: define electronic offences, empower investigation/prosecution, protect citizens and **critical infrastructure**.
- Enforced by: **FIA Cyber Crime Wing**, special teams, designated cybercrime courts.

##### 6.1 Harassment & Personal Harm
- Offences: false info harming reputation/privacy; cyberstalking (incl. via hacked accounts); non‑consensual images; explicit content (especially involving minors); child sexual abuse material; cyberstalking of minors.
- Penalties: up to **3–7 years** and **Rs. 1–10M**, highest for offences involving minors and sexual content.

##### 6.2 Fraud, Forgery & Identity
- Offences: electronic fraud/forgery (incl. critical systems), unauthorized use of identity info, spoofing, spam, providing hacking tools, unauthorized SIM issuance.
- Penalties: months to several years and fines from **tens of thousands** to **millions of rupees**, depending on severity and target.

##### 6.3 System, Data & Critical Infrastructure
- Offences:
  - Unauthorized access, data copying/transmission, data interference, malware creation/spread, interception, device tampering.
  - Critical infrastructure access, data theft, and system damage.
  - Online hate speech, glorifying terrorism, terror recruitment/funding, **cyber terrorism**.
- Cyber terrorism carries the heaviest penalty: up to **14 years imprisonment** and **Rs. 50M** fine.

#### 7. Criticism of PECA
- Claimed to be **over‑broad and harsh**, with overlapping offences and disproportionate punishments.
- Vague wording and wide powers may allow misuse against journalists, activists and ordinary users, threatening **freedom of expression** and access to information.
- Surveillance criteria and content‑blocking powers are seen as too open‑ended and not sufficiently under independent/judicial control.
- Law mixes **cybercrime**, **cyberterrorism** and **cyberwarfare** in one framework, making it harder to distinguish ordinary online offences from national‑security threats.

> **Exam/Project takeaway:** Understand (1) how cybercrime works technically and psychologically (tool/target/medium, recon, social engineering), and (2) how **PECA 2016** classifies offences and penalties—including its limitations and criticisms—so you can design systems that **do not enable offences** and that handle evidence, logging, content, and user data in a legally sound way.

### Lecture 22 – Computer Crimes, Cyber Offences and PECA 2016 (Summary)

#### 1. What Is Computer Crime and Why It’s Growing
- **Computer crime**: any unlawful activity where a computer/digital device is a **tool**, **target**, or **storage medium** for the offence.
- **Growth drivers**:
  - Digital assets (banking, e‑commerce, fintech, crypto) are everywhere.
  - Automation (botnets, exploit kits, ransomware‑as‑a‑service).
  - Human weakness (phishing, weak passwords, social engineering).
  - Low risk, high reward: anonymity, cross‑border attacks, slow law enforcement.
  - Technology (social media, crypto, AI, IoT) evolves faster than law and policing.

#### 2. Evolution of Computer Crime
- **1980s–2000s**: simple viruses/worms, basic hacking, online fraud and piracy; includes Pakistan’s **Brain (1986)** virus.
- **2000s–2015**: targeted website/database hacks, botnets, DDoS, identity theft, phishing, online predators.
- **2015–2025**: large data breaches, RaaS, AI‑based social engineering, deepfakes, crypto/NFT scams, state‑sponsored operations, IoT and cloud/API attacks, zero‑day markets.
- **Key idea**: cybercrime mixes **tech + psychology + economics**, becoming a global, scalable business.

#### 3. Major Categories of Computer Crimes
- **Unauthorized access & hacking**: password attacks, SQLi, XSS, session hijacking, privilege escalation.
- **Data crimes**: theft, copying, leaks, alteration or destruction of data.
- **Malware & ransomware**: viruses, worms, trojans, spyware, encryption + ransom.
- **Online fraud & financial crime**: phishing/vishing, investment scams, auction fraud, credit card and crypto scams, Ponzi schemes.
- **Identity theft & impersonation**: misuse of CNIC, SIM, email, photos, social profiles.
- **Harassment, cyberstalking & blackmail**: threats, monitoring devices, leaking private images.
- **Content offences**: explicit content, revenge porn, CSAM, hate/extremist content.
- **Cyber terrorism & critical infrastructure attacks**: targeting telecom, NADRA, banks, energy, defence, healthcare.
- **Social engineering crimes**: deepfakes, AI voice cloning, fake verification calls, WhatsApp/OTP scams.

#### 4. Technical Attack Lifecycle – Footprinting and Core Attacks
- **Footprinting (recon/OSINT)**:
  - Collect domain, IP ranges, DNS, tech stack, leaked credentials, employee details, public repos/docs.
  - **Passive** (no direct contact) vs **active** (direct scanning/probing).
  - Goals: understand security posture, narrow focus, find vulnerabilities, map the network.
- **Technical methods**:
  - Domain/WHOIS + Netcraft to profile servers and stacks.
  - Port scanning and firewall mapping to find open services.
  - Password attacks, MITM, network sniffing (Wireshark).
  - Web attacks (SQLi, XSS, session hijacking), malware, ransomware, identity theft.

#### 5. Harmful Online Content: Hate Speech, Defamation, Fake News
- **Illegal content** becomes persistent and amplified online; victims lose control once it leaks.
- **Hate speech**: attacks on groups based on religion, ethnicity, sect, nationality, race → can trigger real‑world violence and division.
- **Defamation**: false statements (fake accusations, edited screenshots, rumours) harming reputation, often spread via WhatsApp/social media.
- **Fake news/misinformation**: altered images/videos, fake “breaking news”, wrong info about exams/jobs, causing panic, mistrust, and instability.

#### 6. Jurisdiction and International Issues
- Cybercrime is **borderless**: victim, attacker, servers, and payment can all be in different countries.
- Legal challenges:
  - Which country’s law applies? Where was the offence “committed” and where is harm felt?
  - Extradition needs treaties and dual criminality (crime in both states).
  - Platforms may not cooperate; attackers hide via VPNs, TOR, crypto.
  - Conflicts with privacy/data protection regimes (GDPR, CCPA, etc.).

#### 7. PECA 2016 – Pakistan’s Cybercrime Law
- **Purpose**: define electronic offences, enable investigation/prosecution, protect citizens and critical infrastructure.
- **Enforcement**: FIA Cyber Crime Wing, special investigation teams, designated cybercrime courts.

##### 7.1 Harassment & Personal Harm Offences
- False information harming reputation/privacy, cyberstalking (including via hacked accounts), non‑consensual images/videos, explicit content (especially of minors), and child pornography.
- **Typical penalties**: up to **3–7 years** imprisonment and **Rs. 1–10 million** in fines, with highest penalties for offences involving minors and sexual content.

##### 7.2 Fraud, Forgery & Identity Offences
- Electronic fraud and forgery (including critical systems), unauthorized use of identity info, spoofing, spam, providing hacking tools, unauthorized SIM issuance.
- Penalties range from **months to 7 years** and **tens of thousands to millions of rupees**, increasing with severity and impact.

##### 7.3 System, Data & Critical Infrastructure Offences
- Unauthorized access, data copying/transmission, data interference, malware creation/spread, interception, device tampering.
- Critical infrastructure: unauthorized access, data theft, and damage, plus online hate speech, glorifying terrorism, terror recruitment/funding, and cyber terrorism.
- **Cyber terrorism** has the heaviest penalty: up to **14 years** and **Rs. 50M**.

#### 8. Criticism of PECA
- Claimed to be **too harsh**, with disproportionate punishments and overlapping offences.
- **Vague wording** and broad powers may enable abuse by law enforcement and government.
- Concerns over **freedom of expression**, targeting of journalists and whistleblowers, and weak safeguards on surveillance.
- The enforcement authority is not fully independent and can block or remove content without sufficient judicial oversight.
- Critics say it fails to clearly separate **cybercrime vs. cyberterrorism/warfare**, mixing very different issues in one law.

> **Exam/Project takeaway:** Understand (1) how cybercrimes evolve and operate (tool/target/medium, technical + human angles), and (2) how PECA defines offences and penalties in Pakistan—along with its limitations and criticisms—so you can design secure, lawful systems and recognize legal risk.


