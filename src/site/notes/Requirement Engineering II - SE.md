---
{"dg-publish":true,"permalink":"/requirement-engineering-ii-se/","tags":["notes"],"created":"2024-09-25T18:05:02.566+05:30","updated":"2024-09-25T23:23:44.040+05:30"}
---

# Requirements Gathering
![[Slide Set 5 - Reqt Gathering.pdf#page=2&rect=11,31,702,467|Slide Set 5 - Reqt Gathering, p.2]]
- Inception
- Elicitation
- Elaboration
	- This is where the gathered requirements are further refined and expanded. The details are discussed, and use cases or user stories are developed to clarify each requirement.
- Negotiation
- Specification
- Validation
- Requirements Management

# Inception
- the requirements engineer asks a set of questions to establish
- These questions focus on the customer, other stakeholders, the overall goals, and the benefits

# Elicitation
- Elicitation may be accomplished through two activities 
		- Collaborative requirements gathering 
		- Quality function deployment
	- In this step, stakeholders and users are engaged to gather the requirements. It involves techniques like interviews, questionnaires, and brainstorming sessions to discover what is needed.
	- ==Quality Function Deployment== (QFD) is a quality management technique that ==translates the needs of the customer into technical requirements for software==
		- ![[Slide Set 5 - Reqt Gathering.pdf#page=8&rect=44,55,681,335|Slide Set 5 - Reqt Gathering, p.8]]
		- ![[Slide Set 5 - Reqt Gathering.pdf#page=9&rect=53,22,685,484|Slide Set 5 - Reqt Gathering, p.9]]
- # Use Cases
	- A collection of user scenarios that describe the thread of usage of a system
	- Each scenario is described from the point-of-view of an “actor”—a person or device that interacts with the software in some way
	- ![[Slide Set 5 - Reqt Gathering.pdf#page=12&rect=152,28,628,506|Slide Set 5 - Reqt Gathering, p.12]]
- # Building the Analysis Model
	- Scenario Based
		- Functional
		- Use case
	- Class Based
		- Implied by scenarios
	- Behavioural Based
		- state diagram
	- Flow oriented
		- data flow diagram
- # Class diagram
- ![[Slide Set 5 - Reqt Gathering.pdf#page=14&rect=147,113,425,389|Slide Set 5 - Reqt Gathering, p.14]]
- # State diagram
- ![[Slide Set 5 - Reqt Gathering.pdf#page=15&rect=236,170,519,370|Slide Set 5 - Reqt Gathering, p.15]]

# Elaboration
- During elaboration, the software engineer takes the information obtained during inception and elicitation and begins to expand and refine it
- It is an analysis modeling task 
	– Use cases are developed 
	– Domain classes are identified along with their attributes and relationships 
	– State machine diagrams are used to capture the life on an object
- The end result is an analysis model that defines the functional, informational, and behavioral domains of the problem

# Negotiation
- During negotiation, the software engineer ==reconciles the conflicts between what the customer wants and what can be achieved given limited business resources== 
- ==Requirements are ranked== (i.e., prioritized) by the customers, users, and other stakeholders
- Using an iterative approach, requirements are eliminated, combined and/or modified so that each party achieves some measure of satisfaction

# Specification 
- A specification is ==the final work product== produced by the requirements engineer.
- normally in the form of ==Software Requirements Specification== ( SRS )
- It formalizes the informational, functional, and behavioral requirements of the proposed software in both a graphical and textual format

# Validation
- the work products produced as a result of requirements engineering are assessed for quality
- the specification is examined to ensure that
	 – all software requirements have been stated unambiguously 
	 – inconsistencies, omissions, and errors have been detected and corrected 
	 – the work products conform to the standards established for the process, the project, and the product
 - The formal technical review serves as the primary requirements validation mechanism 
	 – Members include software engineers, customers, users, and other stakeholders

# Requirement Management
- During requirements management, the project team performs a set of activities to identify, control, and track requirements and changes to the requirements at any time as the project proceeds
- Each requirement is assigned a unique identifier 
- The requirements are then placed into one or more ==traceability tables==
- A ==requirements traceability table is also placed at the end of the software requirements specification==