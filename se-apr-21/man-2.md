---
description: Trinath
---

# Man 2

## Practical-1

Project Title: TODO List Application Definition: A TODO List Application is a digital task management tool that allows individuals to create, track, and manage a list of activities or tasks. It serves as a personal productivity assistant to ensure that daily goals are organized, prioritized, and completed within specified timeframes. Information: Task management is the act of organizing and prioritizing activities to maximize personal or professional efficiency. While traditional methods involve handwritten lists or physical planners, a digital TODO application provides a dynamic environment where tasks can be instantly edited, sorted, and filtered. Modern applications go beyond simple checklists by incorporating deadlines, priority levels, and category tagging, allowing users to visualize their workload and focus on high-priority items. This system is essential for students, professionals, and project managers to minimize the risk of forgetting important deadlines and to maintain a structured workflow. Objectives: It facilitates the systematic entry and tracking of various tasks in a centralized location. The system helps in evaluating the progress of projects and individual tasks by providing status updates such as "Pending," "In Progress," or "Completed." Purpose: The purpose of developing the TODO List Application is to computerize the manual method of note-taking and task tracking, offering a more reliable, searchable, and accessible platform for productivity. Functions: i. Administrator ii. User Administrator: The Administrator has the rights to manage the overall system, including user account verification and database maintenance. The Administrator can monitor system usage statistics, manage server-side task categories, and provide technical support to users. User:

* Registered User: The user performs the login to access their personalized dashboard. They have the authority to create new tasks, update existing task descriptions, set priority levels, and mark tasks as finished. Features:
* Task Management: Create, view, edit, and delete tasks from a single, unified interface.
* Priority Ranking: Assign priority levels (High, Medium, Low) to tasks to highlight urgent requirements.
* Status Tracking: Update the lifecycle of a task from creation to completion with real-time status indicators.
* Category Tagging: Organize tasks into specific groups such as "Work," "Personal," or "Shopping" for better clarity.
* Search and Filter: Quickly locate specific tasks using a search bar or by filtering based on date and priority.

## Practical-2

Aim: Identify Suitable Design and Implementation model from the different software engineering models. Spiral Model In each phase of the Spiral Model, the features of the TODO list application are evaluated and analyzed, and the risks at that point in time (such as data persistence issues or UI responsiveness) are identified and resolved through prototyping. This makes the model highly flexible compared to traditional linear models. The Spiral model provides robust support for Risk Handling. Diagrammatically, it appears as a spiral with multiple loops, where each loop represents a phase of the software development process. For a TODO application, the number of loops may vary based on the complexity of features added, such as cloud synchronization or collaborative task sharing. The project manager dynamically determines the phases, ensuring that potential technical hurdles are cleared before full-scale implementation. Justification for choosing Spiral Model The Spiral model is an SDLC method used for risk management that combines the iterative nature of development with the systematic aspects of the Waterfall model. It is chosen for the TODO list application to allow for continuous refinement of the user interface and to handle technical risks associated with data storage and cross-platform synchronization through early prototyping.

***

Justification for not choosing Waterfall Model

* Once the application enters the testing stage, it is very difficult to go back and change core functionalities that were not perfectly defined during the initial concept stage.
* A working version of the software is not produced until very late in the lifecycle.
* High amounts of risk and uncertainty regarding user preference for the task-management flow.
* Not suitable for projects where UI/UX requirements are at a moderate to high risk of changing based on user feedback. Justification for not choosing Incremental Model
* Requires extensive upfront planning and design.
* Needs a completely clear and finished definition of the whole system before it can be broken down into increments.
* The total cost is often higher than a simple Waterfall approach if the increments are not perfectly managed. Justification for not choosing Prototype Model
* Can become costly if the prototyping cycles are not strictly controlled.
* Often results in poor documentation because the focus remains on the evolving prototype rather than the system architecture.
* The user may demand the actual product immediately after seeing an early functional prototype, leading to the delivery of unstable code.

***

Justification why Spiral Model is better than any other model

* In each phase, the TODO list features are analyzed and risks are resolved through prototyping before moving to the next level of development.
* This model provides the highest level of flexibility, allowing the developer to adapt to new task-management requirements at any stage of the spiral.

## Practical-3

