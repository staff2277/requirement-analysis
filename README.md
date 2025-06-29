What is Requirement Analysis?
Requirement Analysis is the process of gathering, understanding, and documenting what a software system must do. It ensures that all stakeholders have a shared understanding of system expectations. This phase involves identifying both functional and non-functional requirements and is essential for guiding design, development, and reducing risks in the software development lifecycle (SDLC).


Why is Requirement Analysis Important?
Requirement Analysis plays a vital role in the success of any software project. Here are three key reasons why it's critical in the SDLC:

a.Prevents Miscommunication
It ensures that all stakeholders—developers, clients, and users—have a clear and unified understanding of what the system should do. This avoids costly misunderstandings later.

b.Reduces Development Costs and Time
By identifying requirements early, development teams avoid unnecessary rework, helping to stay on budget and deliver on time.

c.Improves Product Quality
A well-analyzed set of requirements leads to a system that meets user needs and expectations, resulting in a more functional, reliable, and user-friendly product.

d.Key Activities in Requirement Analysis
The Requirement Analysis phase consists of several essential activities that ensure the system being built meets the intended goals. Below are the five key activities involved:

e.Requirement Gathering
Collecting initial input and information from stakeholders, users, clients, and other sources to understand what the system should achieve.

f.Requirement Elicitation
Engaging with stakeholders using techniques such as interviews, surveys, observations, and workshops to uncover detailed and sometimes hidden requirements.

g.Requirement Documentation
Clearly and formally recording the gathered and elicited requirements in formats like Software Requirements Specifications (SRS), user stories, or use case diagrams.

h.Requirement Analysis and Modeling
Examining the documented requirements for completeness, feasibility, consistency, and clarity. This may include creating models like data flow diagrams (DFDs), entity-relationship diagrams (ERDs), or UML diagrams to visualize requirements.

i.Requirement Validation
Ensuring that the requirements accurately reflect stakeholder needs, are testable, and are aligned with business goals. This often involves reviews, walkthroughs, or prototyping sessions.

Key Activities in Requirement Analysis
The Requirement Analysis phase consists of several essential activities that ensure the system being built meets the intended goals. Below are the five key activities involved:

Requirement Gathering
Collecting initial input and information from stakeholders, users, clients, and other sources to understand what the system should achieve.

Requirement Elicitation
Engaging with stakeholders using techniques such as interviews, surveys, observations, and workshops to uncover detailed and sometimes hidden requirements.

Requirement Documentation
Clearly and formally recording the gathered and elicited requirements in formats like Software Requirements Specifications (SRS), user stories, or use case diagrams.

Requirement Analysis and Modeling
Examining the documented requirements for completeness, feasibility, consistency, and clarity. This may include creating models like data flow diagrams (DFDs), entity-relationship diagrams (ERDs), or UML diagrams to visualize requirements.

Requirement Validation
Ensuring that the requirements accurately reflect stakeholder needs, are testable, and are aligned with business goals. This often involves reviews, walkthroughs, or prototyping sessions.

Types of Requirements
In software development, requirements are typically categorized into two main types: Functional Requirements and Non-functional Requirements. Below are explanations and examples based on a Booking Management System case study.

🔹 Functional Requirements
Functional requirements define the specific behavior or functions of the system — what the system should do.

Examples for the Booking Management Project:

Users can create an account and log in to the system.

Users can search for available bookings based on date, location, or type.

The system allows users to make, update, or cancel bookings.

Admins can manage booking records, view user activity, and generate reports.

The system should send confirmation emails after a successful booking.

🔹 Non-functional Requirements
Non-functional requirements describe how the system performs its functions, focusing on quality attributes like performance, security, and usability.

Examples for the Booking Management Project:

The system should respond to user actions within 2 seconds under normal load.

The application must be accessible from both desktop and mobile devices.

User data must be encrypted and secure from unauthorized access.

The system must support up to 10,000 concurrent users.

Booking data should be backed up daily to ensure data integrity.



Use Case Diagrams
Use Case Diagrams are a type of Unified Modeling Language (UML) diagram used during requirement analysis to visually represent the interactions between actors (users or external systems) and the functionalities (use cases) of a system.

They help teams understand:

Who will use the system (actors)

What the users can do (use cases)

How the system should behave from the user’s perspective

🔍 Benefits of Use Case Diagrams:
Clarify system scope and boundaries

Improve communication between stakeholders

Provide a foundation for identifying system requirements

Aid in validating that all user needs are considered

📌 Use Case Diagram for the Booking Management System
Below is a simple use case diagram representing key interactions in a booking system:


🧑‍🤝‍🧑 Actors:
User – can search, book, and manage bookings

Admin – can manage users and booking records

Payment System (External Actor) – processes payment transactions

⚙️ Main Use Cases:
Register/Login

Search for Bookings

Make a Booking

Modify/Cancel Booking

View Booking History

Manage Users (Admin)

Generate Reports (Admin)

Process Payment (via Payment System)


Acceptance Criteria
Acceptance Criteria are a set of predefined conditions that a software feature must meet for it to be accepted by the product owner, client, or end-user. They are written from the user's perspective and guide both development and testing teams to ensure the feature behaves as expected.

🧾 Importance of Acceptance Criteria in Requirement Analysis:
✅ Clarifies expectations: Helps all stakeholders agree on what “done” looks like.

🧪 Guides testing: Acts as the basis for test case development and validation.

🛠️ Supports development: Gives developers clear guidance on what functionality to implement.

🔁 Reduces rework: Ensures the team builds the right feature the first time.

📚 Improves communication: Creates a shared understanding between technical and non-technical stakeholders.

💡 Example: Acceptance Criteria for the Checkout Feature in the Booking Management System
Feature: Checkout
User Story: As a user, I want to pay for my booking so that my reservation is confirmed.

Acceptance Criteria:

✅ User must be logged in to access the checkout page.

✅ The checkout page displays selected booking details (date, time, location, and price).

✅ User can select a payment method (e.g., credit card, mobile money).

✅ The system validates payment information before submission.

✅ A loading state is shown while processing the payment.

✅ On successful payment, the user sees a confirmation page with a booking reference number.

✅ A confirmation email is sent automatically to the user’s registered email.

✅ Payment failures display a meaningful error message and allow retrying.
