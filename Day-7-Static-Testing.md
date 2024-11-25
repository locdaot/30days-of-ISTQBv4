## 3.1 STATIC TESTING BASICs
> In static testing software under test does not need to be executed. Static testing can be applied for both verification and validation.
### 3.1.1 Work products examninable by Static Testing
Almost any work product can be examined using static testing.
Include requirement specification documents, source code, test plans, test cases, product backlog items, test charters, project documentation, contracts and modules.
### 3.1.2 Value of Static Testing
Static testing can detect defects in the earlier phases of the SDLC, fulfilling the principle of early testing.
### 3.1.3 Differences between statis testing and dynamic Testing
[Refer](Day-1-Fundamentals-Of-Testing-What-is-Testing.md)

## 3.2 FEEDBACK AND REVIEW PROCESS
### 3.2.1 Benefitd of early and frequent stakeholder feedback
Early and frequent feedback allows for the early communication of potential qulity problems.
### 3.2.2 Review Process Activities
1. **Planning**: During the planning phase, the scope of the review, which comprises the purpose, the work product to be reviewed, quality characterstics to be evaluated, areas to focus on, exit criteria, supporting information such as standards, effort and the timeframes for the review, shall be refined
2. **Review initiation**: The goal is to make sure that everyone and everything involved is prepared to start the review.
3. **Individual review**: Every reviewer performs an individual review to assess the quality of the work product under review, and to identify anomalies, recommendations, and questions by applying one or more review techniques (e.g., checklist-based reviewing, scenario-based reviewing).
4. **Communication and analysis**: For every anomaly, the decision should be made on its status, ownership and required actions. This is typically done in a review meeting, during which the partipipants also decide what the quality level of reviewed work product is and what follow-up actions are required
5. **Fixing and reporting**: For every defect, a defect report should be created so that corrective actions can be follow-up. On the exit criteria are reached, the work product can be accepted. The review results are reported.
### 3.2.3 Roles and Responsibilities in reviews
- **Manager**: decides what is to be reviewed and provides resources, such as staff and time for review
- **Author**: creates and fixes the work product under review
- **Moderator**: Ensures the effecttive running of review meetings, including mediation, time management, and a safe review environment in which everyone can speak freely
- **Scribe**(alse known as recorder): Collates anomalies from reviews ans record review information
- **Reviewer**: perform review, a reviewer may be someone on the project, a subject matter expert, or any other stakeholder
- **Reviewer leader**: takes overall responsibility for the review such as deciding who will be involved, and organizing when and where the review will take place.
### 3.2.4 Review Types
Some commonly used review types are:
- **Informal review**: Informal review do not follow a defined process and do not require a formal document output. The main objective is detecting animalies.
- **Walkthrough**: A walkthrough, which is led by the author, can serve many objects, such as evaluating quality and building confidence in the work product
- **Technical review**: A technical review is performed by technically qualified reviewers and led by a moderator. The objectives of a technical review are to gain consensus and make decisions regarding a technical problem, but also to detect anomalies, evaluate quality and build confidence in the work product, generate new ideas, and to motivate and enable authors to improve.
- **Inspection**: In inspections, the author cannot act as the review leader or scribe.
### 3.2.5 Success Factors for Reviews
- Defining clear objectives and measurable exit criteria. Evaluation of participants should never bean objective
- Choosing the appropriate review type to achieve the given objectives, and to suit the type of workproduct, the review participants, the project needs and context
- Conducting reviews on small chunks, so that reviewers do not lose concentration during an individual review and/or the review meeting (when held)
- Providing feedback from reviews to stakeholders and authors so they can improve the product and their activities (see section 3.2.1)
- Providing adequate time to participants to prepare for the review
- Support from management for the review process
- Making reviews part of the organization’s culture, to promote learning and process improvement
- Providing adequate training for all participants so they know how to fulfil their role
- Facilitating meetings

