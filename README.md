# SNHU_CS305_SoftwareSecurity
CS305 SNHU is a repository where my projects for this course (Project 1 and Project 2) are showcased.

-Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a consulting company that creates financial plans for individual customers. They want to maximize how they deliver these financial guidelines to their customers by having an effective software security. For them, this means using the most recent and secure software security.

-What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I applied industry practice principles by addressing the vulnerabilities and how they are addressed. I used sources like the Java Oracle that helped be determine the dependencies and their vulnerability types. As seen throughout the modules, secure coding allows us to find bottlenecks and weak points within the program due to an old implementation that is outdated (which is why we base the dependency check with the most recent version). It also allows us to distinguish between actual failures and false positives. A company's overall well-being is also measured by how the software security is measured and handled, false positives for example show what measures are redundant because they are not applicable. 

-Which part of the vulnerability assessment was challenging or helpful to you?
The most challenging portion for me was the functional testing and that was because we needed to demonstrate the code complied correctly with the new software security enhancements by manually reviewing the code. This was an important step in the Secure Software Report because it is a best practice and it was another taken measure that ensures the codebase can compile correctly.  

-How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
By applying functional testing and secondary testing, I was able to make sure that the software security was compiling correctly. In the future I would like to use the checksum verification alongside the OWASP dependency check tool more because checksum validation is a great tool to gauge the validity of a file (in case if it were altered or corrupted).

-How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Firstly I would run the program before refactoring the code, this way I know that it originally is functional. Then after the functional testing and the secondary testing, I reviewed the results in the terminal. In project two's case, it would be to make sure if the dependencies were in the output alongside the port number that we changed from 8080 to 8443.

-What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I mentioned earlier I used the Java Oracle for all the cipher algorithms and their recommendations, but there is also a github repo that shows the most recent dependency check version that can be used when reviewing the vulnerabilities (within the pom.xml file of a project).

-Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
During this entire project assignment, I have tried to use industry standard practices by knowing what vulnerabilities were needed to go over. Suppress the false positive vulnerabilities that were not applicable to the specific program which avoids redundancy.