Aim: Study Software Requirement engineering and include the SRS document for the TODO List Application project. SRS (Software Requirement Specification) ASSUMPTION:

1. Users are already registered or have access to the login portal. Requirement 1: Registration

* Req 1.1: User Enrollment (by Admin)
  * Input: User details (name, email, role).
  * Output: Save user credentials in the system internally.
* Req 1.2: Profile Creation
  * Input: Enter personal preferences and account details.
  * Output: Initialize the user dashboard and database entry. Requirement 2: Show information of Admin
* Req 2.1: Admin Profile Information
  * Input: Admin ID and password.
  * Output: Username, email, system logs, and administrative privileges.
* Req 2.2: System Overview
  * Input: Account/System information request.
  * Output: Total user count, active tasks across the system, and server status. Requirement 3: Show information of User
* Req 3.1: User Task Dashboard
  * Input: User ID and password.
  * Output: Username, email, list of pending tasks, and task history.
* Req 3.2: Task Progress Information
  * Input: Task ID or category selection.
  * Output: Task name, creation date, priority level, and completion status. Requirement 4: Delete User/Task (only by Admin)
* Input: Target username/Task ID and Admin password.
* Output: Deletion status and data cleanup confirmation. Requirement 5: Modification of Tasks
* Req 5.1: Managing Daily Tasks
  * Input: Task description, deadline, and priority (External).
  * Output: Updated task status (Internal). Requirement 6: View status of every task under User/Admin control
* Function: Display a real-time list of "Completed," "In-Progress," and "Overdue" tasks. Requirement 7: Managing the user according to their specific role
* Function: Ensure Admin can access global logs while Users only see their private TODO lists. Requirement 8: Restricted Access
* Function: Users are not allowed to make changes to system-wide categories or other users' task lists. Requirement 9: Modification of personal information
* Req 9.1: Add new profile changes
  * Input: New email or password updates (External).
  * Output: Addition/Update status.
* Req 9.2: Edit existing task details
  * Input: Changes to task titles or descriptions (External).
  * Output: Updating status.

***

SOFTWARE QUALITY ATTRIBUTES Accuracy: The level of accuracy in the proposed system will be higher. All task updates and time-stamps will be processed correctly, ensuring that the information displayed on the dashboard reflects the true state of the database. Reliability: The reliability of the system will be high. Proper data persistence ensures that tasks are not lost during system restarts and that the information is stored securely in the local or cloud database. No Redundancy: Utmost care is taken to ensure no task or user information is repeated. This ensures economic use of storage space and maintains data consistency, preventing duplicate task entries. Immediate retrieval of information: The main objective is to provide quick and efficient retrieval. Users can instantly filter, search, and view their tasks without delay, facilitating a smooth productivity workflow. Easy to Operate: The TODO list system is designed with a user-centric approach, ensuring it is intuitive and requires minimal training. The architecture allows for rapid development within a short period, fitting within a limited budget while providing a professional-grade task management experience.

***

3. External Interfaces 3.1) Hardware Interfaces: The application is designed to execute seamlessly on personal computers running Windows or macOS. To ensure optimal performance and responsiveness, the following minimum hardware requirements are recommended:

* Hard Disk: 500GB or above (SSD recommended for faster data indexing).
* RAM: 4GB (to ensure smooth multitasking with other productivity tools).
* Processor: Intel Core i3 7th Gen or equivalent.
* Internet Connectivity: Wi-Fi/Ethernet for cloud synchronization features.
* Input Devices: Standard Keyboard and Mouse for task entry and navigation. 3.2) Software Interfaces: The application utilizes a web-based front-end for accessibility, hosted on a secure web server. The backend logic and data storage are managed using high-performance technologies:

1. Programming Language: C++ (for core logic and performance-intensive modules).
2. Database: MongoDB (for flexible, document-oriented storage of task data).
3. Operating Systems: Windows 10 or above, and macOS Monterey or above.
4. Web Environment: The interface uses modern web standards (HTML5/CSS3) and can be served via ASP.NET/ASPX wrappers for enterprise integration. 3.3) Connection Protocols and Interfaces: The TODO List Application is platform-independent and compatible with all major desktop environments.

