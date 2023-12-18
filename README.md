# CS305
- Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
    - Artemis Financial is a consulting company that delivers individualized financial plans to its' clients. They sought to modernize the security of their RESTful api to protect the company from external threats.
      
- What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing? 
    - I was able to use automation tools such as OWASP dependency check and Snyk to detect vulnerabilities. I was also able to research and learn how to read reports and where to look for futher information into the nature of a specific vulnerability. Secure coding protects the integrity of a software application. It also protects both a consumers sensitive data, and a companies pockets and reputation. 
      
- What part of the vulnerability assessment was challenging or helpful to you?
    - It was challenging to understand the different versions and their respective requirements. It was also challenging to understand how each CVE contributes too each vulnerability. I did however like the visual component of an HTML report, as it reminded me of JUnit report.
       
- How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
    - Updating to the latest versions of spring and java drastically reduced the number of vulnerabilities in my project. In the future I will make sure that I am working with the newest libraries, or at the very least analyzing any potential vulnerabilies in older libraries. I would also investigate any modern tools that may exist. One of the benefits to learning in this age, is that there are countless resources that are available for those who want to learn.
      
- How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
    - I made sure to re-run both old and new versions of the vulnerability report. I also checked each remaining vulnerability to ensure that they were low-risk or for any explanations.
      
- What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
    - Tutorials, googling, and AI really helped me in providing context and summaries for any content I may have been confused on. Spring Boot build failures in particular were very hard to diagnose, but the aforementioned tools assisted me in swiftly diagnosing any problems. I also communicated with other students. This was helpful to get the input from others with professional experience.
      
- Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
    - I might show or talk about the diagnostic process I took to working through build failures and compilation errors. I'd also mention some of the investigation that went into CVEs' and how I static tested the project. Those tasks, regardless on the technologies used, was good practice. 
