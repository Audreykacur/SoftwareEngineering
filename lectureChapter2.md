Lab: Have slides and present them within two lab times 
Homework: submit a new vision based on the feedback

Chapter 2 ...


Unified Process
• Unified Process 
	- iterative (repreat the same steps with diffrerent requirements) andincremental software development process framework.
• It should be customized for a specific organization or project.
• It uses the UML.
• Rational Unified Process is its commercial variant.



| Iteration 1 | Iteration 2 | Iteration 3 |Iteration 4 | End of Project |
- Requirement workshop before you start iterations (high level description)
- choose 10 - 15% for iteration 1 


Day 1 + 2: Requirements Workshop
• High-level requirements analysis: identify the names of use cases and key non-functional requirements.
• Select 10-15% of the use cases that have these qualities:
	o Architecturally significant : prioritize relationships based on architectural significance (used the most often or generate revenue)
	o High business value : prioritze risky requirements (integrating with a legacy system)
	o High risk
• Do detailed analysis of the functional and non-functional requirements for the selected use cases.

 ** what are examples of functional and non-functional requirements **


Next Three or Four Weeks: Iteration 1
• Denote the use cases selected during the requirements workshop UC2, UC11, UC14
• Before iteration 1, select a subset from UC2, UC11, UC14 that you design, build, and test within a specified time (e.g. four-week timeboxed iteration).

- use case is how the system is suppose to be used 


Iteration 1
• First two days: 
	o do modeling and design work in pairs
	o sketching UML diagrams at whiteboards in a common room (take a photo for later use)
	o guided by the chief architect
• Then start programming, testing, and integrating continuously over the remaining weeks, using the modeling sketches as a starting point of inspiration, knowing that the models are partial and often vague.
• Do various kinds of testing :
	-  unit : test each method/ unit or function (automated: write code to test code; write a function that solves a quadratic equation and use the method to see if the result is correct; test how ever many times that you need to hit all the solution possibilities)
	- acceptance : test each use case
	- load : test non functional requirements (simulate 10,000 users; use the user to test the system under a heavy load)
	- usability : test tests the user interface (design a user inteerface so it is intuative; so you can usee the interface withhout 					  training; how difficult is it for a user to complete a simple task)

• One week before the end of iteration, ask the team if the original iteration goals can be met.
	o If not, de-scope the iteration and put some goals back on the “to do” list.

• On Tuesday of the last week there is a code freeze; all code must be checked in (all code in a common repository), integrated, and tested.
• On Wednesday morning, demo the partial system to external stakeholders and ask for feedback.
• Do the second requirements workshop near the end of iteration 1
	- such as on Wednesday and Thursday (when finished, perhaps 25% of the use cases and non-functional requirements will be written in detail).
	- select the next UC requirements that you will analysis and implement iin the second iteration
• On Friday morning, hold a planning meeting for the next iteration.


Iterations 2 to 6
• Repeat for iterations 2, 3, 4, 5 and 6.
• At the end of iteration 6, perhaps 70-90% of the requirements have been written in detail (analysied), but only 20 - 50% of the system has been implemented.
	- we don't need to analyse requirements after this 
• We are perhaps only 30% into the duration of the overall project; this is the end of the elaboration phase.


| elaberation phase 1- 6 | construction phase 7 - 15 (spend more time on implementation and testing) |


Risk-Driven and Client-Driven
• Risk-driven (implement the risky requirements first; have plan of how to midigate them) and client-driven (what requirements are important to the client) iterative planning means that the goals of the early iterations are chosen to
	o Identify and drive down the highest risks.
	o Build visible features that the client cares most about.


Architecture-Centric
• Architecture-centric iterative development means that early iterations focus on building, testing, and stabilizing the core architecture.
	o Not having a solid architecture is a common high risk.
	- build a stable architecture as soon as possible 
	- architecture : high level description of the architecture
	- web browser - conected both ways - web server - connected --> database 
			     									- connected --> identity manager
	- if you need identity manager do those as soon as possible 		     									


UP Best Practices
• Tackle high-risk and high-value issues in early iterations.
• Continuously engage users for evaluation, feedback, and requirements.
• Build a cohesive, core architecture in early iterations.
• Continuously verify quality; test early, often, and realistically.
• Do some visual modeling (with the UML).
• Carefully manage requirements.
• Practice change request and configuration management.


UP Phases
• Inception – approximate vision, business case, scope, vague estimates
• Elaboration – refined vision, iterative implementation of the core architecture, resolution of high risks, identification of 								most requirements and scope, more realistic estimates
• Construction – iterative implementation of the remaining lower risk and easier elements, and preparation for deployment
•Transition – beta tests, deployment


UP Disciplines
• Business modeling –the domain model that visualizes noteworthy concepts in the application domain.
• Requirements –the use case model and supplementary artifacts to capture functional and non-functional requirements.
• Design –the design model visualizes software classes.



Unified Process
ADIT



Task 
- use unified process to implement a information system called library
- requirements for an information system 

- use cases 
	- veiw transaction or transfer money: describes the interaction between the user and the system and usually has a result 
		- in english text or a diagram
		- model the system and understand the process


- FIRST STEP: What are the requirements for the system to find a book
	- its important to have all the requirements  
		- library card
		- return and checkout books 
		- support late fees
		- book sorting 
		- function: allows librarian to add, delete and modify books 
		- view leases and history for librarian and or user 
		- request book 
		- recommend books based on other books you have read 
		- rating system 
		- sign up 
		- view analytics


		- find book 


o  Library example: 
	- implement recommend a book 
	 	- you need information abou the book and a copy of the book 
		- how do you recommned the book : genre, author, rating 
	 		- do we want to recommend based on a single book or from the users hisory 
	 	      we will do it based on a single book that the user has read 




- what are the important requirements 
- non functional requirements are specific 













