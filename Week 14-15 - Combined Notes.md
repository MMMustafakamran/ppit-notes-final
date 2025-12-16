### Week 14–15 PPIT Combined Notes

---

## Week 14 – Law & Intellectual Property

### Lecture 18 – Law (High-Level Overview)

- **Purpose of Law**
  - Maintains order, resolves disputes, protects rights and property, and sets standards of conduct.
  - Essential for regulating technology, contracts, cybercrime, and data protection.
- **Sources of Law in Pakistan**
  - **Constitution** – supreme law (fundamental rights, separation of powers).
  - **Legislation** – Acts/Ordinances passed by Parliament or provincial assemblies.
  - **Case Law (precedent)** – decisions of higher courts (Supreme Court, High Courts).
  - **Islamic Law principles** – influence personal and family matters and constitutional interpretation.
  - **Regulations** – rules by bodies like SECP, PTA, SBP, IPO‑Pakistan, etc.
- **Types of Law Relevant to IT**
  - **Civil law** (contracts, torts, IP, employment).
  - **Criminal law** (offences and punishments – e.g., PECA, PPC).
  - **Administrative law** (actions of regulators and government agencies).
- **Key IT‑Related Laws (examples)**
  - Prevention of Electronic Crimes Act 2016 (PECA).
  - Copyright Ordinance 1962.
  - Patents Ordinance 2000.
  - Trademarks Ordinance 2001.
  - Electronic Transactions Ordinance 2002.

---

### Lecture 19 – Judicial System of Pakistan (High-Level Overview)

- **Basic Structure**
  - **Supreme Court of Pakistan** – highest court; constitutional interpretation; final appeals.
  - **High Courts** (one per province + Islamabad) – hear appeals from lower courts and some original cases.
  - **District & Sessions Courts** – civil and criminal cases at district level.
  - **Special Courts/Tribunals** – e.g., banking courts, taxation, anti‑terrorism, cybercrime/PECA courts.
- **Key Concepts**
  - **Jurisdiction** – which court can hear which type of case (subject matter, territory, pecuniary).
  - **Appeal hierarchy** – decisions flow upward from trial courts → High Courts → Supreme Court.
  - **Due process** – fair hearing, right to counsel, evidence rules, and reasoned judgments.
  - **Judicial review** – courts can strike down laws or executive actions that violate the Constitution.
- **Relevance for Computing**
  - PECA and IP disputes are decided in **designated courts**, with appeals up the judicial chain.
  - Developers and companies must understand where to file complaints and how digital evidence is evaluated.

---

### Lecture 20 – Intellectual Property

#### 1. Property & Why IP Is Different
- **Tangible property** – physical objects (phone, laptop) protected by standard theft and damage laws.
- **Intangible property** – creations of the mind (code, designs, brands); can be copied without taking the original.
- Because copying does not deprive the owner of the original, **special IP laws** are needed instead of normal theft laws.

#### 2. What Is Intellectual Property (IP)?
- Creations of human intellect:
  - Software/source code, documentation, multimedia.
  - Literary, artistic, musical and audiovisual works.
  - Scientific and technical designs, formulas, inventions.
  - Logos, symbols, brand identities, domain names.
- **Goal**: encourage innovation and creativity by granting **exclusive rights** for a limited time.

#### 3. Main IP Types (with Computing Focus)
- **Copyright**
  - Protects **expression**, not ideas.
  - Covers: code, UI, documents, images, videos, databases, websites, e‑learning content.
  - Rights: reproduction, distribution, public display, public performance, derivative works.
  - Ownership: normally the creator; can shift to employer (work for hire) or via contract/licensing.
  - Duration in Pakistan: **life of author + 50 years**, or 50 years from publication for anonymous/corporate works.
- **Trademarks**
  - Protect signs that identify source: names, logos, slogans, icons, trade dress.
  - Crucial for software product names, app icons, and company branding.
- **Patents**
  - Protect **new, inventive, industrially applicable** inventions (processes, machines, products, improvements).
  - Pure algorithms or “software as such” often not patentable; only technical‑effect solutions may qualify.
- **Trade Secrets**
  - Confidential information with commercial value (algorithms, internal architecture, client lists, ML models).
  - Protection requires secrecy measures (NDAs, access control) and lasts as long as confidentiality is preserved.
- **Geographical Indications (GI)**
  - Names like *Basmati* or *Darjeeling* linked to geography; relevant to food/handicrafts, not software.

