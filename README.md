CS 320 Module Three Milestone Guidelines and Rubric
Overview
As you have learned in Modules One and Two, various types of software testing can be employed for a given situation. For this assignment, you will be creating unit tests using code to uncover errors for a mobile application. You will develop the contact service and contact object.

Prompt
For Project One, which is due in Module Six, you are asked to develop a mobile application for a customer. The customer will provide you with the requirements. Your job is to code the application and provide unit tests to verify that the application meets the customer’s requirements. For this milestone, you will focus on delivering the contact services. The purpose of these services is to add, update, and delete contact objects within the application.

The contact service uses in-memory data structures to support storing contacts (no database required). In addition, there is no user interface for this milestone. You will verify the contact service through JUnit tests. The contact service contains a contact object along with the contact service. The requirements are outlined below.

Contact Class Requirements

The contact object shall have a required unique contact ID string that cannot be longer than 10 characters. The contact ID shall not be null and shall not be updatable.
The contact object shall have a required firstName String field that cannot be longer than 10 characters. The firstName field shall not be null.
The contact object shall have a required lastName String field that cannot be longer than 10 characters. The lastName field shall not be null.
The contact object shall have a required phone String field that must be exactly 10 digits. The phone field shall not be null.
The contact object shall have a required address field that must be no longer than 30 characters. The address field shall not be null.
Contact Service Requirements

The contact service shall be able to add contacts with a unique ID.
The contact service shall be able to delete contacts per contact ID.
The contact service shall be able to update contact fields per contact ID. The following fields are updatable:
firstName
lastName
Number
Address
What to Submit
To complete this project, you must submit a Contact Service zipped folder containing the following deliverables:

Contact.java
ContactService.java
ContactTest.java
ContactServiceTest.java

