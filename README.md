# CS-305-Software-Security

Artemis Financial Practices for Secure Software Report

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
-Artemis Financial is a financial institution that seeks to upgrade their software security into a more current and up-to-date software security.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
-I updated any plugins or dependencies that needed updating. It's important to always use the latest version of software because a lot of security vulnerabilities come from outdated patches. Everytime software applications are updated, security vulnerabilities are patched so it's imperative to keep up-to-date. I also updated the library to JRE System Library [jdk-22] so that I can ensure my code works the way it's intended, without leaving vulnerabilities.
-It's important to code securely because some vulnerabilities are created from carelessness during the coding process. It is easy to prevent vulnerabilities before they become a problem.
-Software security prevents data breaches and data loss as well as other cyberattacks. Keeping the company's assets secure prevents reputational as well as financial damage. Also, different government regulations require companies to comply with security standards that govern how they keep their private data safe.

What part of the vulnerability assessment was challenging or helpful to you?
-I found generating a certificate authority that browsers trusted for https to be very challenging. No matter how hard I tried, I wasn't able to get any of my browsers to trust the certificate that I had generated on my computer. If I genuinely needed to do this for real world application, I would pay an actual service to have a certificate that could easily be verified.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
-One way I increased layers of security was to run a Maven Dependency Check to look for any known vulnerabilities that apply to my code. In order to make sure that there were no false positives, I made a suppression file that suppressed the false positives.
-One of the simplest mitigation technique that I used was to manually scan through my code and look for any errors that popped up. It seems fundamental, but it is very underrated to use your prior experience to judge what could be a problem.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
-In order to make sure the software application was functional and secure, I ran multiple tests to make sure that I would always get the correct output when I ran the code. I created my own test cases where I made sure I would always get the appropriate output in the localhost site.
-After refactoring the code, I ran the same test cases and they were successful. I also ran multiple maven dependency checks throughout the refactoring process to ensure no new vulnerabilities were created.


What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
-I used all resources available to me online. Discussing with my peers over SNHU's Discord server and coming up with solutions for issues in the console. Stack Overflow is also another website that I visit often to see how other peers code their checksum.java.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
-Generating Certificate Authority
-Utilizing hash functions and cryptography
-Maven Dependency Check
-Vulnerability Suppression
-Using Spring Boot to make a web application
-Updating Java System Libraries and Dependencies
-Creating a Checksum
