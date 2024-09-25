---
{"dg-publish":true,"permalink":"/requirement-engineering-i-se/","tags":["notes"],"created":"2024-09-25T17:41:08.553+05:30","updated":"2024-09-25T23:23:29.283+05:30"}
---


Requirements engineering is the process of establishing 
- the services that the customer requires from a system 
- the constraints under which it operates and is developed

## Types of requirements
may range from high-level abstract statement of a service or a system constraint to a detailed mathematical functional specification
- User 
	- statements in Natural Language plus diagrams of the services 
- System
	- structured document setting out detailed descriptions of the system services. Written as a contract between the client and contractor.
- Software
	- A detailed software description which can serve as a basis for a design or implementation. Written for developers

![Requirement Engineering I - SE ( RequirementReaders ).png](/img/user/Attachments/Requirement%20Engineering%20I%20-%20SE%20(%20RequirementReaders%20).png)

## Functional and non-functional requirements ( they should be complete and consistent )
- Functional ( basic input/output and behavioural situations )
	- Statements of services the system should provide, how the system should react to particular inputs and how the system should behave in particular situations.
	- example
		- The user shall be able to search either all of the initial set of databases or select a subset from it.
		- The system shall provide appropriate viewers for the user to read documents in the document store. 
		- Every order shall be allocated a unique identifier (ORDER_ID) which the user shall be able to copy to the account’s permanent storage area.

- Non-functional ( timing constraints, time for the project )
	- constraints on the services or functions offered by the system such as timing constraints, constraints on the development process, standards, etc.
	- ![Requirement Engineering I - SE (nonfunctionalRequirements).png](/img/user/Attachments/Requirement%20Engineering%20I%20-%20SE%20(nonfunctionalRequirements).png)
	- ![Requirement Engineering I - SE (nonfunctionalClassifications).png](/img/user/Attachments/Requirement%20Engineering%20I%20-%20SE%20(nonfunctionalClassifications).png)

## Domain requirements
- Derived from the application domain and describe system characteristics and features that reflect the domain
- May be new functional requirements, constraints on existing requirements or define specific computations
- If domain requirements are not satisfied, the system may be unworkable

## User requirements
- Should describe functional and non-functional requirements so that they are understandable by system users who don’t have detailed technical domain knowledge
- User requirements are defined using ==natural language==, ==tables== and ==diagrams==

# Guidelines for writing requirements
- Invent a standard format and use it for all requirements
- Use language in a consistent way. Use 
	**shall** for ==mandatory== requirements, 
	**should** for ==desirable== requirements
- Use text highlighting to identify key parts of the requirement
- Avoid the use of computer jargon !!!
- **requirements** should state ==what the system should do== and 
   the **design** should describe ==how it does this==



