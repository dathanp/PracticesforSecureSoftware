# PracticesforSecureSoftware
Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a consulting company that develops financial plans for their clients. The client was people who sought after financial plans that include savings, retirement, investments, and insurance. The issue I was tasked to solve was to secure communications through a web application because they wanted file verification for long term storage and to have secure communication channels.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I did well in finding the list of dependencies that were causing vulnerabilities and I suppressed vulnerabilities that gave false positives. I tested the product after I developed a checksum verification to see if any new vulnerabilities were found. It is important to code securely so that users data does not get leaked or potentially causing system failures due to attacks. Having secure software builds trust within a company allowing people to trust them with their sensitive information. Keeping the company in compliance with regulatory standards is also a must so that transparency is present.

Which part of the vulnerability assessment was challenging or helpful to you?

I think the most challenging part of the assessment was finding which vulnerabilities were more important to fix than others. I needed to click through every vulnerability and read the causes of it and possible solutions in order for me to come to a conclusion for the vulnerability. It was very helpful to see all the areas in which data could be compromised though, allowing me to approach solutions with a different mindset.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increase the layers of security by apply encryption standards for data storage, most notably is AES-256 bit. I also enabled https encryption for the website so that I can prevent man in the middle attacks. In the future I want to use the dependency check tool so that I can see what libaries I need to update or change as my software evolves over time.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I made certain the code and application were functional by running multiple tests and checking my developer tools on my browser to see the requests coming in. Once I refactored my code, I ran the dependency check tool to see if I created any new vulnerabilities. After that I compared the results side by side to verify it was the same.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

In my future assignments, I am going to be referring to the OWASP website to utilize the dependency check tool and review their secure coding guidelines. Practices I used are input validation, error handling, and withdraw from using deprecated methods or libraries to ensure your software is up to date with the latest security measures.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I can show employers that I am able to identify security vulnerabilites, follow compliance guidelines, and solve potential security issues. I also know how to create authorization certificates and employ AES encryption within sites to secure all communication channels from attackers.
