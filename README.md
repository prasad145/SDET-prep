# SDET Track
![Source](https://www.guru99.com/): ![image](https://user-images.githubusercontent.com/50115378/128474292-05a69a4c-69cb-4b9e-952c-0cefac47af20.png)

## Software Development Engineer in Test Preparation
### Software Testing:
   Software Testing is a method to check whether the actual software product matches expected requirements and to ensure that software product is Defect free. It involves execution of software/system components using manual or automated tools to evaluate one or more properties of interest. The purpose of software testing is to identify errors, gaps or missing requirements in contrast to actual requirements.
  
  ### 1. Benefits of Testing:
   - Cost-Effective: It is one of the important advantages of software testing. Testing any IT project on time helps you to save your money for the long term. In case if the bugs caught in the earlier stage of software testing, it costs less to fix.
   - Security: It is the most vulnerable and sensitive benefit of software testing. People are looking for trusted products. It helps in removing risks and problems earlier.
   - Product quality: It is an essential requirement of any software product. Testing ensures a quality product is delivered to customers.
   - Customer Satisfaction: The main aim of any product is to give satisfaction to their customers. UI/UX Testing ensures the best user experience.

  ### 2. Types of Testing:

  ![Types](https://cdn.guru99.com/images/2/061920_1310_Whatissoftwaretesting1.png)
 
   - Functional Testing
      - Unit Testing
      - Integration Testing
      - Smoke Testing
      - User Acceptance Testing
    
   - Non-Functional Testing
      - Performance
      - Load
      - Volume
      - Scalability
      - Usability
    
   - Maintenance Testing
      - Regression Testing
      - Maintenance Testing
 <hr>

### Testing Methodologies:
  Software Testing Methodology is defined as strategies and testing types used to certify that the Application Under Test meets client expectations. Test Methodologies include functional and non-functional testing to validate the AUT.
  ### 1. Waterfall Model

![waterfall-model](https://cdn.guru99.com/images/stories/waterfall.png)
    
   - In the waterfall model, software development progress through various phases like Requirements Analysis, Design, Implementation, Verification, Maintenance sequentially. In this model, the next phase begins only when the earlier phase is completed. 
   - The first phase in the waterfall model is the requirements phase in which all the project requirements are completely defined before starting the testing. During this phase, the test team brainstorms the scope of testing, test strategy and drafts a detailed test plan.
   - Only once the design of software is complete, the team will move on to execution of the test cases to ensure that the developed software behaves as it expected.
   - In this methodology, the testing team proceeds to the next phase only when the previous phase is completed. 
   - This methodology is not suitable for projects where the requirements change frequently.
 
 ### 2. Iterative Development
![iterative-model](https://cdn.guru99.com/images/stories/iterative-model.jpg)
   - In this model, a big project is divided into small parts, and each part is subjected to multiple iterations of the waterfall model. At the end of an iteration, a new module is developed or an existing module is enhanced. This module is integrated into the software architecture and the entire system is tested all together  
   - As soon as iteration is completed, the entire system is subjected to testing. Feedback from testing is immediately available and is incorporated in the next cycle. The testing time required in successive iteration can be reduced based on the experience gained from past iterations. 
   - The main advantage of iterative development is the test feedback is immediately available at the end of each cycle. 
   - This model increases communication overheads significantly since, at the end of each cycle, feedback about deliverables, effort etc must be given. 
 
 ### 3. Agile Methodology
 ![Agile](https://cdn.guru99.com/images/stories/agile_development_model.gif)
   
   - Traditional software development methodologies work on the premise that software requirements remain constant throughout the project. But with an increase in complexity, the requirements undergo numerous changes and continuously evolve. At times, the customer himself is not sure what he wants. Though the iterative model addresses this issue, it's still based on the waterfall model.
   - In Agile methodology, software is developed in incremental, rapid cycles. Interactions amongst customers, developers and client are emphasized rather than processes and tools. The agile methodology focuses on responding to change rather than extensive planning. 
   - Incremental testing is used in agile development methods and hence, every release of the project is tested thoroughly. This ensures that any bugs in the system are fixed before the next release.
   - It is possible to make changes in the project at any time to comply with the requirements.
   - This incremental testing minimizes risks. 

### 4. Extream Programming
![Extream](https://cdn.guru99.com/images/stories/xtreme%20programming.png)
   - Extreme programming is a type of agile methodology which beliefs in short development cycles. A project is divided into simple engineering tasks. Programmers code a simple piece of software and get back to the customer for feedback. Review points from the customer are incorporated and the developers proceed with the next task.
   - In extreme programming developers usually, work in pairs.
   - Extreme Programming is used in places where customer requirements are constantly changing. 
   - Continuous testing and continuous integration of small releases ensure software code is delivered is of high quality.
   - Extreme programming follows a Test-driven development which is described as follows 
      1. Add a Test Case to the test suite  to verify the new functionality which is yet to be developed
      2. Run all the tests and obviously the new test case added must fail since the functionality is not coded yet
      3. Write some code to implement the feature/functionality
      4. Run the test suite again. This time, the new test case should pass since the functionally has been coded  
<hr>

### Manual Testing
   Manual Testing is type of software testing where test cases are executed manually by a tester without using any automated tools. The purpose of Manual Testing is to identify the bugs, issues, and defects in the software application.
   
   ### 1. Types of Manual Testing
   ![types](https://cdn.guru99.com/images/typesofmanualtesting.png)
   
   ### 2. How To perform Manual Testing
   - Read and understand the software project documentation/guides. Also, study the Application Under Test (AUT) if available.
   - Draft Test cases that cover all the requirements mentioned in the documentation.
   - Review and baseline the test cases with Team Lead, Client (as applicable)
   - Execute the test cases on the AUT
   - Report bugs.
   - Once bugs are fixed, again execute the failing test cases to verify they pass.
   
   ### 3. Manual Vs Automation Testing
   | Manual Testing  | Automation Testing |
   | ------------- | ------------- |
   | Manual testing requires human intervention for test execution.  | Automation Testing is use of tools to execute test cases  |
   | Manual testing will require skilled labour, long time & will imply high costs.  | Manual testing will require skilled labour, long time & will imply high costs.  |
   |Any type of application can be tested manually, certain testing types like ad-hoc, whose functional modules changes frequently|Automated testing is recommended only for stable systems and is mostly used for Regression Testing|
   |Manual testing can become repetitive and boring.|The boring part of executing same test cases time and again is handled by automation software in Automation Testing.|
