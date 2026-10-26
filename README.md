# CS305
Software Security
I worked with Artemis Financial, a company that creates customized financial plans for savings, retirement, investments, and insurance. At Global Rain, I secured the company's RESTful web application against external threats while keeping its functionality intact.

I reviewed the Java source code and upgraded the Maven configuration from Spring Boot 2.2.4.RELEASE to 4.1.2. I used OWASP Dependency-Check 13.0.0 to evaluate third-party dependencies. The initial scan found 13 vulnerable dependencies and 151 vulnerabilities, but the final scan showed zero vulnerabilities across 56 entries, with 28 unique dependencies.

Key takeaways from the assessment included identifying dependency vulnerabilities, applying updates, and comparing security results before and after remediation. I also discovered a checksum verification flaw in which the expected checksum was incorrectly set to the generated checksum, sabotaging integrity verification. I maintained the existing SHA-256 functionality and the /hash endpoint while enhancing code maintainability.

For future assessments, I plan to review vulnerability advisories, prioritize findings by severity and business impact, check resolved dependencies, and conduct functional tests and repeated security scans. These practices align with Global Rain's belief that security is a collective responsibility.

The tools and practices I found most effective included OWASP Dependency-Check, Maven dependency management, manual code reviews, cryptographic hashing, and functional testing. To demonstrate my experience to potential employers, I can share several key materials: the vulnerability assessment report, before-and-after scan results, the updated pom.xml file, the refactored Java source code, and documentation on the checksum verification flaw. These documents highlight my expertise in secure coding, dependency remediation, and vulnerability assessment, showing how I helped Artemis Financial maintain secure, reliable software.
