### Key Concepts

- **Systematic Approach**: Software engineering involves a structured method to design and develop software.
- **Responsibilities**:
    - **Designing**: Crafting software architecture and solutions.
    - **Building & Maintaining**: Writing, testing, and updating code.
    - **Consultation**: Engaging with stakeholders and third-party vendors.
- **Roles**:
    - **Software Engineers**: Focus on building systems and ensuring scalability.
    - **Software Developers**: Implement specific functionalities within systems.

---

### Core Processes in Software Engineering

### **Design-Build-Test Cycle**

- **Design**: Create architecture and plan system components.
- **Build**: Develop software using programming languages and tools.
- **Test**: Validate software for quality and performance.

### **Phases of Software Development Life Cycle (SDLC)**

1. **Planning**: Define scope, objectives, and feasibility.
2. **Design**: Develop system architecture and design documents.
3. **Development**: Write and integrate code.
4. **Testing**: Identify and fix defects.
5. **Deployment**: Deliver the product to end users.
6. **Maintenance**: Update and improve the product over time.

---

### Software Engineering Processes

### **Common Processes**

1. **Requirements Gathering**: Identify what the software needs to do.
2. **Design**: Specify architecture and component interactions.
3. **Coding for Quality**: Implement functionality with a focus on reliability.
4. **Testing**: Conduct rigorous evaluations to detect issues.
5. **Releases**: Deploy software incrementally.
6. **Documentation**: Provide details for users and developers.

### **Requirements Gathering**

- Types of Requirements:
    1. **Functional**: Core features and operations.
    2. **External & User Interface**: Interaction design and accessibility.
    3. **System Features**: Performance and compatibility.
    4. **Non-Functional**: Security, scalability, and reliability.

---

### Testing in Software Engineering

### **Levels of Testing**

1. **Unit Testing**: Validate individual components.
2. **Integration Testing**: Test combined modules for interoperability.
3. **System Testing**: Evaluate the entire system.
4. **User Acceptance Testing (Beta Testing)**: Ensure the product meets user needs.

### **Release Stages**

1. **Alpha**: Initial testing phase, typically internal.
2. **Beta**: Limited release for external user feedback.
3. **General Availability (GA)**: Official public release.

---

### Documentation in Software Engineering

### **System Documentation**

- **Purpose**: Assist developers in understanding and maintaining the software.
- **Components**:
    - ReadMe files
    - Inline comments in the code
    - Architecture & design documents
    - Verification and maintenance guides

### **User Documentation**

- **Purpose**: Guide end users in using the software effectively.
- **Components**:
    - **URS (User Requirements Specification)**: Details user needs.
    - **SysRS (System Requirements Specification)**: Outlines system-level specifications.

## **Software Development Models**

### **1. Waterfall Method**

- **Definition**: A linear, sequential approach where each phase must be completed before moving to the next.
- **Phases**:
    1. **Requirements Gathering**: Collect detailed project requirements.
    2. **System Design**: Develop architecture and system design.
    3. **Implementation**: Write code based on design documents.
    4. **Testing**: Validate functionality and performance.
    5. **Deployment**: Deliver the product to the client.
    6. **Maintenance**: Address bugs and implement updates.
- **Characteristics**:
    - Fixed scope and requirements.
    - Each phase has specific deliverables.
    - Changes are costly and difficult to implement later.
- **Advantages**:
    - Clear structure and deliverables.
    - Easy to manage due to its rigidity.
- **Disadvantages**:
    - Limited flexibility for changes.
    - Not suitable for complex or evolving requirements.

---

### **2. V-Model (Verification and Validation Model)**

- **Definition**: An extension of the Waterfall model where testing is planned in parallel with development.
- **Structure**: Shaped like a "V," emphasizing a corresponding testing phase for each development phase.
- **Phases**:
    - **Development Side (Verification)**:
        1. **Requirements Analysis**: Define what needs to be built.
        2. **System Design**: Create a high-level system plan.
        3. **Architectural Design**: Specify modules and their interactions.
        4. **Module Design**: Plan individual components.
    - **Testing Side (Validation)**:
        1. **Unit Testing**: Validate individual modules.
        2. **Integration Testing**: Test module interactions.
        3. **System Testing**: Verify the entire system's functionality.
        4. **User Acceptance Testing (UAT)**: Ensure the product meets user requirements.
