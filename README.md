# CS 305 Project Reflection

## Artemis Financial Client Summary

Artemis Financial is a financial services company that wanted to improve the security of its software application. The company needed to protect sensitive customer financial information by strengthening communication between the client and server and identifying security vulnerabilities in its application. My role was to implement secure communication using HTTPS, generate a self-signed certificate, add a checksum verification feature to ensure file integrity, and perform a vulnerability assessment to identify and address security risks.

## Software Security Reflection

One thing I believe I did well was identifying security vulnerabilities using dependency-checking tools and implementing secure coding practices to reduce those risks. I successfully configured HTTPS with SSL/TLS, generated a certificate, and verified file integrity using SHA-256 hashing. Coding securely is important because it helps protect sensitive data, prevents unauthorized access, and reduces the likelihood of cyberattacks. Strong software security also builds customer trust, protects a company's reputation, and helps avoid costly security breaches.

The most challenging part of the vulnerability assessment was understanding which vulnerabilities required immediate attention and which ones could safely be suppressed because they were false positives or not applicable to the project. However, working through the OWASP Dependency-Check reports helped me better understand how to analyze vulnerabilities instead of simply trying to eliminate every warning.

To increase the application's security, I added encrypted HTTPS communication, implemented checksum verification, and ensured secure cryptographic algorithms were used throughout the application. In the future, I would continue using tools such as OWASP Dependency-Check, static code analysis tools, and regular dependency updates to identify vulnerabilities. I would also reference the OWASP Top 10 and industry best practices when deciding which mitigation techniques to implement.

After making security improvements, I verified that the application still functioned correctly by rebuilding the project with Maven, running the application successfully, and confirming that HTTPS communication worked as expected. I also reran dependency scans after refactoring the code to ensure that no new vulnerabilities had been introduced and that the application remained both functional and secure.

Throughout this project I used several resources that will continue to be valuable in future development work, including Maven, Spring Boot, Java Keytool, OpenSSL concepts, OWASP Dependency-Check, SHA-256 hashing, and secure coding best practices. Learning how to configure certificates, manage dependencies, and interpret vulnerability reports has given me practical experience that I can apply to future software projects.

For future employers, I would showcase this project as an example of my ability to improve application security while maintaining functionality. Specifically, I would demonstrate my experience implementing HTTPS with SSL/TLS, performing vulnerability assessments using OWASP Dependency-Check, generating digital certificates, implementing checksum verification with SHA-256, and applying secure software development practices throughout the software development lifecycle. This project demonstrates both my technical skills and my understanding of modern software security principles.