* Protocols: All client-server communication occurs over TCP/IP and HTTPS to ensure data integrity and security.
* Browser Support: The system supports all modern web browsers, including Google Chrome, Mozilla Firefox, Microsoft Edge, and Safari. 3.4) User Interface:
* Responsiveness: The user interface screen is optimized to respond to any user action (adding a task, checking a box, or filtering) within 5 seconds.
* Design: A clean, clutter-free dashboard that prioritizes the "Daily Tasks" view to minimize cognitive load.

## Practical-4

Aim: Study Software project management planning and prepare the SPMP document for the TODO List Application. Seven Principles of Software Scheduling for TODO List Application

1. Compartmentalization: The project is decomposed into manageable tasks such as UI/UX design, MongoDB database schema creation, C++ backend logic development, and final integration testing.
2. Interdependency: Task dependencies are identified; for instance, the C++ backend logic for task retrieval cannot be finalized until the MongoDB database structure is established.
3. Time Allocation: Each module is assigned a specific timeline. For example, 1 week is allocated for UI design and 2 weeks for core backend functionality.
4. Effort Validation: Since this is a semester project, the workload is distributed to ensure that the development requirements do not exceed the available student hours per week.
5. Defined Responsibilities: Specific roles are assigned, such as the Database Administrator (handling MongoDB) and the Frontend Developer (handling the user interface).
6. Defined Outcomes: Each phase has a tangible work product, such as a finalized SRS document, a functional database, or a compiled source code file.
7. Defined Milestones: Key milestones include the completion of the "Add Task" functionality and the successful implementation of "User Authentication."

***

Scheduling Methods To manage the development of the TODO List Application, the following quantitative tools are applied:

* Program Evaluation and Review Technique (PERT): Used to estimate the time required to complete each task by considering optimistic, pessimistic, and most likely timeframes.
* Critical Path Method (CPM): Used to identify the sequence of critical tasks that directly impact the project completion date. For this project, the critical path involves the database connectivity and core task-handling logic.

***

Project Schedule (Sample Timeline) Activity ID Activity Description Duration Dependency A1 Requirement Analysis & SRS 1 Week - A2 System Design (UI & DB Schema) 1 Week A1 A3 Database Implementation (MongoDB) 1 Week A2 A4 Backend Development (C++) 2 Weeks A3 A5 Frontend & Backend Integration 1 Week A4 A6 Testing and Debugging 1 Week A5 A7 Final Documentation & Submission 1 Week A6 \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Gantt Chart A Gantt chart is utilized to visually represent the TODO List Application project schedule. It displays activities against a timeline, showing start dates, durations, and overlapping tasks.

* Visualization: Each task (e.g., "Coding") is represented by a horizontal bar.
* Overlap: It allows the team to see that "UI Design" can occur in parallel with "Database Setup," while "Testing" must wait until "Integration" is finished.
* Summary: It provides an at-a-glance view of the entire 8-week development cycle for the application.

## Practical-5

Aim: Do cost and Effort Estimation using Software Cost Estimation Model. Objectives: To make use of the COCOMO model to find out the cost of software development for the TODO List Application. Organic Type: A development project is considered organic if the project deals with a well-understood application, the team is small, and members are experienced with similar projects. This TODO List Application falls under the Organic category. Basic COCOMO Model The Basic COCOMO model provides an approximate estimate of project parameters using the following expressions: $$Effort = a_1 \times (KLOC)^{a_2} \text{ PM}$$ $$T_{dev} = b_1 \times (Effort)^{b_2} \text{ Months}$$

* KLOC: Estimated size of the software in Kilo Lines of Code.
* $a\_1, a\_2, b\_1, b\_2$: Constants for the Organic category ($a\_1=2.4, a\_2=1.05, b\_1=2.5, b\_2=0.38$).
* $T\_{dev}$: Estimated time to develop.
* Effort: Total effort in Person Months (PM).

***

Cost Estimation of Software Requirements Counting:

