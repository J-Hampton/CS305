# CS305
1. Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a financial consulting company that develops individualized financial plans for savings, retirement, investments, and insurance for their patrons. They would like to modernize their custom software and implement the most current security. I was intrusted to examine their software for security vulnerabilities and add secure communications.

2. What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I implemented the secure web interface and created a string hashing algorithm that could be used for any portion of their software with minor adjustments to the code.

3. What about the process of working through the vulnerability assessment did you find challenging or helpful?

The most challenging part of working through the vulnerability assessment was sifting through the data provided and finding the useful information that pertained to the vulnerability in question.

4. How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

To increase security the https protocol was enforced and a certificate was generated to verify the server's identity.

5. How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

After refactoring the code I attempted to connect via http and verified the certificate was valid. I also re-ran the vulnerability chack to ensure no new vulnerabilities were discovered.

6. What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

The vulnerability checker was a tool that wa very useful and provided good information on existing vulnerabilities in the software which I can see myself using often in the future.

7. Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I would showcase my ability to create and implement secure communication through a spring/maven application.
