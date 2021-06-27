# CS305SoftwareSecurity
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a financial consulting institution that requested assistance in providing client security. Anyone using their services were considered clients.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I feel that I performed well on identifying the false negatives that arose from the Maven Dependency checks. Secure code is where, no pun intended, the source of a lot of security issues occur. If a code is not properly constructed with safety in mind, the databases and secure information are vulnerable, tarnishing the company if an attack is successful and potentially causing their clientelle damage or distress.

What about the process of working through the vulnerability assessment did you find challenging or helpful?
I found manually inspecting the code to be the most challenging because of the "bigger picture" view that one needs to be successful. Thinking about the return values from the input, or how exceptions could be used against the company... limiting values.. these issues were hard to find, but incredibly important.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
The first thing I did was view the current layers of security. Evaluating the existing codes and consequences helped me mitigate risks and discover vulneratbilities. Frequent testing and trial and error were also part of my security evaluation.

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
I had difficulty getting my server up, but to verify its compliance I would have tested the code on a local server and verify that the input values were coming back as hash values. This would indicate that my algorithms were successful.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
Maven was the primary tool used with dependency checks, NDA databases were referenced when identifiying dependency issues and Spring framework was utilized. I will, beyond a doubt, be using these tools again.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I'm proud of the dependency handling. I'd showcase the suppressions and the indications of false positives found.