* External Inputs (EI): 6 (Add Task, Edit Task, Delete Task, Register, Login, Profile Update)
* External Outputs (EO): 3 (Task List Display, Notifications, Summary Report)
* No. of Inquiries (EQ): 3 (Search Task, Task Status, User Info)
* No. of Internal Files (ILF): 2 (Task Database, User Database)
* No. of External Interfaces (EIF): 1 (Web Browser/Client Interface) Function Point Calculation:
* $EI = 6 \times 3 = 18$
* $EO = 3 \times 4 = 12$
* $EQ = 3 \times 3 = 9$
* $ILF = 2 \times 7 = 14$
* $EIF = 1 \times 5 = 5$
* Count Total = 58 Value Adjustment Factors (VAF): $\sum F\_i = 4 + 5 + 1 + 3 + 1 + 4 + 2 + 4 + 2 + 2 + 3 + 1 + 1 + 4 = 37$ $$Function\ Point = Count\ Total \times [0.65 + (0.01 \times \sum F_i)]$$ $$Function\ Point = 58 \times [0.65 + 0.37] = 58 \times 1.02 = 59.16 \text{ FP}$$ Lines of Code (LOC): Since $1\ FP = 75\ LOC$ for C++: $$59.16 \times 75 = 4437 \text{ LOC} \approx 4.437 \text{ KLOC}$$

***

Basic COCOMO Calculation (Organic Type) Effort: $$Effort = 2.4 \times (4.437)^{1.05}$$ $$Effort \approx 2.4 \times 4.75 \approx 11.4 \text{ PM}$$ Development Time: $$T_{dev} = 2.5 \times (11.4)^{0.38}$$ $$T_{dev} \approx 2.5 \times 2.51 \approx 6.27 \text{ Months}$$ Final Cost: If the salary of the developer is Rs. 10,000/-, then the cost of development will be: $$11.4 \times 10,000 = \textbf{Rs. 1,14,000/-}$$

## Practical-6

Aim: Prepare System Analysis and System Design of identified Requirement specification using structure design as DFD with data dictionary and Structure chart for the specific module.

***

1. Data Flow Diagram (DFD) The Data Flow Diagram represents the flow of data through the TODO List Application, illustrating how user inputs are processed and stored. Level 0: Context Diagram The Context Diagram shows the system's boundaries and its interaction with external entities (User and Administrator).

* User provides task details and receives task views or reports.
* Administrator manages user accounts and monitors system status. Level 1: General Process This level decomposes the system into its primary functional modules:
* 1.0 Login: Validates user credentials against the D4 Admin/User Record.
* 2.0 Manage User: Admin handles registration and account updates.
* 3.0 Manage Task: The core module for adding, updating, and deleting tasks.
* 4.0 Manage Category: Organizes tasks into specific groups (e.g., Work, Personal).
* 5.0 Manage Admin: Handles administrative settings and system logs.
* 6.0 Manage Task Status: Updates the progress of tasks (Pending/Completed).
* 7.0 Generate Report: Produces productivity summaries for the user. Level 2: Manage Task Module A detailed breakdown of the task management process:
* 3.1 Add Task: Captures task name, deadline, and priority, then saves to D2 Task Record.
* 3.2 Update Task: Modifies existing entries in the task database.
* 3.3 Delete Task: Removes tasks from the active list.
* 3.4 View Task: Retrieves filtered task data for the user dashboard.

***

2. Data Dictionary The Data Dictionary provides a formal definition of the data elements used in the DFD. Data Name Description Format User\_ID Unique identifier for the user account Integer Task\_Title Brief name of the task to be performed String (50) Task\_Desc Detailed information about the task String (255) Priority Urgency level (High, Medium, Low) Enum Status Completion state (Pending, Completed) Boolean Deadline Date by which the task must be finished Date
3. Structure Chart The Structure Chart represents the hierarchical structure of the system modules. It shows how the Main Module coordinates various sub-modules like User Authentication, Database Controller, and Output Generator.

* Input Modules: Handle data entry and validation (e.g., Get\_Task\_Details).
* Processing Modules: Perform core logic (e.g., Update\_Task\_Status).
* Output Modules: Manage the display and reports (e.g., Show\_Dashboard). Practical-7 Aim: Designing the module using Object Oriented approach including Use Case Diagram with scenarios, Class Diagram, State Diagram, Collaboration Diagram, Sequence Diagram, and Activity Diagram.

***

1. Use Case Diagram Definition: A use case diagram is a graphical depiction of a user's possible interactions with a system. It shows various use cases and different types of users the system has, often represented by circles or ellipses. Use Case Scenarios for TODO List:

