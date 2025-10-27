# CS305

    Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
        Artemis Financial is a financial institution looking to incorporate additional security into their already existing application.
    What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
        I enjoyed testing potential vulnerabilities in my code via static testing. Secure coding is important to protect not only your property but the property of your users. Personal information and trade secret loss can cause great harm to both people and businesses. Coding secure software helps to secure information and overall helps to protect a company’s reputation in the long run.
    What about the process of working through the vulnerability assessment did you find challenging or helpful?
       The challenging part of the vulnerability assessment was creating a suppression file for all of the dependency vulnerabilities found during the static analysis. The packages were very out-of-date and had many reported issued.
    How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
        Through testing most of the vulnerabilities were caused by using old libraries so by updating the libraries currently in use in the code more secure software is created. Using penetration testing in the future will better assess the and additional vulnerabilities within the code.
    How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
      The application was verified to be functional and secure through reviewing the code and testing to ensure the application worked as expected. An initial dependency vulnerability scan was run before touching the code to determine what issues currently existed. After refactoring the code another scan was run to ensure no additional vulnerabilities were introduced.
    What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
        I used stack overflow quite a bit and checked how peers were solving like situations to mine, especially when running into errors in the console.
    Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this assignment might you want to showcase to a future employer?
      The Vulnerability Assessment Report and the Practices for Secure Software Report would be good examples to showcase the knowledge gained from this work. Additionally, the refactored application from project 2 would be useful to demonstrate an ability to use self signed certificates with a RESTful API.
