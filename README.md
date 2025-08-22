# CS-305
1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a company that provides financial services through a web-based software application. The client needed help identifying and addressing security vulnerabilities in their software. They wanted to make sure their code was safe from cyberattacks and that customer information would be protected. My task was to run security tests and review the code to find weaknesses, then suggest ways to fix them.


2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I think I did well using both static testing tools and manual code review. I used OWASP Dependency-Check to scan for known issues and also looked through the code myself to catch things the tool might miss. It’s important to code securely because any weak spot could be used by a hacker to break into the system. When a company has secure software, it builds trust with customers and helps avoid costly data breaches or legal problems.


3. Which part of the vulnerability assessment was challenging or helpful to you?

Understanding the results from the dependency-check report was the most challenging at first. There was a lot of technical information, and I had to figure out what it meant and which issues were the most serious. But once I got the hang of it, it became a very helpful tool for learning about common vulnerabilities.


4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased layers of security by combining manual review with automated testing. I also looked at which third-party dependencies might be risky and thought about how to remove or update them. In the future, I would continue using tools like OWASP, and I would add more testing tools to get a deeper view of the security issues. I would also stay up to date on secure coding practices and patch vulnerabilities as soon as they’re discovered.


5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

After making changes, I ran the application in Eclipse to make sure it still worked properly. Then, I re-ran the OWASP Dependency-Check to confirm that I didn’t accidentally create new vulnerabilities while fixing the old ones. This helped ensure the software was both functional and secure.


6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I used Maven for managing dependencies and OWASP Dependency-Check for security scanning. I also practiced safe coding habits like avoiding hardcoded credentials and validating user input. These tools and practices are ones I’ll definitely bring into future coding projects.


7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show them my vulnerability assessment report because it highlights my ability to use industry tools, understand security risks, and fix problems in a real codebase. It shows that I take security seriously and can work through the process of identifying and solving technical challenges.
