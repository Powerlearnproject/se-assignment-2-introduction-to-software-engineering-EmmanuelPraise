[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15236668&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
# Define Software Engineering:
## What is software engineering, and how does it differ from traditional programming

### What is Software Engineering?
Software engineering is the systematic application of engineering principles, methods, and tools to the development, operation, and maintenance of software systems. It involves a comprehensive approach to designing, developing, testing, deploying, and maintaining software to ensure it is reliable, efficient, and meets user requirements.

### How Does Software Engineering Differ from Traditional Programming?
1. **Scope and Focus**:
   - **Software Engineering**: Focuses on the entire lifecycle of a software product, from initial planning and design to deployment and maintenance. It emphasizes a structured, disciplined approach to ensure quality and manage complexity.
   - **Traditional Programming**: Concentrates primarily on writing code to solve specific problems or implement particular features. It does not typically encompass the broader planning, design, and long-term maintenance aspects.

2. **Methodologies and Practices**:
   - **Software Engineering**: Utilizes established methodologies and best practices, such as Agile, Waterfall, and DevOps, to manage projects systematically and ensure high-quality outcomes.
   - **Traditional Programming**: May not follow formal methodologies or structured practices, relying more on the programmer's individual skills and experience.

3. **Team Collaboration**:
   - **Software Engineering**: Involves collaborative efforts from multidisciplinary teams, including developers, testers, project managers, and UX designers.
   - **Traditional Programming**: Often performed by individual programmers or small teams, with less emphasis on formal roles and collaboration.

4. **Tools and Technologies**:
   - **Software Engineering**: Employs a wide range of tools for project management, version control, continuous integration/continuous deployment (CI/CD), testing, and more.
   - **Traditional Programming**: Primarily involves coding and basic debugging tools, with less focus on the integrated toolchains and processes used in software engineering.

# Software Development Life Cycle (SDLC):
## Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

### Phases of the Software Development Life Cycle (SDLC)
1. **Requirements**:
   - **Description**: This phase involves gathering and documenting the specific needs and expectations of users and stakeholders. It includes defining functional and non-functional requirements to ensure that the software will meet its intended purpose.
   
2. **Design**:
   - **Description**: In this phase, high-level and detailed designs of the software architecture and user interface are created. This includes designing system components, data structures, and interfaces to meet the specified requirements.
   
3. **Implementation**:
   - **Description**: During this phase, the actual code is written based on the design specifications. Programmers develop the software modules, integrate them, and ensure they function as intended.
   
4. **Testing**:
   - **Description**: This phase involves conducting various tests to verify that the software meets quality standards and functional requirements. Testing can include unit testing, integration testing, system testing, and user acceptance testing.
   
5. **Deployment**:
   - **Description**: In this phase, the software is released to users or customers. This includes installing, configuring, and possibly migrating data to the new system.
   
6. **Maintenance**:
   - **Description**: After deployment, this phase involves providing ongoing support, updates, and enhancements to the software. Maintenance includes fixing bugs, making improvements, and adapting the software to changing requirements.


# Agile vs. Waterfall Models:

## Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

### Agile vs. Waterfall Models of Software Development
**Agile Model**

**Description**: 
The Agile model is an iterative and incremental approach to software development. It focuses on flexibility, collaboration, and rapid delivery of functional software components.

**Key Features**:
- **Iterative Development**: Software is developed in small, manageable increments.
- **Customer Collaboration**: Continuous interaction with customers to refine and prioritize requirements.
- **Flexibility**: Adaptable to changes even late in the development process.
- **Frequent Delivery**: Deliver working software frequently, typically in short cycles called sprints (e.g., 2-4 weeks).
- **Cross-functional Teams**: Teams are composed of members with diverse skills, working collaboratively.

**Waterfall Model**

**Description**: 
The Waterfall model is a linear and sequential approach to software development. Each phase must be completed before moving on to the next, with a strong emphasis on documentation and upfront planning.

**Key Features**:
- **Sequential Phases**: Development proceeds through a fixed sequence: Requirements, Design, Implementation, Testing, Deployment, and Maintenance.
- **Thorough Documentation**: Extensive documentation is created at each phase.
- **Predictability**: Timelines and budgets can be estimated more accurately due to the structured approach.
- **Less Flexibility**: Difficult to accommodate changes once the project is underway.

### Key Differences

1. **Development Approach**:
   - **Agile**: Iterative and incremental.
   - **Waterfall**: Linear and sequential.

2. **Flexibility**:
   - **Agile**: Highly adaptable to changes; requirements can evolve.
   - **Waterfall**: Rigid; changes are difficult and costly to implement once a phase is completed.

3. **Customer Involvement**:
   - **Agile**: High level of customer involvement throughout the development process.
   - **Waterfall**: Limited customer involvement after the initial requirements phase.

4. **Delivery**:
   - **Agile**: Frequent delivery of small, functional software components.
   - **Waterfall**: Single delivery at the end of the project after all phases are completed.

5. **Documentation**:
   - **Agile**: Emphasizes working software over comprehensive documentation.
   - **Waterfall**: Heavy reliance on documentation to guide the process.

6. **Risk Management**:
   - **Agile**: Risks are identified and mitigated early through continuous feedback and iteration.
   - **Waterfall**: Risks are identified upfront, but issues may only become apparent later in the development cycle.

### Preferred Scenarios

**Agile**:
- **Dynamic Requirements**: Projects where requirements are expected to change frequently.
- **Customer Collaboration**: Projects that benefit from continuous customer feedback and involvement.
- **Rapid Delivery**: Need for quick releases of functional software components.
- **Innovation and Creativity**: Environments that encourage experimentation and iterative improvements.

**Waterfall**:
- **Well-Defined Requirements**: Projects with clear, stable, and well-understood requirements from the start.
- **Predictability**: Projects with fixed budgets and timelines where predictability is crucial.
- **Regulatory Compliance**: Projects that require extensive documentation and adherence to strict regulatory standards.
- **Large-Scale Projects**: Projects where the scope is large and complex, and a structured approach helps manage complexity.

# Requirements Engineering:
## What is requirements engineering? Describe the process and its importance in the software development lifecycle.

### What is Requirements Engineering?

Requirements engineering is the systematic process of defining, documenting, and maintaining the requirements for a software system. It involves understanding what the users and stakeholders need from the software, and translating these needs into clear, precise, and actionable requirements that guide the development process.

### The Requirements Engineering Process

The requirements engineering process typically consists of several key activities:

1. **Elicitation**:
   - **Description**: Gathering requirements from stakeholders, users, and other sources. Techniques include interviews, surveys, workshops, observation, and document analysis.
   - **Importance**: Ensures that all relevant requirements are identified and understood.

2. **Analysis**:
   - **Description**: Examining and prioritizing the gathered requirements to resolve conflicts, determine feasibility, and understand the impact of each requirement.
   - **Importance**: Helps refine and clarify requirements, ensuring they are realistic and achievable.

3. **Specification**:
   - **Description**: Documenting the requirements in a clear, precise, and unambiguous manner. This can include creating use cases, user stories, functional and non-functional requirements, and other detailed descriptions.
   - **Importance**: Provides a clear and comprehensive guide for designers and developers to follow.

4. **Validation**:
   - **Description**: Ensuring that the documented requirements accurately reflect the needs and expectations of the stakeholders. Techniques include reviews, prototyping, and model validation.
   - **Importance**: Confirms that the requirements are correct, complete, and feasible before development begins.

5. **Management**:
   - **Description**: Continuously managing and maintaining the requirements throughout the software development lifecycle. This includes handling changes to requirements, tracking progress, and ensuring consistency.
   - **Importance**: Keeps the project on track by managing changes and ensuring that all stakeholders are aware of the current requirements.

### Importance of Requirements Engineering in the Software Development Lifecycle

1. **Foundation for Development**:
   - Requirements engineering provides a solid foundation for the entire software development process. Well-defined requirements guide the design, implementation, testing, and maintenance phases, ensuring that the software meets user needs and expectations.

2. **Reduction of Errors**:
   - Early and thorough requirements engineering helps identify and resolve potential issues and conflicts before development begins, reducing the likelihood of costly errors and rework later in the project.

3. **Improved Communication**:
   - Clear and well-documented requirements improve communication among stakeholders, developers, and other team members. This ensures that everyone has a shared understanding of what the software needs to accomplish.

4. **Scope Management**:
   - Requirements engineering helps define and manage the scope of the project, preventing scope creep and ensuring that the project stays focused on delivering the agreed-upon functionality.

5. **Customer Satisfaction**:
   - By involving stakeholders in the requirements engineering process and ensuring that their needs are accurately captured and met, the likelihood of delivering a product that satisfies customers is greatly increased.

6. **Risk Management**:
   - Identifying and analyzing requirements early in the project allows for better risk management, as potential challenges and uncertainties can be addressed proactively.

# Software Design Principles:
## Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

### Concept of Modularity in Software Design

**Modularity** in software design refers to the practice of dividing a software system into distinct, self-contained units or modules, each with a specific responsibility. These modules are designed to be independent of each other, interacting through well-defined interfaces. This approach promotes separation of concerns, where each module handles a specific aspect of the software’s functionality.

### Key Characteristics of Modularity

1. **Encapsulation**:
   - Each module encapsulates its data and functionality, exposing only what is necessary through interfaces. This hides the internal workings of the module from other parts of the system.

2. **Cohesion**:
   - Modules are designed to be cohesive, meaning that the functionalities within a module are closely related and serve a single purpose.

3. **Loose Coupling**:
   - Modules are loosely coupled, meaning that changes in one module have minimal impact on others. This is achieved through well-defined interfaces and minimizing dependencies.

### How Modularity Improves Maintainability

1. **Ease of Understanding**:
   - Smaller, self-contained modules are easier to understand, test, and debug. Developers can focus on a single module without needing to comprehend the entire system.

2. **Isolation of Changes**:
   - Changes in one module can be made independently of others, reducing the risk of introducing bugs elsewhere in the system. This isolation simplifies debugging and testing.

3. **Reusability**:
   - Modules can be reused across different parts of the system or in different projects. This reduces redundancy and speeds up development.

4. **Simplified Testing**:
   - Modules can be tested individually, making it easier to identify and fix defects. Unit tests can be more focused and comprehensive.

5. **Parallel Development**:
   - Different modules can be developed simultaneously by different teams, speeding up the development process and improving productivity.

### How Modularity Improves Scalability

1. **Independent Scaling**:
   - Individual modules can be scaled independently based on their specific performance needs. For example, a module handling user authentication can be scaled separately from a module handling data processing.

2. **Performance Optimization**:
   - Performance bottlenecks can be identified and optimized at the module level, allowing for targeted improvements without overhauling the entire system.

3. **Distributed Deployment**:
   - Modules can be deployed across different servers or environments, enabling load balancing and better resource utilization.

4. **Flexible Updates**:
   - Updates or new features can be rolled out to specific modules without affecting the entire system, allowing for more flexible and less disruptive upgrades.

# Testing in Software Engineering:
## Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

### Levels of Software Testing

1. **Unit Testing**:
   - **Description**: Unit testing involves testing individual units or components of the software in isolation. Developers write test cases to validate the functionality of specific functions, methods, or classes.
   - **Purpose**: To ensure that each unit of the software behaves as expected and functions correctly within the scope of its defined specifications.

2. **Integration Testing**:
   - **Description**: Integration testing focuses on testing the interactions and interfaces between different units or modules of the software. It verifies that integrated components work together seamlessly.
   - **Purpose**: To detect defects in the interactions between modules and ensure the smooth integration of different parts of the software.

3. **System Testing**:
   - **Description**: System testing evaluates the behavior of the entire software system as a whole. It tests the system against its functional and non-functional requirements, including performance, reliability, and usability.
   - **Purpose**: To validate that the software meets the specified requirements and performs as expected in its intended environment.

4. **Acceptance Testing**:
   - **Description**: Acceptance testing assesses whether the software meets the acceptance criteria defined by stakeholders, including end-users, customers, and business owners. It evaluates the software's functionality, usability, and overall satisfaction.
   - **Purpose**: To gain confidence that the software satisfies stakeholder requirements and is ready for deployment.

### Importance of Testing in Software Development

1. **Quality Assurance**:
   - Testing ensures that the software meets quality standards and performs reliably, leading to a positive user experience.

2. **Bug Detection**:
   - Testing helps identify and eliminate bugs, errors, and defects early in the development process, reducing the likelihood of costly fixes later on.

3. **Risk Reduction**:
   - By uncovering issues and vulnerabilities, testing mitigates the risk of software failures, security breaches, and negative impacts on users and businesses.

4. **Validation of Requirements**:
   - Testing validates that the software meets its specified requirements and aligns with stakeholder expectations, ensuring that it delivers the intended functionality.

5. **Continuous Improvement**:
   - Testing provides feedback to developers, enabling them to iterate, refine, and improve the software over time, leading to continuous enhancement and innovation.

6. **Customer Satisfaction**:
   - Delivering high-quality software through thorough testing enhances customer satisfaction and loyalty, fostering positive relationships and driving business success.

7. **Compliance and Regulation**:
   - Testing helps ensure compliance with industry standards, regulations, and legal requirements, reducing the risk of penalties and legal issues.

# Version Control Systems:
## What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

### Version Control Systems (VCS)

**Version control systems** (VCS) are software tools that enable developers to manage changes to source code and other files throughout the software development lifecycle. They track modifications, revisions, and updates made to files, allowing developers to collaborate effectively, maintain project history, and manage codebase versions.

### Importance of Version Control Systems in Software Development

1. **Collaboration**: VCS enables multiple developers to work on the same codebase concurrently without conflicts. It facilitates teamwork by providing mechanisms for merging and resolving conflicts.

2. **History and Audit Trail**: VCS maintains a history of changes made to files, including who made the changes and when. This audit trail is invaluable for tracking the evolution of the codebase, understanding past decisions, and troubleshooting issues.

3. **Branching and Merging**: VCS allows developers to create branches to work on new features or experiments independently. Branches can later be merged back into the main codebase, facilitating parallel development and release management.

4. **Undo and Rollback**: VCS enables developers to revert changes to previous states of the codebase, providing a safety net for experimentation and troubleshooting. This ability to undo mistakes or revert to known good states is crucial for maintaining stability and reliability.

5. **Backup and Disaster Recovery**: VCS serves as a backup mechanism for code and project assets. By storing code in a centralized repository, developers can recover lost or corrupted files and restore project data in the event of a disaster.

6. **Traceability and Compliance**: VCS provides traceability by linking code changes to specific issues, tasks, or requirements. This helps maintain compliance with regulatory standards and enables efficient auditing of software development processes.

### Popular Version Control Systems and Their Features

1. **Git**:
   - **Features**: Distributed version control, branching and merging, lightweight and fast, offline support, strong community support, integration with popular development tools (e.g., GitHub, GitLab, Bitbucket).
   - **Examples**: GitHub, GitLab, Bitbucket.

2. **Subversion (SVN)**:
   - **Features**: Centralized version control, branching and tagging, atomic commits, easy repository browsing, support for binary files.
   - **Examples**: Apache Subversion (SVN), VisualSVN, TortoiseSVN.

3. **Mercurial**:
   - **Features**: Distributed version control, branching and merging, easy-to-use command-line interface, efficient handling of large repositories.
   - **Examples**: Mercurial (Hg), Bitbucket.

4. **Perforce Helix Core**:
   - **Features**: Centralized version control, high-performance file versioning, support for large binary files, fine-grained access controls, built-in code review.
   - **Examples**: Perforce Helix Core (formerly known as Perforce SCM).

5. **Microsoft Team Foundation Version Control (TFVC)**:
   - **Features**: Centralized version control, integration with Microsoft Visual Studio and Azure DevOps, support for large projects and enterprise-scale development.
   - **Examples**: Azure DevOps Services, Team Foundation Server (TFS).

# Software Project Management:
# Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

### Role of a Software Project Manager

A software project manager is responsible for overseeing the planning, execution, and delivery of software projects. They serve as leaders, coordinators, and communicators, ensuring that the project meets its objectives, stays within budget and timeline, and satisfies stakeholder requirements. The role of a software project manager encompasses various responsibilities and challenges:

### Key Responsibilities

1. **Project Planning**:
   - Define project scope, objectives, deliverables, and timeline.
   - Develop project plans, schedules, and resource allocation.

2. **Team Management**:
   - Build and lead cross-functional project teams.
   - Assign tasks, set priorities, and monitor progress.
   - Provide guidance, support, and motivation to team members.

3. **Stakeholder Communication**:
   - Communicate project status, updates, and risks to stakeholders.
   - Manage expectations and address concerns.
   - Facilitate collaboration and alignment among stakeholders.

4. **Risk Management**:
   - Identify potential risks and develop mitigation strategies.
   - Monitor and assess project risks throughout the project lifecycle.
   - Implement contingency plans to address unforeseen challenges.

5. **Quality Assurance**:
   - Ensure adherence to quality standards and best practices.
   - Implement processes for testing, validation, and quality control.
   - Address issues and defects promptly to maintain software quality.

6. **Budget and Resource Management**:
   - Estimate project costs, budget allocation, and resource requirements.
   - Track expenses, manage budgets, and optimize resource utilization.
   - Make decisions to ensure the project stays within budget constraints.

7. **Change Management**:
   - Manage changes to project scope, requirements, and timelines.
   - Evaluate change requests, assess impacts, and communicate decisions to stakeholders.
   - Implement change control processes to minimize disruption and maintain project focus.

### Challenges Faced in Managing Software Projects

1. **Scope Creep**:
   - Managing evolving requirements and scope changes while maintaining project objectives and timelines.

2. **Resource Constraints**:
   - Balancing resource availability, skills, and workload to meet project demands and deadlines.

3. **Communication Issues**:
   - Ensuring effective communication and collaboration among distributed teams, stakeholders, and project members.

4. **Technical Complexity**:
   - Addressing technical challenges, dependencies, and integration issues within the project.

5. **Schedule Pressure**:
   - Managing tight deadlines and competing priorities while maintaining quality standards and avoiding burnout.

6. **Risk Management**:
   - Identifying, assessing, and mitigating project risks to minimize their impact on project outcomes.

7. **Client Expectations**:
   - Managing client expectations, addressing feedback, and ensuring alignment between project deliverables and stakeholder needs.

# Software Maintenance:
## Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

### Software Maintenance

**Software maintenance** refers to the process of modifying, updating, and enhancing software after it has been deployed. It involves making changes to the software to address defects, improve performance, adapt to new requirements, and enhance functionality. Software maintenance is crucial for ensuring the longevity, reliability, and effectiveness of software systems throughout their lifecycle.

### Types of Maintenance Activities

1. **Corrective Maintenance**:
   - **Description**: Correcting defects, errors, or bugs discovered in the software during testing or after deployment. This involves identifying the root cause of the issue and implementing fixes to resolve it.
   - **Example**: Patching security vulnerabilities, fixing software crashes, resolving user-reported issues.

2. **Adaptive Maintenance**:
   - **Description**: Adapting the software to changes in the environment, such as new hardware, operating systems, or regulations. This involves modifying the software to ensure compatibility and functionality in the updated environment.
   - **Example**: Upgrading software to support the latest version of an operating system, updating integrations with third-party services, complying with new industry standards.

3. **Perfective Maintenance**:
   - **Description**: Improving the software's performance, efficiency, or usability based on feedback from users or stakeholders. This involves enhancing existing features, optimizing code, and refining user interfaces.
   - **Example**: Adding new features to meet evolving user needs, optimizing database queries for improved performance, enhancing user experience through UI/UX redesign.

4. **Preventive Maintenance**:
   - **Description**: Proactively identifying and addressing potential issues or risks in the software to prevent future problems. This involves implementing measures to enhance reliability, security, and maintainability.
   - **Example**: Conducting code reviews to identify and fix potential vulnerabilities, updating software components to mitigate security risks, implementing automated tests to catch regressions.

### Importance of Software Maintenance

1. **Enhanced Reliability**: Maintenance ensures that software remains reliable and stable by addressing defects and errors that could impact its performance.

2. **Adaptation to Change**: Maintenance enables software to adapt to changing requirements, technologies, and environments, ensuring its continued relevance and effectiveness.

3. **Improved Performance**: Maintenance activities such as optimization and tuning can enhance the performance and efficiency of software systems, leading to better user experiences and resource utilization.

4. **Extended Lifespan**: Maintenance prolongs the lifespan of software by addressing issues and making improvements over time, allowing organizations to maximize their investment in software assets.

5. **Cost Savings**: Proactively addressing issues through preventive maintenance can help prevent costly failures and downtime, ultimately saving time and resources in the long run.

6. **Customer Satisfaction**: Regular maintenance ensures that software meets user needs and expectations, leading to higher levels of customer satisfaction and loyalty.

7. **Compliance and Security**: Maintenance activities such as updates and patches help ensure that software remains compliant with regulations and industry standards, as well as secure against emerging threats and vulnerabilities.



# Ethical Considerations in Software Engineering:
## What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

Software engineers may encounter various ethical issues throughout their careers, including:

1. **Privacy Concerns**: Ensuring that user data is handled responsibly and ethically, protecting privacy rights and preventing unauthorized access or misuse of personal information.

2. **Security Vulnerabilities**: Addressing security vulnerabilities and ensuring that software systems are secure from cyber threats and attacks, such as data breaches, malware, and hacking.

3. **Bias and Fairness**: Addressing biases in algorithms and decision-making processes to ensure fairness and equity, particularly in applications such as machine learning and artificial intelligence.

4. **Intellectual Property**: Respecting intellectual property rights, including copyright, patents, and trademarks, and avoiding plagiarism, piracy, or unauthorized use of proprietary software and technologies.

5. **Transparency and Accountability**: Being transparent about the capabilities and limitations of software systems, providing clear documentation, and taking responsibility for the consequences of software actions.

6. **Environmental Impact**: Considering the environmental impact of software development, including energy consumption, carbon emissions, and electronic waste generation, and striving to minimize environmental harm.

7. **Social Impact**: Considering the broader social impact of software systems on communities, societies, and cultures, and ensuring that software promotes positive outcomes and avoids harm.

To ensure they adhere to ethical standards in their work, software engineers can take several measures:

1. **Ethics Training**: Receive training and education on ethical principles, values, and best practices relevant to software engineering, including courses, workshops, and certifications.

2. **Code of Ethics**: Adhere to professional codes of ethics and conduct, such as those outlined by organizations like the Association for Computing Machinery (ACM) and the Institute of Electrical and Electronics Engineers (IEEE).

3. **Ethics Reviews**: Conduct ethics reviews and assessments of software projects and decisions, considering potential ethical implications and seeking input from diverse perspectives.

4. **Stakeholder Engagement**: Engage with stakeholders, including users, customers, and communities, to understand their concerns and values and incorporate ethical considerations into software design and development.

5. **Ethical Design Practices**: Apply ethical design principles, such as privacy by design, security by design, and inclusive design, to ensure that software systems are built with ethical considerations in mind from the outset.

6. **Whistleblowing**: Speak up about ethical concerns or violations within their organizations, including reporting unethical behavior or practices to appropriate authorities or regulatory bodies.

7. **Continuous Learning**: Stay informed about emerging ethical issues and developments in the field of software engineering, and actively seek opportunities for professional development and learning in ethics-related topics.

By integrating ethical considerations into their work and decision-making
processes, software engineers can contribute to the development of software
systems that are ethical, responsible, and beneficial to society.

### References:

- [Wikipedia - Software Engineering](https://en.wikipedia.org/wiki/Software_engineering)
- [Michigan Tech University - What is Software Engineering?](https://www.mtu.edu/cs/undergraduate/software/what/)
- [Wikipedia - Version Control](https://en.wikipedia.org/wiki/Version_control)
- [GeeksforGeeks - Software Engineering and Software Project Management](https://www.google.com/amp/s/www.geeksforgeeks.org/software-engineering-software-project-management-spm/amp/)
- [Synopsys - Top 4 Software Development Methodologies](https://www.synopsys.com/blogs/software-security/top-4-software-development-methodologies.html)
- [OpenAI Chat](https://chat.openai.com/)

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
