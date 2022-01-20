POWER POINT NOTES

Analysis
- Analysis focuses on an investigation of the problem and requirements.
	“What will the system do?”
		--> do how solve how the system will work
	E.g.: also called:
	- Requirements analysis – an investigation of the requirements
	- Object-oriented analysis – an investigation of domain objects

	An example:
		Requirements for internet banking (local: 50,000 customers)
		- secure 
		- authentication
		- must run for 50,000 users
		- 10,000 users should be able to concurently use the system  (non-functional)
		- profiles for user, supports currencies
		- view transactions 
		- look at balence 
		- transfer money 
		- apply for debit or credit card
		- dispute transactions

		- we dont talk about how we are going to create it 


Design
- Design focuses on a conceptual solution that fulfills the requirements, rathe than on implementation.
	“How will the system fulfill the requirements?”
	E.g.:
	- Object-oriented design – design of software objects
	- Database design – design of database schema


	- design a system that will support user profiles (banking example)
	- this is not implementation 


Concept Definition
- What is a concept? An idea, thing, or object.
	An object can be:
	- Represented symbolically 
	- Defined or described 
	- Exemplified 
	Examples:
	- Agency
	- Applicant

	- Account, user, internet banking (banking system)
	- conceptual class - transaction (not a programming class: just something we want to describe)




Model
- We will use models when developing software.
- Model is a simplification of reality which helps to better understand the system under development.
- We will visualize models using Unified Modeling Language (UML).

- we simplify the reality(the system) talk about the system in a simplified way
- remove details we dont want to talk about now 



Engineering Approach
- Before we start with software development, we will model and visualize the system.
- We will use established notation, methods, and workflows.
- The software will be programmed according to the model that was created by the software architect, analyst, and designer. (use the model to program the system)

- one person can be an architect, analyst, and designer or the roles could be split up


	example: Library
		- use cases 
				- veiw transaction or transfer money: describes the interaction between the user and the system and usually has a result 
				- in english text or a diagram
		- 
				- model the system and undeerstand the process
		- 
				- 

				- 

Use cases (example a banking system)
	create a scenario that descibes the interactions of the system in detail 
	1.	user fills in the currency amount 
	2.  user summits the form 
	3.  system chacks to make sure information is entered properly 
	4.  if correcct system will allow transaction



Domain model (Analysis step: conceptual level)
- Domain model is not a description of software objects.
- It is a visualization of the concepts (it is also called a conceptual object model).

- describes just the problem : creatd so we understand the problem 
- this is how to undersstand the requirements 





These diagrams show software classes.
- Sequence diagram = dynamic view of collaborating objects
	
- Class diagram = static view of collaborating objects
	- code can be slightly different 
	- use a white board and marker do not create documents of these 

“The Unified Modeling Language (UML) is a visual language for specifying, constructing and documenting the artifacts of systems.”
- Visual = diagramming notation for drawing or presenting pictures (with some text)





Three Ways to Apply UML
- UML as sketch – informal and incomplete diagrams created to explore difficult parts of the problem or solution.
	- dont want them to be complete or perfect
	- we do this to clarify something ex. how a probelem will be solved
	

- UML as blueprint – relatively detailed design diagrams used either for
	- Reverse engineering: to visulize and better understand exsisting code in UML diagrams 
	- Code generation (forward engineering)

- UML as programming language : 






Three Perspectives to Apply UML
- Conceptual perspective – the diagrams describe real things.
	- talk about concepts
	- analysis
- Specification (software) perspective – the diagrams describe software abstractions or components with specifications and interfaces.
	- describe classes (like java classes)
	- can be created in different languages 
	- design
- Implementation (software) perspective – the diagrams describe software implementations in a particular technology
	- could be bound to specific technology
	- design




- FIRST STEP: What are the requirements for the system to find a book
	- its important to have all the requirements  
		- library card
		- return and checkout books 
		- support late fees
		- find book + sorting 
		- function: allows librarian to add, delete and modify books 
		- view leases and history for librarian and or user 
		- request book 
		- recommend books based on other books you have read 
		- rating system 
		- sign up 
		- view analytics


 Unified Process
 
- A software development process describes an approach to building, deploying, and possibly maintaining software.
	- maintenece : fixing bugs and errors in a system, upgrading to a new operating system 
	- when you deploy a sysem with a client typically it will require work after implementation 
	- create new versions of the system 

