# Lab Report: Architecture

___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Sebastian Alejos
**GitHub Handle:** SebastianAlejos
**Repository:** <https://github.com/SebastianAlejos/cis411_lab2_arch>
**Collaborators:**
___

# Step 1: Confirm Lab Setup

- [x] I have forked the repository and created my lab report
- [x] I have reviewed the [lecture / discsussion](../assets/04p1_SolutionArchitectures.pdf) on architecture patterns.
- [x] If I'm collaborating on this project, I have included their handles on the report and confirm that my report is informed, but not copied from my collaborators.

# Step 2: Analyze the Proposal
Serve Central ... ENTER A BASIC SYSTEM INTRODUCTION HERE (1-2 Sentences).

This system would allow a user to find service oportunities near them. It would also allow organizations to find volunteers in their area.

## Step 2.1 Representative Use Cases  

| Use Case #1 | |
|---|---|
| Title | User Signs up to volunteer at a service oportunity|
| Description / Steps | The user selects and confirms the service opportunity. |
| Primary Actor | Volunteer User.|
| Preconditions | 1. User has signed in. </br> 2. Service opportunity is still available. </br> 3. Service opportunity need volunteers.|
| Postconditions | 1. Confirmation of attendance is stored in the database.</br> 2. Confirmation of attendance is notified to user and organization.|

| Use Case #2 | |
|---|---|
| Title | Organization wants to set up an event|
| Description / Steps | Organization needs to put up an event for volunteers to be able to find it.|
| Primary Actor | Organization|
| Preconditions | 1. The user has signed into the organization account. </br> 2. The user enters the information for the event and saves it.|
| Postconditions |1. The event is saved in the database. </br> 2. The event is displayed in the events page.|

## Step 2.2 Define the MVC Components

| Model | View | Controller |
|---|---|---|
|Service Opportunities|Events List|ShowEvents  |
|Profile|Account Page|ShowProfile |
|Event location|Event information page|ShowEvent|
|Volunteers| Event Page|SignUp|

## Step 2.3 Diagram a Use Case in Architectural Terms

This is the use case for the Volunteers model.

![Volunteer Use Case](/assets/usecase.png)

# Step 3: Enhancing an Architecture

## Step 3.1 Architecture Change Proposal
INSERT Architectural change proposal here, and how it meets the two new requirements.  Explain both the benefits and draw backs of your proposal.

## Step 3.2 Revised Architecture Diagram
INSERT IMAGE HERE with a Description.

# Step 4: Scaling an Architecture
INSERT Architectural change proposal here, and how it meets the four new requirements.  Explain both the benefits and draw backs of your proposal.  If the changes are significant, then you need to explain why the changes are necessary versus a nice-to-have enhancement.

# Extra Credit
If you opt to do extra credit, then include it here.