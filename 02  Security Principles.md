# security principles

## Learning objectives
- Understand the CIA Triad and its Importance
- Explain risk,Privacy and Accessiblilty
- Relate security principles to real world cyber incidents

# CIA Triad
- The CIA Triad forms the foundation of information security.
- Each element ensures that information remains safe and trustworthy.

| Element            | Description                                           | Example                                              |
| ------------------ | ----------------------------------------------------- | ---------------------------------------------------- |
| *Confidentiality*| Ensures data is accessible only to authorized users.  | Encrypying files,using passwords,access comtrol lists |
| *Integrity*      | Ensures data is accurate,consistent and not tempered with | Using hashings,digital signaturing,checksums     |
| *Availability*   | Ensures System and data are available when needed.    | Redundant servers,backups,DDos protections       |<img width="237" height="212" alt="download" src="https://github.com/user-attachments/assets/e4979918-4e3a-4add-93f8-10fadb2c1c7c" />


<img width="2037" height="2012" alt="download" src="https://github.com/user-attachments/assets/ebb8e91b-406d-414f-afe7-e28151edf1d1" />

##examples
- Confidentiality violation:Unaouthorized access to customer data(e.g, Favebook-Cambridge Analytic case).
- Integrity Violation:Tampered medical data in hospitals leading to misdiagnosis
- Availability violation: DDos attack on banking websites preventing service access


# Risk,Privacy and Accountability
## Risk
- Defenition: probability of a threat exploiting a vulnerability to cause harm
*components*
  - Threat-->something that can cause damage
  -  Vulnerability--> weakness that can be exploited
  -  Impact--> damage if threat is realized
*Formula*
  - Risk=Threat x Vulnerability x Impact
 
## examples
- Threat: phishing
- Vulnerability: Employee lack of awareness
-  Impact:Credential theft,financial loss
  
<img width="300" height="168" alt="images" src="https://github.com/user-attachments/assets/ddc0918d-9f02-4333-b8a5-f8950bdc55f9" />


# Privacy
- protecting personal and sensitive information of individuals
- Governed by Laws lik GDPR,DPDP Act (India),HIPAA.

![download](https://github.com/user-attachments/assets/d90d2bdb-1b01-4fa9-a87f-8e83952829eb)


## key practices:
- Data minimization
- Informed consent
- Data anonymization

Example: A healthcare app must not share user health data without consent

# Accountability
Ensuring every action in an IT system can be traced back to an induvidual.

## Achieved through:
- Logging & auditing
- Using access tracking
- Non-repudiation mechanisms


Example:Audit logs in firewalls to trace malicious user actions.


Real-Wolrd Case Studies


|        Case                  |           Description                           |           Violated Principle |
| ------------------ | ----------------------------------------------------- | ---------------------------------------------------- |
|WannaCry (2017)               | Ransomware disabled hospital systems worldwide  | Availability                 |
|Equifax Breach (2017)         | Personal data of  143M users leaked             | Confidentiality & Integrity|
|Twiter Hack (2020)            | Insider access to admin tools                   | Confidentiality & Accountability|