- **Characteristics**:
    - Testing is planned early in the lifecycle.
    - Focuses on defect prevention.
- **Advantages**:
    - Early detection of defects.
    - Clear and organized testing phases.
- **Disadvantages**:
    - Rigid and inflexible.
    - Not suitable for frequent changes.

---

### **3. Agile Model**

- **Definition**: A flexible, iterative approach that focuses on delivering small, functional increments of the product.
- **Phases** (Iterative):
    1. **Concept**: Define a high-level vision.
    2. **Iteration Planning**: Break work into small increments (sprints).
    3. **Design and Build**: Develop features in each sprint.
    4. **Testing**: Continuous validation during each sprint.
    5. **Delivery**: Provide usable features at the end of every sprint.
    6. **Feedback & Improvement**: Incorporate user feedback into subsequent iterations.
- **Characteristics**:
    - Incremental delivery.
    - High customer collaboration.
    - Adaptability to changes.
- **Advantages**:
    - Responds well to changing requirements.
    - Continuous feedback improves quality.
    - Short delivery cycles provide faster value.
- **Disadvantages**:
    - Requires strong team collaboration.
    - Difficult to predict costs and timelines for the entire project.

---

### Comparison Table

| **Aspect** | **Waterfall** | **V-Model** | **Agile** |
| --- | --- | --- | --- |
| **Approach** | Linear | Sequential with parallel testing | Iterative and incremental |
| **Flexibility** | Low | Moderate | High |
| **Testing Phase** | After development | Parallel to development | Continuous |
| **Delivery** | End of the lifecycle | End of the lifecycle | Frequent (per sprint) |
| **Best for** | Fixed requirements projects | High-reliability systems | Evolving requirements |
| **Key Drawback** | Difficult to adapt to changes | Rigid structure | Hard to estimate overall cost |

## **Sequential Development**

### **Definition**

- A linear approach where each phase of the project is completed before moving to the next.
- Example: Waterfall model.

### **Characteristics**

- **Fixed Workflow**: Each phase (e.g., requirements, design, development, testing) is completed in order.
- **No Overlaps**: One phase must finish before the next starts.
- **Rigid Structure**: Changes are difficult to accommodate once a phase is completed.

### **Advantages**

- **Clear Structure**: Easy to understand and manage.
- **Defined Deliverables**: Each phase has specific outcomes.
- **Best for Fixed Requirements**: Suitable for projects with stable and well-defined requirements.

### **Disadvantages**

- **Low Flexibility**: Difficult to adapt to changes after phases are completed.
- **Late Testing**: Defects are identified late in the lifecycle.
- **High Risk**: Failure in one phase can cascade into subsequent phases.

---

## **Iterative Development**

### **Definition**

- A cyclical approach where the project is broken into smaller iterations, each producing a functional increment.
- Example: Agile model.

### **Characteristics**

- **Incremental Progress**: Work is divided into smaller cycles (iterations).
- **Continuous Feedback**: Adjustments are made based on user or stakeholder input after each iteration.
- **Flexible Workflow**: Allows revisiting and refining earlier phases during the project.

### **Advantages**

- **Early Results**: Deliverables are available after each iteration.
- **High Adaptability**: Accommodates evolving requirements.
- **Reduced Risk**: Issues are identified and addressed early.

### **Disadvantages**

- **Requires Collaboration**: Success depends on regular communication with stakeholders.
- **Complex Planning**: Requires detailed tracking of iterations.
- **Difficult Cost Prediction**: Hard to estimate the total project effort upfront.

---

## **Comparison Table**

| **Aspect** | **Sequential** | **Iterative** |
| --- | --- | --- |
| **Approach** | Linear, phase-by-phase | Cyclical, repeating iterations |
| **Flexibility** | Low | High |
| **Output** | Delivered at the end | Incremental, frequent deliveries |
| **Feedback** | Limited to post-development | Continuous during iterations |
| **Best for** | Fixed requirements projects | Evolving requirements |
| **Risk Handling** | High risk, late issue discovery | Reduced risk, early issue discovery |
| **Testing** | After development | Integrated in every iteration |
- **Sequential** is ideal for projects with stable requirements and minimal changes.
- **Iterative** is better for dynamic environments where feedback and flexibility are essential.

## **Software Versions**

### **1. Alpha Version**

