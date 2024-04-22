# C305R4817
Class assignments and journal entry


Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Artemis Financial acted as our demo financial company, they specialized in software design for financial business and government agencies by helping to develop individual financial plans for customers. They were looking to modernize their public web interfaces and seeking help to protect their clients financial information. 

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
I felt my best skill came from describing the issues to the client during the various assignments in the course. Security is incredibly important to the client/customer trust, staying committed to security is a difficult thing as it often doesn’t pay benefits in a noticeable way but when it fails it is severely detrimental. 

What part of the vulnerability assessment was challenging or helpful to you?
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
The part I found most difficult was the time consuming nature of addressing dependency vulnerabilities. It was time consuming and many could not be addressed and would have to circumnavigate having satisfying resolutions could leave a bad taste in my mouth. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Added self-signed certificate and encryption to transitioning and stored files for their software. In the future while I did implement a checksum verification, I would like to do more investigation as to what common user attacks are. 

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Running the software through OWASP dependency-check using Maven to identify further vulnerabilities after changes were made, this was used to rule out if any new feature of the existing dependencies that were added contained further vulnerabilities.  

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
OWASP - dependency-check was throughout and very readable. I would see if there are other plug-ins on the market but I would be happy to use it again. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
I believe I’d show off the checksum verification, and give an explanation as to why the product would need need something like this as well as a go into detail about different types of attacks, include but not limited to SQLinjections. 