## TEST
Question #1 (1 Point) (3.1.1.001)</br>
Which of the following work products are examinable by static testing? 
- [ ] Only source code
- [ ] Only test cases
- [x] Any tangile work product including code, specifications, designs, and documents
- [ ] Only test plans
****
Question #2 (1 Point) (3.1.2.009) </br>
Which of the following is NOT a benefit of static testing?
- [ ] Early defect detection
- [ ] Reduction in testing costs
- [ ] Identification of issues in requirements and designs
- [x] Identification of all issues dynamic testing can find but earlier in SDLC
****
Question #3 (1 Point) (3.1.3.001) </br>
Which of the following statements best describes a key difference between static testing and dynamic testing?
- [ ] Static testing involves executing the software code, while dynamic testing focuses on reviewing documents and code without executing the program.
- [ ] Dynamic testing involves reviewing the code and documents without executing the software, while static testing focuses on executing the program to uncover defects.
- [ ] Both static and dynamic involve executing the software code, but dynamic testing focuses on uncovering defects through code review, while static testing involves executing test cases.
- [x] Static testing focuses on analying code and documents without executing the software, while dynamic testing involves executing the program to identify defects through actual execution.
****
Question #4 (1 Point) (3.1.2.215) </br>
Which of the following would be considered a form of static analysis, as described in the text?
- [ ] Examnining code coverage reports to identify untested areas.
- [ ] Running automated regression tests after a new software build.
- [x] Using a tool to check for inconsistent variable naming conventions in the code
- [ ] Observing user behavior during a usability testing session
****
Question #5 (1 Point) (3.1.3.243) </br> 
Decide which of the following statements (i-v) are true for dynamic testing and which are true for static testing </br>
i. It can be used to measure non-functional quality characteristics </br>
ii. It can be applied to both executable and non-executable work products </br>
iii. Failures can be identified with this testing </br>
iv. It can be applied to all test levels </br>
v. Finding discrepancies from a coding standard is easier with this testing </br>
> i, ii, iv, v are true for static testing. i, iii, iv are true for dynamic testing
****
Question #6 (1 Point) (3.1.1.216) </br>
Which of the following is a list of the work products that can't be checked by static analysis?
- [ ] Test charters
- [ ] Test plans
- [ ] Test cases
- [x] COST software intended for data encryptiion and security.
****
Question #7 (1 Point) (3.1.2.411) </br>
Refer to the following statements about static and dynamic testing: </br>
i. 3rd party executable code developed by COTS can be examined using static testing </br>
ii. Static testing by identifying defects early in the SDLC reduces the cost associated with fixing defects at a later stage </br>
iii. Mismatched numbers in interface specification are easier to find through static testing </br>
iv. Static testing can be used to measure quality characteristics that are dependent on executing code </br>
Which of the following is FALSE? </br>
> i, iv
****
Question #8 (1 Point) (3.1.3.477) </br>
Decide which of the following statements (i-v) are true for static testing. </br>
i. It can identify potential security issues like hardcoded passwords or sensitive information leakage in source code. </br>
ii. It is incapable of identifying any defects in testware </br>
iii. It aids in the detection of failures by examining the software with static analysis tools </br>
iv. It can be performed very early in the software development lifecycle, even before any code is executed </br>
v. It offers a means to check for consistency and completeness in user story acceptance criteria </br>
> i, iv, v are true for static testing
****
Question #9 (1 Point) (3.1.2.091) </br>
What distinguishes static analysis from other forms of static testing?
- [ ] Static analysis requires the software to be executed in the controlled environment.
- [ ] It is typically conducted after the software has been fully developed and developed
- [x] Static analysis often utilizes tools to analyze the source code for potential defects
- [ ] It is a manual process that relies solely on the experties of the developer to identify defects
****
Question #10 (1 Point) (3.1.3.280) </br>
Which of the following statements accurately describes a key difference between static testing and dynamic testing?
- [x] Static testing directly identifies defects, while dynamic testing causes failures from which defects are analyzed aferward.
- [ ] Static testing replies solely on the execution of code, while dynamic testing focuses on reviewing documents and code without execution.
- [ ] Statis tesing primarily detects defects on rarely executed code paths, while dynamic testing detects defects on frequently executed code paths.
- [ ] Dynamic testing can measure quality characteristics that are not dependent on executing code, while static testing cannot.
****
Question #11 (1 Point) (3.1.1.090) </br>
The following is a list of the work products produced in the SDLC </br>
i. Coverage items, test data requirements, and test environment requirements </br>
ii. A JavaScript function implementing a sorting algorithm for use in a web application </br>
iii. Data Flow Diagrams (DFD), Entity-Relationship Diagrams (ERD), and Business Process Model & Notation (BPMN) Diagrams </br>
iv. Third-party custom firmware for network routers distributed by manufacturers without the source code </br>
v. Integrated COTS Project Management Software in a Tech Startup </br>
During a software audit, which of the following would NOT typically be subject to static testing due to its nature?
> iv, v
****
Question #12 (1 Point) (3.1.2.211) </br>
Which of the following is the BEST summary of the key difference between static and dynamic testing?
- [x] Dynamic testing involves executing the software, while static testing does not
- [ ] Statis tesing primarily focuses on code quality, while dynamic testing focuses on functionality
- [ ] Statis tesing is performed by testers, while dynamic testing is performed by developers
- [ ] Statis testing is a verifycation activity, while dynamic testing is a validation activity.
****
Question #13 (1 Point) (3.1.3.212) </br>
Which statement about static and dynamic testing is true?
- [x] Static testing may more early detect defects that lie on paths through the code that are rarely executed or hard to reach using dynamic testing, such as unreachable or duplicated code
- [ ] Static testing can be applied only to non-executable work producs, while dynamic testing can be applied to both executable and non-executable work producs
- [ ] Static and dynamic testing can both lead to the detection of failures, howerver, failures found by static testing are generally cheaper and easier to fix
- [ ] Security vulnerabilities, such as buffer overflows, can only detected by dynamic testing, as code execution is required. Static testing, on the other hand, can be used to measure quality characteristics that are not dependent on executing code, such as maintainability.
**** 
Question #14 (1 Point) (3.1.2.076) </br>
Which of the following best describes the purpose of a static analysis tool in software testing?
- [ ] To automatically execute test cases and record test result
- [ ] To monitor the application's performance in real-time
- [x] To analyze code or other software artifacts for potential defects, code compliance, and quality standards without executing the program
- [ ] To manage the test cases, requirements, and defects for a software project
****
Question #15 (1 Point) (3.1.3.237) </br>
Decide which of the following statements (i-v) are true for dynamic testing and which are true for static testing </br>
i. Identifying missed elements in the database structure is easier with this testing</br>
ii. Finding variables that are declared but never used is easier with this testing </br>
iii. Defects and failures can be identified with this testing </br>
iv. The test objective is to identify defects as early as possible </br>
v. Identifying insufficient response time of the external interface is easier with this testing </br>
> i, ii, iv are for static testing. iii, iv, v for dynamic testing
****
Question #16 (1 Point) (3.1.1.016)</br>
For which of the following would static testing be least effective due to the nature of the artifact? </br>
i. A UML sequence diagram outlining the interaction between system components for a custom software project </br>
ii. Encrypted third-party libraries </br>
iii. A proprietary COTS ERP software package without access to its source code, used for managing company resources </br>
iv Python code for a custom-developed data analysis tool intended for internal use </br>
v. A flowchart outlining a business process re-engineering workflow </br>
> ii, iii
****
Question #17 (1 Point) (3.1.2.010) </br>
What is the primary objective of static testing?
- [ ] To validate the system's behavior against its specification
- [ ] To execute test cases against the software
- [x] To find defects early in the SDLC
- [ ] To perform load testing on the software
****
Question #18 (1 Point) (3.1.3.010) <br>
Which of the following statements is true regarding the timing of static testing and dynamic testing in the software development lifecycle (SDLC)?
- [ ] Static testing occurs during the design phase, while dynamic testing occurs during the coding phase
- [ ] Dynamic testing occurs during the design phase, while static testing occurs during the coding phase
- [ ] Both static and dynamic testing occur during design phase
- [x] Static testing can occur earlier in the SDLC than dynamic testing
****
Question #19 (1 Point) (3.1.2.356) </br>
Which of the following statements CORRECTLY reflects the value of static testing?
- [ ] By introducing reviews, we have found that both the quality of specifications and the time required for development and testing have increased
- [ ] Using static testing means we have better control and cheaper defect management due to the ease of detecting defects later in the lifecycle
- [ ] Now that we require the use of static analysis, missed requirements have decreased and communication between testers and developers has improved
- [x] Since we started using static analysis, we found coding defects that might have not been found by performing only dynamic testing
****
Question #20 (1 Point) (3.1.3.311) </br>
Which of the following statements is true regarding the application of static testing and dynamic testing to work products?
- [x] Dynamic testing can only be applied to executable work products, while static testing can be applied to both executable and non-executable work products
- [ ] Static testing can only be applied to non-executable work products, while dynamic testing can only be applied to executable work products
- [ ] Both static and dynamic testing can only be applied to non-executable work products
- [ ] Both static and dynamic testing can only be applied to both executable and non-executable work products
****
Question #21 (1 Point) (3.1.1.205) </br>
Which of the following software work products CAN be examined using static testing? </br>
i. Test case </br>
ii. Component's code </br>
iii. Web pages </br>
iv. Test procedure </br>
v. User stories </br>
> all
****
Question #22 (1 Point) (3.1.2.405) </br>
Refer to the following statements about static and dynamic testing: </br>
i. Test plans and test reports can be examined using static testing </br>
ii. Static testing is an expensive alternative to dynamic testing </br>
iii. Security vulnerabilities such as buffer overflows are easier to find through dynamic testing </br>
iv. Static and dynamic testing (with analysis of failures) can both lead to the detection of defects </br>
Which of the following is TRUE?
> i, iv
****
Question #23 (1 Point) (3.1.3.466) </br>
Decide which of the following statements (i-v) are true for static testing. </br>
i. It is best suited for identifying issues that only appear under specific runtime conditions. </br>
ii. It can help in finding and fixing gaps in test-based coverage. </br>
iii. It involves the execution of test cases to find defects. </br>
iv. It is effective for detecting ambiguities and inconsistencies in requirements. </br>
v. Deviations from coding standards are readily identified through this form of testing. </br>
> ii, iv, v are trur for static testing
****
Question #24 (1 Point) (3.1.2.051) </br>
Which of the following statements is true about static analysis tools?
- [ ] They are used to perform load testing on the application
- [x] They are automatically detect some types of defects in the code without executing it
- [ ] Theyare primarily used for dynamic testing activities
- [ ] They can only be used effectively after the software has been fully developed.
****
Question #25 (1 Point) (3.1.3.201) </br>
Which of the following types of defects would MOST likely be detected through dynamic testing rather than static testing?
- [ ] A typographical error in a requirements specification
- [x] A memory leak caused by improver resource deallocation
- [ ] An incorrect interface definition between modules
- [ ] An unreachable code block
****
Question #26 (1 Point) (3.1.1.111) </br>
In the context of static testing, which of the following would be the most challenging to test?
- [ ] User stories and acceptance criretia
- [ ] COST software user manuals
- [ ] Code writeen in a domain-specific language (DSL)
- [x] Encrypted API keys in environment variable to secure application intagrations and prevent unauthorized access
****
Question #27 (1 Point) (3.1.2.025) </br>
Which of the following is NOT an example of a static testing technique?
- [ ] Code reviews
- [x] Unit testing
- [ ] Walkthroughs
- [ ] Inspections
