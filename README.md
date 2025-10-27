# CS305-ProjectTwo
Deploying a cryptographic cypher in JAVA for CS-305 Software Security


Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
The client was Artemis Financial, a financial services company that needed to secure its web application to protect client data. The company wanted me to identify and fix software security vulnerabilities, focusing on encryption, checksum verification, and secure communications.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I did well at identifying weak encryption and outdated dependencies, then refactoring the code to use SHA-256 hashing and a secure SSL certificate. Secure coding protects sensitive information, prevents breaches, and builds client trust. Strong software security also ensures business continuity and legal compliance.

Which part of the vulnerability assessment was challenging or helpful to you?
The challenging part was analyzing dependency-check reports and verifying which vulnerabilities were real. The most helpful part was learning how to prioritize high-risk issues efficiently.


How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased security by implementing SHA-256 for checksums, generating an SSL certificate for HTTPS, and validating all inputs to prevent injection attacks.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I ran JUnit tests to confirm functionality and used dependency-check scans to verify that no new vulnerabilities appeared after refactoring. I reran the OWASP Dependency-Check tool and reviewed all scan results to confirm that all previous vulnerabilities were resolved and no new ones were added.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?\
I used Spring Boot, JUnit, SHA-256 hashing, SSL certificates, and OWASP Dependency-Check, all of which are essential for building secure applications.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show screenshots of the secure checksum verification, dependency-check report results, and refactored SHA-256 and SSL code to demonstrate my skills in secure software development.