- **Definition**: An early version of software, often incomplete, meant for internal testing.
- **Purpose**: Identify major bugs and assess core functionalities.
- **Users**: Developers and internal testers.
- **Characteristics**:
    - Feature-incomplete.
    - Likely to contain significant bugs.
    - Not ready for public or external use.
- **Examples**:
    - A game developer testing core mechanics internally.
    - Early build of an operating system with limited features.

---

### **2. Beta Version**

- **Definition**: A version of software released to a limited audience for external testing.
- **Purpose**: Collect feedback, discover bugs, and refine features.
- **Users**: Selected external testers or the public (open beta).
- **Characteristics**:
    - Feature-complete but may still contain some bugs.
    - Feedback-driven improvements.
- **Examples**:
    - WhatsApp beta for testing new UI features before the official release.
    - Google Chrome beta releases for testing new web technologies.

---

### **3. Release Candidate (RC)**

- **Definition**: A pre-release version close to the final product, used for final testing.
- **Purpose**: Ensure stability and address any remaining issues.
- **Users**: Select testers or development teams.
- **Characteristics**:
    - Feature-stable and nearly production-ready.
    - High focus on quality assurance.
- **Examples**:
    - A "release preview" version of Microsoft Windows before the official launch.
    - Linux distributions testing release candidates.

---

### **4. General Availability (GA)**

- **Definition**: The final, polished version of the software released to the public.
- **Purpose**: Provide stable, functional software for end-users.
- **Users**: General public or enterprise customers.
- **Characteristics**:
    - Fully tested and stable.
    - Regular updates may follow (e.g., patches and minor version updates).
- **Examples**:
    - iOS 17 official release for all iPhone users.
    - Final release of Adobe Photoshop CC.

---

### **5. Patch/Update Versions**

- **Definition**: Minor updates or fixes for the software after its release.
- **Purpose**: Address bugs, improve security, or add minor enhancements.
- **Users**: Existing users of the software.
- **Characteristics**:
    - Represented as minor version increments (e.g., 1.0.1, 1.0.2).
    - Focused on maintenance rather than new features.
- **Examples**:
    - Windows 11 security updates.
    - Bug fix patches for popular video games like "Cyberpunk 2077."

---

### **6. Major Versions**

- **Definition**: A significant update introducing new features, architecture changes, or major improvements.
- **Purpose**: Transform the product with substantial advancements.
- **Users**: Existing and new customers.
- **Characteristics**:
    - Represented as major version increments (e.g., 1.0 → 2.0).
    - May require new licensing or payment.
- **Examples**:
    - Transition from Android 12 to Android 13.
    - Microsoft Office 2019 upgrade to Office 2021.

---

### Versioning Format Examples

| **Versioning Format** | **Description** | **Example** |
| --- | --- | --- |
| **Major.Minor.Patch** | Standard semantic versioning format. | 2.3.1 |
| **Year-based** | Indicates the release year. | Office 2021, Ubuntu 22.04 |
| **Code names** | Internal or public project identifiers. | Android "Oreo", Windows "Blue" |

## **Software Testing**

### **Definition**

- **Software Testing**: The process of evaluating a software application to identify defects and ensure it meets the specified requirements.

---

### **Objectives**

- Detect bugs and errors.
- Ensure the software meets user needs.
- Validate performance, functionality, and reliability.
- Enhance overall quality.

---

### **Types of Software Testing**

### **1. Functional Testing**

- **Definition**: Validates the software’s functionality against requirements.
- **Examples**:
    - **Unit Testing**: Test individual components/modules.
    - **Integration Testing**: Verify interactions between combined modules.
    - **System Testing**: Evaluate the entire application.
    - **User Acceptance Testing (UAT)**: Ensure the software meets user expectations.

### **2. Non-Functional Testing**

- **Definition**: Tests software attributes like performance, scalability, and usability.
- **Examples**:
    - **Performance Testing**: Evaluate speed, responsiveness, and stability.
    - **Load Testing**: Check system behavior under expected loads.
    - **Stress Testing**: Test limits under extreme conditions.
    - **Usability Testing**: Assess user experience and interface.

### **3. Regression Testing**

- **Definition**: Ensures that changes (e.g., bug fixes, feature updates) do not break existing functionality.
- **Purpose**:
    - Verify the stability of the software after modifications.
    - Ensure new features or fixes do not introduce new defects.
