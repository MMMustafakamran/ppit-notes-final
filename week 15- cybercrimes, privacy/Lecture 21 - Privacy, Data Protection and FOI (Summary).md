### Lecture 21 – Privacy, Data Protection and FOI (Summary)

#### 1. Why Data Protection Matters
- Modern apps, cloud services, IoT and AI **continuously collect personal data**, often stored globally.
- Data leaks harm users (fraud, discrimination), damage company reputation, and create serious legal risk.
- Global clients expect compliance with laws like **GDPR, CCPA, PDPL, HIPAA**, so privacy must be built into system design.

#### 2. What Is Privacy in Computing?
- **Privacy**: control over your personal information, identity, and personal space.
- Digital dimensions:
  - **Access control** – who can see/use your data.
  - **Usage control** – how your data is processed and shared.
  - **Exposure control** – what systems can infer about you.
- Elements:
  - **Personal boundaries** – solitude, anonymity, intimacy.
  - **Control over information** (“reserve”) – choosing what to share, with whom, and under what conditions.

#### 3. Core Data Protection Principles
- **Fair & lawful processing** – clear, honest reasons for collection; no hidden practices.
- **Purpose limitation** – collect for specific purposes and don’t reuse for unrelated ones without consent.
- **Data minimization** – only collect what’s necessary (avoid extra CNIC/GPS/contacts/etc.).
- **Accuracy** – keep data correct and updateable; wrong data leads to unfair or harmful outcomes.
- **Storage limitation** – no “store forever”; define retention and delete securely when no longer needed.

#### 4. Practical Developer Duties (Minimization, Accuracy, Retention)
- Design forms and APIs with **minimal fields**; keep permissions tight for apps and services.
- Provide **user edit/update flows**, validation and synchronization across microservices.
- Implement **expiry schedules**, automatic deletion of old logs/backups/inactive accounts, and secure wiping instead of soft-deletes only.

#### 5. Security Measures
- **Access control**: RBAC, least privilege, MFA for sensitive areas.
- **Encryption**: HTTPS/TLS in transit; encrypted databases and backups at rest.
- **Integrity & verification**: hashes, signatures, change logs, versioning, audit trails.
- **Backup & recovery**: regular backups, off‑site redundancy, tested disaster recovery.
- **Monitoring & breach response**: intrusion detection, anomaly alerts, incident runbooks, and timely legal notification.

#### 6. Article 19A & Freedom of Information (Pakistan)
- **Article 19A**: every citizen has the right to access information in matters of public importance, subject to reasonable restrictions.
- FOI / RTI laws (federal + provinces) let citizens request public records (spending, contracts, policies, decisions).
- Not accessible: national security/classified info, private citizens’ personal data, internal memos.
- For government IT systems: must support **transparency, record‑keeping, and lawful disclosure**.

#### 7. GDPR and Other Global Privacy Laws
- **GDPR (EU)**:
  - Scope: any organization processing EU residents’ data.
  - Rights: informed consent, access, deletion (“right to be forgotten”), portability, and 72‑hour breach notification.
  - Principles: fairness & transparency, purpose limitation, minimization, accuracy, storage limitation, integrity & confidentiality.
  - Penalties: up to **€20M or 4% of global turnover**; very large fines already imposed on major tech companies.
- **HIPAA (US health)**: protects **PHI** (health data) and requires policies, training, compliance officer, audits, enforcement and corrective actions.
- **CCPA (California)**: gives rights to know, delete, and opt out of data selling; requires clear notices; fines for mishandling.
- **UAE PDPL / Saudi PDPL**: strict consent, security, cross‑border transfer rules; special protection for sensitive data and strong user rights.

#### 8. Data Mining, Secondary Use, and Re‑Identification
- **Data mining**: ML/statistical analysis of large datasets for recommendations, ads, fraud detection, etc.
- **Secondary use**: using data for new purposes not originally disclosed (e.g., selling GPS trails, political micro‑targeting) → often illegal and always risky for trust.
- **Re‑identification**:
  - “Anonymous” datasets can be linked to other public or leaked data to identify individuals.
  - Netflix Prize case showed that supposedly anonymized movie ratings could be matched to IMDb profiles.

#### 9. Location Data, IoT and AI‑Based Surveillance
- **Location tracking**: GPS/Wi‑Fi/cell/Bluetooth reveal home, work, routines and habits.
- **IoT devices**: cars, wearables, smart homes continuously stream sensitive data; often shipped with weak security and cloud dependence.
- **Smart city surveillance**: ANPR, CCTV with facial recognition, toll and traffic systems create powerful, centralized datasets attractive to attackers and controversial for privacy.
- **AI‑based identification**:
  - Facial & voice recognition; biometrics (fingerprints, iris, gait, typing patterns).
  - Behaviour profiling infers interests, politics, shopping habits, and even health conditions.

#### 10. Privacy by Design & Secure Data Lifecycle
- **Privacy by Design**:
  - Build privacy into architecture from the start (minimal personal fields, secure APIs/DBs).
  - Default to privacy (opt‑in tracking, conservative permissions).
  - Be transparent (clear notices, easy‑to‑use privacy settings).
  - Limit internal access (RBAC, no blanket production access).
  - Secure data end‑to‑end (encryption, monitoring, deletion policies).
  - Test regularly (privacy impact assessments, pen‑tests, configuration reviews).
- **Secure Data Lifecycle**:
  - **Collect** only necessary data with clear notice.
  - **Store** securely with encryption and access control.
  - **Use** only for stated purposes.
  - **Share** only with trusted, compliant parties.
  - **Retain** only as long as needed under policy.
  - **Delete** securely across systems and, where possible, backups.

> **Exam/Project takeaway:** As a developer, you’re responsible for (1) collecting minimal personal data with clear purposes, (2) implementing strong security and lifecycle controls, and (3) aligning your systems with legal frameworks like GDPR, HIPAA, CCPA, PDPL and Pakistan’s FOI/Article 19A obligations.

 
