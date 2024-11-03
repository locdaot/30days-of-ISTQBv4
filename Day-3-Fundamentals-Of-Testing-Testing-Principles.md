# 1.3 TESTING PRINCIPLES
**Testers who know and take advantage of testing principles set achievable goals and realistic objects:**
- Reduce the likelihood of end-user to find uncovered defects
- Use risk analysis, test techniques and priorities to find as many defect as possible in a limited amount of time
- Defect leakage of less than 5%
- Defect density of less than 5%
- Defect-detection pecentage of more than 95%
- Code coverage of more than 70%
- Requirement coverange of 100%

  
**Testers who don't know the testing principles set unattainable goals and realistic objects:**
- Prove that software is defect free
- Test everything and find all defects in the system.

# SEVEN PRINCIPLES OF SOFTWARE TESTING

1. Testing Principles I - Testing shows the presence not the absence of defects (Kiểm thử chứng minh sự hiện diện của lỗi)
   -
2. Testing Principles II - Exhaustive testing is impossible (Không thể kiểm thử toàn bộ)
   -
   - Testing everything (all combination of inputs and preconditions) is not feasible except for trivial cases. Rather then attempting to test exhaustively, risk analysis, test techniques and priorities should be used to focus test efforts.
   - For any real-sized system, the number of possible test cases is ether infinite or close to infinite
3. Testing Principles III - Early testing saves time and money (Kiểm thử càng sớm càng tốt)
   -
   - To find defects early, both static and dynamic test activities should be started as early as possible in SDLC. Early Testing is sometimes reffered to as 'shift left'.
   - Testing early in SDLC helps reduce or eliminate costly changes. The cost of finding and removing a defect imcreases each time that defect escape to a later SDLC phase.
   - According to some studies, a defect found after release is at least five times mote expensive to fix than a defect found during the requirement or design phase.
4. Testing Principles IV - Defects cluster together. (Lỗi thường phân bố tập trung)
   -
   - A small number of modules usually contains most of the defects discovered during pre-release testing, or they are responsible for most of the operational failures.
   - Predicted defect clusters, and the actual observed defect clusters in test or operation, are an important inout into a risk analysis used to focus the test effort.
   - Defects like to group. Defects like parties
   If you find a bug on one area, search for another one. You have an 80% chance to find one more in the same area. And only 20% chance of finding a defect in the next area. Unless the next area is another defects cluster.
5. Testing Principles V - Tests wear out (Beware of the pesticide paradox) (Nghịch lý thuốc trừ sâu)
   -
   - If the same tests are repeated and over again, eventually these tests no longer find any new defects.
   - Regression testing. When we run automated regression tests, we're ensuring that the software that we are testing is still working as it was before.
6. Testing Principles VI - Testing is context dependent (Kiểm thử phụ thuộc vào ngữ cảnh)
   -
   - Testing is done differently in deferent contexts.
7. Testing Principles VII - Absence-of-defects fallacy (Quan niệm sai lầm về "hết lỗi")
   -
   -  It is a fallacy (i.e., a misconception) to expect that software verification
will ensure the success of a system. Thoroughly testing all the specified requirements and fixing all the
defects found could still produce a system that does not fulfill the users’ needs and expectations, that
does not help in achieving the customer’s business goals, and that is inferior compared to other
competing systems. In addition to verification, validation should also be carried out
****
# QUIZ:

**Question #1 (1 Point) (c)**

Mr. Test has been testing software applications on mobile devices for a period of 5 years. 
He has a wealth of experience in testing mobile applications and achieves better results in a shorter time than others. 
Over several months, Mr. Test did not modify the existing automated test cases and did not create any new test cases. 
This leads to fewer and fewer defects being found by executing the tests. What principle of testing did Mr. Test not observe?
- a) Testing depends on the environment.
- b) Exhaustive testing is not possible.
- c) Repeating of same tests will not find new defects.
- d) Defects cluster together.
****
**Question #2 (1 Point) (1.3.724) (d)**

Which of the following account for most of the failures in a system?
- a) They will be found in the smallest modules.
- b) They will be evenly distributed among all modules.
- c) They will be found in the largest modules.
- d) They will be found in a small proportion of modules.
****
**Question #3 (1 Point) (1.3.254) (1-C, 2-A, 3-E)**

Which general testing principles(1-3) are characterized by the descriptions(A-F) below?

1. Testing shows the presence, not the absence of defects

2. Absence-of-defects fallacy

3. Defects cluster together

A. This testing principle emphasizes more than others the importance of validation, not just verification

B. If many defects were found be testers, the end users will be satisfied because the system will be stable

C. Testing can show that defects are present in the test object, but cannot prove that there are no defects.

D. The tester with the help of confirmation testing can show that defects haven’t been introduced or uncovered in unchanged areas of the software.

E. This principle is an illustration of the Pareto principle. (The Pareto Principle, also known as the 80-20 rule,)

