# Requirement Analysis in Software Development
- Its primary purpose is to provide a centralized and structured collection of all documentation, models, and artifacts related to understanding, defining, and managing the requirements for the software project.
  ## What is Requirement Analysis?
Requirement analysis is a fundamental process in the **software development lifecycle (SDLC)** that involves defining, documenting, and managing the requirements for a software system. It is a critical bridge between the user's needs and the technical solution. The main goal is to understand what the user wants and needs from the software and to translate these into a clear, unambiguous set of requirements that the development team can use. This phase is also known as **requirements engineering**.

***

## Key Steps in Requirement Analysis
Requirement analysis is a fundamental process in the **software development lifecycle (SDLC)** that involves defining, documenting, and managing the requirements for a software system. It is a critical bridge between the user's needs and the technical solution. The main goal is to understand what the user wants and needs from the software and to translate these into a clear, unambiguous set of requirements that the development team can use. This phase is also known as **requirements engineering**.

***

### Key Steps in Requirement Analysis

Requirement analysis is a systematic process with several key steps:

* **Elicitation:** This is the process of gathering requirements from various stakeholders, including end-users, customers, business managers, and domain experts. Techniques for elicitation include interviews, surveys, workshops, and observation of existing systems. The goal is to collect all relevant information to understand the problem domain completely.

* **Analysis:** After requirements are gathered, they must be analyzed for consistency, completeness, and clarity. This step involves identifying conflicts or ambiguities, prioritizing requirements based on business value, and creating models (like use cases or flowcharts) to visualize the system's behavior.

* **Specification:** The analyzed requirements are documented in a formal **Software Requirements Specification (SRS)** document. This document serves as a contract between the stakeholders and the development team. It details the functional requirements (what the system must do) and non-functional requirements (how the system should perform, e.g., security, performance, usability).

* **Validation:** Once specified, the requirements are reviewed with stakeholders to ensure they accurately reflect their needs. This step helps in catching errors early and reduces the chances of building the wrong product.

***

**Importance in the SDLC**

Requirement analysis is arguably the most crucial phase in the SDLC for several reasons:

* **Reduces Project Failure:** Many software projects fail or are significantly delayed because of poor or incomplete requirements. By clearly defining the scope and objectives upfront, requirement analysis minimizes the risk of scope creep, budget overruns, and missed deadlines.
* **Ensures Stakeholder Satisfaction:** A thorough analysis ensures that the final product aligns with the stakeholders' expectations. It prevents the common scenario where the delivered software meets the documented requirements but not the underlying business needs.
* **Improves Communication:** The SRS document acts as a single source of truth for all teams involved—development, quality assurance (QA), and management. It minimizes miscommunication and ensures everyone is working toward the same goal.
* **Early Error Detection:** Finding and fixing errors in the requirement phase is significantly cheaper and less time-consuming than fixing them during coding or testing. A bug found in the requirements can be corrected with a simple document change, whereas the same bug found in production might require a complete code rewrite.
* **Facilitates Better Planning:** Clear requirements allow project managers to create more accurate schedules, allocate resources effectively, and estimate costs more precisely. This leads to more predictable and manageable project execution.

   ## Why is Requirement Analysis Important?
  Requirement analysis is critical in the SDLC for three main reasons: **mitigating project risk**, **ensuring stakeholder satisfaction**, and **improving communication and planning**.

***

**Mitigating Project Risk**

Thorough requirement analysis helps in **reducing the risk of project failure**. Without a clear understanding of what a software system needs to do, projects often suffer from **scope creep**—the uncontrolled expansion of project scope beyond its initial boundaries. This can lead to budget overruns and missed deadlines. By defining and documenting requirements upfront, a project team can create a stable foundation, minimizing the chances of having to rebuild or redesign the software later in the development process. 

***

**Ensuring Stakeholder Satisfaction**

The primary goal of any software project is to deliver a product that meets the needs of its users. Requirement analysis is the direct method for **ensuring stakeholder satisfaction**. By actively engaging with users and other stakeholders during the elicitation and validation phases, the development team can confirm that their understanding of the requirements aligns with the stakeholders' expectations. This process prevents the common problem of a delivered product that technically works but fails to address the actual business problem.

***

**Improving Communication and Planning**

