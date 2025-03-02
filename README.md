# CS305-Journal-Entry

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a consulting firm that develops financial plans for its customers. They have contracted us, Global Rain to create a validation step, in the form of a checksum, to ensure secure communication.



What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I belive that implementing secure coding practices such as avoiding hardcoding secrets as wells as utilizing 256 bit hash function is something that will work well for this client. The other factor was runing a dependency check to adhere to the current vulnerabilities in the code and services we are currently utilizing. Not only does security prevent financial loss in the sense of preventing malicious third parties from gaining access to the customers financials and pivate information, but it would also prevent the reputation of the company from being labeled as careless and prone to data leaks. 



Which part of the vulnerability assessment was challenging or helpful to you?

The biggest challenge I faced was creating a keystore given that Eclipse does not come pre-packaged with a keystore and the instructions aren't clear online. 
It took alot of back and forward between creating a CER as well as implementing the correct values for the local server to be able to authenticate and finally publish. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
We increased the layers of security by implementing the checksum, creating a HTTPS restful API, as well as updating the dependencies to avoid previously published vulnerabilities. 


How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Running a dependency check thru maven, before and after refactoring the code. 


What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Looking online for solutions to common issues, paying attention to the spelling of the suppression files as well as the location of certificates created outside of the IDE

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would gladly show them the secure code that I was able to develop from the learnings of this program as well as perhaps the dependencies checks and suppression and certificates that I was able to generate. 
