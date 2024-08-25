[Domain 8](#domain8-top) **Software Development Security**

[8.1](#8.1) Understand and integrate security in the Software Develoment Life Cycle (SDLC) (OSG-9 Chpt 20)
- Domain 8 is focused on helping security pros understand and apply software or application security
    - Applications can present significant risks, and security pros must understand and balance these risks with business requirements and implement appropriate risk mitigation; if a company develops custom software, the custom solution can present additional, unique risks and vulns 
        - orgs with custom solutions should be on the lookout for logic weaknesses (e.g. buffer overflow vulns), and guard against malicious changes (e.g. backdoors) that can leave the system vulnerable to attacks
    - As software development environments have become increasingly complex, it's important to review this area -- one of the biggest threats to an organization's security

- In this domain you'll learn the basic principles behind securely designing, building, testing, operating and even decomissioning enterprise apps
- Security should be part of the design, and incorporated into the architecture, with the level of protection based on requirements and operating environment
- The Software Development LifeCycle consists of the following steps:
    - Requirements gathering: why create the software, what it will do, and for whom it will be created
    - Design: encapsulating how the software will meet requirements
    - Development: creating/coding the software to meet spec, and integrating with other systems as required
    - Testing: verifying/validating software meets requirements
    - Operations and Maintenance: deploying, and ensuring it's appropriately configured, patched, and monitored

- **Acceptance**: formal, structured hand-off of the completed software system to the customer org; usually involves test, analysis and assessment activites
- **Accreditation**: AKA Security Accreditation a formal declaration by a designated accrediting authority (DAA) that an information system is approved to operate at an acceptable level of risk, absed onthe implementation an approved set of technical, managerial, and procedural safeguards
- **ACID Test**: data integrity provided by means of enforcing atomicity, consistency, isolation, and durability policies
- **Aggregation**: ability to combine non-sensitive data from separate sources to create sensitive info
- **Arbitrary code**: alternate set of instructions and data that an attacker attempts to trick a processor into executing
- **Buffer overflow**: source code vulnerability allowing access to data locations outside of the storage space allocated to the buffer; can be triggered by attempting to input data larger than the size of the buffer. Input that is too large can “overflow” a data structure to affect other data stored in the computer’s memory.
- **Bypass attack**: attempt to bypass front-end controls of a database to access information
- **Certification**: comprehensive technical security analysis of a system to ensure it meets all applicable security requirements
- **Citizen programmers**: organizational members who codify work-related knowledge, insights, and ideas into (varying degress of) usable software; the process and result is ad hoc, difficult to manage, and usually bereft of security considerations
- **Code protection/logic hiding**: prevents one software unit from reading/altering the source/intermediate/executable code of another software unit
- **Code resuse**: reuse of code, rather than re-invented code means units of software (procedures/objects) means higher productivity toward development requirements using correct, complete, safe code
- **Object/Memory reuse**: systems allocate/release and reuse memory/resources as objects to requesting processes; data remaining in the object when it is reused is a potential security violation (i.e. data remanence)
- **CORBA**: Common Object Request Broker Architecture is a set of standards addressing interoperability between software and hardware products, residing on different machines across a network; providing object location and use across a network
- **Configuration Control**: process of controlling modifications to hardware, firmware, software, and documentation to protect the information system against improper modifications prior to, during, and after system implementation
- **Configuration Management (CM)**: collection of activities focused on establishing and maintaining integrity of IT products and information systems, through the control of processes for initialization, changing and monitoring the configurations of those products and systems throughout the system development lifecycle
- **Covert Channels/Paths**: communication pathways that violate security policy or requirement (deliberately or unwittingly)
- **Data Contamination**: attackers attempt to use malformed inputs, at the field, record, transaction, or file level, in an attempt to disrupt the proper functioning of the system. 🔥Can also be referred to as the mixing of data from a higher classification level and/or need-­to-­know requirement with data from a lower classification level and/or need-­to-­know requirement.
- **Data Lake**: a data warehouse incorporating multiple types of streams of unstructured or semi-structured data
- **Data Mining**: analysis and decision-making technique that relies on extracting deeper meanings from many different instances and types of data; often applied to data warehouse content
- **Data Modeling**: design process that identifies all data elements that the system will need to input, create, store, modify, output, and destroy during operational use; should be one of the first steps in analysis and design
- **Data Protection and Data Hiding**: restricts or prevents one software unit from reading or altering the private data of another software unit
- **Data Type Enforcement**: how a language protects a developer from trying to perform operations on dissimilar types of data, or in ways that would lead to erroneous results
- **Data Warehouse**: collection of data sources such as separate internal databases to provide a broader base of info for analysis, trending and reference; may also involve databases from outside the org
- **Data-centric Threat Modeling**: methodology and framework focusing on the authorized movements and data input/output into and from a system; corresponds with protecting data in transit, at rest, and in use when classifying organizational data
- **Defensive Programming**: design/coding allowing acceptable but sanitized data inputs to a system; lack of defensive programming measures can result in arbitrary code execution, misdirection of the program to other resoruces/locations, or reveal info useful to an attacker
- **Emerging Properties**: an alternate/more powerful way of looking at systems-level behavior characteristics such as safety and security; helps provide a more testable, measurable answer to questions such as "how secure is our system?"
- **Encapsulation**: note see network [Encapsulation](https://github.com/jefferywmoore/CISSP-Study-Resources/blob/main/CISSP-Domain-4-Objectives.md) (disambiguation); enforcement of data/code hiding during all phases of software development and operational use; bundling together data and methods is the process of encapulation (opposite of unpacking/revealing)
- **Executable/Object Code**: binary representation of the machine language instruction set that the CPU and other hardware of the target computer can directly execute
- **XML**: Extensible Markup Language is a set of HTML extensions providing for data storage and transport in networked environments; frequently used to integrate web pages with databases; XML is often embedded in the HTML files making up elements of a web page
- **Functional requirements**: describes a finite task or process the system must perform; often directly traceable to specific elements in the final system's design and construction
- **Hierarchical database model**: data elements and records are arranged in tree-like parent-child structures
- **Integrated Product and Process Development (IPPD)**: management technique that simultaneously integrates essential acquisition activities through the use of multidisciplinary teams to optimize the design, manufacturing, and supportability processes
- **Integrated Product Team (IPT)**: team of stakeholders and individuals that possess different skills and who work together to acheive a defined process or product.
    - It was designed by the Defense Department in 1995.
    - It was a predecessor to the Agile methodology, which uses tools like the scrum approach and user stories to conduct software development work. 
- **Interactive Application Security Testing (IAST)**: testing that combines or integrates SAST and DAST to improve testing and provide behavioral analysis capabilities to pinpoint the source of vulnerabilities
- **Knowledge Discovery in Database (KDD)**: mathematical, statistical, and visualization method of identifying valid and useful patterns in data
- **Knowledge Management**: efficent/effective management of info and associated resources in an enterprise to drive busienss intelligence and decision-making; may include workflow management, business process modeling, doc management, db and info systems and knowledge-based systems
- **Level of abstraction**: how closely a source-code/design doc represents the details of the underlying object/system/component; lower-level abstractions generally have more detail than high-level ones
- **Living off the land** (non-malware based ransom attack): system attack where the system/resources compromised are used in pursuit of additional attacks (i.e. the attacker's agenda); anti-malware defence doesn't detect/prevent the attack given the attacker's methodology
- **Malformed input attack**: not currently handling input data is a common source of code errors that can result in arbitrary code exec, or misdirection of the program to other resources/locations
- **Manipulation** is the authorized or unauthorized alteration of data in a database.
- **Markup Language**: non-programming language used to express formatting or arrangement of data on a page/screen; usually extensible, allowing users to define additional/other operations to be performed; they etend the language into a programming language (e.g. in the same way JavaScript extends HTML)
- **Metadata**: info that describes the format or meaning of other data, which can be used to provide a systematic method for describing resources and improving info retrieval
- **Mobile code (executable content)**: file(s) sent by a system to others, that will either control the execution of systems/applications on that client or be directly executed
- **Modified prototype model**: approach to system design/build that starts with a simplified version of the application; feedback from stakeholders is used to improve design of a second version; this is repeated until owners/stakeholders are satisfied with the final product
- **Network database model**: database model in which data elements and records are arranged in arbitrary linked fashion (.e.g lists, clusters, or other network forms)
- **Nonfunctional requirements**: broad characteristics that do not clearly align with system elements; many safety, security, privacy, and resiliency can be deemed nonfunctional
- **Object**: encapsulation of a set of data and methods that can be used to manipulate that data
- **Object-oriented database model**: database model that uses object-oriented programming concepts like classes, instances, and objects to organize, structure, and store data and methods; schemas define the structure of the data, views specify table, rows, and columns that meet user/security requirements
- **Object-oriented security**: systems security designs that make sue of object-oriented programming characteristics such as encapsulation, inheritance, polymorphism, and polyinstantiation
- **Open-source software**: source code and design info is made public, and often using licenses that allow modification and refactoring
- **Polyinstantiation**: creates a new instance (copy) of a data item, with the same identifier or key, allowing each process to have its own version of that data; useful for enforcing and protecting different security levels for a shared resource. Polyinstantiation is the creation of different database records for users of differing security levels.
- **Procedural programming**: emphasizes the logical sequence of steps to be peformed, where a procedure is a set of software that performs a particular function, requiring specific input data, producing a specific set of outputs, and procedures can invoke other procedures
- **Query attack**: use of query tools to access data not normally allowed by the trusted front end, including the views controlled by the query application; could also result from malformed queries using SQL to bypass security controls; improper/incomplese checks on queries can be used in a similar way to bypass access controls
- **Ransom attack**: form of attack that threatens destruction, denial, or unauthorized public release/remarketing of private information assets; usually involves encrypting assets and withhold the decryption key until a ransom is paid by the victim
- **Refactoring**: partial or complete rewrite of a set of software to perform the same functions, but in a more straightforward, more efficient, or more maintainable form
- **Regression testing**: test a system to ascertain whether recently approved modifications have changed performance of other approved functions or introduced other unautorized behavior.
    - Regression testing is performed after developers make changes to an application. It reruns a number of test cases and compares the results to baseline results. 
    - Orthogonal array testing is a method for generating test cases based on statistical analysis.
    - Pattern testing uses records of past software bugs to inform the analysis.
    - Matrix testing develops a matrix of all possible
inputs and outputs to inform the test plan. 
- **Relational database model**: data elements and records arragned in tables which are related or linked to each other to implement business logic, where data records of different structures or types are needed together in the same activity. Records are identified using a variety of keys.
    - **Candidate Keys**: is a subset of attributes that can be used to uniquely identify any record in a table. No two records in the same table will ever contain the same values for all attributes composing a candidate key. Each table may have one or more candidate keys, which are chosen from column headings.
    - **Primary Keys**: is selected from the set of candidate keys for a table to be used to 🧠uniquely identify the records in a table. Each table has only one primary key, selected by the database designer from the set of candidate keys. The RDBMS enforces the uniqueness of primary keys by disallowing the insertion of multiple records with the same primary key.
    - **Alternate Keys**: Any candidate key that is not selected as the primary key is referred to as an alternate key.
    - **Foreign Keys**: is used to enforce relationships between two tables, also known as referential integrity. Referential integrity ensures that if one table contains a foreign key, it corresponds to a still-­existing primary key in the other table in the relationship. It makes certain that no record/tuple/row contains a reference to a primary key of a nonexistent record/tuple/row. Foreign keys are used to enforce 🧠referential integrity constraints between tables that participate in a relationship.
    - **Normalization**: Database developers strive to create well-­organized and efficient databases. To assist with this effort, they’ve defined several levels of database organization known as normal forms. The process of bringing a database table into compliance with normal forms is known as normalization.The three most common are first normal form (1NF), second normal form (2NF), and third normal form (3NF). Each of these forms adds requirements to reduce redundancy in the tables, eliminate misplaced data, and perform a number of other housekeeping tasks. The normal forms are cumulative—­in other words, to be in 2NF, a table must first be 1NF compliant. Before making a table 3NF compliant, it must first be in 2NF.
    - Relational database transactions have four required characteristics: atomicity, consistency, isolation, and durability. Together, these attributes are known as the ACID model, which is a critical concept in the development of database management systems.
        - **Atomicity**: Database transactions must be atomic—­that is, they must be an “all-­or-­nothing” affair. If any part of the transaction fails, the entire transaction must be rolledback as if it never occurred. It states that if any part of the transaction fails, the entire transaction must be rolled back
        - **Consistency**: All transactions must begin operating in an environment that is consistent with all of the database’s rules (for example, all records have a unique primary key). When the transaction is complete, the database must again be consistent with the rules, regardless of whether those rules were violated during the processing of the transaction itself. No other transaction should ever be able to use any inconsistent data that might be generated during the execution of another transaction. The consistency principle says that the database must always be in a state that complies with the database model’s rules.
        - **Isolation**: The isolation principle requires that transactions operate separately from each other. If a database receives two SQL transactions that modify the same data, one transaction must be completed in its entirety before the other transaction is allowed to modify the same data. This prevents one transaction from working with invalid data generated as an intermediate step by another transaction.It states that two transactions operating on the same data must be
temporarily separated from each other so that one does not interfere with the other.
        - **Durability**: Database transactions must be durable. That is, once they are committed to the database, they must be preserved. Databases ensure durability through the use of backup mechanisms, such as transaction logs. The durability principle says that transactions committed to the database must be preserved
          
- **Representational State Transfer (REST)**: software architectural style for synchronizing the activities of two or more apps running on different systems on a network; REST facilitiates these processes exchanging state information, usually via HTTP/S
- **Reputation monitoring**: defensive tactic that uses the trust reputation of a website or IP address as a means of blocking an org's users, processes or systems from connecting to a possible source of malware or exploitations; possibly the only real defense against zero-day exploits; involves monitoring URLs, domains, IP addresses or other similar info to separate untrustworthy traffic
- **Runtime Application Security Protection (RASP)**: security agents comprised of small code units built into an app which can 🧠detect set of security violations; upon detection, the RASP agent can cause the app to terminate, or take other protective actions
- **Security Assessment**: testing, inspection, and analysis to determine the degree to which a system meets or exceeds the required security posture; may assess whether an as-built system meets the requirements in its specs, or whether an in-use system meets the current perception of the real-world security threats
- **Software Quality Assurance**: variety of formal and informal processes that attempt to determine whether a software app or system meets all of its intended functions, doesn't perform unwanted functions, is free from known security vulns, and is free from insertion or other errors in design and function
- **SDLC**: Software Development LifeCycle is a framework and systematic associated with tasks that are performed in a series of steps for building, deploying, and supporting software apps; 🧠begins with planning and requirements gathering, and ends with decommissioning and sunsetting; there are many different SDLCs, such as agile, DevSecOps, rapid prototyping, offering different approaches to defining and managing the software lifecycle
    - All systems development processes should have several activities in common. Although they may not necessarily share the same names, these core activities are essential to the development of sound, secure systems:
        - 🆎Phase 1: Conceptual definition
        - 🆎Phase 2: Functional requirements determination:  conducted by the senior team members with inputs from all the stakeholders and domain experts. Planning for the quality assurance requirements and recognization of the risks involved is also done at this stage.
        - 🆎Phase 3: Control specifications development, feasibility studies
        - 🆎Phase 4: Design review:  emphasizes the importance of ensuring that the appropriate security controls, objectives, and goals are identified and initiated 
        - 🆎Phase 5: Coding
        - 🆎Phase 6: Code review walk-­through
        - 🆎Phase 7: System test review
        - 🆎Phase 8: Maintenance and change management
- **Source code**: program statements in human-readable form using a formal programming language's rules for syntax and semantics
- **Spyware/Adware**: software that performas a variety of monitoring and data gathering functions; AKA potentailly unwanted programs/applications (PUP/PUA), may be used in monitoring employee activities/use of resources (spyware), or advertising efforts (adware); both may be legit/authorized by system owners or unwanted intruders
- **Strong data typing**: feature of a programming language preventing data type mismatch errors; strongly typed languages will generate errors at compile time
- **Input validation** verifies that user-supplied input does not violate security conditions. Effective against buffer overflow, XSS and SQL Injection attacks. Parameter checking, or input validation, is used to ensure that input provided by users to an application matches the expected parameters for the application. Developers may use parameter checking to ensure that input does not exceed the expected length, preventing a buffer overflow attack.
- **Bounds checking** is a form of input validation, but it is typically used to ensure that numeric input falls within an acceptable range
- **Limit Check** which is the verification that input is within a preset range or domain
- **Threat surface**: total set of penetrations of a boundary or perimeter that surrounds or contains system elements
- **TOCTOU attack**: time of check vs time of use (TOCTOU) attack takes advantage of the time delay between a security check (such as authentication or authorization) being performed and actual use of the asset. Time-­of-­check to time-­of-­use (TOCTTOU) attacks exploit timing differences that lead to race conditions. TOC/TOU is a type of timing vulnerability that occurs when a program checks access permissions too far in advance of a resource request.
- **Trapdoor/backdoor**: hidden mechanism that bypasses access control measures; an entry point into an architecture or system that is inserted in software by devs during development to provide a method of gaining access for modification/support; can also be inserted by an attacker, bypassing access control measures designed to prevent unauthorized software changes. Backdoors are code that allows those with knowledge of the backdoor to bypass authentication mechanisms

- 8.1.1 Development methodologies (e.g. Agile, Waterfall, DevOps, DevSecOps)
    - 📁**Agile methodology**: a project management approach to development that involves breaking the project into phases and emphasizes continuous collaboration and improvement; teams follow a cycle of planning, executing, and evaluating
        - Agile development emphasizes:
            - the delivery of working software in short iterations, helping to get the software to market faster 
            - reduced risk by frequently testing and providing feedback, helping to identify and resolve issues earlier in the development process
        - Agile was started by 17 pioneers in 2001, producing the "Manifesto for Agile Software Development" (agilemanifesto.org) that lays out the core philosophy of the Agile approach:
            - **individuals and interactions** over processes and tools
            - **working software** over comprehensive documentation
            - **customer collaboration** over contract negotiation
            - **responding to change** over following a plan
        - Agile Manifesto also defines 12 principles:
            - the highest priority is to satisfy the customer through early and continuous delivery of valuable software
            - 🧠It does not prioritize security over other requirements.
            - welcome changing requirements, even late in development; Agile processes harness change for the customer’s competitive advantage
            - deliver working software frequently, from a couple of weeks to a couple of months, with a preference for the shorter timescale
            - business people and developers must work together daily throughout the project
            - build projects around motivated individuals; give them the environment, support, and tools and trust them to build
            - emphasizing face-to-face conversation
            - working software is the primary measure of progress
            - agile processes promote sustainable development; the them should be able to maintain a constant pace indefinitely
            - continuous attention to technical excellence and good design enhances agility
            - simplicity, or the art of maximizing the amount of work not done,  is essential
            - the best architectures, requirements, and designs emerge from self-organizing teams
            - at regular intervals, the team reviews their effective and adjusts for improvement
        - Several methodologies have emerged that take these Agile principles and define specific processes around them:
            - ❄️**Scrum**: a management framework that teams use to self-organize and work towards a common goal; it describes a set of meetings, tools, and roles for efficient project delivery, allowing teams to self-manage, learn from experience, and adapt to change; named from the daily team meetings, called scrums
                - It is an agile model that help agile teams to work together and deliver complex products
                - primarily used for software dev but has grown to be accepted within other industries
                - provides a set of rules, practices and roles to put the agile prinicples into action
            - ❄️**Kanban**: a 📝visual system used to manage and keep track of work as it moves through a process; the word kanban is Japanese for "card you can see"; Kanban teams focus on reducing the time a project (or user story) takes from start to finish, using a kanban board and continuously improving their flow of work
            - ❄️**Rapid Application Development (RAD)**: an agile software development approach that focuses more on ongoing software projects and 📝user feedback and less on following a strict plan, emphasizing rapid prototyping over planning
            - ❄️**Rational Unified Process (RUP)**: an agile software development methodology that splits the project life cycle into four phases:
                - 🎈Inception: which defines the scope of the project and develop business case
                - 🎈Elaboration: Plan project, specify features, and baseline the architecture 
                - 🎈Construction: Building the product
                - 🎈Transition: providing the product to its users 
                - during each of the phases, all six core development disciplines take place: business modeling, requirements, analysis and design, implementation, testing, and deployment
            - ❄️**Agile Unified Process (AUP)**: a 📝simplified version of the rational unified process, it describes a simple, easy to understand approach to developing business application software using agile techniques and concepts yet still remaining true to the RUP
            - ❄️**Dynamic Systems Development Model (DSDM)**: an agile project delivery framework, initially used as a software development method; key principles:
                - focus on the 📝business need: DSDM teams establish a valid business case and ensure organizational support throughout the project
                - deliver on time: work should be time-boxed and predictable, to build confidence in the development team
            - ❄️**Extreme Programming (XP)**: an Agile project management methodology that targets 📝speed and simplicity with short development cycles, using five guiding values, five rules, and twelve practices for programming; the goal of the rigid structure, focused sprints and continuous integrations is higher quality product
            - ❄️**Scaled Agile Framework® (SAFe)**: a set of org and workflow patterns for implementing agile practices at an enterprise scale; the framework is a body of knowledge that includes structured guidance on roles and responsibilities, how to plan and manage the work, and values to uphold.
               - it includes structured guidance on roles and responsibilities, how to plan and mage the work and which values to uphold.
               - promotes alignment, collaboration and delivery across large numbers of agile teams
               - It builds on several Agile concepts. It does not replace Agile, rather it adds neccessary layers to make Agile work in large enterprise-level context
                   - Cordination Across Teams
                   - Strategic alignment with orgs business objectives
                   - emphasizes quality as a non-negotiable aspect of delivery
                   - architectural guidance for future evolution and scaling
                   - Cadence and synchronization through Programme Increment PI planning and demos (PI is a quarterly excersice where the group plans thier work)
                   - Lean-Agile leadership 
               - it was developed leveraging 3 primary bodies of knowledge
                   - Agile Software Developement
                   - Lean Product Developement
                   - Systems Thinking
    - 📁**Waterfall**: 
        - Developed by Winston Royce in 1970, the waterfall model uses a linear sequential life-cycle approach where each phase must be completed before the next can begin; all project requirements are gathered up front, and there is no formal way to integrate changes as more information becomes available
        - Traditional model has 7 stages, as each stage is completed, the project moves into the next phase; the iterative waterfall model does allow development to return to the previous phase to correct defects 
            - System Requirements
            - Software Requirements
            - Preliminary Design
            - Detailed Design
            - Code and Debug
            - Testing
            - Operations and Maintenance
        - It allows developers to go backacross the 7 stages to make corrections. But you can only return to a previous stage (Only on stage back)
        - A major criticism of this model is that it's very rigid, and not ideal for most complex projects which often contain many variables that affect the scope throughout the project's lifecycle
        - Despite many organizations moving to Agile, DevOps, or other more responsive development methodologies, waterfall remains a strong contender when clear objectives, upfront planning and stable requirements are combined with a need to prevent flaws and to have a high level of control over the development process and output.
        - It is mainly used where time and cost is not important
        - Still used in public utility projects and even building of nuclear reactors
        - In the waterfall model, the software development process follows five sequential steps that are, in order: Requirements, Design, Coding, Testing, and Maintenance.
        - The ✏️Iterative waterfall model uses a seven-­stage approach to software development and includes a feedback loop that allows development to return to the previous phase to correct defects discovered during the subsequent phase.
    - 📁**Spiral model**: improved waterfall dev process providing for a cycle of Plan, Do, Check, Act (PDCA) sub-stages at each phase of the SDLC; a risk-driven development process that follows an iterative model while also including waterfall elements
        - following defined phases to completion and then repeats the process, resembling a spiral
        - It allows for multiple iterations of the waterfall-style process
        - It is known as a "Metamodel" or "Model of Models"
        - the spiral model provides a solution to the major criticism of the waterfall model in that it allows devs to return to planning stages as technical demands and customer requirements iterate
        - In this approach, developers use multiple iterations of a waterfall-style software development process. This becomes a “loop” of iterations through similar processes.
        - Each loop of the spiral results in the development of a new system prototype.
    - 📁**DevOps (Development and Operations)**: an approach to software development, quality assurance, and technology operations that seeks to unite siloed staff, and bring the three functions together in a single operational model
        - closely aligned with lean and the Agile development approach, DevOps aims to dramatically decrease the time required to develop, test, and deploy software changes
        - using the DevOps model, and continuous integration/continuous delivery (CI/CD), orgs strive to roll out code dozens or even hundreds of times per day and the can deploy code extremely rapidly.
        - this requires a high degree of 🧠automation, including integrating code repositories, the software configuration management process, and the movement of code between development, testing and production environments
        - the tight integration of development and operations also calls for the simultaneous integration of security controls
        - security must be tightly integrated and move with the same agility
        - The DevOps approach to technology management seeks to integrate software development, operations, and quality assurance in a seamless approach that builds collaboration between the three disciplines.
        - The three elements of the DevOps model are 🔥software development, 🔥quality assurance, and 🔥IT operations.
    - 📁**DevSecOps**: refers to the integration of development, security, and operations
        - provides for a merger of phased review (as in the waterfall SDLC) with the DevOps method, to incorporate the needs for security, safety, resilience or other emerging properties in the final system, at each turn of the cycle of development
        - DevSecOps supports the concept of software-defined security, where security controls are actively managed into the CI/CD pipeline
        - The four elements of the DevSecOps model are 🔥software development, 🔥quality assurance, 🔥IT operations and 🔥Information security (introduced in the DevSecOps model)

- 8.1.2 Maturity models (e.g., Capability Maturity Model (CMM), Software Assurance Maturity Model (SAMM))
    - Software Engineering Institute (SEI) (Carnegie Mellon University) created the Capability Maturity Model for Software (AKA Software Capability Maturity Model, abbreviated SW-CMM, CMM, or SCMM)
        - **SW-CMM**: a management process to foster the ongoing and continuous improvement of an org's processes and workflows for developing, maintaining and using software
        - all software development moves through a set of maturity phases in sequential fashion, and CMM describes the principles and practices underlying software process maturity, intended to help improve the maturity and quality of software processes
        - note that CMM doesn't explicitly address security
        - stages of the CMM:
            - Level 1: Initial: process is disorganized; usually little or no defined software development process
            - Level 2: Repeatable: in this phase, basic lifecycle management processes are introduced
            - Level 3: Defined: in this phase, software devs operate according to a set of formal, documented software development processes
            - Level 4: Managed: in this phase, there is better management of the software process. The organization uses quantitative measures to gain a detailed understanding of the development process.
            - Level 5: Optimizing: in this phase continuous improvement occurs
    - **Software Assurance Maturity Model (SAMM)**: an open source project maintained by the Open Web Application Security Project (OWASP)
        - provides a framework for integrating security into the software development and maintenance processes and provides orgs with the ability to assess their maturity
        - SAMM associates software development with 5 business functions:
            - 📝Governance: the activities needed to manage software development processes
                - this function includes practices for:
                    - strategy
                    - metrics
                    - policy
                    - compliance
                    - education
                    - guidance
            - 📝Design: process used to define software requirements and develop software
                - this function includes practices for:
                    - threat modeling: designed to reduce the number of security-related design and coding flaws as well as the severity of other flaws. **Threat modeling** is a process by which potential security threats and vulnerabilities can
be identified, and mitigations can be prioritized. Threat modeling can be used to help securely ✏️develop applications or to help reduce risk in an already ✏️deployed application. There are numerous approaches to threat modeling, but three of the most commonly
used are called STRIDE, DREAD, and PASTA.
                    - threat assessment using threatmodelling techniques
                    - security requirements
                    - security architecture
            - 📝Implementation: process of building and deploying software components and managing flaws
                - this function includes:
                    - secure build
                    - secure deployment
                    - defect management practices
            - 📝Verification: activities undertaken to confirm code meets business and security requirements
                - this function includes:
                    - architecture assessment
                    - requirements-driven testing
                    - security testing
            - 📝Operations: actions taken to maintain security throughout the software lifecycle after code is released
                - function includes:
                    - incident management
                    - environment management
                    - operational management
    - **IDEAL Model**: developed by SEI, a model for software development that uses many of the SW-CMM attributes, using 5 phases:
        - Initiating: business reasons for the change are outlined, support is built, and applicable infrastructure is allocated
        - Diagnosing: in this phase, engineers analyze the current state of the organization and make general recommendations for change
        - Establishing: development of a specific plan of action based on the diagnosing phase recommendations
        - Acting: in this phase, the org develops solutions and then tests, refines, and implements them
        - Learning: continuously analyze efforts to achieve these goals, and propose new actions as required

    - IDEAL vs SW-CMM: I...I, Dr. Ed, am lo

        | IDEAL | SW-CMM | 
        |----------------|---------------|
        | Initiating|Initial|
        | Diagnosing  | Repeatable|
        | Establishing | Defined| 
        | Acting  | Managed| 
        | Learning| Optimizing|
    

- **A Gantt chart** is a type of bar chart that shows the interrelationships over time between projects and schedules. It provides a graphical illustration of a schedule that helps you plan, coordinate, and track specific tasks in a project. They are particularly useful when coordinating tasks that require the use of the same team members or other resources.
- **Program Evaluation Review Technique (PERT)** is a project-­scheduling tool used to judge the size of a software product in development and calculate the standard deviation (SD) for risk assessment. PERT relates the estimated lowest possible size, the most likely size, and the highest possible size of each component. The PERT chart  shows the dependencies between different project tasks.
    - PERT charts use nodes to represent milestones or deliverables and then show the estimated time to move between milestones 
- **Rapid Application Development, or RAD**, focuses on fast development and the ability to quickly adjust to changing requirements. RAD uses four phases: requirements planning, user design, construction, and cutover.

- 8.1.3 Operations and maintenance
    - Once delivered to the production environment, software devs must make any additional changes to accomodate unexpected bugs, vulnerabilities, or interoperability issues
    - They must also keep pace with changing business processes, and work closely with the operations team (typically IT), to ensure reliable operations
        - together, ops and development transition a new system to production and management of the system's config
    - The dev team must continually provide hotfixes, patches, and new releases to address discovered security issues and identified coding errors
- 8.1.4 🔴Change management
    - Change management (AKA control management) plays an important role when monitoring systems in a controlled environment, and has 3 basic components:
        - 💢**Request Control**: process that provides an organized framework within which users can request modifications, managers can conduct cost/benefit analysis, and developers can prioritize tasks
            - Change Request: The request process begins with a user-initiated request for a feature. Change and release control are initiated by developers seeking to implement changes. Design review is a phase of the change approval process initiated by developers when they have a completed design.
            - Request control provides users with a framework to request changes and developers with the opportunity to prioritize those requests
            - Request control provides an organized framework for users to request modifications.
        - 💢**Change Control**: the process of controlling specific changes that need to take place during the life cycle of a system, serving to document the necessary change-related activities 
            - where change management is the project manager’s responsibility for the overarching process, change control is what devs do to ensure the software or environment doesn’t break when changed
            - change control is basically the process used by devs to re-create a situation encountered by a user and analyze the appropriate changes; it provides a framework where multiple devs can create and test a solution prior to rolling it out into a prod environment
            - The change control process is responsible for providing an organized framework within which multiple developers can create and test a solution prior to rolling it out in a production environment.
        - 💢**Release Control**: once changes are finalized, they must be approved for release through the release control procedure. Release control manages the deployment of code into production. One of the responsibilities of the release control process is ensuring that the process includes 📝acceptance testing that confirms that any alterations to end-user work tasks are understood and functional prior to code release. 
- 8.1.5 Integrated Product Team (IPT)
    - **Integrated Product Team (IPT)**:Introduced by the DoD as an approach to bring together multifunctional teams with a single goal of delivering a product or developing a process or policy, and fostering parallel, rather than sequential, decisions
    - Essentially, IPT is used to ensure that all aspects of a product, process, or policy are considered during the development process

[8.2](#8.2) Identify and apply security controls in software development ecosystems (OSG-9 Chpts 15,17,20,21)
- Applications, including custom systems, can present significant risks and vulnerabilities, and to protect against these it's important to introduce security controls into the entire system’s development lifecycle
- 8.2.1 Programming languages
    - Computers understand 1s and 0s (binary), and each CPU has its own (machine) language
    - **Assembly language**: a way of using mnemonics to represent the basic instruction set of a CPU
    - **Assemblers**: tools that convert assembly language source code into machine code 
    - Third-generation programming languages, such as C/C++, Java, and Python, are known as high-level languages
        - high-level languages allow developers to write instructions that better approximate human communication
    - **Compiled language**: converts source code into machine-executable format
        - compiled code is generally less prone to manipulation by a third party, however easier to embed backdoors or other security flaws without detection
    - **Decompilers**: convert binary executable back into source code
    - **Disassemblers**: convert back into machine-readable assembly language (an intermediate step during the compilation process)
    - **Interpreted language**: uses an interpreter to execute;sourcecode is viewable; e.g. Python, R, JavaScript, VBScript. 📝JavaScript remains the one mobile code technology that may affect the security of modern browsers and their host OSs. 
    - **Object-oriented programming (OOP)**: defines an object to be set of a software that offers one or more methods, internal to the object, that software external to that object can request to access; each method may require specific inputs and resources and may produce a specified set of outputs; focuses on the objects involved in an interaction
        - OOP languages include C++, Java, and .NET
        - think of OOP as a group of objects that can be requested to perform certain operations or exhibit certain behaviors, working together to provide a system’s functionality or capabilities
        - OOP has the potential to be more reliable and to reduce the propagation of program change errors, and is better suited to modeling or mimicking the real world
        - each object in the OOP model has methods that correspond to specific actions that can be taken on the object
        - objects can also be subclasses of other objects and inherit methods from their parent class; the subclasses can use all the methods of the parent class and have additional class-specific methods
        - from a security standpoint, object-oriented programming provides a black-box approach to abstraction
        - OOP terms:
            - **message**: a communication to or input of an object
            - **method**: internal code that defines the actions of an object
            - **behavior**: results or output exhibited by an object
                - behaviors are the results of a message being processed through a method
            - **class**: a collection of the common methods, from a set of objects that defines the behavior of those objects
            - **instance**: objects are instances of or examples of classes that contain their methods
            - **inheritance**: occurs when the methods from a class (parent or superclass) are inherited by another subclass (child) or object
            - **delegation**: the forwarding of a request by an object to another object or delegate
            - **polymorphism**: the characteristic of an object that allows it to respond with different behaviors to the same message or method because of changes in external conditions
            - **cohesion**: describes the strength of the relationship between the purposes of the methods within the same class
                - if all methods have similar purposes, there is high cohesion, and a sign of good design
            - **coupling**: the level of interaction between objects
                - lower coupling: means less interaction
                - lower coupling provides better software design because objects are more independent, and code is easier to troubleshoot and update
    
- 8.2.2 Libraries
    - **Software library (Code Libraries)**: a pre-written collection of components (classes, procedures, scripts etc) that do specific tasks, useful to other components (e.g. software libraries for encryption algorithms, managing network connections, or displaying graphics)
    - Shared software libraries contain reusable code, improving developer's efficiency, and reducing the need to write well-known algorithms from scratch; often available as open source
        - shared libraries can also include many security issues (e.g. Heartbleed), and devs should be aware of the origins of the shared code that they use, and keep informed about any security vulns that might be discovered in these libraries
        - Code repositories may be used to manage the distribution and updating of these libraries.
        - **Software Development Kits SDK**: Organizations trying to make libraries more accessible to developers often publish SDKs. SDKs are collections of software libraries combined with documentation, examples, and other resources designed to help programmers get up and running quickly in a development environment. SDKs also often include specialized utilities designed to help developers design and test code.
    
- 8.2.3 Tool sets
    - Forcing all devs to use the same toolset can reduce productivity and job satisfaction; however letting every dev choose their own tools and environment widens an organization's attack surface
        - a better approach is to use a change advisory board to validate developer tool requirements, assess associated risks; if approved, the sec team monitors controls
    - Developers use a variety of tools, and one of the most important is the IDE (defined below)

- 8.2.4 Integrated Development Environment (IDE)
    - **Integrated Development Environment (IDE)**: software applications, their control procedures, supporting databases, libraries and toolsets that provide a programmer or team what they need to specify, code, compile, test, and integrate code; IDEs provide developers with a single environment where they can write their code, test and debug, and compile it
- 8.2.5 Runtime
    - **RunTime Environments (RTE)**: allows the portable execution of code across different operating systems or platforms without recompiling (e.g. Java Virtual Manager (JVM))
        - this is known as portable code, which needs translation between each environment, the role of the RTE
- 8.2.6 Continuous Integration and Continuous Delivery (CI/CD)
    - **Continuous Integration and Continuous Delivery**: workflow automation processes and tools that attempt to reduce, if not eliminate, the need for manual communication and coordination between the steps of a software development process
    - **Continuous integration (CI)**: all new code is integrated into the rest of the system as soon as the developer writes it, merging it into a shared repo
        - this merge triggers a batch of unit tests
        - if it merges without error, it's subjected to integration tests
        - CI improves software development efficiency by identifying errors early and often
        - CI also allows the practice of continuous delivery (CD)
    - **Continuous Delivery (CD)**: incrementally building a software product that can be released at any time; because all processes and tests are automated, code can be released to production daily or more often
    - CI/CD relies on automation and often third-party tools which can have vulnerabilities or be compromised
    - Secure practices such as threat modeling, least privilege, defense in depth, and zero trust can help reduce possible threats to these tools and systems

- 8.2.8 Software Configuration Management (SCM)
    - **Software Configuration Management (SCM)**: a product that identifies the attributes of software at various points in time and performs methodical change control for the purpose of maintaining software integrity and traceability throughout the SDLC
        - SCM tracks config changes, and verifies that the delivered software includes all approved changes
        - SCM systems manage and track revisions made by multiple people against a single master software repository, providing concurrency management, versioning, and synchronization
 
- 8.2.9 Code repositories
    - Software development is a collaborative effort, and larger projects require teams of devs working simultaneously on different parts
    - Code repositories support collaborations, acting as a central storage point for source code
        - github, bitbucket, and sourceforge are examples of systems that provide version control, bug tracking, web hosting, release management, and communications functionality
    
- 8.2.10 Application security testing (e.g., Static Application Security Testing (SAST), Dynamic Application Security Testing (DAST))
    - **Static Application Security Testing (SAST)**: (Inside Out) AKA static analysis, tools and technique to help identify software defects (e.g. data type errors, loop/structure bounds violations, unreachable code) or security policy violations and is carried out by examining the code without executing the program (or before the program is compiled)
        - the term SAST is generally reserved for automated tools that assist analysts and developers, whereas manual inspection by humans is generally referred to as code review
        - Tester has access to the underlying framwork, design, source code and implementation
        - SAST allows devs to scan source code for flaws and vulns; it also provides a scalable method of security code review and ensuring that devs are following secure coding policies
        - Static testing performs code analysis in an offline fashion, without actually executing the code.
    - **Dynamic Application Security Testing (DAST)**: (Outside In)  AKA dynamic analysis, is the evaluation of a program while running in real time
        - tools that execute the software unit, application or system under test, in ways that attempt to drive it to reveal a potentially exploitable vulnerability
        - Dynamic testing evaluates code in a runtime environment.
        - Tester has NO knowledge of the underlying framework, design, source code and implementation
        - It is by definition a form of black-box testing
        - DAST is usually performed once a program has cleared SAST and basic code flaws have been fixed 
        - DAST enables devs to trace subtle logical errors that are likely to cause security problems, without the need to create artificial error-inducing scenarios
        - dynamic analysis is also effective for compatibility testing, detecting memory leakages, identifying dependencies, and analyzing software without accessing the software’s actual source code. Examples of DAST include Fuzzing and Web application vulnerability scanning
     
- **Interactive Application Security Testing (IAST)**: testing that combines or integrates SAST and DAST to improve testing and provide behavioral analysis capabilities to pinpoint the source of vulnerabilities
     - It analyses codes for vulnerabilities while it is being used
     - it focuses on real-time reporting to optimize testing and analysis process
     - unlike SAST & DAST, IAST analyses internal functions of the application while it is running
     - it is often built into CI\CD automated release testing
- **Software Composition Analysis (SCA)**: It is used to track the components of a software package or application
     - It is of particular concern for apps built with open-source software components becuase open-source software components often involve re-usable code libraries.
     - SCA tools identify flaws/vulnerabilities in these open-source components to ensure the latest versions are in use
     - It is often automated and combines application security and patch management
  - **Code Review**: A process where one or more developers examine another developer's code to identify any errors, security vulnerabilities, or areas for improvement.
      - Pass-around reviews are often done via email or using a central code review system, allowing developers to review code asynchronously.
      - Pair programming requires two programmers to work together, with one writing code and the other reviewing and tracking progress.
      - Team reviews are typically done in a group
      - Fagan inspection is a formal review process that would involve both the developer and a team to review the code using a formal process. 
  - **White-Box Testing**: A software testing approach where the tester has complete knowledge of the internal structure, code, and logic of the application being tested. White-box tests also have access to the source code but perform testing from a developer’s perspective.
  - **Black-box testing** begins with no prior knowledge of the system implementation, simulating a user perspective. They do not have access to source code.
  - **Gray-box testing** provide partial knowledge of the system, respectively, in advance of the test. In a gray-box test, the tester evaluates the software from a user perspective but has access to the source code as the test is conducted.
  - **Unit testing** focuses on the smallest parts of an application, like functions, methods, or classes, ensuring they operate correctly in isolation. Unit tests are often automated, allowing developers to run them frequently to catch issues early in the development process, ensuring each component works correctly. Unit testing focuses on testing each module of a program instead of against its previous functional state. 
  - **Integration testing**: A testing method used to validate how software modules work together
  - **System testing**: Testing on a complete integrated product
  - **User Acceptance Testing**: (UAT) is typically the last phase of the testing process. It verifies that the solution developed meets user requirements and validates it against use cases.
  - Static testing, white-box testing, and code review approaches all require access to the source code of the application but dynamic testing does not.
  - Both static and dynamic testing may use automated tools
  - **Positive Testing**: also known as "happy path" testing, involves providing valid and expected inputs to the software to ensure that it behaves as intended. The focus is on verifying that the application performs its expected functions correctly when given correct and anticipated data.
  - **Negetive Testing**: Negative testing involves providing invalid, unexpected, or erroneous inputs to the software to ensure that it handles these situations gracefully. The aim is to verify that the application can handle incorrect data or operations without crashing, producing incorrect results, or compromising security.
  - **Complete coverage**: It is a process to ensure that all of the functions of their software are testedCoverage analysis is performed to ensure that functionality, requirements, or other elements are completely tested.

[8.3](#8.3) Assess the effectiveness of software security (OSG-9 Chpts 20,21)
- 8.3.1 Auditing and logging of changes
    - Applications should be configured to log details of errors and other security events to a centralized log repository
    - The Open Web Application Security Project (OWASP) Secure Coding Practices suggest logging the following events:
        - input validation failures
        - authentication attempts, especially failures
        - access control failures
        - tampering attempts
        - use of invalid or expired session tokens
        - exceptions raised by the OS or applications
        - use of admin privileges
        - Transport Layer Security (TLS) failures
        - cryptographic errors
    - ✏️Code Signing: Code signing provides developers/entity/organisation with a way to confirm the authenticity of their code to end users. Developers use a cryptographic function to digitally sign their code with their own private key, and then browsers can use the developer’s public key to verify that signature and ensure that the code is legitimate and was not modified by unauthorized individuals.
- 8.3.2 Risk analysis and mitigation
    - Risk management is at the center of secure software development, in particular regarding the mapping of identified risks and implemented controls
        - this is a difficult part of secure software dev, especially related to auditing
    - Threat modeling is important to dev teams, and particularly in DevSecOps
    - Assessors are also interested in the linkages between the software dev and risk management programs
        - software projects should be tracked in the org’s risk matrix, to ensure the dev team is connected to the broader risk management efforts, and not working in isolation

[8.4](#8.4) Assess security impact of acquired software (OSG-9 Chpts 16,20)
- 8.4.1 Commercial-off-the-shelf (COTS)
    - **Commercial Off-the-Shelf (COTS)**: software elements, usually apps, that are provided as finished products (not intended for alteration by or for the end-user)
    - When using commercial off-the-shelf (COTS) software, customers do not generally have access to the source code and must depend upon the vendor to release security patches that correct vulnerabilities.
    - Most widely used commercial-off-the-shelf (COTS) software products have been security researcher (both benign and malicious) tested 
        - researching discovered vulnerabilities and exploits can help us understand how seriously the vendor takes security
        - for niche products, you should research vendor certifications, such as ISO/IEC 27034 Application Security
        - other than secure coding certification, you can look for overall information security management system (ISMS) certifications such as ISO/IEC 27001 and FedRAMP (which are difficult to obtain, and show that the vendor is serious about security)
    - If you can talk with a vendor, look for processes like defensive programming, which is a software development best practice that means as code is developed or reviewed, they are constantly looking for opportunities for things to go badly
        - e.g. treating all input routines as untrusted until proven otherwise
 
- 8.4.2 Open source
    - Open source is typically released with licensing allowing code access and inspection so devs can look for security issues
        - typically, however, this means that there is no sevice or support that comes with the software and requires in-house support for configuration, and security testing
        - An example is the OpenSSL package is a widely used implementation of TLS encryption that is available as an open source package. 
        - it also means that both open-source devs as well as adversaries are able to review the code for vulns 
        - the greatest risk of open-source software is relying on outdated versions -- especially true of shared libraries 
        - an org should develop processes to ensure that all open-source software is periodically updated, likely in a way that differs from the process for updating COTS
        - By monitoring assets containing open source libraries for vulnerabilities, organizations can stay informed about any newly discovered vulnerabilities or weaknesses in these libraries. This allows them to take proactive measures, such as applying patches or updates, implementing workarounds, or finding alternative solutions, to mitigate the risk of zero-day attacks.

- 8.4.3 Third-party
    - **Third-party software**: (AKA outsourced software) is software made specifically for an org by a third party
        - third-party software is not considered COTS, since the software is custom or customized
        - third-party software may rely on open-source software, but since it's customized, it may have different or additional vulns
        - it's best practice to use a third-party to do an external audit and security assessment; this should be built into the vendor's contract, with passing the audit conditional for finalizing software purchase
- 8.4.4 Managed services (e.g. Software as a Service (SaaS), Infrastructure as a Service (IaaS), Platform as a Service (PaaS))
    - As orgs continue to migrate to the cloud (SaaS, IaaS, PaaS), they should increase the security assessment of those services
    - The top reasons for cloud breaches continues to be misconfigurations, lack of visibility into access settings, and poor access controls
        - cloud service providers have tools to help mitigate these issues, and orgs should consider bringing in third-party experts to help if they don't have the internal expertise

- 8.4.5 **Cloud Service Models**
    - 🔴**Infrastructure as a Service (IaaS)**: Provides virtualized computing resources over the internet. Examples: AWS EC2, Microsoft Azure Virtual Machines, Google Compute Engine.
        - 🔔Cloud Service Provider (CSP): Manages data centers, servers, networking/firewall equipment, and storage. Provides hypervisor or virtualization layer. Secures the infrastructure that runs all services offered by the provider. Ensures availability, scalability, and performance of infrastructure components. Since the vendor is responsible for managing the storage hardware, the vendor would retain responsibility for destroying or wiping drives as they are taken out of service.
        - 🔔Customer: Configures and secures the operating system running on virtual machines. Installs, configures, and secures applications and middleware. Manages and secures data stored and processed within the virtual machines. Configures local firewall rules, network access controls, and VPN connections. IaaS service model provides an organization with the most control compared to the other models, and this model requires the organization to perform all maintenance on operating systems and applications. In an infrastructure as a service environment, security duties follow a shared responsibility model. However, it is still the customer's responsibility to validate that the vendor's sanitization procedures meet their requirements prior to utilizing the vendor's storage services.
    
    - 🔴**Platform as a Service (PaaS)**: Provides a platform allowing customers to develop, run, and manage applications without managing underlying infrastructure. Examples: AWS Elastic Beanstalk, Microsoft Azure App Service, Google App Engine.
        - 🔔Cloud Service Provider (CSP): Provides and manages the development platform (e.g., runtime environment, databases, web servers), middleware services required for application development and deployment, Manages platform-level security patches and updates, Ensures scalability and availability of the platform.
        - 🔔Customer: Application Development: Develops, tests, and deploys applications on the provided platform. Manages and secures application data stored within the platform. Configures user access controls and identity management within the platform. Integration: Integrates applications with other services and components. The PaaS model splits control and maintenance responsibilities between the CSP and the organization.

    - 🔴**Software as a Service (SaaS)**: Delivers software applications over the internet on a subscription basis. Examples: Google Workspace (formerly G Suite), Microsoft Office 365, Salesforce.
        - 🔔Cloud Service Provider (CSP): Provides access to the software application over the internet. Manages all underlying infrastructure and resources required to deliver the application. Manages updates, patches, and maintenance of the application. Ensures security and privacy of customer data stored within the application.
        - 🔔Customer: Configures application settings and user preferences within the provided interface. Manages user data and ensures compliance with data protection regulations. Manages user access controls and permissions within the application. Integrates the SaaS application with other enterprise systems if necessary. The SaaS model gives the organization the least control, and the cloud service provider (CSP) is responsible for all maintenance.
    
    - 🔴**Function as a Service (FaaS)**: Serverless computing model where developers execute functions in response to events. Examples: AWS Lambda, Azure Functions, Google Cloud Functions.
        - 🔔Cloud Service Provider (CSP): Executes functions in response to events or triggers. Ensures scalability and availability of the serverless execution environment. Manages performance metrics and response times for function executions. Implements security controls around function execution and data handling.
        - 🔔Customer: Develops and uploads function code to the serverless platform. Configures event sources and triggers that invoke the functions. Manages data inputs and outputs from function executions. Monitors function performance and troubleshoots any issues.
    
    - 🔴**Identity as a Service (IDaaS)**: Provides identity and access management capabilities as a cloud service. Examples: Okta, Microsoft Azure Active Directory, Ping Identity.
        - 🔔Cloud Service Provider (CSP): Provides centralized identity management services such as user authentication, authorization, and access control. Offers SSO capabilities to enable users to access multiple applications and services with a single set of credentials. Manages the lifecycle of user accounts, including creating, modifying, and disabling accounts based on organizational policies. Provides options for MFA to enhance security by requiring additional verification factors beyond passwords.
        - Supports federation protocols (e.g., SAML, OAuth, OpenID Connect) to establish trust relationships between different identity domains. Implements policies and controls for managing identities and ensuring compliance with regulatory requirements. Monitors identity-related events and provides audit logs for visibility and compliance purposes. Adheres to relevant regulations and standards regarding identity management and data protection.
        - 🔔Customer: Defines and manages user accounts, roles, and permissions within the IDaaS platform. Integrates IDaaS with existing on-premises or cloud applications and services requiring authentication and access control. Configures and enforces identity and access management (IAM) policies based on organizational requirements and security best practices. Utilizes the IDaaS platform to authenticate users and enforce security measures such as password policies and MFA. Defines access policies and permissions for applications and resources accessed through the IDaaS platform. Monitors user activity and security events related to identity and access management, and responds to incidents as necessary. Provides training and awareness programs to users regarding identity security practices and the use of IDaaS services effectively.Ensures that the use of IDaaS complies with internal policies, industry regulations, and legal requirements related to identity management.
    - **Considerations around Cloud Services when access the Impact of acquired Software**: A clear understanding of contractual responsibilities of your CSP is important for security, availability and compliance
        - Data Security and Privacy: Evaluating the CSPs data security measures, encryption processes, access controls is crucial to confidentiality and integrity of the organizations data
            - Data residency and privacy (GDPR, PCI, PHI etc) may vary based on the cloud provider you choose 
        - Shared Responsibility Model: know the model and have clear definition of the responsibilities of each party is essential to avoid security gaps or overlap.
            - know your responsibilites with any CSP hosting your app or data 
        - CSP Security Practices: Assessing the CSPs security policies, incident response procedures and thier track record in addressing security incidents
        - Multi-Tenenacy & Isolation: Evaluate the CSPs tenant isolation mechanism to prevent unauthorised access or data leakage between tenants. Logical and physical isolation options are fairly consistent across the big 3 CSPs.
        - Identity & Access Managment: Assessing the CSPs IAM capabilities, including auth mechanisms (MFA), and role based access controls to ensure granular, and just-in-time controls
            - Also verify support for App's preferred identity providers 
        - Monitoring, Logging & Auditing: Evaluate the CSPs logging and monitoring capabilities, log retention policies, and the organisations ability to access and analyse relevant logs. Cloud services hosting your app should have a consumable audit trail.
        - Incident Response & Notification: Have a clear understanding of your CSPs incident response procedures and notification protocols, in the event of a security incident or data breach
            - contractual details matter becuase you cannot transfer accountabilit
            - if your CSP is breach and your customer data is compromised, your organisation's responsibility to the customer is the same 
        - Compliance and Regulatory: Depending on the org's industry and type of data involved, there may be specific compliance and/or regulatory requirements that a CSP must adhere to. Assessing the CSPs compliance to these requirements and thier ability to provide relevant certifications is essential
        - Data Portability and Exit Strategy: Organisations need to have a clear understanding  of their abiltiy to migrate or exit the cloud service if neccessary
            - Evaluate the CSPs data portability capabilties, export formats, and the organisations ability to retrieve its data in the event of service termination
            - this is crucial in maintaining business continuity and avoiding vendor lock-in
        - Supply Chain Security: Cloud services often involve complex supply chains, with multiple 3rd party components and services integrated into the overall solution.
            - Evaluate the CSPs supply chain risk managment processes is important to mitigate potential vulnerabilities or threats introduced through thier supply chain      

[8.5](#8.5) Define and apply secure coding guidelines and standards (OSG-9 Chpts 20,21)
- **Secure Coding Guidelines and Standards**: best practices identified by a variety of software and security professionals, that when used correctly can dramatically reduce the number of exploitable vulnerabilities introduced during development that remain in the operationally-deployed system
- 8.5.1 Security weaknesses and vulnerabilities at the source-code level
    - A source code vulnerability is a code defect providing a threat actor with an opportunity to compromise the security of a software system
        - source code vulns are caused by design or implementation flaws
        - **design flaw**: if dev did everything correctly, there would still be a vulnerability
        - **implementation flaw**: dev incorrectly implemented part of a good design
    - The Open Web Application Security Project (OWASP) is widely considered as the most authoritative source on web application security issues.
    - The Open Web Application Security Project (OWASP) produces an annual list of the top ten web application security issues that developers and security professionals around the world rely upon for education and training purposes. The OWASP vulnerabilities form the basis for many web application security testing products.
    - The OWASP top 10 vulnerabilities for 2021:
        - Broken access control
        - Cryptographic failures
        - Injection
        - Insecure design
        - Security misconfiguration
        - Vulnerable and outdated components
        - Identification and authentication failures
        - Software and data integrity failures
        - Security logging and monitoring failures
        - Server Side Request Forgery (SSRF)

- 8.5.2 Security of Application Programming Interfaces (APIs)
     - 🔴**Application Programming Interface (API)**: specifies the manner in which a software component interacts with other components
        - API's reduce the effort of providing secure component interactions by providing easy implementation for security controls 
        - API's reduce code maintenance by encouraging software resue, and keeping the location of changes in one place
        - **Securing APIs**
            - 1. Authentication: Use OAuth2 or OpenID Connect: Implement strong, token-based authentication mechanisms and Multi-Factor Authentication (MFA) for sensitive API endpoints.
              2. Authorization: use RBAC and Limit API access to only what the client application needs.
              3. Input Validation (Parameter validation): ensuring that any API parameter is checked against being malformed, invalid, or malicious helps ensure API secure use; validation confirms that the parameter values being received by an app are within defined limits before they are processed by the system
              4. Output Encoding: Sanitize Outputs/Encode outputs to prevent the injection of malicious scripts (e.g., XSS attacks).
              5. Secure API Endpoints: Avoid Exposing Unnecessary Endpoints. Ensure that GET requests are safe and do not modify state, and use POST, PUT, DELETE, etc., appropriately.
              6. Rate Limiting and Throttling: Prevent Abuse by Implement rate limiting to prevent excessive requests from overloading the API.
              7. Error Handling: Avoid revealing details about the internal structure of the API in error messages. Use consistent error codes that provide enough information without exposing sensitive details.
              8. Secure Session Management: Use Secure Cookies for APIs that rely on session-based authentication, ensure that cookies are secure, HttpOnly, and have appropriate expiration. Implement session timeouts to reduce the risk of session hijacking.
              9. Logging and Monitoring: Ensure that all security-relevant events, such as authentication failures and unauthorized access attempts, are logged. Continuously monitor logs for signs of malicious activity.
              10. Secure Data Handling: Limit the amount of data exposed by the API, especially sensitive information. Mask Sensitive Data: Ensure that sensitive information, such as credit card numbers, is masked or encrypted in API responses.
              11. Secure API Documentation: Ensure that API documentation is only accessible to authorized users and does not expose sensitive information.
              12. Security Headers: CORS (Cross-Origin Resource Sharing): Implement secure CORS policies to control which domains can interact with your API. Apply Content Security Policy (CSP) headers to protect against cross-site scripting (XSS).
              13. Code Security Practices: Regularly review API code for security vulnerabilities using Static and Dynamic Analysis Tools
              14. API Hardening: Disable Unused Features: Turn off any API features or endpoints that are not actively used. Avoid providing unnecessary details in API responses that could aid an attacker.
        - 🔨**Closed system** is designed to work well with a narrow range of other systems, generally all from the same manufacturer. The standards for closed systems are often proprietary and not normally disclosed. A closed system is one that uses largely proprietary or unpublished protocols and standards.
        - 🔨**Open systems** are designed using agreed-upon industry standards. Open systems are much easier to integrate with systems from different manufacturers that support the same standards or that use compatible application programming interfaces (APIs).
        
- 8.5.3 Security coding practices
    - Secure coding practices can be summarized as standards and guidelines
        - **standards**: mandatory activities, actions, or rules
        - **guidelines**: recommended actions or ops guidelines that provide flexibility for unforeseen circumstances
        - orgs greatly reduce source code vulns by enforcing secure coding standards and maintaining coding guidelines that reflect best practices
    - To be considered a standard, coding practice must meet the following:
        - reducees the risk of a particular type of vuln 
        - enforceable across all of an org's software development efforts
        - verifiably implemented
    - Note: secure coding standards, rigorously applied, is the best way to reduce source code vulns; coding standards ensures devs always do certain things in a certain way, while avoiding others
    - Secure coding guidelines are recommended practices that tend to be less specific than standards
            - e.g. consistently formatted code comments, or keeping code funtions short/tight

- 8.5.4 Software-defined security
    - A **security model** provides a framework to implement a security policy.A security model provides a way for designers to map abstract statements into a solution that prescribes the algorithms and data structures necessary to build hardware and software. Thus, a security model gives software designers something against which to measure their design and implementation. 
    - **Software-defined security (SDS or SDSec)**: a security model in which security functions such as firewalling, IDS/IPS, and network segmentation are implemented in software within an SDN environment 
        - one of the advantages of this approach is that sensors (for systems like IDS/IPS) can be dynamically repositioned depending on the threat
        - SDS provides a decoupling from physical devices, because it abstracts security functions into software that can run on any compatible physical or virtual infrastructure, critical for supporting cloud services dynamic scaling and virtualized data centers
    - DevSecOps supports the concept of software-defined security, where security controls are actively managed into the CI/CD pipeline
    - security infrastructure may be easily manipulated by code. It is an example of  infrastructure as code (IaC) implementation.
        
- **Fail-Safe**: Ensures the system defaults to a safe state in the event of a failure.e.g An automatic door locks when the power goes out, preventing unauthorized access. 
- **Fail-Secure** (Synonym of Fail Closed): Maintains a secure state during a failure, prioritizing security over other concerns. e.g  Blue screen of death to ensure that security is not compromised during a failure.
- **Fail-Closed**: Closes or shuts down access when a failure occurs, restricting entry or use. e.g a network firewall that blocks all traffic if it encounters a malfunction. Sacrifices availability for security.
Fail-Open: Opens up or grants access during a failure, allowing processes to continue to maintain  availability, potentially at the cost of security.
- **Fail-Soft**: Allows a system to continue operating in a reduced or limited capacity after a failure. e.g A computer that turns off non-critical services to keep essential services running after a hardware failure.

- **Database Security**
    - Concurrency, or edit control: is a preventive security mechanism that ensures that the information stored in the database is always correct or at least has its integrity and availability protected. This feature can be employed on a single-­level or multilevel database. Databases that fail to implement concurrency correctly may suffer from the following issues:
        - **Lost Updates** Occur when two different processes make updates to a database, unaware of each other’s activity.
        - **Dirty Reads** Occur when a process reads a record from a transaction that did not successfully commit. 
    - Aggregation: SQL provides a number of functions that combine records from one or more tables to produce potentially useful information. This process is called aggregation. Aggregation attacks are used to collect numerous low-­ level security items or low-­value items and combine them to create something of a higher security level or value.
    - Inference: Inference attacks involve combining several pieces of nonsensitive information to gain access to information that should be classified at a higher level. However, inference makes use of the human mind’s deductive capacity rather than the raw mathematical ability of modern database platforms.
    - Cell suppression: is the concept of hiding individual database fields or cells or imposing more security restrictions on them.
    - Semantic integrity: ensures that user actions don’t violate any structural rules. It also checks that all stored data types are within valid domain ranges, ensures that only logical values exist, and confirms that the system complies with any and all uniqueness constraints.
    - Polyinstantiation: in the context of databases, occurs when two or more rows in the same relational database table appear to have identical primary key elements but contain different data for use at differing classification levels. Polyinstantiation is often used as a defense against some types of inference attacks, but it introduces additional storage costs to store copies of data designed for different clearance levels. It allows the storage of multiple different pieces of information in a database at different classification levels to prevent attackers from inferring anything about the absence of information.
    - Open Database Connectivity (ODBC): is a database feature that allows applications to communicate with different types of databases without having to be directly programmed for interaction with each type. It acts as a proxy between applications and the back-­end DBMS.
    - NoSQL databases are a class of databases that use models other than the relational model to store data. There are 3 types:
        - Key/value stores are perhaps the simplest possible form of database. They store information in key/value pairs, where the key is essentially an index used to uniquely identify a record, which consists of a data value.
        - Graph databases store data in graph format, using nodes to represent objects and edges to represent relationships.
        - Document stores are similar to key/value stores in that they store information using keys, but the type of information they store is typically more complex than that in a key/value store and is in the form of a document. Common document types used in document stores include XML and JSON
- **Cardinality & Degree** :The cardinality of a table refers to the number of ✏️rows in the table, whereas the degree of a table is the number of ✏️columns. In this case, a table has three columns (name, telephone number, and customer ID), so it has a degree of three.        - 

- 🔴**Common Web Application Vulnerabilities**
    - 🔥Cross-Site Scripting (XSS): XSS attacks involve injecting malicious scripts into web pages, which are then executed in the context of another user’s browser. These scripts can steal cookies, session tokens, or other sensitive information from users, manipulate the content of the web page, or perform actions on behalf of the user. Input validation is the most effective defense against cross-site scripting attacks. Escaping restricted characters/metacharacters is also a good defence against XSS attacks.  XSS attacks may take advantage of the use of 🧠reflected input in a web application where input provided by one user is displayed to another user. In a reflected attack, the attacker can embed the attack within the URL so that it is reflected to users who follow a link.
    - 🔥Cross-Site Request Forgery (CSRF or XSRF): CSRF attacks force authenticated users to execute unwanted actions on a web application in which they are currently authenticated. By 🧠social engineering/tricking a user into clicking a link or loading an image, an attacker can send unauthorized requests to the web application. Cross-­site request forgery (XSRF) attacks exploit authentication trust between browser tabs. It is an attack utilizing social engineering and a malicious Uniform Resource Locator (URL) link to take advantage of a victim's existing browser session with a web application. XSRF or (CSRF) attacks exploit the trust that sites have in a user's browser by attempting to force the submission of authenticated requests to third-party sites. 
    - 🔥SQL Injection: Injecting malicious SQL statements into an entry field for execution on a backend database. Server-side inout validation is effective against SQL injection. Client-side input validation is not an effective control against any type of attack because the attacker can easily bypass the validation by altering the code on the client. Escaping restricted characters prevents them from being passed to the database, as does parameterization. Limiting database permissions prevents dangerous code from executing. Developers of web applications should leverage parameterized queries to limit the application’s ability to execute arbitrary code.
    - 🔥Buffer Overflow: Occurs when a program writes more data to a buffer than it can hold, leading to adjacent memory locations being overwritten. The best protection against buffer overflow attacks is server-side input validation. This technique limits user input to approved ranges of values that fit within allocated buffers. **Address space layout randomization (ASLR)** is a memory-protection process for operating systems (OSes) that guards against buffer-overflow attacks by randomizing the location where system executables are loaded into memory.
    - 🔥Broken Authentication and Session Management: Flaws in the authentication and session management functions that can be exploited to impersonate other users e.g Session ID exposure, weak password management.
    - 🔥Security Misconfiguration: Insecure default configurations, incomplete or ad-hoc configurations, open cloud storage, Improper enforcement of access control policies, misconfigured HTTP headers, and error messages containing sensitive information. Can lead to unauthorized access and data exposure.
    - 🔥Insecure Deserialization: Issues arising from the deserialization of untrusted data, which can lead to remote code execution, replay attacks, and injection attacks. Can lead to exploitation and manipulation of application logic.
    - 🔥Cross-Site Script Inclusion (XSSI): Attacks where sensitive information from script files can be accessed by unauthorized scripts. can lead to data leakage, exposure of internal APIs and configurations.
    - 🔥Server-Side Request Forgery (SSRF): An attacker can trick the server into making requests to unintended locations, potentially leaking internal information.
    - 🔥XML External Entity (XXE) Attacks: Exploitation of XML parsers to include malicious content or access sensitive data. It can be used for server-side request forgery.
    - 🔥Directory Traversal: Manipulating file paths to access restricted directories and execute commands outside of the web root directory. The attacker attempts to force the web application to navigate up the file hierarchy and retrieve a file that should not normally be provided to a web user, such as the password file.
    - 🔥Command Injection: Injecting system commands via an application that is executed by the host’s operating system.
    - 🔥Session Hijacking: It's when an attacker steals or takes over a session (like a logged-in state) that belongs to another user. This can happen if the session ID (which identifies the user’s session) is intercepted or guessed by the attacker. Once hijacked, the attacker can pretend to be the user without needing their login credentials.Transport Layer Security (TLS) provides the most effective defense against session hijack-ing because it encrypts all traffic between the client and server, preventing the attacker from stealing session credentials. Session hijacking attacks attempt to steal previously authenticated sessions but do not force the browser to submit requests.
    - 🔥URL encoding: This in itself is not an attack; rather, it is a method used to represent characters in a URL string using a percent sign (%) followed by two hexadecimal digits. This encoding is necessary to transmit data safely over the Internet, especially when the data contains special characters that might be misinterpreted by the web server or browser. In URL encoding, the . character is replaced by %252E, and the / character is replaced by %252F. However, URL encoding can be misused in certain contexts to facilitate attacks such as:
        - 🧯SQL Injection: SQL injection directly attacks a database through a web application. Attackers may use URL encoding to bypass input validation and inject malicious SQL queries into the application.
        - 🧯Cross-Site Scripting (XSS): By encoding malicious scripts or payloads in URLs, attackers can attempt to inject these scripts into web pages viewed by other users.
            - 📝Cross-site tracing (XST): leverages the HTTP TRACE or TRACK methods and could be used to steal a user's cookies via cross-site scripting (XSS).
        - 🧯Directory Traversal: Encoded characters can be used to traverse directories and access unauthorized files on the server.
        - 🧯Parameter Manipulation: Encoding can be used to manipulate parameters and alter the intended functionality of web applications.

- 🔴**Malware: (Malicious Software)** is a general term used to describe any software intentionally designed to cause damage to a computer, server, client, or computer network. It encompasses a wide range of malicious programs, including but not limited to:       
    - 🔥Viruses: Programs that replicate themselves and infect other files on a computer. Require humn intervention to replicate.
    - 🔥Trojans: Programs that appear legitimate but perform malicious activities when executed. Trojan horses masquerade as useful software but then carry out malicious functions after installation.
    - 🔥Ransomware: Encrypts files on a victim's system and demands ransom for decryption.
    - 🔥Spyware: Secretly gathers information about a user's activities.
    - 🔥Adware: Displays unwanted advertisements. classed as potentially unwanted programs (PUPs)
    - 🔥Worms: Self-replicating malware that spreads over networks. e.g stuxnet, code red worm. Worms are malicious code objects that move between systems under their own power, whereas viruses require some type of human intervention.
    - 🔥Rootkits: Conceal the existence of malware or malicious processes. it is commonly used for 🧠privilege escalation. Privilege escalation attacks, such as those carried out by rootkits, seek to upgrade normal user accounts to administrative
access rights.
    - 🔥Logic Bombs: Malicious code that lies dormant until certain conditions are met. Logic bombs wait until certain conditions are met before delivering their malicious payloads.
    - 🔥Cryptomalware: Designed to steals computing power and uses it to mine cryptocurrency.
    - 🔥Remote access Trojans (RATs) are designed to grant attackers remote administrative access to systems.
    - 🔥Potentially unwanted programs (PUPs) are any type of software that is initially approved by the user but then performs undesirable actions. 
        - 💥Viruses: A virus is a specific type of malware that replicates by inserting its code into other programs or files. When the infected program is executed, the virus code activates and spreads to other files or systems. The have the ability to modify other programs or files, making them contagious and capable of spreading rapidly. While all viruses are malware (because they are designed to cause harm), not all malware are viruses. For example, ransomware encrypts files for ransom, while spyware gathers information without replicating itself. Trojans masquerade as legitimate software but have malicious functions. Below are common types of viruses:
            - 🧯File Infectors: These viruses attach themselves to executable files (.exe, .com, etc.). They can overwrite the file, infect it, or alter the behavior of the executable. When the infected file is run, the virus is activated. e.g CIH (Chernobyl), Sasser.
            - 🧯Macro Viruses: These viruses target applications that use macros, such as Microsoft Word or Excel. They infect and spread through macro-enabled documents, affecting document files rather than the system itself. e.g Melissa, Concept.
            - 🧯Boot Sector Viruses: These viruses infect the master boot record (MBR) of a hard disk or a removable drive's boot sector. They are activated when the system starts up, spreading before the operating system is loaded. E.g Michelangelo, Stone.
            - 🧯Multipartite Viruses: These viruses can infect multiple parts of a system, such as both the boot sector and executable files. They spread in multiple ways and can re-infect systems even after cleanup if not all parts are addressed. E.g Tequila, Invader.
            - 🧯Polymorphic Viruses: These viruses can change their code or signature each time they infect a new system. They use encryption and code mutation to avoid detection by antivirus software. E.g Storm Worm, Vundo.
            - 🧯Metamorphic Viruses: These viruses rewrite their own code each time they infect a new file, making each version different. They can completely change their structure and functionality to evade detection. E.g Simile, ZMist.
            - 🧯Stealth Viruses: These viruses hide themselves by intercepting system calls and returning false information to the antivirus software. They avoid detection by using stealth techniques, such  as intercepting read requests from the antivirus software and returning a correct-looking version of the infected file masking their presence, often hiding file size changes or memory usage. E.g Tchernobyl, Frodo. 
            - 🧯Resident Viruses: These viruses embed themselves in the system's memory. They stay active even after the host program is terminated, allowing them to infect other files and programs. E.g Randex, CMJ.
            - 🧯Non-resident Viruses: These viruses do not embed themselves in the memory. They act immediately by infecting files as soon as they are executed and do not remain in memory. E.g Cascade, Vienna.
            - 🧯Ransomware: While often classified separately from traditional viruses, ransomware can be seen as a type of malicious code that encrypts the victim's data. It demands a ransom for the decryption key. It spreads like a virus, often through email attachments or malicious links. E.g WannaCry, Cryptolocker.
            - 🧯Encrypted virus: uses encryption to conceal its malicious code. The virus contains a decryption routine and an encrypted copy of the virus code. Each time the virus infects a new file, it generates a new encryption key and encrypts its code. When the infected file is executed, the decryption routine is triggered, decrypting the virus code and allowing it to execute.

- **Computing Resilience**:        
    - Multitasking is processing more than one task at the same time. In most cases, multitasking is simulated by the OS (using multiprogramming or pseudo-­simultaneous execution) even when not supported by the processor.
    - - Multicore is also able to perform simultaneous execution but does so with multiple execution cores on one or more CPUs.
      - Multistate is a type of system that can operate at various security levels (or classifications, risk levels, etc.)
      - Multithreading permits multiple concurrent tasks (i.e., threads) to be performed within a single process. A dual-core single-processor system can operate on two threads at a time (one by each core). A single-core single processor system would be limited to one thread executing at a time. 
      - Multiprocessing: In a multiprocessing environment, a multiprocessor computing system (that is, one with more than one CPU) harnesses the power of more than one processor to complete the execution of a multithreaded application.

- **Application Resilience**: two related principles: Scalability and elasticity are common features of cloud platforms and are a major driver toward the use of these platforms in enterprise computing environments.
    - Scalability says that applications should be designed so that computing resources they require may be incrementally added to support increasing demand.
         - Vertical Scalling: This may include adding more resources to an existing computing instance, which is known as vertical scaling or “scaling up.”
         - Horizontal Scaling: It may also include adding additional instances to a pool, which is known as horizontal scaling, or “scaling out.”
    - Elasticity goes a step further than scalability and says that applications should be able to automatically provision resources to scale when necessary and then automatically deprovision those resources to reduce capacity (and cost) when they are no longer needed. You can think of elasticity as the ability to scale both up and down on an as-­needed basis.


- **Memory Management**: Applications are often responsible for managing their own use of memory, and in those cases, poor memory management practices can undermine the security of the entire system.
    - Resource Exhaustion: Whether intentional or accidental, applications may consume all of the memory, storage, processing time, or other resources available on the system, rendering it disabled or crippled for other uses.
        - Memory leaks: are one example of resource exhaustion. If an application requests memory from the operating system, it will eventually no longer need that memory and should then return the memory to the operating system for other uses. In the case of an application with a memory leak, the application fails to return some memory that it no longer needs, perhaps by simply losing track of an object that it has written to a reserved area of memory.
        - Pointer Dereferencing: Memory pointers can also cause security issues. Pointers are an area of memory that stores an address of another location in memory. For example, we might have a pointer called photo that contains the address of a location in memory where a photo is stored. When an application needs to access the actual photo, it performs an operation called pointer dereferencing. This means that the application follows the pointer and accesses the memory referenced by the pointer address.  One particular issue that might arise is if the pointer is empty, containing what programmers call a NULL value. If the application tries to dereference this NULL pointer, it causes a condition known as a null pointer exception. In the best case, a NULL pointer exception causes the program to crash, providing an attacker with access to debugging information that may be used for reconnaissance of the application’s security. In the worst case, a NULL pointer exception may allow an attacker to bypass security controls. 
