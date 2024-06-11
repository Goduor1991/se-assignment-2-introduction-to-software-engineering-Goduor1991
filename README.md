[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15251610&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
software enginnering is the application of engineering principles and methods that involves the design, development,testing  and deployement of software products.


What is software engineering, and how does it differ from traditional programming?
Software enginnering involves an iterative development process,where software is contineously refined and improved based on user feedback while on the other hand traditional programming is a convetional approach of writting code to create specific instructions for a computer to follow.

Software Development Life Cycle (SDLC):
Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
1. Requirements : gathering resources and documenting what is required for a system
2. Design: Coming up with the user interface
3. Implementation: this is the coding part of the software according to the design usign a programming language e.g python.
4. Testing: this involved running a test of the software in order to meet rfequired standards.
5. Deployment: this involves releasing the software to the customers.
6. Maintance: after deployment of the software to the customer, maintanance involves running updates and adding some improved features that were not in the software during deployment.

Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
1.Agile
 Is a type of software development methodology that anticipates the need for flexibility and applies a level of pragmatism to the delivery of fineshed products.
 it is used is a scenario where a team collaborates together and understand their specific roles in the process, testing is done throughout the process of development thus giving an opportunity to make changes as needed and alert teams to any potential issues.

 2. Waterfall
 This is a linear,sequential approach to software development.Development teams must complete each phaseentirely beforet they move onto the next phase.
 it works best in projects that require less complex objectives i.e projects that dont have complicates requirements.

Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
- Requirements engineering is a strict approach to the defination,creation and verification of requirements for a software system to guaranteee the effective creation of a software product.

Requirements Engineering Process.
1. Feasibility study - Feasibility study decides whether or not the proposed system is worthwhile. if the system contributes to the organisational objectives, if the system can be engineered using the current technology and within budget, if the system can be intergrated with other systems that are used. In other words feasibily study is used to justify a project, it compares various implementation alternatives based on their economic (cost and benefit of the project), technical (current resources both hardware and softwarerequired to develop the project) and operational (how easy the product will be to operate and mantain after deployement).

2. Requirement elicitation - This is the use of various ways to gain knowledge about the project domain and requirements. The various sources of domain knowledge include customers,business manuals, the existing software of the same type,standards,and other stakeholders of the project. The techniques used for requirements elicitation include:

*interviews - this is a one-on-one conversations with stakeholders to gather information about their needs and expectationsfor the software system.

*survey - these are questionnaires about there needs and expactations.

*focuus groups - these are small groups of stakeholders whos are brought together do discuss their needs and expectations for the software system.

*observation - this technique involves observing the stakeholders in their work envairoment to gather information about their needs and expectations.

*prototyping  - this technique involves creating a working model of the software system, which can be used to gather feedback from stakeholders and to validate requirements.

3. Requirement specification - This activity is used to produce formal software requirement models. All the requirements including the functional as well as the non-functional requirements and the constraints are specified by these models in totality.Below are some of the requirements commonly specified.

* functional requirements - these describe what the software system should do e.g inpiut validation, data storage and user interface.

* non-functional requirements - these describe how well the software system should do it e.g performance,reliability, userbility and security.

* constraints - this descibes the limitations and restriction that must be considered when developing the software system.

* acceptance criteria - these describes the conditions that must be met for the software system to be considered complete and ready for release.

4. Requirements verificstion and validation

verification - it refers to the set of tasks that ensures that the software correctly implement a specific function.
Validation - It refers to a different set of tasks that ensures that the software that has been built is traceable to customer requirements.If requirements are not validated, errors in the requirement definitions would propagate to the successive stages resulting in a lot of modification and rework. 

5. Requirements management - is the process of analyzing, documenting, tracking, prioritizing, and agreeing on the requirement and controlling the communication with relevant stakeholders. This stage takes care of the changing nature of requirements. below are key factors in requirement management.

* Tracking and controlling changes -  this involves monitoring and controlling changes to the requirements throughout the development process, including identifying the source of the change, assessing the impact of the change, and approving or rejecting the change.
* Version control -  this involves keeping track of different versions of the requirements document and other related artifacts.
* Traceability - this involves linking the requirements to other elements of the development process, such as design, testing, and validation.
* Communication -  this involves ensuring that the requirements are communicated effectively to all stakeholders and that any changes or issues are addressed promptly.
* Monitoring and reporting - this involves monitoring the progress of the development process and reporting on the status of the requirements.


Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Testing in Software Engineering:
modularity is a concept that involves encapsulating information within a module,exposing only what is only neccessary throutgh a well defined interface and hiding the rest. This seperation of concerns ensures that individual modules can operate independently while interacting through strictly defined interfaces.
* in regards to maintainability, changes in in one module typically does not affect others, making bugs easier to track down and fix without risking other parts of the system.

* scalability - modular systems can be scaled more readily by adding new modules or enhancing existing ones without impacting the rest of the system.

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

* levels of software testing refers to the different phases or stages of testing software during its development cycle. Below are some of the stages.

1. unit testing - also reffered to as component testing is done at the code level, where each component is tested individually to ensure their impatiability and analyse their functionality.

2. integration testing - enables software testers to test group units integrated into a system or subsystems, it helps identify any bugs or issues arising from coding errors or integrations between modules. it is possible to automate intergration testing.

3. system testing - this is performed on an integrated envairoment comprissing the whole application, where all components are assed against specific business requirements. You can use automation tools for system testing.

4. Acceptance testing - involves testing the system functional and non-functional aspects, such as performance,security, usability,accessibility,compatiability and reliability.

* in conclussion testing is a neccessary process that gurantees the software does what it should and meets all the requirements.



Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
* version control system - these are software tools that help software teams manage changes to source code over time. version control system play a very important role in software development as it streamline the collaboration process,enabling developers to work efficiently and deliver projects at a faster pace. by providing a centralized repository for managing changes, version control systems eliminates the need of manual coordination and ensures all team members are on the same page.

* Examples of VCS include Git and its key features are tracks history,free and open source,supports n0n-linear development,creates backups and also supports collaboration.

* Github is anothet example of a VCS that allows teams to collaborate and maintain  the entire history of code changes.

* GitLab is another example of VCS that comes in handy with features like an intergarted project, a project website etc.

Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
Software Maintenance:
* in software development a project manager oversees the planning, execution and delivery of software projects.
 
 Below are some of the challenges faced in managing software projects.

 1. Changing requirements - requirements might change during the development cycle which make it difficult to design a software that meets user needs.
 2. Tight deadlines - presure to deliver software products on schedule can result to rushed development and compromised quality.
3. Technical debt - technical debt can impede future development efforts and increase maintainance cost.


Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
* software maintenance is the process of modifying, changing, and updating a software system or module to resolve errors, improve performance or adapt to a changing envairoment.

* Below are types of softaware maintance activities.
1. Corrective software maintenance addresses the errors and faults within a software application that could impact various parts of your software icludind the design, logic and code. This reports usually come from bug reports that were created by users or customers.

2. Adaptive maintenance - adaptive maintenance becomes important when the envairoment of you software changes. This can be brought by changes to the operating system,hardware,software dependancies,cloud storage or even changes within the operating system.
3. perfective maintenance - perfective maintenance focuses on the evolution of requirements and features that existing in your sytems. As users interract with your application, they may notice things that you did not or suggest new features that they would like as part of the software.
4. Preventive maintenance - preventive maintenance helps to make changes and adaptations to your software so that it can work for a longer period of time. The focus on this type of maintenance is to prevent the deteriotation of your software as it continues to adopt and change.

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethicalstandards in their work?
* software engineers might face the below ethical issue in their field of work. this includes:
1. conflict of interest
2. bribery
3. inadequate information about a potential negative effects of products and technologies.

* in the softwware enginnering field, engineers can adhere to to ethical standardsby balancing their proffesional obligations within their ethical responsibilities, this might involve pushing back against the requests , seeking advice from collegues or proffessional bodies or in extreme cases, considering whether they can continue working under such conditions.

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