A well-defined set of requirements acts as a **single source of truth** for everyone involved in the project. It provides a common language and understanding for developers, testers, project managers, and clients. This clarity in communication is essential for avoiding misunderstandings and misinterpretations. Furthermore, detailed requirements enable project managers to create more **accurate and realistic plans**. With a clear scope, it is possible to more precisely estimate development time, allocate resources, and schedule tasks, leading to more predictable and successful project execution.

## Key Activities in Requirement Analysis.
The five key activities in requirement analysis are gathering, elicitation, documentation, analysis and modeling, and validation.

* **Requirement Gathering**: This is the initial phase of the requirement process where information about the system's needs is collected from various sources. It's a broad activity that involves understanding the problem domain, identifying stakeholders, and collecting existing documentation. Think of it as the foundational research phase before the more targeted elicitation begins.

* **Requirement Elicitation**: This is the process of actively discovering and extracting requirements from stakeholders. It's a more proactive activity than gathering. Techniques used include **interviews**, **surveys**, **workshops**, **brainstorming sessions**, and observing users in their environment to uncover what they truly need. The goal is to get a deep understanding of the problem and desired outcomes from those who will use or be affected by the system.

* **Requirement Documentation**: This activity involves formally recording the collected requirements in a clear, unambiguous, and structured manner. The primary output is typically the **Software Requirements Specification (SRS)** document. This document acts as a blueprint for the entire project, detailing functional and non-functional requirements, constraints, and assumptions. Proper documentation is crucial for communication and serves as a contract between stakeholders and the development team.

* **Requirement Analysis and Modeling**: In this phase, the documented requirements are studied to identify and resolve any conflicts, ambiguities, or incompleteness. Requirements are categorized, prioritized, and modeled using techniques like **use case diagrams**, **flowcharts**, or **data models**.  This process helps in visualizing the system's behavior and structure, ensuring the requirements are feasible and logically consistent before development begins.

* **Requirement Validation**: This is the final stage where the documented requirements are reviewed and confirmed with stakeholders to ensure they accurately reflect their needs and business goals. The goal is to verify that the team is building the "right" product. This is often done through formal **walkthroughs**, **inspections**, and **prototyping**. Validation helps in catching errors early, reducing the risk of developing a product that doesn't meet the user's expectations.

  ## Types of Requirements.

### Functional Requirements
Functional requirements define what the system **must do**. They describe the specific behaviors and functions of the software.

* **View Booking Service**: The system must allow users (both customers and managers) to view their current and past booking details.
* **Customer Booking Service**: The system must enable customers to search for hotels and book a room.
* **Hotel Management Service**: The system must allow hotel managers/owners to manage their hotel's related information, such as updating room availability or pricing.
* **Payment Service**: The booking service must interact with a third-party payment service to process payments.
* **Notification Service**: The system must send notifications to customers and managers regarding booking events (e.g., booking confirmation for customers, new booking alerts for managers).

***

### Non-functional Requirements
Non-functional requirements specify **how the system performs a certain function**. They relate to the quality attributes of the system, such as performance, security, and scalability.

* **Scalability**: The system must be able to handle a high amount of user traffic, as indicated by the use of **micro-service architecture**, **load balancers**, and distributing the system into small, manageable chunks.
* **Performance**: The system must have low response times. This is achieved by using a **CDN (Content Delivery Network)** to serve content to customers and a **Redis** caching system to store temporary data, reducing the load on the database.
* **Data Integrity and Reliability**: The system must ensure data consistency between the master and slave databases, as mentioned in the **master-slave architecture** for the hotel database. Additionally, it must handle high volumes of data effectively using databases like **Cassandra** for archival purposes.
* **Search Functionality**: The system's search feature for hotels must be efficient. The case study notes the use of **Elasticsearch**, a NoSQL database, specifically because it's "best for its search engine functionality."
* **Decoupling**: The system should use a **Messaging Queue System (like Kafka, RabbitMQ)** to decouple different services, ensuring that data updates are processed asynchronously and reliably.

  ## Use Case Diagrams.
  A **Use Case Diagram** is a type of UML (Unified Modeling Language) diagram that shows a system's functionality from a user's perspective. It illustrates the different ways a user, or **actor**, interacts with a system to achieve a specific goal. The diagram consists of actors, use cases, and the relationships between them.

