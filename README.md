Summary of Client and Software Requirements
Client Overview

Artemis Financial is a financial services company that needed to enhance the security of their software systems. The client required an assessment of their current software infrastructure to identify and address any existing security vulnerabilities. The goal was to protect sensitive financial data and ensure compliance with industry regulations.

Software Requirements and Issues Addressed

Artemis Financial’s primary requirement was to secure their software applications by identifying vulnerabilities within their codebase and third-party dependencies. The main issue addressed was the presence of outdated and vulnerable dependencies that could potentially expose sensitive information or allow unauthorized access.

Response to Security Vulnerabilities
What Was Done Well

I effectively utilized the OWASP Dependency-Check Maven plugin to identify security vulnerabilities within the third-party libraries used by Artemis Financial's software. This automated tool allowed me to generate detailed reports on potential vulnerabilities and prioritize them based on their severity. I also refactored the code to replace or update insecure dependencies with more secure versions, aligning with best practices for secure software development.

Importance of Secure Coding

Coding securely is crucial to prevent vulnerabilities that can be exploited by malicious entities. Secure coding practices ensure that software is robust against attacks, protecting sensitive data and maintaining customer trust. For a company like Artemis Financial, secure software is essential to safeguarding client financial information and avoiding the reputational damage associated with security breaches.

Challenges and Lessons Learned
Challenging and Helpful Parts of the Vulnerability Assessment

One challenging aspect of the vulnerability assessment was identifying all outdated or insecure dependencies in the codebase. Many third-party libraries used in the project had multiple versions, and determining the safest and most compatible update required careful analysis. However, this challenge was also an opportunity to learn more about dependency management and the importance of maintaining an up-to-date and secure codebase.

Increasing Layers of Security

To increase security layers, I updated vulnerable dependencies to their latest stable versions and removed any unnecessary libraries that posed potential risks. Additionally, I applied security patches and enhanced the application’s configuration to ensure secure communications and data handling. In the future, I would continue to employ tools like OWASP Dependency-Check and incorporate additional automated security testing techniques, such as static and dynamic analysis, to ensure comprehensive vulnerability management.

Ensuring Functionality and Security
Ensuring Functionality and Security of Code

After refactoring the code to replace vulnerable dependencies, I performed extensive testing to ensure the application remained functional and secure. This included running unit tests, integration tests, and regression tests to confirm that the updates did not introduce new issues. I also reran the dependency checks to verify that all vulnerabilities had been effectively addressed.

Tools and Practices for Future Use
Resources, Tools, and Coding Practices

Key tools and practices used in this project, which will be valuable for future assignments, include:

OWASP Dependency-Check Maven Plugin: Used to automatically scan and identify vulnerable dependencies within the project.
Version Control and Dependency Management: Regular updates and patches to dependencies are essential for maintaining software security.
Secure Configuration Management: Ensuring that software configurations are secure and align with best practices.
Showcasing Skills to Future Employers
Demonstrating Skills and Knowledge

For future employment opportunities, I can showcase my ability to conduct thorough vulnerability assessments using automated tools and implement secure coding practices. The experience with Maven and dependency management, along with the demonstrated ability to update and secure third-party libraries, highlights my proficiency in maintaining secure and robust software applications. Additionally, my experience in writing effective tests to validate security and functionality is a critical skill for any software development role.
