# Practices-for-Secure-Software-Report

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address? 

	Artemis Financial is a financial consulting company that develops financial plans for their customers. The plans range from checking, savings, retirement and investments. Artemis Financial aims to modernize their software and security for their customers. Taking a closer look at web-based applications,  Artemis Financial would like my development team to address all security vulnerabilities presented within their software.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing? 

	I was able to identity all known software vulnerabilities and researched how to patch or update the code to remedy the 16 vulnerabilities found. Updating code or applying patches helps to mitigate code from breaking and reduce code error. Software security protects the company as a whole and all connected associations such as customers or vendors. Comprised data from Artemis Financial can bleed over into associated transitions within the company such as vendor purchases or customer transactions.
	The importance of software security lies in the need to prevent or mitigate malicious attacks on sensitive data. This varies from customers personal information (debit/credit card or address) or company secrets (employee information or vendor information). A security breach on the systems could cause a backlash of trust from both customer and vendors. If security is put to the side or neglected throughout development; customers could potentially look elsewhere for financial planning competitors.

What part of the vulnerability assessment was challenging or helpful to you? 

	Performing the dependency check for the vulnerability assessment itself was easy to understand and starlight forward. The tricky part is how to address the vulnerabilities without editing to much code and introducing new vulnerabilities. Researching solutions of the vulnerabilities indicated patching and updating software regularly to avoid errors and mitigate malicious attacks. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use? 

	The first step to increase layers of security, is a manual review of the code base. It revealed that no such algorithm existed to transmit data securely. I applied the AES-256 algorithm to the code source and used OWSAP Dependency Check tool to identify vulnerabilities within the application. In future use; I will continue to use dependency checks to asses vulnerabilities prior to testing and release.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities? 

	To make certain the code ran without errors required multiple runs of the code and multiple checks of security. I ran multiple dependency checks throughout the project to make sure no new vulnerabilities had been introduced into the application and verified the presented vulnerabilities matched the new dependency check. This further proved that no new vulnerabilities were introduced.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks? 

	The main online resources I turn to when coding is “stack overflow” and “w3resources” (multiple languages and databases) for solution's when solving code errors or how to create a function within a specific language. To help streamline the process, I utilized the vulnerabilities assessment process flow chart when approaching the assignment. It helped me to map out what I needed to focus on security wise and how to reach the solution.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment? 

	One of the best ways to showcase your work is not from the answer itself but how you arrived to the conclusion and what knowledge was gained during process. From this assignment, I would showcase the workflow process from assessing the vulnerabilities assessment process flow to identifying solutions presented in the vulnerabilities dependency check. The scale of the the assignment is much smaller than an organization's projects, but the workflow process is how I would present an example of my work. Though the assignment is a little outdated in terms of updating its application; it still showcases I worked with an outdated application and arrived to a secure but yet functioning application.
