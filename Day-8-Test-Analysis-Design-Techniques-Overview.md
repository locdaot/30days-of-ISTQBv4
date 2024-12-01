## 4. TEST ANALYSIS AND DESIGN
### 4.1.1 Test Techniques Overview

![image-10](https://github.com/user-attachments/assets/e967a0f5-6c9a-414a-808f-a28ff1236d52)
> Techniques are classified as black-box, white-box and expericened-based.


![image-11](https://github.com/user-attachments/assets/e46fc7fb-5de9-4066-8cfe-5602b3218864)

### 4.2 Black-box test techniques
#### 4.2.1 Equivalence Partitioning 
EP devides data into partitions
Example: If a field accepts integer values between 1 and 10, then the valid class contains all numbers between 1 and 10, and the two invalid classes are numbers smaller than 1, and numbers higher than 10. This means that 3 total test cases are enough to cover all possible classes. 

#### 4.2.2 Boundary Value Analysis
BVA is a technique based on exercising the boundaries of equivalence partitions.Therefore, BVA can only be used for ordered partitions. The minimum and maximum values of
a partition are its boundary values. 
Example: Using the same field as above, the valid boundaries are 1 and 10, and the invalid are 0 and 11.
#### 4.2.3 Decision Table Testing
Where the relationships between inputs and outputs are displayed in a tabular format. The table typically has columns for conditions, and rows for the different combinations. Each row should have a corresponding test case. </br>
Example: This technique works on more complex scenarios. Let’s say we have a bank loan application with the following conditions:
| Conditions    | Age equal to or over 25 | Income equal to or over 50000 USD | Outcome |
| ---------- | :--------- | :----------: | ----------: |
| 1 | True | True   | Approve lawn  |
| 2  | True  | False    | Reject loan   |
| 3   | False   | False     | Refer to a manager    |
| 4    | False    | False      | Reject loan     |
#### 4.2.4 State Transition Testing
Verifies the behavior of a system as it transitions between different states. </br>
Example: Let’s say you are testing a basic bug tracker. The statuses diagram is:
![Screenshot 2024-12-01 at 22 36 36](https://github.com/user-attachments/assets/0a814acf-8613-4753-914d-8ef0863a0cb5)
### 4.3 White-box Test Techniques
> This section focuses on two code-related white-box test
techniques: </br>
• Statement testing </br>
• Branch testing

#### 4.3.1 Statement Testing and Statement Coverage

### Key words
- Acceptance criteria (AC): The criteria that a component or system must satisfy in other to be accepted by a user, customer, or other authorized entity
- Acceptance test-driven development: A collaboration-based test-first approach that defines acceptance tests in the stakeholder's domain language.
- Black-box test technique: A test technique based on an anlysis of the specification of a component or system.
- Boundary value analysis: A black-box testing technique in which test cases are designed based on boundary values
- Branch coverage: The coverage of branches in a control flow graph
- Checklist-based testing: An experience-based test technique in which test cases are design to exercise of a checklist
- Collaboration-based test approach: An approach to testing that focuses on defect avoidance by collaborating among stakeholders
- Coverage: The degree to which specified coverage items are exercised by a test suite, expressed as a percentage
- Coverage items: An attribute or combination of attributes derived from one or more test conditions by using a test technique.
- Decision table testing: A black-box test technique in which test cases are designed to exercise the combinations of conditions and the resulting actions shown in a decision table
- Equivalence partitioning: A black-box test technique in which test conditions are equivalence partitions exersiced by one representative member of each partition.
- Error guessing: A test technique in which tests are derived on the basis of the tester's knowledge of past failures, or general knowledge of failure modes
- Experience-based test technique - A test technique based on the tester's experience, knowledge and intuition
- Exploratory testing - An approach to testing in which the testers dynamically design and execute tests based on their knowledge, exploration of the test item and the results of previous tests.
- State transition testing - A black-box test technique in which test cases are designed to exercise elements of a state transition model.
- Statement coverage - The coverage of executable statements
- Test technique - A procedure used to define test conditions, design test cases, and specify test data. 
- White-box test technique - A test technique only based on the internal structure of a component or system


Question 1:
Test analysis summarizes:
- [ ] How to test
- [x] What to test
- [ ] Why to test

Question 2:
Test techniques support the tester in:
- [ ] Test analysis
- [ ] Test design
- [ ] Identify coverage items
- [x] All of the above

Question 3:
Test techniques that also known as specification-based techniques:
- [ ] Experience-based test techniques
- [x] Black-box test techniques
- [ ] White-box test techniques

Question 4:
The test cases in this technique are independent of how the software is implemented.
- [ ] White-box test techniques
- [x] Black-box test techniques

Question 5:
White-box test techniques are:
- [ ] The test cases are dependent on how the software is designed
- [ ] Test cases can only be created after the design or implementation of the test object
- [ ] Also known as structure-based techniques
- [x] All of the above

Question 6:
Experience-based test techniques can detect defects that may be missed using the black-box and white-box test techniques.
- [x] TRUE
- [ ] FALSE
