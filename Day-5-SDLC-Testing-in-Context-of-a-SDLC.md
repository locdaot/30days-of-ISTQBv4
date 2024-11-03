# 2.1. TESTING IN THE CONTEXT OF A SDLC
> A software development lifecycle (SDLC) model is an abstract, high-level representation of the software
development process. A SDLC model defines how different development phases and types of activities
performed within this process relate to each other, both logically and chronologically. Examples of SDLC
models include: sequential development models (e.g., waterfall model, V-model), iterative development
models (e.g., spiral model, prototyping), and incremental development models (e.g., Unified Process).
Some activities within software development processes can also be described by more detailed software
development methods and Agile practices. Examples include: acceptance test-driven development
(ATDD), behavior-driven development (BDD), domain-driven design (DDD), extreme programming (XP),
feature-driven development (FDD), Kanban, Lean IT, Scrum, and test-driven development (TDD).
## 2.1.1 IMPACT OF THE SDLC ON TESTING
Testing must be adapted to the SDLC to succeed. The choice of the SDLC impacts on the: <br/>
1. Scope and limit of testing activities
2. Level of detail of test documentation.
3. Choice of test techiques and test approach.
4. Extend of test automation.
5. Role of responsibities of tester.
   
## 2.1.2 SDLC AND GOOD TESTING PRATICES

## 2.1.3 TESTING AS A DRIVER FOR SOFTWARE DEVELOPMENT

![napkin-selection-2](https://github.com/user-attachments/assets/d19f9931-cb9b-46d6-b881-a05ce8034444)

### TEST-DRIVEN DEVELOPMENT (TDD) <br/>
Direct the coding through testcases <br/>
Tests are written first, then the code written to satisfy the tests and then the tests and code are refactored <br/>
### ACCEPTANCE TEST-DRIVEN DEVELOPMENT (ATDD) <br/>
Derives tests from acceptance criateria as a part of the system design process.<br/>
Tests are written before the part of the application is developed to satisfy the tests.<br/>
### BEHAVIOR-DRIVEN DEVELOPMENT (BDD)<br/>
Expressed the derives behavior of the application with the testcases are written in a simple form of natural language <br/>
(using Given, When, Then format)<br/>
The test cases are the automatically translated into excutable tests.<br/>

## 2.1.4 DEVOPS AND TESTING
technical practice: <mark> Continuous Integration (CI) and Continous Delivery (CD) </mark> This enables the teams to build, test and release high-quality code faster through a DevOps
delivery pipeline <br/>
## 2.1.5 SHIFT-LEFT APPROACH
The principle of early testing is sometimes referred to shift-left<br/>
Shift-left nomarlly suggests that testing should be done earlier (... not wating for code to be implemented or for components to be integrated)
but it does not mean that testing later in SDLC should be neglected.

![napkin-selection-3](https://github.com/user-attachments/assets/9b576204-591f-47fa-aef6-20e980665c2f)
## 2.1.6 RETROSPECTIVES AND PROCESS IMPROVEMENT
Retrospectives (also known as “post-project meetings” and project retrospectives) are often held at the
end of a project or an iteration, at a release milestone, or can be held when needed. <br/> The timing and
organization of the retrospectives depend on the particular SDLC model being followed. <br/> In these
meetings the participants (not only testers, but also e.g., developers, architects, product owner, business
analysts) discuss:<br/>
• What was successful, and should be retained? <br/>
• What was not successful and could be improved?<br/>
• How to incorporate the improvements and retain the successes in the future?<br/>
<img width="432" alt="Screenshot 2024-11-03 at 16 08 31" src="https://github.com/user-attachments/assets/ad76c882-e463-4c80-b970-0ca16edb341e">