- **Techniques**:
    - **Retest-All**: Re-testing all test cases.
    - **Regression Test Selection**: Test only selected cases (critical areas).
    - **Automated Regression**: Use tools to rerun tests quickly.
- **Examples**:
    - Re-testing login functionality after updating the authentication module.
    - Ensuring payment gateway works after adding new currencies.
- **Common Tools**: Selenium, TestComplete, Appium.

### **4. Automated Testing**

- **Definition**: Uses scripts and tools to execute tests automatically.
- **Examples**:
    - Regression testing using Selenium.
    - Continuous testing pipelines in CI/CD environments.

### **5. Manual Testing**

- **Definition**: Tests performed by human testers without automation tools.
- **Examples**:
    - Exploratory Testing: Ad hoc testing without predefined test cases.

---

### **Levels of Testing**

1. **Unit Testing**:
    - Smallest unit of software.
    - Example: Testing a login function.
2. **Integration Testing**:
    - Interaction between modules.
    - Example: Database and API integration.
3. **System Testing**:
    - Complete system as a whole.
    - Example: Testing an e-commerce website.
4. **User Acceptance Testing (UAT)**:
    - Validating with end-users.
    - Example: Beta testing a mobile app.

---

### **Testing Methods**

1. **White-Box Testing**:
    - **Definition**: Focuses on internal logic and structure.
    - **Example**: Testing algorithms for correctness.
2. **Black-Box Testing**:
    - **Definition**: Examines functionality without knowing internal code.
    - **Example**: Verifying outputs for given inputs.
3. **Grey-Box Testing**:
    - **Definition**: Combines aspects of white-box and black-box testing.
    - **Example**: Testing web application security with knowledge of code.

---

### **Key Metrics**

- **Defect Density**: Bugs per unit of code.
- **Test Coverage**: Percentage of code or functionality tested.
- **Defect Leakage**: Bugs found after release.

---

### **Advantages of Software Testing**

- Identifies issues early.
- Improves software quality.
- Reduces future costs and risks.
- Enhances customer satisfaction.

---

### **Disadvantages of Software Testing**

- Time-consuming and resource-intensive.
- Incomplete coverage of all scenarios.
- Cannot guarantee a bug-free product.

---

### **Common Tools**

- **Functional Testing**: Selenium, QTP.
- **Performance Testing**: JMeter, LoadRunner.
- **Regression Testing**: Selenium, TestComplete.
- **Bug Tracking**: Jira, Bugzilla.
- **CI/CD**: Jenkins, GitLab CI.

## **Documentation in Software Engineering**

### **Definition**

- **Documentation**: Organized written records and instructions that provide information about a software system.
- **Purpose**: To ensure clarity, communication, and usability for stakeholders throughout the software lifecycle.

---

## **Types of Documentation**

### **1. Product Documentation**

- **Definition**: Focuses on the product itself, describing its functionality, use, and maintenance.
- **Purpose**: Help end-users and administrators understand and use the software effectively.
- **Examples**:
    - **User Documentation**:
        - Manuals, guides, FAQs, tutorials.
        - Example: Microsoft Word user manual.
    - **System Documentation**:
        - Code comments, system architecture, API references, and technical details.
        - Example: API documentation for a web service.

### **Key Features**:

- Written for **end-users**, **administrators**, or **technical teams**.
- Includes **operational instructions**, **maintenance procedures**, and **technical specifications**.

---

### **2. Process Documentation**

- **Definition**: Focuses on the development process, ensuring that every step is documented and reproducible.
- **Purpose**: To provide insights into how the software was developed and maintained.
- **Examples**:
    - Project plans, schedules, and timelines.
    - Requirements documentation (SRS – Software Requirements Specification).
    - Testing documentation (test cases, test plans, results).
    - Development standards and workflows (e.g., Agile or Scrum procedures).

### **Key Features**:

- Written for **developers**, **testers**, and **project managers**.
- Ensures compliance with development standards and efficient collaboration.

---

### **Comparison: Product vs. Process Documentation**

| **Aspect** | **Product Documentation** | **Process Documentation** |
| --- | --- | --- |
| **Focus** | Describes the software product. | Describes the development process. |
| **Audience** | End-users, administrators, technical teams. | Developers, testers, project managers. |
| **Purpose** | Explains functionality and usage. | Guides the development process. |
| **Examples** | User manuals, system architecture, API references. | SRS, test cases, development workflows. |
| **Scope** | Post-development and ongoing use. | During and after the software lifecycle. |

