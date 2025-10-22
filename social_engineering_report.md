social_engineering_report.md
# An Analysis of Social Engineering Attacks: Phishing, Pretexting, and Baiting

**Author:** SHARVAN KOUL


**Course:** B.Tech in COMPUTER SCIENCE


**Institution:** JSPM RSCOE


**Date:** 22 OCT 2025


**Submitted for:** Internship Task 5 - Research Report on Social Engineering Attacks

---

## Abstract

This report examines the mechanisms of social engineering, a class of cyber attack that targets human psychology rather than technical systems. Focusing on three prevalent attack vectors—Phishing, Pretexting, and Baiting—the analysis deconstructs how threat actors manipulate fundamental psychological triggers to deceive individuals and compromise organizational security. The report finds that these attacks are effective because they exploit innate human tendencies such as trust, fear, and curiosity, often bypassing sophisticated technical defenses by leveraging legitimate communication channels and established business workflows. Case studies of recent Business Email Compromise (BEC) incidents highlight the severe financial and reputational damages that result, with losses scaling into the tens of millions of dollars without any technical system breach. The findings underscore that the human element remains a primary security concern, particularly as remote work models expand the digital attack surface. Consequently, this report concludes that an effective defense against social engineering requires a multi-layered strategy that integrates technical controls, robust policy enforcement, and a continuous, organization-wide commitment to employee security training and awareness.

---

## Table of Contents

