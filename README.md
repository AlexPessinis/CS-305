# CS-305
Repository for final work completed within the "CS-305" course at SNHU.
### Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial was an international financial service company, which developed savings plans for investments, retirement, etc. The issue that was to be addressed was a 
modernization effort in order to successfully protect client data, using momdern and effective security strategies employed within the industry.
### What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
During this assigment I helped identify potential risks, and refactored their code to help mitigate these risks. This involved exception handling to help avoid stack trace 
exposure, enforcing HTTPS, and apply cryptography to the software. This adds a lot to a company's well being, from client protection to company reputation.
### Which part of the vulnerability assessment was challenging or helpful to you?
The most difficult part of the vulnerability assessment was definitely identifying false positives. On top of feeling as if instructions weren't entirely clear and being 
generally unable to identify them in the first place, the XML file was also giving me difficulties when I tried suppressing the false positives.
### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I added layers of security by adding cryptography, implementing static testing, implementing better exception handling, and appropriately restructuring code to maximize 
readability and maintainability.
### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I made sure to manually inspect the code several times, as well as test the code after each new implementation to garauntee there were no new vulnerabilities introduced.
### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Using tools such as keytool, eclipse, self-signed certificate generation, and configuring spring boot may prove to be very valuable in the future, either through school or 
in any future jobs that I may have.
### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
Certainly the code I wrote for the final project. By employing appropriate exception handling, using cryptography, configuring spring boot, using the keytool, and of course, 
designing readable, maintainable, and easily scalable code with future coding in mind is something that I would show my future employers.