- The Unified Process is an iterative software development process for building object-oriented systems.
	- Agile Unified Process (UP)
		- imediatly take action when a change is required 

- SECOND STEP: find the requirements you want to complete for the first interation (Analysis: before writing code)
		- INTERATION 1: Find a book and sorting & check out a book 
	- analysis of requirements in detail
	- 
	- interations 4 weeks 
	-  select requirements --> write down scenarios --> design partial system --> implement partial system --> test the result --> partial system --> show to user --> feedback --> modify the system --> iteration 2

	- ITERATION 2 : return book and add book


Iterative Development
- **INTERATIONS** 
- Development is organized into a series of short, fixed-length (for example, threeweek) mini-projects called iterations.

- The outcome of each iteration is a tested, integrated, and executable partial system.

- Each iteration includes its own requirements analysis, design, implementation, and testing.

- The system grows incrementally over time, iteration by iteration, and thus this approach is also known as iterative and incremental development.

- Because feedback and adaptation evolve the specifications and design, it is also known as iterative and evolutionary development.

- Each iteration involves choosing a small subset of the requirements, and quickly designing, implementing, and testing.

- The act of taking a small step before all requirements are finalized, or the entire design is speculatively defined, leads to rapid feedback from the users, developers, and tests (such as load and usability tests).



- You receive 20 requirements 
- dont develop all the requirements in one step
- you select something like 2 requierments 
- analysis two requirements in detail 
- design partial system 
- implement partial system that solves the two requirements you have choosen 
- this takes 4 weeks or so 

- next you take two or three more and repeat with integration with what you already have and you have another partial system that you show the customer 

- in the beggining you do multiple senerios, implement, test it, partial sysem is complete, and show the system to the customer, get feedback, this is not a problem b/c we welcome the feedback and fix the system to fix the requierments 
	- sometimes the requirements are misunderstood and reqirements can get confused 

- why do we use iterations 
	- you could do it without iterations but it could "waterfall" there are many projects that fail (40%) so the approach when you implement all at once has a higher chance of failure 
	- this fixes the crisis in software engineering 
		- budget and time frame is not ensured to be met 
		- better productivity 
		- less bugs/ better programs 

	- what could you risk in internet banking 
		- you have technology and budget
			- technology you have can't meet requirements 
			- a possibility of failure is always there 

	- when you create a system you usually implement it with a system that already exsists (LEGACY SYSTEM) 
		- spent a lot of money on the legacy system 
				- could be a point of failure if you cant implement the new system with the legacy system 
				- if you fail within the first iteration its better to know then then after 6 months 
				- midigation of high risk 

				- you can start with the risky requirements first 





Benefits of Iterative Development
- Less project failure, better productivity, and lower defect rates
- Early rather than late mitigation of high risks (technical, requirements, objectives, usability, and so forth)
- Early visible progress
- Early feedback, user engagement, and adaptation leading to a refined system that more closely meets the real needs of the stakeholders.
- Managed complexity; the team is not overwhelmed by “analysis paralysis”.
- The learning within an iteration can be methodically used to improve the development process itself.
	
	- you can have someone from the buisness that knows what they want in the system to be a part of the development team 
	- take what works for you and accomidate it to the situation 



Timeboxing
- A typical iteration lasts between two and six weeks.
	- fixed length iteration
	- DESCOPE - if requirements cant be meet they will be postponed (will be a partial iteration: ex. you may not be able to transfer money)
- A key idea is that iterations are timeboxed (fixed in length).
- If it seems that it will be difficult to meet the deadline, the recommended response is to remove tasks or requirements from the iteration, and include them in a future iteration, rather than slip the completion date



Waterfall
- In a waterfall (or sequential) lifecycle process, there is an attempt to define (in detail) all or most of the requirements before programming.
- It is strongly associated with high rates of failure, lower productivity, and higher defect rates (than iterative projects).
- Analysis -> Design -> Implementation -> Testing -> Deployment 

Change in Software Development
- Change is the constant on software projects.
- Any analysis, modeling, development, or management practice based on the assumption that things are long-term stable is fundamentally flawed.
- Iterative and evolutionary methods assume and embrace change and adaptation of partial and evolving specifications, models, and plans based on feedback.







