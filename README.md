# CS-320-Software-Automation

**Given Scenario:**
You are a software engineer for Grand Strand Systems, a software engineering company specializing in developing and testing back-end services. You’ve been given the assignment to develop a mobile application for a customer. The customer will provide you with the requirements. Your job is to code up the application and provide unit tests to verify that it meets the customer’s requirements. In addition, you will be delivering the contact, task, and appointment services. These services aim to add, update, and delete contact, task, and appointment objects within the application.

**Given Direction for the following projects:**

ContactService, TaskService, and AppointmentService Files
For this assignment, you will incorporate the code and unit tests that you have developed for the mobile application:
You developed the contact service and contact object, which you completed in the Module Three milestone.
You developed the task service and task object, which you completed in the Module Four milestone.
You developed the appointment service and appointment object, which you completed in the Module Five milestone.

**Contact Service**:

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

**The Task:**
The task service uses in-memory data structures to support storing tasks (no database required). In addition, there is no user interface for this milestone. You will verify the task service through JUnit tests. The task service contains a task object along with the task service. The requirements are outlined below.

Task Class Requirements
The task object shall have a required unique task ID String that cannot be longer than 10 characters. The task ID shall not be null and shall not be updatable.
The task object shall have a required name String field that cannot be longer than 20 characters. The name field shall not be null.
The task object shall have a required description String field that cannot be longer than 50 characters. The description field shall not be null.
Task Service Requirements
The task service shall be able to add tasks with a unique ID.
The task service shall be able to delete tasks per task ID.
The task service shall be able to update task fields per task ID. The following fields are updatable:
Name
Description

**The appointmnet:**

The appointment service uses in-memory data structures to support storing appointments (no database required). In addition, there is no user interface for this milestone. You will verify the appointment service through JUnit tests. The appointment service contains an appointment object along with the appointment service. The requirements are outlined below.

Appointment Class Requirements
The appointment object shall have a required unique appointment ID string that cannot be longer than 10 characters. The appointment ID shall not be null and shall not be updatable.
The appointment object shall have a required appointment Date field. The appointment Date field cannot be in the past. The appointment Date field shall not be null.
Note: Use java.util.Date for the appointmentDate field and use before(new Date()) to check if the date is in the past.
The appointment object shall have a required description String field that cannot be longer than 50 characters. The description field shall not be null.
Appointment Service Requirements
The appointment service shall be able to add appointments with a unique appointment ID.
The appointment service shall be able to delete appointments per appointment ID.
