# CS_305

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a company that wanted to have secure transactions involving banking information across the globe. This meant that they desperately needed to find a way to encrypt and secure private information in a way that would not leave their clients vulnerable to any number of malicious attacks in an attempt to gather financial or personal data.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I think I did  a relatively good job in finding the vulnerabilities in the dependency check that showed that many of the dependencies were outdated and needed updated, and this resulted in even more of the dependencies showing false positives. Updating critical dependencies can make a big difference in how various portions interact with each other and allow for a more secure experience. 

What about the process of working through the vulnerability assessment did you find challenging or helpful?
I really struggle with the Checksum portion and getting my localhost to connect. Due to a lot of traveling for work, I couldn't really tell if it was due to the network I was on causing an issue attempting to access or if there was another reason. I was able to resolve this issue previously but as I am currently in a hotel in AK and the wifi is abysmal, I am hoping the when i get home tomorrow and back to my desktop I can recreate what I need to in order to successfully finalize my project two in time to be graded.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
I believe that writing out a solid recommendation with an explanation and going for the highest level of encryption was the best option due to the sheer level of information that was being communicated on their servers and the amount of money that would be moving around. I also think that validating true dependencies with critical results and supressing ones that were false flags was important to understand and write the most secure and functional code. 

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
The best way to complete this was by solving the dependencies that weren't false flags, supressing the ones that were, and rerunning the check and revisiting new issues that popped up or moving to supress again if needed. 

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
Doing my best to code with comments was incredibly useful in this case, especially as I had two other classes at the same time also working on coding in java and teaching other items. It was difficult to keep each portion straight sometimes - especially all in the same Eclipse workspace, so I plan to create new workspaces in future classes to better segregate classwork and reduce confusion. 

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I think I would want to rework the entire assignment after doing another round of deepdives. I don't think that this term has been my best work due to rushing to catch up after multiple travel trips and I am beyond excited that traveling will be limited for the next few months. Once I rework what I have done to a satisfactory and 100% comprehensible point, then I would love to share my vulnerability report - hands down!