#### 4. Multiple IP Protections for One Software Product
- **Copyright** – code, documentation, UI, website, media.
- **Patent** – novel technical method or protocol.
- **Trade secret** – internal logic, model weights, tuning, architecture.
- **Trademark** – app name, logo, visual identity.
- **Design protection** – aesthetic aspects (icons, shapes, GUI look, packaging).

#### 5. Protecting a Startup / FYP
- Use **copyright** automatically for all original code and content.
- Consider **patents** for truly innovative technical solutions (after checking patentability).
- Keep core algorithms/internal tools as **trade secrets** behind NDAs.
- Register **trademarks** early for your product/company name and logo.
- Understand Pakistan’s IP laws and global treaties (TRIPS, Berne, Paris, WIPO) that affect international protection.

---

### Exam Tips (Week 14)
- **Q1 MCQs**: Know what jurisdiction means; civil courts under High Courts (true); legislative process = National Assembly + Senate; succession is civil law; trademark vs. domain; unauthorized copying is illegal/unethical.
- **IP recall**: Copyright protects expression (code/UI/docs/media), not ideas; life + 50 years; trademarks for names/logos; patents need novelty + inventiveness + industrial application (pure software/algorithms often excluded unless technical effect); trade secrets need secrecy.
- **Law vs. ethics**: Moral principles ≠ law; legality doesn’t guarantee ethicality.
- **Short answers**: For indemnity, cost-plus vs. fixed price—keep 3–4 crisp points (from study guide).

---

## Week 15 – Privacy, Data Protection, FOI, Cybercrime & PECA

### Lecture 21 – Privacy, Data Protection and FOI

#### 1. Privacy & Modern Data Ecosystem
- **Privacy**: control over personal information, identity, and personal space.
- Digital privacy dimensions:
  - **Access control** – who can see/use your data.
  - **Usage control** – how your data is processed and shared.
  - **Exposure control** – what systems can infer about you.
- Modern ecosystem:
  - Massive data from apps, sensors, IoT, social media, cloud, and AI.
  - Data stored globally; AI can analyse behavior, biometrics, and movement patterns.
  - Developers have increased responsibility to design with privacy and security in mind.

#### 2. Core Data Protection Principles
- **Fair & lawful processing** – clear, honest reasons for data collection; no dark patterns.
- **Purpose limitation** – use data only for the **specific** purpose explained to users.
- **Data minimization** – collect only what is necessary (avoid unnecessary CNIC, GPS, contacts, etc.).
- **Accuracy** – keep data correct and updateable; wrong data can cause unfair decisions.
- **Storage limitation** – no “store forever”; define retention periods and delete safely.

#### 3. Security Measures for Protecting Data
- **Access control** – RBAC, least privilege, MFA for sensitive data.
- **Encryption** – in transit (TLS/HTTPS) and at rest (DB/backups).
- **Integrity & verification** – hashes, signatures, change logs, audit trails.
- **Backup & recovery** – regular backups, redundancy, disaster‑recovery plans.
- **Monitoring & incident response** – detect intrusions, respond quickly, meet legal breach‑notification deadlines.

#### 4. GDPR and Other Global Privacy Laws
- **GDPR (EU)**:
  - Applies to any company handling **EU residents’ data**, even outside EU.
  - Rights: informed consent, access, correction, deletion (“right to be forgotten”), portability, and 72‑hour breach reporting.
  - Principles: fairness & transparency, purpose limitation, minimization, accuracy, storage limitation, integrity & confidentiality.
  - Heavy fines (up to €20M or 4% global turnover); major tech firms have been fined heavily.
- Other key laws:
  - **CCPA** (California) – rights to know, opt‑out of sale, and receive clear disclosures.
  - **HIPAA** (US health) – protects PHI; requires policies, training, audits, and sanctions.
  - **UAE PDPL / Saudi PDPL** – strict consent, security, cross‑border transfer rules; strong user rights.

#### 5. Pakistan – FOI & Article 19A
- **Article 19A (Constitution)** – citizens have the right to access information on matters of public importance, subject to reasonable restrictions.
- **FOI / RTI laws** (federal and provincial) enable public access to records on:
  - Public spending, contracts, policies, decisions.
  - Records affecting citizens or public interest.
- Restrictions:
  - Classified/national security data, private citizens’ personal data, internal government memos.