---

### **Importance of Both Types**

- **Product Documentation**: Ensures end-users can effectively use the software.
- **Process Documentation**: Streamlines collaboration, compliance, and future enhancements.

## **Types of Documentation in Software Development**

### **1. Requirements Documentation**

- **Definition**: Specifies the functionalities, constraints, and goals of the software.
- **Purpose**: Serves as a guideline for development and testing.
- **Key Elements**:
    - Functional Requirements: Features and behavior (e.g., login system).
    - Non-Functional Requirements: Performance, scalability, security, etc.
    - Constraints: Budget, timelines, or technology limitations.
- **Examples**:
    - **SRS (Software Requirements Specification)** document.
    - Use case diagrams or user stories.
- **Audience**: Developers, testers, and stakeholders.

---

### **2. Design Documentation**

- **Definition**: Details the architecture and components of the software system.
- **Purpose**: Guides developers in implementing the system and ensures consistency.
- **Key Elements**:
    - High-level architecture diagrams.
    - Data flow diagrams (DFD) and entity-relationship diagrams (ERD).
    - Module and component descriptions.
- **Examples**:
    - System architecture design.
    - UML diagrams.
- **Audience**: Architects, developers, and testers.

---

### **3. Technical Documentation**

- **Definition**: Provides in-depth technical details about the software for maintenance and enhancement.
- **Purpose**: Assists developers in understanding code and APIs.
- **Key Elements**:
    - Code documentation (inline comments, coding standards).
    - API references (endpoints, request/response formats).
    - System configurations and deployment instructions.
- **Examples**:
    - Swagger documentation for APIs.
    - Configuration guides for servers or environments.
- **Audience**: Developers, DevOps teams, and system administrators.

---

### **4. QA (Quality Assurance) Documentation**

- **Definition**: Focuses on testing plans, cases, and strategies to ensure software quality.
- **Purpose**: Provides a roadmap for verifying and validating the software.
- **Key Elements**:
    - Test Plans: Objectives, scope, and methods.
    - Test Cases: Specific scenarios to validate functionality.
    - Test Results: Reports on test execution and outcomes.
    - Bug Reports: Identified issues with severity and status.
- **Examples**:
    - Test case documents (e.g., login tests).
    - Automated testing scripts (e.g., Selenium).
- **Audience**: QA testers, developers, and managers.

---

### **5. User Documentation**

- **Definition**: Guides end-users on how to use the software effectively.
- **Purpose**: Enhances user experience and reduces support queries.
- **Key Elements**:
    - User Manuals: Step-by-step instructions.
    - Tutorials and FAQs: Help users resolve common issues.
    - Troubleshooting Guides: Solutions for potential errors.
- **Examples**:
    - Product manuals (e.g., for Microsoft Word).
    - Help center articles and knowledge bases.
- **Audience**: End-users and administrators.

---

### **Comparison of Documentation Types**

| **Type** | **Purpose** | **Audience** | **Examples** |
| --- | --- | --- | --- |
| **Requirements** | Defines what to build. | Developers, testers, stakeholders. | SRS, user stories. |
| **Design** | Describes how to build it. | Architects, developers. | UML diagrams, architecture designs. |
| **Technical** | Provides technical details. | Developers, admins. | API docs, code comments. |
| **QA** | Ensures quality and reliability. | Testers, developers. | Test plans, bug reports. |
| **User** | Guides end-users. | End-users, administrators. | User manuals, tutorials. |

## **Roles in Software Development**

### **1. Software Developer/Engineer**

- **Role**: Designs, builds, and maintains software systems.
- **Responsibilities**:
    - Writing and testing code.
    - Debugging and fixing issues.
    - Implementing new features based on requirements.
    - Collaborating with other team members and stakeholders.

---

### **2. Frontend Developer**

- **Role**: Focuses on the user interface (UI) and user experience (UX) aspects of software.
- **Responsibilities**:
    - Designing and implementing UI components (e.g., using HTML, CSS, JavaScript).
    - Ensuring responsiveness and cross-platform compatibility.
    - Enhancing user experience through interactive features.
    - Collaborating with designers to implement visual elements.

---

### **3. Backend Developer**