* Actor (User): Performs login, creates a task, marks a task as completed, and filters tasks by priority.
* Actor (Admin): Manages user accounts, resets passwords, and monitors overall system logs.

***

2. Class Diagram Definition: A type of static structure diagram that describes the structure of a system by showing the system's classes, their attributes, operations (or methods), and the relationships among objects. Core Classes for TODO Application:

* User Class: Attributes (userId, username, password); Operations (login(), logout()).
* Task Class: Attributes (taskId, title, description, priority, status, deadline); Operations (createTask(), updateStatus(), deleteTask()).
* Category Class: Attributes (categoryId, categoryName); Operations (addCategory()).

***

3. State Diagram Definition: Used to describe the behavior of systems by showing a finite number of states. It is a form of abstraction for complex system logic. Task States:
4. Created: The task is initialized in the system.
5. Pending: The task is awaiting action.
6. In-Progress: The user has started working on the task.
7. Completed: The task is marked as finished.
8. Deleted: The task is removed from the active view.

***

4. Sequence Diagram Definition: A Unified Modeling Language (UML) diagram that illustrates the sequence of messages between objects in an interaction. It shows the control structures and message flow between objects. Interaction (Adding a Task):
5. User enters task details in the UI.
6. UI sends a saveTask() request to the Controller.
7. Controller validates the data and sends an insert() command to the Database.
8. Database confirms the save status back to the Controller.
9. Controller updates the UI to display the new task.

***

5. Collaboration Diagram Definition: Also known as a Communication Diagram, it focuses on the structural relationships between objects and how they interact to perform a specific function. Description: In the TODO application, the UserInterface, TaskController, and MongoDB\_Interface objects collaborate to synchronize task data. While a sequence diagram shows the timing, the collaboration diagram highlights which objects are connected to handle task updates.

***

6. Activity Diagram Definition: Describes the procedural flow of control from one activity to another, focusing on the dynamic behavior of the system. Workflow (Updating a Task):

* Start: User selects a task.
* Action: System displays the edit form.
* Decision: Does the user save changes?
  * Yes: Validate data $\rightarrow$ Update Database $\rightarrow$ Show Success.
  * No: Discard changes $\rightarrow$ Return to Dashboard.
* End: Dashboard refreshed.

## Practical-7

Aim: Designing the module using Object Oriented approach including Use Case Diagram with scenarios, Class Diagram, State Diagram, Collaboration Diagram, Sequence Diagram, and Activity Diagram.

1. Use Case Diagram Definition: A use case diagram is a graphical depiction of a user's possible interactions with a system. It shows various use cases and different types of users the system has, often represented by circles or ellipses. Use Case Scenarios for TODO List:

* Actor (User): Performs login, creates a task, marks a task as completed, and filters tasks by priority.
* Actor (Admin): Manages user accounts, resets passwords, and monitors overall system logs.

2. Class Diagram Definition: A type of static structure diagram that describes the structure of a system by showing the system's classes, their attributes, operations (or methods), and the relationships among objects. Core Classes for TODO Application:

* User Class: Attributes (userId, username, password); Operations (login(), logout()).
* Task Class: Attributes (taskId, title, description, priority, status, deadline); Operations (createTask(), updateStatus(), deleteTask()).
* Category Class: Attributes (categoryId, categoryName); Operations (addCategory()).

3. State Diagram Definition: Used to describe the behavior of systems by showing a finite number of states. It is a form of abstraction for complex system logic. Task States:

* Created: The task is initialized in the system.
* Pending: The task is awaiting action.
* In-Progress: The user has started working on the task.
* Completed: The task is marked as finished.
* Deleted: The task is removed from the active view.

4. Sequence Diagram Definition: A Unified Modeling Language (UML) diagram that illustrates the sequence of messages between objects in an interaction. It shows the control structures and message flow between objects. Interaction (Adding a Task):

* User enters task details in the UI.
* UI sends a saveTask() request to the Controller.
* Controller validates the data and sends an insert() command to the Database.
* Database confirms the save status back to the Controller.
* Controller updates the UI to display the new task.