F. Defects always have a pair, once you find one always look for another one.
****
**Question #4 (1 Point) (1.3.314) (d)**

As a result of risk analysis, more testing is being directed to those areas of the system under test where initial testing found more defects than average. 
Which of the following testing principles is being applied?
- a) Tests wear out.
- b) Testing is context dependent.
- c) Absence-of-defects fallacy
- d) Defects cluster together.
****
**Question #5 (1 Point) (1.3.721) (d)**

Which of the statements below is the best assessment of how the Testing principles apply across the test life cycle?
- a) Testing principles only affect the planning and test analysis activities.
- b) Testing principles only affect the design and test implementation activities.
- c) Testing principles only affect, the planning and test design test implantation activities.
- d) Testing principles affect activities throughtout the test life cycle.
****
**Question #6 (1 Point) (1.3.503) (b)**

Which of the following definitions BEST describes an exhaustive testing approach?
- a) A test approach in which the test suite comprises all combinations of output values and preconditions.
- b) A test approach in which the test suite comprises all combinations of input values and preconditions.
- c) A test approach in which the test suite comprises all combinations of output values and output values.
- d) A test approach in which the test suite comprises all combinations of pre-conditions and post-conditions.

****

**Question #7 (1 Point) (1.3.513) (b)**

A product owner says that your role as a tester on an Agile team is to catch all the bugs before the end of each iteration. 
Which of the following is a testing principle that could be used to respond to this (false) statement?
- a) Defect clustering
- b) Testing shows the presence of defects
- c) Absence of error fallacy
- d) Root cause analysis.
****
**Question #8 (1 Point) (1.3.199) (1-D, 2-A, 3-B)**

Which general testing principles(1-3) are characterized by the descriptions(A-F) below?

1. Exhaustive testing is impossible

2. Testing is context dependent

3. Early testing saves time and money

A. There is no single universally applicable approach to testing.

B. The cost of quality will be reduced since fewer failures will occur later in the SDLC.

C. The more defects found in the later stages of SDLS, the better the testers performed their job.

D. Test techniques, test case prioritization, and risk-based testing, should be used to focus test efforts to overcome challenges of this principle.

E. Regardless of the type and stage of the project, testers should always try to automate as many test cases as possible.

F. All lines of code cannot be tested, so the tester should write only those tests that cover the largest number of lines of code
****
**Question #9 (1 Point) (1.3.654) (b)**

For two weeks, the testing team tested four modules A, B, C, and D. At the moment, the testing is completed, but the testing team still has a spare day for exploratory testing. 
Modules A and B were quite simple, and it wasn't expected to have any problems with those. Modules C and D were large and complex, the development team coded those very carefully. 
Due to the complexity and significance of C and D modules, it was expected that a lot of defects would be found by the testing team. 
However, the situation was reversed, the testing team found many defects in Modules A and B, and only a few defects in Modules C and D.
On which modules should the testing team spend one day of exploratory testing if the goal is to find as many defects as possible?
- a) The testing team should concentrate on testing modules C and D as those are more complex.
- b) The testing team should concentrate on testing modules A and B as they may still have more undiscovered defects.
- c) The testing team should divide the testing time equally between modules A, B, C and D.
- d) The testing team should concentrate on testing modules C and D as the testing team already spent a lot of time on the simple modules A n B and a lot of issues were already discovered there.
****
**Question #10 (1 Point) (1.3.182) (b)**

A development team has defined two main testing objectives: 
verifying that a test object complies with regulatory requirements and validating whether the test object is complete and works as expected by the stakeholders. 
The verification process will be done by an independent testing team. 
For validation, it was decided to use two forms of acceptance testing, such as alpha testing and beta testing, to involve the end-users in testing as early as possible.
Which testing principle explains the desire to involve end-users in testing in addition to the testing team testing for validation purposes?
- a) Early testing saves time and money.
- b) Absence-of-defects fallacy.
- c) Testing is context dependent.
- d) Exhaustive testing is impossible.
****
**Question #11 (1 Point) (1.3.673) (b)**

The testing team consistently finds around 85% of the defects present in the system under test. 
The manager asked how long it takes the testing team to develop a regression test suite to find 100% of bugs. 
The testing team asked for three months. During this time, they have significantly improved the test coverage and increased the number of tests. 
However, the rate of defects found has only increased to 95%, and users are still finding bugs after the release. 
Most of these bugs relate to creating an email campaign that has different configurations on a test and production environment. 
Therefore, the testing team requests access to the production environment to be able to find all the bugs.
Is the test team right to ask for access to the production environment, why?
- a) The testing team is right, testing is context dependent.
- b) The testing team is wrong, exhaustive testing is impossible.
- c) The testing team is right, defects cluster together.
- d) The testing team is wrong, absence-of-defects fallacy.
****
**Question #12 (1 Point) (1.3.945) (b)**