* 1.0 Introduction to Social Engineering ................... [p. #]
* 2.0 The Psychology of Deception: How Attackers Exploit Human Nature ..... [p. #]
* 3.0 Major Types of Social Engineering Attacks ................... [p. #]
* 4.0 Case Studies in Business Email Compromise (BEC) ................... [p. #]
* 5.0 Analysis of Attack Patterns and Vulnerabilities ................... [p. #]
* 6.0 The Consequences of Successful Attacks ................... [p. #]
* 7.0 Multi-Layered Prevention Strategies ................... [p. #]
    * 7.1 Technical Controls ................... [p. #]
    * 7.2 Human Controls ................... [p. #]
    * 7.3 Policy Controls ................... [p. #]
* 8.0 Actionable Recommendations ................... [p. #]
    * Immediate Actions (0-1 Month) ................... [p. #]
    * Mid-Term Actions (1-6 Months) ................... [p. #]
    * Long-Term Actions (6+ Months) ................... [p. #]
* 9.0 Conclusion ................... [p. #]
* 10.0 References ................... [p. #]
* Appendix ................... [p. #]

  
## 1.0 Introduction to Social Engineering

This section defines the concept of social engineering and establishes its critical relevance in the modern cybersecurity landscape. By focusing on the manipulation of human behavior rather than the exploitation of software flaws, social engineering represents a unique and persistent threat. Understanding why attackers choose this method is the first step toward building effective defenses against it.

**Defining Social Engineering**
Social engineering is a form of "human hacking" where attackers deceive individuals to gain their information. Rather than breaking into a system using technical means, an attacker manipulates a legitimate user into willingly providing access or sensitive data. This approach targets people, exploiting their inherent trust and psychological tendencies to circumvent security protocols.

**Targeting the Human Element**
Attackers often target humans over systems because people can be more vulnerable and unpredictable than machines. User-level attacks are a primary concern for many threat types, as humans are susceptible to various strategies that make attacks difficult to detect and anticipate. Cybercriminals exploit established business workflows, timing, and trust to bypass technical security checks. For instance, an email from a compromised but legitimate account is unlikely to be flagged by automated filters, leaving the human recipient as the sole line of defense.

**Contemporary Relevance**
The relevance of social engineering has grown significantly in recent years. The global shift to remote work during the COVID-19 pandemic expanded the digital "attack surface" for many organizations as employees began working from home online. This change in work culture coincided with a sky-rocketing rate of cybercrime, making social engineering a more potent and frequent threat.

To fully understand these attacks and their effectiveness, one must first explore the psychological principles they are built upon.

---

## 2.0 The Psychology of Deception: How Attackers Exploit Human Nature

Social engineering is fundamentally an exploitation of human psychology. Its success hinges on an attacker’s ability to manipulate natural human responses and cognitive biases. This section deconstructs the key psychological triggers—trust, fear, urgency, curiosity, and authority—that attackers manipulate to bypass rational thought and persuade a target to take a desired action.

**Exploiting Core Psychological Triggers**

- **Trust:** Attackers build trust by creating a credible story or by impersonating a trusted entity. This can include posing as a senior leader, a member of the IT department, or a familiar vendor. The goal is to establish a sense of legitimacy that lowers the victim's guard. For example, a successful attack on a multinational firm was executed by inserting a fraudulent request into a genuine email thread between the company and one of its key suppliers, exploiting the pre-existing trust between the two parties.

- **Fear and Urgency:** Fear and a sense of urgency are powerful tools used to bypass a victim's rational thought processes. In pretexting attacks, an attacker might invent a scenario in which immediate action is required to avoid a negative consequence, such as an account being suspended or a financial penalty. This pressure convinces the victim to act quickly without questioning the request or verifying its authenticity.

- **Curiosity:** Humans are naturally curious, and attackers leverage this by presenting enticing offers or "bait." This often takes the form of an advertisement for a free download, an exclusive offer, or a link to seemingly interesting content. This technique, used in advertising-based attacks, lures victims into clicking on malicious links or opening infected files, which then activates malware.

- **Authority:** People are generally conditioned to comply with requests from figures of authority. Attackers exploit this by impersonating senior leadership, government agencies, or law enforcement. A request that appears to come from a CEO or a government agency is less likely to be questioned, making it a highly effective tactic for compelling employees to perform actions like transferring funds or providing confidential information.

These psychological tactics are the foundation for several distinct types of attacks, which will be detailed in the following section.

---

## 3.0 Major Types of Social Engineering Attacks

While the psychological principles behind social engineering are similar, the methods of execution vary. These methods, or attack vectors, are tailored to different communication channels and target behaviors. This section will define and differentiate three primary types of social engineering attacks: Phishing, Pretexting, and Baiting, providing clear examples for each.

### 3.1 Phishing

Phishing is a social engineering mechanism designed to gain vital information from users, such as usernames, passwords, and credit card details. The attacker typically masquerades as a trustworthy entity in an electronic communication. There are several specialized forms of phishing:

- **Spear Phishing:** A highly targeted form of phishing that focuses on a specific individual, organization, or group. The messages are customized with personal information to appear more credible.
- **Smishing:** A phishing attack implemented through short messaging services (SMS). The attacker sends a text message pretending to be a legitimate organization, like a bank or government agency, containing a link that directs the victim to a fraudulent website.
- **QRishing:** In this attack, a phisher distributes a Quick Response (QR) code, often disguised as a legitimate advertisement. When the victim scans the code, their device is directed to a malicious website designed to steal their information.

### 3.2 Pretexting

Pretexting is an attack driven by a fabricated scenario, or pretext, where an intruder builds a credible story to steal personal or organizational information. This method requires the attacker to create a detailed narrative that leaves little room for doubt. Pretexting attacks often manipulate emotions like fear and urgency while simultaneously building a sense of trust with the victim to convince them to provide the sought-after information.

### 3.3 Baiting

Baiting uses an enticement or "bait" to lure a victim into executing a malicious action. This is often seen in advertising-based attacks, where an advertisement on an authorized website hosts malware that activates when a user clicks on it. This technique is particularly difficult to detect because the malicious content is delivered through a legitimate advertising service, making the bait appear trustworthy.

**Comparison of Attack Types**

The following table summarizes the key characteristics of these three attack methods.

| Criteria | Phishing | Pretexting | Baiting |
| :--- | :--- | :--- | :--- |
| **Primary Method** | Deceptive emails, SMS, or QR codes with malicious links/attachments. | A fabricated scenario or story delivered via voice or email. | An enticing offer (e.g., free download, advertisement) that contains malware. |
| **Psychological Trigger** | Authority, Trust, Urgency | Trust, Fear, Urgency | Curiosity, Enticement |
| **Goal** | Steal credentials, financial data, or other sensitive information. | Obtain sensitive personal or organizational information through deception. | Trick the victim into activating malware on their system. |

The real-world impact of these methods is best understood by examining actual security incidents where they were successfully deployed.

---

## 4.0 Case Studies in Business Email Compromise (BEC)

This section analyzes three real-world incidents to illustrate the devastating financial impact and operational disruption caused by social engineering. These cases, all forms of Business Email Compromise (BEC), demonstrate how attackers exploit trust within established business processes to achieve their objectives without relying on malware or technical exploits.

**Case Study: Multinational Manufacturing Firm (2023)**

- **Attack Summary:** An attacker gained unauthorized access to the email account of a regional finance director at a large European manufacturing firm. The attacker then monitored the mailbox to understand the company's invoice workflows.
- **Timeline:** After identifying a recurring payment schedule with a key supplier, the attacker inserted themselves into a genuine email thread. Using the compromised director's account, they sent a PDF with updated banking instructions, directing a future payment to an attacker-controlled account.
- **Impact:** The attack resulted in the fraudulent redirection of a wire transfer, causing a financial loss of $25 million.
- **Lessons Learned:** This incident highlights how attackers can succeed by exploiting existing business workflows and the inherent trust between a company and its long-term suppliers. Because the fraudulent request came from a legitimate, albeit compromised, email account, it bypassed standard technical security checks.

**Case Study: Orion S.A. (2024)**

- **Attack Summary:** An employee at Orion S.A., a global specialty chemicals company, was deceived through social engineering into executing multiple fraudulent wire transfers.
- **Timeline:** The attack manipulated the company's internal financial processes, convincing the employee to send funds to accounts controlled by third-party criminals.
- **Impact:** The company reported a staggering $60 million loss. Notably, filings with the U.S. Securities and Exchange Commission (SEC) confirmed there was no evidence of unauthorized access to the company's data or systems.
- **Lessons Learned:** This case starkly demonstrates that catastrophic financial losses can occur without any technical breach of a company's systems. It underscores the extreme vulnerability of human-operated financial processes to sophisticated social engineering tactics.

**Case Study: NSW Government Department (2024)**

- **Attack Summary:** Cybercriminals impersonated a legitimate financial institution and used email-based deception to convince employees at a New South Wales (NSW) government department in Australia to alter payment details.
- **Timeline:** The attackers sent deceptive emails that led government staff to redirect funds intended for a legitimate recipient to accounts controlled by the criminals.
- **Impact:** The attack led to a loss of $2.1 million AUD.
- **Lessons Learned:** This incident shows that government bodies are high-value targets for BEC attacks. It also proves that simple email deception can defeat standard organizational processes if strict, out-of-band verification procedures are not mandated for changes to financial information.

A deeper analysis of these cases reveals common patterns and vulnerabilities inherent in many organizations.

---

## 5.0 Analysis of Attack Patterns and Vulnerabilities

Moving from specific cases to a broader analysis, this section identifies the common threads among these sophisticated attacks. It explores why even well-intentioned and trained employees become victims and underscores the strategic importance of combining security awareness with procedural validation to build a resilient defense.

**Common Patterns in BEC Attacks**

The case studies reveal several consistent patterns. All three incidents were forms of Business Email Compromise (BEC) that succeeded without deploying malware. Instead, the attackers exploited legitimate communication channels and deeply embedded business workflows. Key commonalities include:

- **Targeting Financial Processes:** The primary goal was direct financial theft through the manipulation of wire transfers and invoice payments.
- **Exploitation of Trust:** Attackers leveraged the trust inherent in business relationships—between employees, between departments, and between a company and its suppliers.
- **Impersonation and Legitimacy:** The attacks relied on impersonating a trusted party or using a legitimately compromised account, making the fraudulent communications appear authentic.

**Why Trained Employees Fall Victim**

BEC attacks are notoriously difficult to detect, even for trained employees, because the attacker’s behavior often mirrors the legitimate user’s context. These attacks do not target the email system's technical infrastructure; they target the business logic and trust that the system facilitates. An attacker operating from within an authenticated and compromised account appears as a legitimate user. Their requests, though malicious, align with normal business operations (e.g., updating an invoice, processing a payment), making them invisible to many technical security tools and difficult for a busy employee to question.

**The Importance of Awareness and Process Validation**

Because these attacks are designed to bypass technical defenses, the most effective countermeasures often involve robust, non-technical procedures. Security awareness training is a critical foundation, but it is not sufficient on its own. Organizations must supplement training with mandatory process validation. This includes:

- **Out-of-Band Verification:** Implementing a strict policy that requires verification through a secondary channel (such as a phone call to a known, trusted number) for any request to change financial information or approve a significant transaction.
- **Cultivating Healthy Skepticism:** Fostering an organizational culture where employees feel empowered to question unusual or urgent requests, especially those involving financial transactions, without fear of reprisal.

The failure to implement such multi-layered defenses leads to a predictable set of severe consequences for any organization.

---

## 6.0 The Consequences of Successful Attacks

The impact of a successful social engineering attack extends far beyond the initial incident. The consequences can be far-reaching, creating cascading effects that disrupt operations, erode trust, and inflict lasting financial and reputational harm. This section categorizes and details these major consequences.

- **Direct Financial Loss:** This is the most immediate and quantifiable consequence. As demonstrated in the case studies, successful attacks can result in multi-million dollar losses. The redirected funds stolen from Orion S.A. (60 million), the multinational manufacturing firm (25 million), and the NSW government department ($2.1 million AUD) serve as stark reminders of the direct financial stakes.
- **Data Loss and Theft:** Beyond financial theft, a primary goal of many social engineering attacks is to gain access to sensitive information. A successful attack can lead to significant data loss or the theft of intellectual property, trade secrets, and personal customer data.
- **Reputational and Trust Damage:** Security breaches erode confidence. Successful attacks can lead to diminished trust between customers and the enterprise. Internally, such incidents can also cause a decrease in staff morale, as employees may feel responsible for the breach or become anxious about future attacks.
- **Legal and Compliance Issues:** A significant security incident can trigger legal and regulatory obligations. As seen in the Orion S.A. case, the company was required to submit filings to the U.S. Securities and Exchange Commission (SEC). Depending on the industry and the nature of the data compromised, organizations may face regulatory fines, lawsuits, and mandatory public disclosures.

Now that the risks and consequences are clear, the report will shift to outlining concrete strategies for prevention and mitigation.

---

## 7.0 Multi-Layered Prevention Strategies

Since social engineering attacks target people, processes, and technology, a robust defense must address all three layers. A single solution is insufficient; resilience is built by combining technical, human, and policy-based controls. This section provides a structured overview of these controls that organizations can implement to protect themselves.

### 7.1 Technical Controls

Technical controls form the first line of defense by automatically filtering, blocking, or flagging malicious attempts before they reach an employee. They are designed to reduce the volume of threats and provide a safety net for human error.

- **Email Filtering and Boundary Protection:** These systems monitor and control communications at an organization's network boundaries. They are designed to identify and block malicious content, such as emails from known spam sources, attachments with malware, and links to phishing sites. (Reference: NIST SC-7). Effort: Medium.
- **Multi-Factor Authentication (MFA):** MFA requires users to provide two or more verification factors to gain access to an account. Even if an attacker steals a user's password, MFA can prevent unauthorized access, though organizations must be wary of social engineering tactics like "MFA fatigue," where attackers spam users with push notifications hoping for an accidental or frustrated approval. (Reference: NIST IA control family). Effort: Medium.
- **Domain Authentication (SPF/DKIM/DMARC):** These are email authentication protocols that help prevent email spoofing by verifying that an email claiming to come from a specific domain was indeed authorized by the owner of that domain. By verifying the authenticity of an email's origin, these methods help prevent spoofing, a primary vector for delivering malicious code (SI-3) and compromising information integrity (SI-7). Effort: High.
- **Domain Blacklisting:** This technique involves maintaining a list of known harmful websites or domains. When a user attempts to access a URL on the blacklist, access is blocked. This is one of the most commonly used methods for phishing detection. (Reference: "Phishing Attacks in Social Engineering: A Review"). Effort: Low.

### 7.2 Human Controls

Because attackers target human psychology, the most critical defense is a well-informed and vigilant workforce. Human controls focus on equipping employees with the knowledge and skills to become an active part of the organization's defense.

- **Security Awareness and Literacy Training:** All users should receive regular training on how to recognize and report suspicious activities. This training should cover common social engineering tactics, such as phishing emails, urgent requests, and impersonation attempts. (Reference: NIST AT-2). Effort: Medium.
- **Role-Based Training:** Personnel in high-risk roles—such as finance, human resources, and system administrators—require specialized, intensive training. This training should address the specific threats they are likely to face, such as invoice fraud or executive impersonation. (Reference: NIST AT-3). Effort: Medium.
- **Phishing Simulations:** Organizations should conduct regular phishing simulations by sending harmless, simulated phishing emails to employees. These exercises test their awareness, measure the effectiveness of training, and provide a practical learning experience in a safe environment. (Reference: NIST IR-2). Effort: High.

### 7.3 Policy Controls

Policies create a formal, enforceable structure for secure operations. They remove ambiguity, mandate safe procedures, and establish clear lines of responsibility, ensuring that security is integrated into daily business processes.

- **Financial Verification Procedures:** A formal policy should mandate out-of-band verification (e.g., a phone call to a known number) for any request to change payment information or approve large fund transfers. This single policy could have prevented all three attacks detailed in the case studies. Effort: Medium.
- **Incident Response Plan:** A documented incident response plan is essential. It should outline the specific steps for detection, analysis, containment, and recovery from a security incident, ensuring a swift and coordinated response when an attack occurs. (Reference: NIST IR-8). Effort: High.
- **Access Control and Least Privilege:** Policies should enforce the principle of least privilege, ensuring that users only have access to the information and systems absolutely necessary for their jobs. This limits an attacker's ability to move laterally or access sensitive data if they compromise a user's account. (Reference: NIST AC-6). Effort: High.

These strategies can be distilled into a set of actionable recommendations for organizations to implement over time.

---

## 8.0 Actionable Recommendations

This section translates the prevention strategies into a practical, time-phased implementation plan. The following 10 actions are categorized by their recommended deployment timeline to help organizations prioritize their efforts and build a comprehensive defense against social engineering attacks.

**Immediate Actions (0-1 Month)**

- **Mandate Out-of-Band Verification:** Immediately implement and enforce a policy requiring voice or in-person verification for all requests to change fund transfer details or approve payments above a specified threshold. This is the single most effective control against BEC.
- **Conduct an Awareness Briefing:** Hold a mandatory, organization-wide security briefing to review recent social engineering threats, share examples of malicious emails, and reinforce procedures for reporting suspicious activity.
- **Review Privileged Account Access Logs:** Conduct an immediate review of access logs for all privileged accounts (e.g., administrators, finance executives) to identify and investigate any atypical usage patterns or access times. (Reference: NIST AU-6).

**Mid-Term Actions (1-6 Months)**

- **Deploy Multi-Factor Authentication (MFA):** Roll out strong, phishing-resistant MFA across all critical systems, including email, VPNs, and financial applications. Avoid easily exploitable methods like simple push notifications.
- **Launch a Phishing Simulation Program:** Begin a program of regular, unannounced phishing simulation tests. Use the results to identify vulnerable departments or individuals and provide targeted follow-up training.
- **Implement Enhanced Email Filtering:** Deploy and properly configure advanced email boundary protection tools to better detect and quarantine spoofed emails, malicious links, and suspicious attachments. (Reference: NIST SC-7).
- **Formalize the Incident Response Plan:** Develop, document, and formally approve a comprehensive incident response plan. Ensure all stakeholders know their roles and responsibilities in the event of a social engineering attack. (Reference: NIST IR-8).

**Long-Term Actions (6+ Months)**

- **Implement a Zero Trust Architecture:** Begin a strategic initiative to adopt a Zero Trust security model. This approach is built on the principle of least privilege and requires continuous verification for all users and devices, significantly reducing the attack surface. (Reference: NIST AC-6).
- **Automate Security Monitoring:** Deploy automated security information and event management (SIEM) tools to enable continuous monitoring of network traffic and user behavior, allowing for faster detection of anomalies that could indicate a compromise. (Reference: NIST SI-4).
- **Establish a Continuous Training Culture:** Integrate security awareness into the entire employee lifecycle. Security training should be part of onboarding, supplemented by regular refresher courses and integrated into annual performance reviews to make it a permanent part of the organizational culture. (Reference: NIST AT family).

These recommendations, when implemented systematically, form a comprehensive defense that prepares an organization for the evolving social engineering threat landscape.

---

## 9.0 Conclusion

Social engineering remains one of the most significant threats to modern organizations precisely because it bypasses technology to exploit the human element—often the most accessible and persistent vulnerability. As this report has shown, attackers leverage deep-seated psychological triggers to manipulate well-intentioned individuals, turning them into unwitting participants in security breaches. The ongoing challenge of user-level intervention means that purely technical solutions will always be incomplete.

Effective cybersecurity is therefore not just a technological problem but a human and procedural one. The most resilient organizations are those that build a layered defense combining robust technical controls, clear and strictly enforced policies, and a deeply ingrained, security-aware culture. A vigilant, empowered workforce, supported by strong verification processes, is the ultimate defense against deception. By investing in people and processes with the same rigor applied to technology, organizations can significantly mitigate the risk posed by these pervasive threats.

Future research in this area should focus on adapting Machine Learning and AI-based techniques to develop more sophisticated systems for phishing detection. In parallel, new educational models are needed to provide users with deeper, more intuitive insights into recognizing scams and understanding the psychological tactics used against them, thereby hardening the human firewall.

---

## 10.0 References

- Adu-Manu, K. S., Ahiable, R. K., Appati, J. K., & Mensah, E. E. (2022). Phishing Attacks in Social Engineering: A Review. *Journal of Cyber Security, 4*(4), 239–267. https://doi.org/10.32604/jcs.2023.041095
- National Institute of Standards and Technology. (2020). *Security and Privacy Controls for Information Systems and Organizations* (NIST Special Publication 800-53, Rev. 5). U.S. Department of Commerce. https://doi.org/10.6028/NIST.SP.800-53r5
- Palo Alto Networks. (n.d.). *What Is Business Email Compromise (BEC)?* Retrieved October 27, 2023, from https://www.paloaltonetworks.com/cyberpedia/what-is-business-email-compromise-bec

---

## Appendix

**Psychological Triggers and Countermeasures**

The following table outlines the primary psychological triggers exploited by social engineers and provides an associated prevention tip for each.

| Psychological Trigger | Example of Exploitation | Associated Prevention Tip |
| :--- | :--- | :--- |
| **Trust** | An attacker impersonates a known supplier and sends an email with "updated" banking details for an invoice. | **Mandate Out-of-Band Verification:** Implement a policy requiring a phone call to a known contact to confirm any change in payment information. |
| **Fear** | A victim receives an email threatening account suspension or legal action unless they immediately click a link and "verify" their credentials. | **Security Awareness Training:** Train employees to recognize and report high-pressure or threatening language as a red flag for a phishing attempt. |
| **Urgency** | An email from a "senior executive" demands an immediate, "confidential" wire transfer to close a time-sensitive deal. | **Implement Financial Verification Procedures:** Establish clear, multi-step approval processes for financial transactions that are not bypassed for "urgent" requests. |
| **Curiosity** | An employee sees an online advertisement for a free, popular software tool and clicks the link to download it, which instead installs malware. | **Deploy Advanced Web Filtering:** Use technical controls to block access to known malicious websites and filter out attachments from untrusted sources. |
| **Authority** | A finance department employee receives an email that appears to be from their CEO instructing them to process an unusual payment without question. | **Role-Based Training:** Provide specialized training for finance and HR staff on recognizing and verifying executive impersonation attempts. |