- **Role**: Develops the server-side logic and integrates the frontend with the backend.
- **Responsibilities**:
    - Writing server-side code (e.g., in Python, Java, Node.js).
    - Managing databases and data storage.
    - Creating APIs and ensuring their security and performance.
    - Optimizing system performance and scalability.

---

### **4. Full-Stack Developer**

- **Role**: Works on both frontend and backend aspects of the software.
- **Responsibilities**:
    - Developing complete solutions, including UI, APIs, and databases.
    - Debugging issues across the entire software stack.
    - Bridging communication between frontend and backend teams.

---

### **5. Software Architect**

- **Role**: Designs the overall structure and high-level solutions of the software.
- **Responsibilities**:
    - Defining the architecture and design patterns.
    - Ensuring scalability, maintainability, and performance of the system.
    - Making technology stack decisions.
    - Mentoring developers and reviewing code.

---

### **6. QA Engineer/Tester**

- **Role**: Ensures software meets quality standards through rigorous testing.
- **Responsibilities**:
    - Creating test plans, cases, and scripts.
    - Conducting manual and automated testing.
    - Reporting bugs and verifying fixes.
    - Ensuring software reliability, usability, and performance.

---

### **7. UI/UX Designer**

- **Role**: Designs user interfaces and enhances user experience.
- **Responsibilities**:
    - Creating wireframes, mockups, and prototypes.
    - Conducting user research and usability testing.
    - Collaborating with developers to implement designs.
    - Ensuring accessibility and visual consistency.

---

### **8. DevOps Engineer**

- **Role**: Manages deployment, CI/CD pipelines, and infrastructure.
- **Responsibilities**:
    - Setting up automated build and deployment pipelines.
    - Monitoring system performance and uptime.
    - Managing cloud infrastructure (e.g., AWS, Azure).
    - Ensuring system security and backups.

---

### **9. Product Manager**

- **Role**: Defines the product vision and manages its development lifecycle.
- **Responsibilities**:
    - Gathering and prioritizing requirements from stakeholders.
    - Creating product roadmaps and managing timelines.
    - Aligning the team with business objectives.
    - Acting as a liaison between technical and non-technical stakeholders.

---

### **10. Project Manager**

- **Role**: Oversees the planning, execution, and delivery of software projects.
- **Responsibilities**:
    - Managing project scope, timelines, and resources.
    - Facilitating communication among team members.
    - Tracking progress and resolving roadblocks.
    - Ensuring project deliverables meet quality standards.

---

### **11. Business Analyst**

- **Role**: Acts as a bridge between stakeholders and the development team.
- **Responsibilities**:
    - Gathering and documenting business requirements.
    - Analyzing processes and suggesting improvements.
    - Creating use cases and workflows.
    - Ensuring the final product aligns with business goals.

---

### **12. System Administrator**

- **Role**: Manages and maintains IT infrastructure.
- **Responsibilities**:
    - Installing and configuring servers and networks.
    - Monitoring system performance and security.
    - Troubleshooting and resolving system issues.
    - Ensuring data backup and disaster recovery.

---

### **13. Data Engineer**

- **Role**: Focuses on building systems to collect, store, and analyze data.
- **Responsibilities**:
    - Designing and managing data pipelines.
    - Integrating data from multiple sources.
    - Ensuring data quality and consistency.
    - Optimizing data processing for performance.

---

### **14. Security Specialist**

- **Role**: Ensures software and systems are secure from vulnerabilities.
- **Responsibilities**:
    - Conducting vulnerability assessments and penetration tests.
    - Implementing encryption and access controls.
    - Monitoring systems for security breaches.
    - Educating team members about security best practices.

---

### **15. Technical Writer**

- **Role**: Creates and maintains documentation for technical and non-technical audiences.
- **Responsibilities**:
    - Writing user manuals, API documentation, and FAQs.
    - Ensuring documentation is clear and accurate.
    - Collaborating with developers to understand technical details.
    - Updating documents to reflect changes in software.

---

### **Team Collaboration Example**

- **Frontend Developer** implements the UI designed by the **UI/UX Designer**.
- **Backend Developer** integrates APIs defined by the **Software Architect**.
- **QA Engineer** tests functionality based on requirements from the **Product Manager**.
- **DevOps Engineer** deploys the final build, ensuring it runs smoothly in production.