***

**Components of a Use Case Diagram**

* **Actor**: An actor represents a role that a user or another system plays when interacting with the system. It's typically drawn as a stick figure.
* **Use Case**: A use case is a description of a set of actions performed by a system to produce an observable result for an actor. Use cases are usually represented as an oval.
* **System Boundary**: This is a box that represents the scope of the system. All use cases are placed inside the boundary, while actors are outside.
* **Relationships**: These show how actors and use cases are connected. Common relationships include:
    * **Association**: The main relationship linking an actor with a use case.
    * **Include**: Used when one use case is included in the flow of another.
    * **Extend**: Used when a use case adds functionality to an existing one under specific conditions.



***

**Benefits of Use Case Diagrams**

* **Simplifies Communication**: They provide a high-level view of a system's functionality, making it easy for stakeholders—including non-technical ones—to understand the system's purpose and how users will interact with it.
* **Early Requirements Capture**: Use case diagrams are excellent for capturing and defining system requirements early in the software development lifecycle. They help in identifying all the major functionalities required by the users.
* **Provides a Blueprint**: They serve as a foundational blueprint for more detailed design and development. The use cases can be broken down into more specific requirements and test cases, guiding the entire development process.
* **Identifies System Boundaries**: By clearly separating actors from use cases within a system boundary, the diagram helps in defining what the system will and will not do. This is crucial for preventing **scope creep**.

  ## Acceptance Criteria.
  - Acceptance criteria are crucial in Requirement Analysis because they define the specific conditions that a software feature must meet to be considered complete and acceptable to stakeholders. They act as a checklist that validates whether the requirement has been successfully implemented.

***

**Key Roles of Acceptance Criteria**

* **Clarity and Shared Understanding**: Acceptance criteria translate high-level requirements into clear, verifiable statements. This eliminates ambiguity and ensures that everyone—from the product manager to the developers and testers—has the same understanding of what needs to be built. For example, instead of a vague requirement like "The user can log in," a clear acceptance criterion would be, "Given a registered user, when they enter a valid email and password, then they should be redirected to their dashboard."

* **Basis for Testing**: Acceptance criteria serve as the foundation for creating **test cases**. Testers can directly use these criteria to design tests that confirm the functionality works as expected. This ensures comprehensive testing and a direct link between requirements and the final product's quality.

* **Scope Definition and Control**: By outlining the exact conditions for a feature's completion, acceptance criteria help to prevent **scope creep**. They provide a clear boundary for the work, ensuring that the team doesn't add extra functionality that wasn't initially agreed upon.

* **Facilitates 'Done' Definition**: They provide a concrete definition of "done" for a particular task or user story. This is particularly important in agile development methodologies, where teams can quickly and confidently move on to the next task once all acceptance criteria for the current one have been met.

  - Here is an example of acceptance criteria for the "Checkout" feature in the hotel booking management system, broken down by scenario. These criteria ensure that the feature works correctly for all anticipated user actions and system states.

**Acceptance Criteria for the "Checkout" Feature**

The following criteria are written in the **Given/When/Then** format, which is common in Behavior-Driven Development (BDD).

 **Scenario 1: Successful Payment and Booking Confirmation**

**Given** a customer has added a hotel to their cart and entered valid payment information,
**When** the customer clicks "Confirm Booking,"
**Then** the system should process the payment successfully, a booking confirmation should be displayed to the customer, and a confirmation email with booking details should be sent to the customer's registered email address. The hotel manager should also receive a notification of the new booking.

 **Scenario 2: Payment Failure**

**Given** a customer has added a hotel to their cart and entered invalid payment information (e.g., incorrect card number or expired card),
**When** the customer clicks "Confirm Booking,"
**Then** the system should decline the payment, display an error message explaining the failure, and prompt the user to re-enter their payment details. The booking status should remain pending.

 **Scenario 3: Room Unavailability**

**Given** a customer has a hotel in their cart, but the last available room for the selected dates is booked by another user before they can complete the payment,
**When** the customer attempts to finalize the booking,
**Then** the system should inform the customer that the selected room is no longer available and suggest alternative dates or rooms. The payment should not be processed.