What is the MAIN benefit of designing tests early in the life cycle?
- a) It is cheaper than designing tests during the test phases.
- b) It helps prevent defects from being introduced into the code.
- c) Tests designed early are more effective than tests designed later
- d) It saves time during the testing phases when testers are busy.
****
**Question #13 (1 Point) (1.3.730) (c)**

A new product for renting electric scooters is planned to be released next month. 
The testing team found a large number of bugs that were fixed. A good regression test suite has been written, from which all tests are automated. 
Stakeholders read reports from various departments and saw a recommendation in the test report. 
The test team advises conducting acceptance testing with real potential users. 
Stakeholders noted that a considerable part of the budget and that they did not understand why additional testing was needed.
Which of the testing principles will MOST help the team make the case for its recommendation?
- a) Test wear out.
- b) Exhausive testing is impossible
- c) Absence-of-defects fallacy
- d) Testing is context dependent
****
**Question #14 (1 Point) (1.3.923) (b)**

After launching a new online shopping platform, the company received feedback that users find the checkout process confusing, even though this feature passed all tests with no defects found. 
Which testing principle does this scenario illustrate?
- a) Test wear out.
- b) Absence-of-defects fallacy
- c) Exhausive testing is impossible
- d) Testing is context dependent
****
**Question #15 (1 Point) (1.3.741) (d)**
Which of the following is an example of addressing one of the testing principles?
- a) Test wear out, so you need to automate regression test suites
- b) Exhausive testing is impossible, therefore testing should be limited in time, and testers should try to fit into it.
- c) Due to the Absence-of-defects fallacy testing principle, the lower the level of test independence, the more bugs tester will find.
- d) Testing is context dependent, so test practices that have been applied successfully on one project may work poorly or not all all on another.
****
**Question #16 (1 Point) (1.3.912) (b)**

During testing, the team notices that a particular module consistently contains the majority of defects. 
How does this observation relate to the testing principle of "Defect clustering"? What actions should the team take based on this principle?
- a) It suggests that defects are evenly distributed across all modules, so no specific action is required.
- b) This aligns with the principle of "Defect clustering", indicating that a small number of modules contain the majority of defects. The team should prioritize testing efforts on this module.
- c) This aligns with the principle of "Defect clustering", indicating that a small number of modules contain the majority of defects. The team should prioritize testing efforts on other modules to find more defects.
- d) It emphasizes that testing should begin with the smallest modules firt, so the team should start testing other modules fisrt.
****
**Question #17 (1 Point) (1.3.755) (c)**

The users are dissatisfied with the online shop and find a lot of defects after each release. 
Most of the defects are found in the main functionalities like purchase, registration, shopping cart, and wishlist. 
The manager decides to hire an independent test team and gives them the task to write a comprehensive test suite, and automate all test cases, so those will be a part of the CI/CD process. 
After 2 months of work, the testing team presents the test pack. 
During the next 6 months, the users are generally happy with the system, and the failures that have occurred have generally been of low impact. 
However, after 3 months, the situation worsened significantly, and the level of satisfaction with the product returned to the level it was before; 
the users were unhappy about the online shop and started to leave for the competitor. 
The manager believes that the independent testing team did a poor job and schedules another call with them.

Which of the testing principles will be the MOST useful to explain the situation to the manager?
- a) Testing shows the presence, not the absence of defects
- b) Exhausive testing is impossible
- c) Test wear out.
- d) Defects cluster together.
****
**Question #18 (1 Point) (1.3.901) (b)**

A software development team is debating when to start testing their project. 
Some team members argue for postponing testing until all features are implemented, while others advocate for starting testing early. 
According to testing principles, what would be the most appropriate course of action in this scenario, and why?
- a) Start testing early to save time for automation testing in the future
- b) Start testing early to identify defects sooner and reduce the risk of late-stage issues
- c) Begin testing after all futures are implemented to minimize rework
- d) Delay testing untill after UAT to align with stakeholder expectations
****
**Question #19 (1 Point) (1.3.761) (c)**

What does the principle "Testing shows the presence of defects" imply?
- a) Testing can prove that a software product is defect-free
- b) Testing reduces the likelihood of undiscovered defects
- c) Testing can find defects, but cannot prove there are no defects
- d) Testing ensures that the software product meets its requirements
****
**Question #20 (1 Point) (1.3.890) (b)**

Which of the following is NOT a core testing principle?
- a) Exhausive testing is impossible
- b) Regression testing is essential 
- c) Testing is context dependent
- d) Defects cluster together.
****
**Question #21 (1 Point) (1.3.844) (a)**

The "Absence-of-defects fallacy" principle suggests that:
- a) The absence of known defects is not a good indicator of software quality
- b) A software product is useful and usable merely because it does not contain any defects
- c) Testing can find all defects in software
- d) High-quality software does not require testing.

