- Implications:
  - Government systems must support **transparency, record‑keeping, and lawful disclosure**.

#### 6. Data Mining, Secondary Use & Re‑Identification
- **Data mining** – using statistics/ML to find patterns (classification, clustering, association rules, prediction).
- **Secondary use** – reusing collected data for new purposes without consent (e.g., selling GPS data, political targeting).
  - Often violates GDPR/CCPA/PDPL and erodes user trust.
- **Re‑identification** – supposedly anonymous datasets can be linked with other data to identify individuals.
  - Netflix Prize case: researchers deanonymized “anonymous” Netflix ratings by matching to public IMDb profiles.

#### 7. Location, IoT & AI‑Based Surveillance
- **Location tracking** – GPS, Wi‑Fi, cell towers, Bluetooth reveal home/work/routines.
- **IoT devices** – cars, wearables, smart homes constantly collect sensitive data; weak security is common.
- **Smart city surveillance** – ANPR, CCTV with facial recognition, toll and traffic systems; large central databases increase risk.
- **AI‑based identification**:
  - Facial/voice recognition, biometric analysis (fingerprints, iris, gait).
  - Behaviour profiling (interests, shopping, politics, health) raises deep ethical and privacy concerns.

#### 8. Privacy by Design & Secure Data Lifecycle
- **Privacy by Design principles**:
  - Build privacy into system architecture from the start.
  - Default to privacy (off by default for tracking/permissions).
  - Be transparent and give users clear choices and controls.
  - Limit internal access with RBAC; no blanket access to production.
  - Secure data through encryption, monitoring, deletion and retention policies.
  - Regularly test with privacy impact assessments and pen tests.
- **Secure data lifecycle**:
  - **Collect** only what’s necessary with clear notices.
  - **Store** securely with access controls.
  - **Use** strictly for the stated purposes.
  - **Share** only with trusted, compliant parties.
  - **Retain** only as long as needed.
  - **Delete** securely, including from logs/backups where feasible.

---

### Lecture 22 – Computer Crimes, Cyber Offences & PECA 2016

#### 1. What Is Computer Crime and Why It’s Growing
- **Computer crime** – unlawful activity where a computer/digital device is a **tool, target, or evidence medium**.
- Growth factors:
  - **Digital assets**: banking, e‑commerce, fintech, crypto, freelancing.
  - **Automation**: botnets, exploit kits, ransomware‑as‑a‑service.
  - **Human weakness**: phishing, social engineering, weak passwords.
  - **Low risk, high reward**: anonymity (VPN, TOR, crypto) and cross‑border operations.
  - **Law lagging tech**: new platforms (social media, AI, IoT, crypto) outpace legislation.

#### 2. Evolution of Computer Crime
- **1980s–2000s** – simple viruses/worms, basic hacking, piracy, credit card theft; includes Pakistan’s *Brain* virus (1986).
- **2000s–2015** – targeted hacking, botnets, DDoS, identity theft, phishing, online predators.
- **2015–2025** – mass data breaches, RaaS, AI‑driven social engineering, deepfakes, crypto/NFT scams, IoT and cloud/API attacks, state‑sponsored operations.

#### 3. Major Categories of Computer Crimes
- **Unauthorized access & hacking** – password attacks, SQLi, XSS, session hijacking, privilege escalation.
- **Data crimes** – theft, copying, leaks, alteration, destruction, DB breaches.
- **Malware & ransomware** – viruses, worms, trojans, spyware, ransomware with extortion.
- **Online fraud & financial crime** – phishing/vishing, investment scams, auction fraud, credit card/crypto scams, Ponzi schemes.
- **Identity theft & impersonation** – misuse of CNIC, SIM, email, photos, social profiles.
- **Harassment, cyberstalking & blackmail** – threats, device monitoring, leaking private images.
- **Content‑related offences** – explicit material, revenge porn, CSAM, hate/extremist content.
- **Cyber terrorism & critical infrastructure attacks** – targeting telecom, NADRA, banks, energy, defence, healthcare.
- **Social engineering crimes** – deepfakes, AI voice cloning, fake “verification” calls, WhatsApp/OTP scams.

#### 4. Technical Attack Lifecycle & Footprinting
- **Footprinting / Reconnaissance (OSINT)**:
  - Collect domain, IP ranges, DNS, tech stack, leaked credentials, employee info, public repos/docs.
  - **Passive** (no direct contact) vs **active** (scans, probes).
  - Goals: map systems, identify vulnerabilities, focus attack surface.