5. Collaboration Diagram Definition: Also known as a Communication Diagram, it focuses on the structural relationships between objects and how they interact to perform a specific function. Description: In the TODO application, the UserInterface, TaskController, and MongoDB\_Interface objects collaborate to synchronize task data. While a sequence diagram shows the timing, the collaboration diagram highlights which objects are connected to handle task updates.
6. Activity Diagram Definition: Describes the procedural flow of control from one activity to another, focusing on the dynamic behavior of the system. Workflow (Updating a Task):

* Start: User selects a task.
* Action: System displays the edit form.
* Decision: Does the user save changes?
  * Yes: Validate data \rightarrow Update Database \rightarrow Show Success.
  * No: Discard changes \rightarrow Return to Dashboard.
* End: Dashboard refreshed. Would you like me to generate the Mermaid code for these diagrams so you can include high-quality visuals in your manual?

## Practical-8

Aim: Defining Coding Standards and walk through. Coding Standard: Coding conventions are a set of guidelines for a specific programming language that recommend programming style, practices, and methods for each aspect of a program written in that language. These conventions usually cover file organization, indentation, comments, declarations, statements, white space, naming conventions, programming practices, programming principles, programming rules of thumb, architectural best practices, etc. These are guidelines for software structural quality. Software programmers are highly recommended to follow the Software Engineering guidelines to help improve the readability of the source code and make software maintenance easier. Coding conventions are only applicable to the human maintainers and peer reviewers of a software project. Conventions may be formalized in a documented set of rules that an entire team follows. In the Library Management System, coding standards are followed to ensure accuracy in transaction tracking, secure authentication, structured database handling, and reliable stock calculation. Why Are Coding Standards Important? There are several reasons why coding standards are important:

1. Compliance with industry standards.
2. Consistent code quality no matter who writes the code.
3. Software security from the start.
4. Reduced development costs and accelerated time to market. Coding standards help prevent defects in modules such as fine calculation, catalog management, role-based access control, and duplicate issue prevention . Without proper coding conventions, the project may result in reduced engineer motivation, increased development time, complex code base structure, and difficult debugging and maintenance . Common Aspects of Coding Standard: Naming Conventions: Naming conventions define how packages, classes, methods, and variables should be named. ● Class names: Pascal Case (Example: BookManager). ● Method names: camelCase (Example: calculateFine()). ● Local variables: camelCase starting with small letter. ● Global variables: start with capital letter. ● Constants: capital letters only (Example: MAX\_BORROW\_LIMIT). Meaningful and understandable variable names help anyone understand the reason for using it. File and Folder Naming and Organization: The file and folder structure should be organized properly. Each module should have a standard header format including Name of module, Date of module creation, Author of the module, Modification history, and Global variables accessed . Formatting and Indentation: Code should be written in standardized format and indentation. All braces should start from a new line. Code after closing braces should start from a new line. Consistent spacing should be maintained. This improves readability and reduces confusion. Commenting and Documenting: Proper comments must be added for complex stock logic, fine calculation formulas, database queries, and role validation logic . Documentation helps in understanding system behavior during maintenance. Classes and Functions: Each function should perform a single task. Avoid long and complex functions. Use modular design. Avoid excessive global variables. Testing: Testing should ensure: ● Login validation works correctly. ● The same physical book copy cannot be issued twice simultaneously. ● Only authorized admins can manage transactions. ● Fines and stock counts are calculated correctly. Error Return Values and Exception Handling Conventions: All functions that encounter error conditions should return proper error messages, handle invalid inputs, and prevent system crashes . Examples include Invalid login credentials or an attempt to issue a book that is out of stock . Google Code of Conduct:
5. Serve Users (Integrity, Usefulness, Privacy)
6. Respect Each Other (Equal opportunity, Positive environment, Safe workplace)
7. Avoid Conflicts of Interest
8. Preserve Confidentiality
9. Protect Organization Assets
10. Ensure Financial Integrity
11. Obey the Law These ethical guidelines ensure professional behavior in software What is Code Review? Code review is a software quality assurance process in which source code is analyzed manually by a team or by using automated tools. The motive is to find bugs, resolve errors, and improve code quality. Reviewing the code base ensures that every module of the Library Management System maintains proper structure and security. Best Code Review Techniques:
12. Instant Code Reviewing Technique - Developer writes code while reviewer checks simultaneously. Advantages: Immediate feedback, Quick bug detection . Disadvantages: Requires more workforce, Interrupts workflow .
13. Ad-hoc (Synchronous) Code Reviewing Technique - Developer completes the code and then asks reviewer to review it informally. Advantages: Simple and flexible. Disadvantages: May miss errors, Interrupts working flow .
14. Meeting Based Code Reviewing Technique - Entire team reviews code together in a meeting. Advantages: Knowledge sharing, Collective discussion . Disadvantages: Time consuming, Hard to conduct regularly .
15. Tool Based Code Reviewing Technique - Code is reviewed using tools such as version control systems. Advantages: Structured review process, Trackable changes, Efficient for large code bases . For the Library Management System, tool-based review is recommended for maintaining consistency and security

