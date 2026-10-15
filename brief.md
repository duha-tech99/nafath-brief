Version: NAFATH-V4

Track: Software

## Overview
The national service provider contains sensitive information, including customer data. As a result, it needs to protect its systems from threats. IT fields help detect threats that can compromise systems. They also reduce security risks such as sniffing, phishing, and data tampering. IT fields cover software, artificial intelligence, mobile applications, networking, cybersecurity, and data. These fields examine different techniques to protect systems from manipulation and hacking. However, protecting systems does not guarantee that every attack will be prevented. Instead, it reduces risks and enhances the reliability of services. The expected result is to protect important data, build trust among system users, and ensure reliable services.

## Software
According to the Twelve-Factor App, application settings and credentials should be stored in environment variables. Examples include passwords, API keys, and database connection settings. They should be separated from the application code because settings vary depending on the deployment environment. Storing credentials in code may expose sensitive information when the project is shared or published.
Resource: The Twelve-Factor App - https://12factor.net/config

## AI
Adversarial machine learning involves attacks that try to make machine learning models produce incorrect results. Two main types are poisoning and evasion attacks. Poisoning attacks happen during training when an attacker changes the training data, causing the model to learn incorrect patterns. In contrast, evasion attacks happen after training, when an attacker manipulates input data to trick the model into making incorrect predictions. The main difference is when the attack happens and what is changed.
Resource: Adversarial Machine Learning: A Taxonomy and Terminology of Attacks and Mitigations - https://csrc.nist.gov/pubs/ai/100/2/e2025/final

## Mobile
The OWASP Mobile Application Security Verification Standard (MASVS) is a security standard used to assess mobile applications. It helps developers build secure apps and allows security testers to check whether an app meets security requirements. The standard covers areas such as data storage, cryptography, authentication, network communication, and privacy. Testers can use the OWASP Mobile Application Security Testing Guide (MASTG) to perform security tests and verify the app's security controls.
Resource: OWASP MASVS - https://mas.owasp.org/MASVS/

## Networking
BGP route hijacking occurs when an unauthorized network falsely announces IP address routes, causing internet traffic to be redirected to the wrong destination. RPKI helps prevent this by using cryptographically signed Route Origin Authorizations (ROAs) to verify which network is allowed to announce an IP prefix. However, standard RPKI origin validation does not verify the entire network path or prevent route leaks and IP packet spoofing, so additional security measures are needed.
Resource: NIST SP 800-189 – https://csrc.nist.gov/pubs/sp/800/189/final

## Cybersecurity
Log4Shell (CVE-2021-44228) was a critical security flaw in Apache Log4j2, a Java library utilized for recording application events. This vulnerability enabled attackers to remotely execute harmful code by sending specially crafted input to affected applications. With a CVSS score of 10.0, the highest possible severity rating, this issue posed a significant threat to system integrity. Apache resolved the problem by deactivating lookups by default in version 2.15.0 and eliminating JNDI lookup capabilities in version 2.16.0.
Resource: NVD – CVE-2021-44228: https://nvd.nist.gov/vuln/detail/CVE-2021-44228

## Data
A Software Bill of Materials (SBOM) is a formal record listing the software components, libraries, and dependencies used to build a software product. It improves software supply chain transparency and helps organizations identify vulnerable components. According to NTIA, the minimum required elements include supplier name, component name, component version, other unique identifiers, dependency relationships, SBOM author, and timestamp. These details help organizations track software components and manage security risks more effectively.
Resource: NTIA – The Minimum Elements for a Software Bill of Materials (SBOM) – https://www.ntia.gov/report/2021/minimum-elements-software-bill-materials-sbom

## Misconception in My Track
**Misconception: Good Programmers Must Memorize All Coding Syntax**
Many people believe that good programmers must memorize every programming language syntax and function. However, this is not true, Programming involves problem-solving and understanding how to build solutions, not just memorizing code. According to MDN Web Docs, professional web developers regularly use documentation to look up information they have forgotten.Programmers should therefore focus on understanding concepts, solving problems, testing their code, and learning how to find reliable information when needed.
Source: MDN Web Docs - Research and learning - https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Soft_skills/Research_and_learning

## Open Question
How can software developers design scalable and secure applications that maintain high performance as the number of users and amount of data increase?