- Other core techniques:
  - Password attacks, MITM, sniffing (Wireshark), web attacks (SQLi, XSS, session hijacking), malware, ransomware, identity theft.

#### 5. Harmful Online Content: Hate Speech, Defamation, Fake News
- **Illegal content** persists online and is amplified by platforms; victims lose control after leaks.
- **Hate speech** – attacks on groups by religion, ethnicity, sect, nationality or race; can incite real‑world violence.
- **Defamation** – false statements (fake accusations, edited screenshots, rumours) harming reputation.
- **Fake news/misinformation** – altered media, fake “breaking news”, wrong info on exams/jobs; leads to panic and mistrust.

#### 6. Jurisdiction & International Issues
- Cybercrime is **borderless**: victim, attacker, servers and payments may all be in different countries.
- Issues:
  - Which country’s law applies? Where is the offence “committed” and harm felt?
  - Extradition needs treaties and dual criminality.
  - Platforms may not cooperate; attackers hide behind VPNs/TOR/crypto.
  - Evidence and privacy standards differ (GDPR/CCPA vs local rules).

#### 7. PECA 2016 – Pakistan’s Cybercrime Law
- **Purpose**: define electronic offences, empower investigation/prosecution, protect citizens and critical infrastructure.
- **Enforcement**:
  - FIA Cyber Crime Wing, special investigation teams, and designated cybercrime courts.

##### 7.1 Harassment & Personal Harm
- Offences:
  - False info harming reputation/privacy.
  - Cyberstalking (including via hacked accounts).
  - Non‑consensual images/videos.
  - Explicit content, especially involving minors, and child sexual abuse material.
- Penalties:
  - Up to **3–7 years** and **Rs. 1–10M**, higher for offences involving minors and explicit content.

##### 7.2 Fraud, Forgery & Identity
- Offences:
  - Electronic fraud and forgery (incl. critical systems).
  - Unauthorized use of identity information.
  - Spoofing and spam.
  - Providing hacking tools.
  - Unauthorized issuance of SIM cards.
- Penalties:
  - From months to several years and fines from **tens of thousands** to **millions of rupees** depending on severity.

##### 7.3 System, Data & Critical Infrastructure
- Offences:
  - Unauthorized access, data copying/transmission, data interference, malware creation/spread, interception, device tampering.
  - Critical infrastructure access, data theft, and damage.
  - Hate speech, glorifying terrorism, online terror recruitment/funding, and **cyber terrorism**.
- Penalties:
  - Severe sentences, with **cyber terrorism** up to **14 years** imprisonment and **Rs. 50M** fine.

#### 8. Criticism of PECA
- Alleged **over‑breadth and harsh penalties**; overlaps with existing laws.
- **Vague language** allows potential abuse by law enforcement and government.
- Concerns about **freedom of expression**, impact on journalists, whistleblowers, and online speech.
- Weak safeguards for surveillance and content blocking; authority is not fully independent of the executive.
- Does not clearly separate **ordinary cybercrime** from **cyberterrorism/warfare**, mixing very different threats in one law.

---

### Exam Tips (Week 15)
- **Q1 MCQs**: Data mining (pattern analysis), collaborative filtering (recs), micro-targeting (target groups), business attacks purpose, jurisdiction challenges (borderless, extradition, anonymity, crypto, multi-country servers).
- **Q2 (Ethical Decision Making)**: For privacy/bias/cybercrime scenarios—use the 4-step model; stakeholders include users, org, regulators, society. Apply Consequentialism, Rights/Duties (fairness, privacy), Deontology (universalize? respect persons).
- **PECA recall**: Tool/target/evidence; major offence buckets (harassment, fraud/forgery/identity, system/data/critical infra); cyber terrorism up to 14 years/50M; criticisms: vague/harsh/overbroad, expression concerns, overlap with other laws.
- **Privacy principles**: Fair/lawful, purpose limitation, minimization, accuracy, storage limitation; security controls (RBAC, MFA, encryption, logging, IR).
- **Global laws**: GDPR rights (consent, access, correction, deletion, portability, 72h breaches), CCPA opt-out, HIPAA PHI protections, PDPLs (consent, security, transfers).
- **FOI/RTI (Art.19A)**: Right to information on public importance, with reasonable restrictions (security, personal data, classified/internal memos).

---