## Practical-9

Aim: Write the test cases for the identified module.

1. Introduction to Testing The testing process requires direct communication with programmers to understand exactly how the code works. Effective communication among testers is also vital to determine what to test, identify required resources, and establish a testing schedule. The software test plan is the primary document used by testers to communicate their intent to developers, and the test case is the core component of this plan.
2. Test Case Definition A test case is a formal document describing the specific data inputs and operating conditions needed to run a test, along with the expected results.

* Pass: The actual results are in complete agreement with the expected results.
* Fail: Some or all results do not match the expected outcome, indicating a potential error.

3. Test Cases for TODO List Module

| Test Case ID | Test Case Objective | Test Case Description                        | Input                                  | Expected Output                | Results |
| ------------ | ------------------- | -------------------------------------------- | -------------------------------------- | ------------------------------ | ------- |
| TC-01        | Validate Login      | Enter valid credentials on the login screen. | Username: admin, Password: password123 | Redirect to Dashboard.         | Pass    |
| TC-02        | Create New Task     | Click "Add Task" and enter details.          | Task: Finish Lab, Priority: High       | Task appears in list.          | Pass    |
| TC-03        | Task Completion     | Click the checkbox for an active task.       | Select Task ID 101                     | Status changes to "Done".      | Pass    |
| TC-04        | Invalid Login       | Enter incorrect password.                    | Username: admin, Password: wrong       | Error: "Invalid Login".        | Pass    |
| TC-05        | Delete Task         | Click the delete icon on a task.             | Select Task ID 102                     | Task removed from list.        | Pass    |
| TC-06        | Task Filtering      | Filter tasks by "High" priority.             | Select Filter: High                    | Only High priority tasks show. | Pass    |

3. Would you like me to draft the Conclusion and Future Enhancements section to finish your lab manual?

## Practical-11

Aim: Define security and quality aspects of the identified module. Software Quality

* Software Quality indicates how good and reliable a product is.
* Functionally correct software is not considered high-quality if it has an unusable program or user interface.
* Quality goes beyond "fitness of purpose"; it requires the code to be comprehensible and maintainable. Factors of Software Quality The quality of the TODO List application is measured by these key factors:
* Portability: The software can be easily created to work in different package environments and on different machines.
* Usability: Both novice and knowledgeable users can easily invoke the functions of the product.
* Reusability: Different modules can be easily reused to develop new products.
* Correctness: Different needs specified in the SRS document are properly implemented.
* Maintainability: Errors can be easily corrected as they show up, and new functions can be added easily.
* Reliability: The software has fewer failures and can recover easily if failures occur.
* Efficiency: The software uses minimal CPU time, memory, disk space, and network bandwidth. Software Quality Management System (SQMS) The SQMS contains the methods used by authorities to develop products with the desired quality.
* Managerial Structure: Responsible for managing the quality structure as a whole within the organization.
* Individual Responsibilities: Each individual has specific responsibilities that must be taken seriously and reviewed by top management.
* Quality System Activities: These include project auditing, quality system reviews, and the development of guidelines and methods. Evolution of Quality Management System The evolution of the Quality Management System is a process involving these stages:
* Quality Control: Tasked with detecting defective devices, finding causes of defects, and correcting bugs.
* Quality Assurance: Helps an organization produce good quality products by passing them through security and quality checks.
* Total Quality Management (TQM): Assures that all procedures are continuously improved through regular process measurements.
