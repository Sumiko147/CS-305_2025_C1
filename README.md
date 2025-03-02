# Author: Sumiko Mitchell
## Course: CS-305
## Date: 3/1/2025

**This README focuses on Project Two, while both Project One and Project Two documents have been included in the repository for reference and archival purposes.**

Artemis Financial (AF) is a fictional consulting firm that provides its customers with customized savings, retirement, investment, and insurance plans. They hired Global Rain to strengthen their web application using checksums to ensure the integrity and security of sensitive financial information data transfers. 

When I found Artemis Financia's security vulnerabilities, I implemented SHA-256 for checksum verification, converted HTTPS with SSL/TLS encryption, updated vulnerable dependencies, and updated their application with the proper cryptographic operations. Secure coding is essential because it protects data from breaches, ensures regulatory compliance with standards like ISO/IEC 27001 and the Gramm-Leach-Bililey Act, and maintains client trust, which is fundamental to AF's business integrity.

The most challenging aspect of the vulnerability assessment was learning to understand and interpret the dependency checker report due to the amount of information it provided. However, analyzing these reports helped me identify critical vulnerabilities in outdated dependencies like Spring Framework that could have compromised the entire system.

As I stated earlier, I increased security layers by implementing SHA-256 checksums, HTTPS with SSL/TLS encryption, and updated dependencies; in the future, I would continue using the OWASP Dependency-Check tool alongside manual code reviews and follow NIST guidelines to assess vulnerabilities and determine appropriate mitigation strategies. 

I conducted thorough functional testing of the refactored code to ensure functionality and security. I ran dependency checks before and after implementation to verify that I did not introduce new vulnerabilities during the security enhancement process.

I utilized OWASP Dependency Check, Java's cryptographic libraries, HTTPS/SSL implementation, and proper exception handling. I also followed NIST-approved security standards, practices, and tools that will be valuable in any future software security work.

I would show future employers my comprehensive security implementation for Artemis Financial, demonstrating my ability to identify vulnerabilities, implement industry-standard encryption (AES-256 and SHA-256), establish secure communications through HTTPS/SSL, follow regulatory compliance requirements, and verify security through rigorous testing—showcasing both technical security skills and understanding of financial industry security needs.

