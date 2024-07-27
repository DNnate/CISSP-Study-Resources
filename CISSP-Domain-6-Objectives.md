[Domain 6](#domain6-top) **Security Assessment and Testing**

- Security assessment and testing programs are an important mechanism for validating the on-going effectiveness of security controls
    - they include a variety of tools, such as vulnerability assessments, penetration tests, software testing, audits, and other control validation
- Every org should have a security assessment and testing program defined and operational
- **Security assessments**: comprehensive reviews of the security of a system, application, or other tested environment
    - during a security assessment, a trained information security professional performs a risk assessment that identifies vulnerabilities in the tested environment that may allow a compromise and makes recommendations for remediation, as needed
    - a security assessment includes the use of security testing tools, but go beyond scanning and manual penetration tests
    - the main work product of a security assessment is normally an assessment report addressed to management that contains the results of the assessment in nontechnical language and concludes with specific recommendations for improving the security of the tested environment
- An organization’s audit strategy will depend on its size, industry, financial status and other factors
    - a small non-profit, a small private company and a small public company will have different requirements and goals for their audit strategies
    - the audit strategy should be assessed and tested regularly to ensure that the organization is not doing a disservice to itself with the current strategy
    - there are three types of audit strategies: internal, external, and third-party

- **Artifact**: piece of evidence such as text, or a reference to a resource which is submitted in response to a question
- **Assessment**: testing or evaluation of controls to understand which are implemented correctly, operating as intended and producing the desired outcome in meeting the security or privacy requirements of a system or org
- **Audit**: process of reviewing a system for compliance against a standard or baseline (e.g. audit of security controls, baselines, financial records) can be formal and independent, or informal/internal
- **Chaos Engineering**: discipline of experiments on a software system in production to build confidence in the system's capabilities to withstand turbulent/unexpected conditions
- **Compliance Calendar**: tracks an org's audits, assessments, required filings, due dates and related
- **Compliance Tests**: an evaluation that determines if an org's controls are being applied according to management policies and procedures
- **Penetration Testing/Ethical Penentration Testing**: security testing and assessment where testers actively attempt to circumvent/defaut a system's security features; typically constrained by contracts to stay within specified Rules of Engagement (RoE)
- **Examination**: process of reviewing/inspecting/observing/studying/analyzing specs/mechanisms/activities to understand, clarify, or obtain evidence
- **Findings**: results created by the application of an assessment procedure
- **Judgement Sampling**: AKA purposive or authoritative sampling, a non-probability sampling technique where members are chosen only on the basis of the researcher's knowledge and judgement
- **Misue Case Testing**: testing strategy from a hostile actor's point of view, attempting to lead to integrity failures, malfunctions, or other security or safety compromises
- **Plan of Action and Milestones (POA&M)**: a document indentifying tasks to be accomplished, including details, resources, milestones, and completion target dates
- **RoE**: Rules of Engagement, set of rules/constraints/boundaries that establish limits of participant activity; in ethical pen testing, an RoE defines the scope of testing, and to establish liabilty limits for both testers and the sponsoring org or system owners
- **Statistical Sampling**: process of selecting subsets of examples from a population with the objective of estimating properties of the total population
- **Substantive Test**: testing technique used by an auditor to obtain the audit evidence in order to support the auditor's opinion
- **Testing**: process of exersizing one or more assessment objects (activities or mechanisms) under specified conditions to compare actual to expected behaior
- **Trust Services Criteria (TSC)**: used by an auditor when evaluating the suitability of the design and operating effectiveness of controls relevant to the security, availabiliity, or processing integrity of information and systems or the confidentiality or privacy of the info processed by the entity

[6.1](#6.1) Design and validate assessment, test, and audit strategies (OSG-9 Chpt 15)
- 6.1.1 Internal
    - An organization’s security staff can perform security tests and assessments, and the results are meant for internal use only, designed to evaluate controls with an eye toward finding potential improvements
    - An internal audit strategy should be aligned to the organization’s business and day-to-day operations
        - e.g. a publicly traded company will have a more rigorous internal auditing strategy than a privately held company
    - Designing the audit strategy should include laying out applicable regulatory requirements and compliance goals
    - Internal audits are performed by an organization’s internal audit staff and are typically intended for internal audiences
    
- 6.1.2 External
    - An external audit strategy should complement the internal strategy, providing regular checks to ensure that procedures are being followed and the organization is meeting its compliance goals
    - External audits are performed by an outside auditing firm
        - these audits have a high degree of external validity because the auditors performing the assessment theoretically have no conflict of interest with the org itself
        - audits by these firms are generally considered acceptable by most investors and governing bodies
    
- 6.1.3 Third-party
    - Third-party audits are conducted by, or on behalf of, another org
    - In the case of a third-party audit, the org initiating the audit generally selects the auditors and designs the scope of the audit
    - The statement on **Standards for Attestation Engagements document 18 (SSAE 18)**, titled Reporting on Controls, provides a common standard to be used by auditors performing assessments of service orgs with the intent of allowing the org to conduct external assessments, instead of multiple third-party assessments, and then sharing the resulting report with customers and potential customers
        - outside of the US, similar engagements are conducted under the International Standard for Attestation Engagements (ISAE) 3402, Assurance Reports on Controls at a Service Organization
    - SSAE 18 and ISAE 3402 engagements are commonly referred to as a service organization controls (SOC) audits
    - Three forms of SOC audits:
        - **SOC 1 Engagements**: assess the organization’s controls that might impact the accuracy of financial reporting
        - **SOC 2 Engagements**: assess the organization’s controls that affect the security (confidentiality, integrity, and availability) and privacy of information stored in a system
            - SOC 2 audit results are confidential and are usually only shared outside an org under an NDA
        - **SOC 3 Engagements**: assess the organization’s controls that affect the security (confidentiality, integrity, and availability) and privacy information stored in a system
            - however, SOC3 audit results are intended for public disclosure, and intended for distribution to third parties
    - Two types of SOC reports:
        - **Type I Reports**: provide the auditor’s opinion on the description provided by management and the suitability of the design of the controls
            - type I reports also cover only a specific point in time, rather than an extended period
            - think of Type I report as more of a documentation review
        - **Type II Reports**: go further and also provide the auditor’s opinion on the operating effectiveness of the controls
            - the auditor actually confirms the controls are functioning properly
            - Type II reports also cover an extended period of time, at least 6 months
            - think of Type II report as similar to a traditional audit; the auditor is checking the paperwork, and verifying the controls are functioning properly
        - Type II reports are considered much more reliable than Type I reports (Type I reports simply take the service orgs word that the controls are implemented as described)
     
- 6.1.4 Location for Auditing
    - Third-party audits are conducted by, or on behalf of, another org
    - **On-Premise**:
        - Physical Access: Auditors typically need physical access to hardware, network devices, and data centres for inspection, configuration reviews and testing
        - Control and Visibility: Organisation retains greater control over its infrastructure thus auditors have ore direct visibility into security configurations
        - Scope: Audits may be focused on traditional IT infrastructure , including network security, operating systems, physical safeguards etc
    - **Cloud**:
        - Shared Responsibility: Security is a shared responsibility between the organisation and the cloud provider. Audit focus shifts towards how the organisation uses the cloud services
        - Documentation & APIs: Auditors typically will rely on heavily on cloud provider documentations, service configurations, and access to relevant APIs for gathering evidence.
        - Compliance Focus: Emphasis often on meeting cloud-specific security standards (e.g SOC 2, ISO 27001, FedRAMP), and the organisations configuration of cloud services. CSPs provide attestation documents for certification of the underlying infrastructure but the customer still needs to configure the cloud service in a compliant manner.
        - Customer right-to-audit is often limited, and be  mindful of rules of engagement when it comes to penetration testing
    - **Hybrid**:
        - Increased Complexity: presents the most complexity due to the mix of on-premise and cloud components that need auditing
        - Data Flows: Understanding how data moves between on-premise and cloud environments is crucial for risk assessment
        - Integrated Controls: Auditors must evaluate the evaluate the effectiveness of security controls accros the entire hybrid landscape.

- **Assurance Challenges with Virtualization & Cloud**: The cloud is made possible by virualization technologies that enable dynamic environments needed for a global provider platform.
    -  Depending on the cloud arhitecture deployed, the cloud security professional may need to perorm multiple layers of auditing.
    -  To be effective, the auditor must understand the virualization architecture of the cloud provider
        - Provider (Cloud Service Provider): The CSP i.e Microsoft, Amazon & Google will usually be responsible for the audits of controls over the hypervisor
        - Customer (Cloud conusmers):  VMs deployed on top of the hardware are usually owned by the customer
        - **Right-to-Audit**:
            - The customer can request right-to-audit the service provider to ensure compliance with the security requirements agreed in the contract
            - Contracts are often written to allow CSPs standard audits (SOC 2, ISO 27001) to be used in place of customer-performed audit.
        - **Metrics**: If there are specific indicators that the CSP must provide to the customer, they should be documented in a contract
            - Metrics tell you how compliance with the agreement will be measured
        - Major CSPs make SOC 2 Type II (or other report) available on demand 
        - The use of vulnerability scanners and pen testers may be limited by the CSP's terms of service or cloud contractual arrangment.
            - 

[6.2](#6.2) Conduct security control testing (OSG-9 Chpt 15)
- Security control testing can include testing of the physical facility, logical systems and applications; common testing methods:
- 6.2.1 Vulnerability assessment
    - **Vulnerabilities**: weaknesses in systems and security controls that might be exploited by a threat
    - Vulnerability assessments: examining systems for these weaknesses
    - The goal of a vulnerability assessment is to identify elements in an environment that are not adequately protected -- and not necessarily from a technical perspective; you can also assess the vulnerability of physical security or the external reliance on power, for instance
        - can include personnel testing, physical testing, system and network testing, and other facilities tests
    - Vulnerability assessments are some of the most important testing tools in the information security professional’s toolkit
    - **Security Content Automation Protocol (SCAP)**: provides a common framework for discussion and facilitation of automation of interactions between different security systems (sponsored by NIST)
        - SCAP components related to vulnerability assessments:
            - **Common Vulnerabilities and Exposures (CVE)**: provides a naming system for describing security vulnerabilities
            - **Common Vulnerability Scoring Systems (CVSS)**: provides a standardized scoring system for describing the severity of security vulnerabilities. The score can range from 0.0 (least severe) to 10.0 (most severe).
            - **Common Configuration Enumeration (CCE)**: provides a naming system for system config issues
            - **Common Platform Enumeration (CPE)**: provides a naming system for operating systems, applications, and devices
            - **Extensible Configuration Checklist Description Format (XCCDF)**: provides a language for specifying security checklists
            - **Script Check Engine (SCE)** is designed to make scripts ­interoperable with security policy definitions.
            - **Open Vulnerability and Assessment Language (OVAL)**: provides a language for describing security testing procedures
    - Vulnerability scans automatically probe systems, applications, and networks looking for weaknesses that could be exploited by an attacker. Vulnerability Scanners scan remote machines to gather information, including fingerprints from responses to queries and connections, banner information from services, and related data.
    - Four main categories of vulnerability scans:
        - network discovery scans: Network discovery scanners use many different techniques to identify open ports on remote systems:
            - 🔔TCP SYN Scanning Sends a single packet to each scanned port with the SYN flag set. This indicates a request to open a new connection. If the scanner receives a response that has the SYN and ACK flags set, this indicates that the system is moving to the second phase in the three-­way TCP handshake and that the port is open. TCP SYN scanning is also known as 📝“half-­open” scanning.
            - 🔔TCP Connect Scanning Opens a full connection to the remote system on the specified port. This scan type is used when the user running the scan does not have the necessary permissions to run a half-­open scan. Most other scan types require the ability to send raw packets, and a user may be restricted by the operating system from sending hand-crafted packets. The TCP SYN scan sends a SYN packet and receives a SYN ACK
            - 🔔TCP ACK Scanning Sends a packet with the ACK flag set, indicating that it is part of an open connection. This type of scan may be done in an attempt to determine the rules enforced by a firewall and the firewall methodology. 
            - 🔔UDP Scanning Performs a scan of the remote system using the UDP protocol, checking for active UDP services. This scan type does not use the three-­way handshake, because UDP is a connectionless protocol.
            - 🔔Xmas Scanning Sends a packet with the FIN, PSH, and URG flags set. A packet with so many flags set is said to be “lit up like a Christmas tree,” leading to the scan’s name.
        - 🔔Network vulnerability scans e.g nmap, nikto, OpenVAS, QualysGuard, Nessus, Rapid7, Tenable. Note: Nmap only scans 1000 TCP and UDP ports by default, including ports outside the 0–1024 range of “well-known” ports. By using the defaults, you miss 64,535 ports! **nmap states** are Open Port: The port is accessible on the remote system and an application is accepting connections on that port. Closed Port: The port is not accessible on the remote system. Filtered Port: The port is accessible on the remote system, but no application is accepting connections on that port.
        - web application vulnerability scans e.e OWASP, Nikto, Burp Suit, Nessus, Arachni, W3af
        - database vulnerability scans e.g SQLMap, DBProtect, Rapid7, Oracle DBSAT, IBM Guardium, Nessus
    - 🔔Active Scanning is useful for testing IDS or IPS systems. Scripted attacks are part of active scanning
    - 🔔Passive scanning can help identify rogue devices by capturing MAC address vendor IDs that do not match deployed devices, by verifying that systems match inventories of organizationally owned hardware by hardware address, and by monitoring for rogue SSIDs or connections.
    - 🔔Authenticated Vulnerability scans use a read-only account to access configuration files, allowing more accurate testing of vulnerabilities. It  provides the most accurate and detailed information about the security state of a server.
        - Authenticated scans can read configuration information from the target system and reduce the instances of false positive and false negative reports.

- 6.2.2 Penetration testing
    - Penetration tests goes beyond vulnerability testing techniques because it actually attempts to exploit systems. In most organizations, senior management needs to approve penetration tests due to the risk to the organization and the potential impact of the test. In a small number of organizations, the service owner may be able to make this decision, but penetration tests often have broader impacts than a single service, meaning that senior management is the proper approval path.
    - NIST defines the penetration testing process as consisting of four phases:
    - **planning**: includes agreement on the scope of the test and the rules of engagement
        - ensures that both the testing team and management are in agreement about the nature of the test and that it is explicitly authorized
    - **information gathering and discovery**: uses manual and automated tools to collect information about the target environment
        - basic reconnaissance (website mapping)
        - network discovery
        - testers probe for system weaknesses using network, web and db vuln scans
    - **attack**: seeks to use manual and automated exploit tools to attempt to defeat system security
        - step where pen testing goes beyond vuln scanning as vuln scans don’t attempt to actually exploit detected vulns
    - **reporting**: summarizes the results of the pen testing and makes recommendations for improvements to system security
    - tests are normally categorized into three groups:
        - **white-box penetration test**:
            - provides the attackers with **detailed information** about the systems they target
            - this bypasses many of the reconnaissance steps that normally precede attacks, shortening the time of the attack and increasing the likelihood that it will find security flaws
            - these tests are sometimes called "**known environment**" tests
        - **gray-box penetration test**:
            - AKA **partial knowledge tests**, these are sometimes chosen to balance the advantages and disadvantages of white- and black-box penetration tests
            - this is particularly common when black-box results are desired but costs or time constraints mean that some knowledge is needed to complete the testing
            - these tests are sometimes called "**partially known environment**" tests
        - **black-box penetration test**:
            - does not provide attackers with any information prior to the attack
            - this simulates an external attacker trying to gain access to information about the business and technical environment before engaging in an attack
            - these tests are sometimes called "**unknown environment**" tests
- **Excersice Types**:
    - **Red Team**: A group of security professionals who simulate real-world attacks to test the defenses of an organization.
        - They are an internal or external entity dedicated to testing the effectiveness of a security program by emulating tools and techniques of likely attackers in the most realistic way possible
        - They are offence
        - Think of attackers testing the system for weaknesses.
    - **Blue Team**: A group of security professionals responsible for defending an organization’s IT infrastructure from attacks.
        - They are internal security team that defends against Red Team and real attackers
        - They are defence
        - Think of defenders protecting the system from attacks.
    - **Purple Team**: A collaboration between the red team and blue team to improve the overall security of an organization.
        - exist to ensure and maximise the effectiveness of the red and blue teams
        - They are for process improvement
        - Think of a cooperative effort where attackers and defenders work together to strengthen security.
   - **White Team**: responsible for overseeing an engagement/competition between a Red Team of mock attackers and a Blue Team of actual defenders.
        - They do not participate directly in the attack (red team) or defense (blue team) activities but ensure fair play and adherence to the rules.
        - Facilitate communication and coordination between red and blue teams.
        - Observe the security exercise to ensure that it is realistic and that all parties follow the guidelines.
        - Set the boundaries and objectives of the security exercise to ensure it is controlled and focused.
        - Think of judge or referee
      
- 6.2.3 Log reviews
    - **Security Information and Event Management (SIEM)**: packages that collect information using the syslog functionality present in many devices, operating systems, and applications. Note: Windows systems generate logs in the Windows native logging format. To send syslog events, Windows systems require a helper application or tool.
    - Admins may choose to deploy logging policies through Windows Group Policy Objects (GPOs)
    - Logging systems should also make use of the Network Time Protocol (NTP) to ensure that clocks are synchronized on systems sending log entries to the SIEM as well as the SIEM itself, ensuring info from multiple sources have a consistent timeline
    - Examples include SPlunk, LogRythm, Microsoft Azure Sentinel, IBM Qradar
    - Information security managers should also periodically conduct log reviews, particularly for sensitive functions, to ensure that privileged users are not abusing their privileges
    - **Network flow** (NetFlow) NetFlow records contain an entry for every network communication session that took place on a network and can be compared to a list of known malicious hosts. It is routinely saved as a matter of normal activity. Cisco has developed a version of NetFlow called Flexible NetFlow (FNF), which can be combined with secure transmission methods. However, the specific built-in decryption capability for NetFlow data is generally referred to as **Encrypted Traffic Analytics (ETA)**. ETA is designed to provide visibility into network traffic, even when the traffic is encrypted. 
    - **Synthetic monitoring (or active monitoring)** uses emulated or recorded transactions to monitor for performance changes in response time, functionality, or other performance monitors. e.g Grafana, Zabbix, Selenium. It performs artificial transactions against a website to assess performance. Synthetic monitoring uses simulated or recorded traffic and thus can be used to proactively identify problems.
    - **Passive monitoring** uses a span port or other method to copy traffic and monitor it in real time. e.g wireshark,  PRTG, Cacti, ntoping, prometheus. **Real user monitoring (RUM)** is a variant of passive monitoring where the monitoring tool
reassembles the activity of individual users to track their interaction with a website. RUM records user interaction with an application or system to ensure performance and proper application behavior. Passive monitoring works only after issues have occurred because it requires actual traffic.
    - **Identity and access management (IAM)** systems combine lifecycle management and monitoring tools to ensure that identity and authorization are properly handled throughout an organization. e.g AD, DUO, OKTA

- 6.2.4 Synthetic transactions
    - **Synthetic transactions**: scripted transactions with known expected results
    - Dynamic testing may include the use of synthetic transactions to verify system performance; synthetic transactions are run against code and compare out to expected state

- 6.2.5 Code review and testing
    - Code review and testing is "one of the most critical components of a software testing program"
    - These procedures provide third-party reviews of the work performed by developers before moving code into a production environment, possibly discovering security, performance, or reliability flaws in apps before they go live and negatively impact business operations
    - In code review, AKA peer review, developers other than the one who wrote the code review it for defects
    - **Fagan inspections**: the most formal code review process follows six steps:
        1) planning
        2) overview
        3) preparation
        4) inspection
        5) rework
        6) follow-up
    - **Static application security testing (SAST)**: evaluates the security of software without running it by analyzing either the source code or the compiled application
    - **Dynamic application security testing (DAST)**: evaluates the security of software in a runtime environment and is often the only option for organizations deploying applications written by someone else

- 6.2.6 Misuse case testing
    - **Misuse case testing**: AKA abuse case testing - used by software testers to evaluate the vulnerability of their software to known risks
    - In misuse case testing, testers first enumerate the known misuse cases, then attempt to exploit those use cases with manual or automated attack techniques

- 6.2.7 Test coverage analysis
    - A test coverage analysis is used to estimate the degree of testing conducted against new software
    - **Test coverage** = number of use cases tested / total number of use cases
        - requires enumerating possible use cases (which is a difficult task), and anyone using test coverage calcs to understand the process used to develop the input values
    - Five common criteria used for test coverage analysis:
        - **branch coverage**: has every IF statement been executed under all IF and ELSE conditions?
        - **condition coverage**: has every logical test in the code been executed under all sets of inputs?
        - **functional coverage**: has every function in the code been called and returned results?
        - **loop coverage**: has every loop in the code been executed under conditions that cause code execution multiple times, only once, and not at all?
        - **statement coverage**: has every line of code been executed during the test?

- 6.2.8 Interface testing
    - Interface testing assesses the performance of modules against the interface specs to ensure that they will work together properly when all the development efforts are complete
    - Three types of interfaces should be tested:
        - application programming interfaces (APIs): offer a standardized way for code modules to interact and may be exposed to the outside world through web services
            - should test APIs to ensure they enforce all security requirements
        - user interfaces (UIs): examples include graphical user interfaces (GUIs) and command-line interfaces
            - UIs provide end users with the ability to interact with the software, and tests should include reviews of all UIs
        - physical interfaces: exist in some apps that manipulate machinery, logic controllers, or other objects
            - software testers should pay careful attention to physical interfaces because of the potential consequences if they fail

- 6.2.9 Breach attack simulations
    - **Breach and attack simulation (BAS)**: platforms that seek to automate some aspects of penetration testing
    - The BAS platform is not actually waging attacks, but conducting automated testing of security controls to identify deficencies
    - Breach and Attack Simulation, systems are systems that combine red team (attack) and blue team (defense) techniques together with automation to simulate advanced persistent threats and other advanced threat actors when run against your environment. This allows a variety of threats to be replicated and assessed in an environment without as much overhead as a fully staffed purple team would.
    - Designed to inject threat indicators onto systems and networks in an effort to trigger other security controls (e.g. place a suspicious file on a server)
        - detection and prevention controls should immediately detect and/or block this traffic as potentially malicious
    - See:
        - OWASP Web Security Testing Guide
        - OSSTMM (Open Source Security Testing Methodology Manual)
        - NIST 800-115
        - FedRAMP Penetration Test Guidance
        - PCI DSS Information Supplemental on Penetration Testing Note📝 PCI DSS requires a rescan of  application at least annually and after any change in the application.

- 6.2.10 Compliance checks
    - Orgs should create and maintain compliance plans documenting each of their regulatory obligations and map those to the specific security controls designed to satisfy each objective
    - Compliance checks are an important part of security testing and assessment programs for regulated firms: these checks verify that all of the controls listed in a compliance plan are functioning properly and are effectively meeting regulatory requirements

[6.3](#6.3) Collect security process data (e.g. technical and administrative) (OSG-9 Chpts 15,18)
- 6.3.1 Account management
    - Preferred attacker techniques for obtaining privilege user access include:    
        - compromising an existing privileged account: mitigated through use of strong authentication (strong passwords and multifactor), and by admins use of privileged accounts only for specific tasks
        - privelege escalation of a regular account or creation of a new account: these approaches can be mitigated by paying attention to the creation, modification, and use of user accounts

- 6.3.2 Management review and approval
    - Account management reviews ensure that users only retain authorized permissions and that unauthorized modifications do not occur
    - Full review of accounts: time-consuming to review all, and often done only for highly privileged accounts
    - Organizations that don’t have time to conduct a full review process may use sampling, but only if sampling is truely random
    - The two main methods of choosing records from a large pool for further analysis are sampling and clipping. **Sampling** uses statistical techniques to choose a sample that is representative of the entire pool, while **clipping** uses threshold values to select those records that exceed a predefined threshold because they may be of most interest to analysts.
    - Adding accounts: should be a well-defined process, and users should sign AUP
    - Adding, removing, and modifying accounts and permissions should be carefully controlled and documented
    - Accounts that are no longer needed should be suspended
    - ISO 9000 standards use a Plan-Do-Check-Act loop
        - plan: foundation of everything in the ISMS, determines goals and drives policies
        - do: security operations
        - check: security assessment and testing (this objective)
        - act: formally do the management review

- 6.3.3 Key performance and risk indicators
    - **Key Performance Indicator (KPIs)**: measures that provide significance of showing the performance an ISMS compared to stated goals
    - Choose the factors that can show the state of security
    - Define baselines for some (or better yet all) of the factors
    - Develop a plan for periodically capturing factor values (use automation!)
    - Analyze and interpret the data and report the results
    - Key metrics or KPIs that should be monitored by security managers may vary from org to org, but could include:
        - number of open vulns
        - time to resolve vulns
        - vulnerability/defect recurrence
        - number of compromised accounts
        - number of software flaws detected in pre-production scanning
        - repeat audit findings
        - user attempts to visit known malicious sites
    - Develop a dashboard of metrics and track them

- 6.3.4 Backup verification data
    - Managers should periodically inspect the results of backups to verify that the process functions effectively and meets the organization’s data protection needs
        - this might include reviewing logs, inspecting hash values, or requesting an actual restore of a system or file
        -  ensures that the organization’s data protection requirements are met effectively

- 6.3.5 Training and awareness
    - Training and awareness programs play a crucial role in preparing an organization’s workforce to support information security programs
    - They educate employees about current threats and advise them on best practices for protecting information and systems under their care from attacks
    - Program should begin with initial training designed to provide foundation knowledge to employees who are joining the org or moving to a new role; the initial training should be tailored to an individual’s role
    - Training and awareness should continue to take place throughout the year, reminding employees of their responsibilities and updating them on changes to the organization’s operating environment and threat landscape
    - Use phishing simulations to evaluate the effectiveness of their security awareness programs

- 6.3.6 Disaster Recover (DR) and Business Continuity (BC)
    - **Business Continuity (BC)**: the processes used by an organization to ensure, holistically, that its vital business processes remain unaffected or can be quickly restored following a serious incident
    - **Disaster Recovery (DR)**: is a subset of BC, that focuses on restoring information systems after a disaster
    - These processes need to be periodically accessed, and regular testing of disaster recovery and business continuity controls provide organizations with the assurance they are effectively protected against disruptions to business ops
    - Protection of life is of the utmost importance and should be dealt with first before attempting to save material things

[6.4](#6.4) Analyze test output and generate report (OSG-9 Chpt 15)
- Step 1: review and understand the data
    - The goal of the analysis process is to proceed logically from facts to actionable info
    - A list of vulns and policy exceptions is of little value to business leaders unless it's used in context, so once all results have been analyzed, you're ready to start writing the official report
- Step 2: determine the business impact of those facts
    - Ask "so what?"
- Step 3: determine what is actionable
    - The analysis process leads to valuable results only if they are actionable

- 6.4.1 Remediation
    - Rather than software defects, most vulnerabilities in average orgs come from misconfigured systems, inadequate policies, unsound business processes, or unaware staff
    - Vuln remediation should include all stakeholders, not just IT 

- 6.4.2 Exception handling
    - **Exception handling**: the process of handling unexpected activity, since software should never depend on users behaving properly
        - "expect the unexpected", gracefully handle invalid input and improperly sequenced activity etc 
    - Sometimes vulns can't be patched in a timely manner (e.g. medical devices needing re-accreditation) and the solution is to implement compensitory controls, document the excpetion and decision, and revisit
        - **compensitory controls**:measures taken to address any weaknesses of existing controls or to compensate for the inability to meet specific security requirements due to various different constraints
        - e.g. micro-segmentation of device, access restrictions, monitoring etc
    - Exception handling may be required due to system crash as the result of patching (requiring roll-back)

- 6.4.3 Ethical disclosure
    - While conducting security testing, cybersecurity pros may discover previously undiscovered vulns (perhaps implementing compensating controls to correct) that they may be unable to correct
    - **Ethical disclosure**: the idea that security pros who detect a vuln have a responsibility to report it to the vendor, providing them with enough time to patch or remediate
        - the disclosure should be made privately to the vendor providing reasonable amount of time to correct
        - if the vuln is not corrected, then public disclosure of the vuln is warrented, such that other professionals can make informed decisions about future use of the product(s)

[6.5](#6.5) Conduct or facilitate security audits (OSG-9 Chpt 15)
- 6.5.1 Internal
    - Having an internal team conduct security audits has several advantages:
        - understanding of the internal environment reduces time
        - an internal team can delve into all parts of systems, because they have insider knowledge
        - internal auditors can be more agile in adapting to changing needs, rescheduling failed assessment components quickly
    - Disadvantages of using an internal team to conduct security audits:
        - the team may have limited exposure to new/other methodologies (e.g. the team may have depth but not breadth of experience and knowledge)
        - potential conflicts of interest (e.g. reluctance to throw other teams under the bus and accurately report their findings)
        - audit team members may start with an agenda (say to secure funding) and overstate faults, or have interpersonal motives

- 6.5.2 External
    - An external audit (sometimes called a second-party audit) is one conducted by (or on behalf of) a business partner
    - External audits are tied to contracts; by definition, an external audit should be scoped to include only the contractual obligations of an organization

- 6.5.3 Third-party
    - Third-party audits are often needed to demonstrate compliance with some government regulation or industry standard
    - Advantages of having a third-party audit an organization:
        - they likely have breadth of experience auditing many types of systems, across many types of organizations
        - they are not affected by internal dynamics or org politics
    - Disadvantage of using a third-party auditor:
        - cost: third-party auditors are going to be much more costly than internal teams; this means that the organization is likely to conduct audits as frequently
        - internal resources are still required to assist or accompany auditors, to answer questions and guide
     
- 6.5.4 Location: Facilitating Security Audit
    - On-Premise:
    - **Cloud**: distributed nature and scale of cloud infrastructure makes conducting an audit of cloud infrasturcture challenging.
        - You generally cannot audit the underlying infrastructure managed by the CSP
        - cloud computing enables distributed services , with systems that can replicate globally. The impact is the additional geographic locations auditors must consider when performing an audit
        - Common technique in cloud auditing is sampling - picking a subset of the physical infrastructure to inspect
        - CSPs can collect evidence that provides auditors with sufficient assurance that they have collected a representative sample to save time and expense while still mainting accuracy
        - In relation to audit compliance, the 3 audit standards commonly used by the big CSPs include SSAE, ISAE, and CSA.
            - **SSAE (Statement on Standards for Attestation Engagements)**: SSAE is a standard developed by the American Institute of Certified Public Accountants (AICPA) for reporting on the controls at a service organization.
                - SSAE 18 is designed to enhance the quality and usefulness of SOC reports
                - SSAE is the framework for creating System and Organization Controls (SOC) reports, such as SOC 1, SOC 2, and SOC 3.
                  - SOC 1: report that focuses on financial reporting by certified public accountants.
                  - SOC 2 Type I: report that focuses on security, availability, processing integrity, confidentiality, and privacy controls at a specific point in time.
                  - SOC 2 Type II: report that asseses the security, availability, processing integrity, confidentiality, and privacy controls over time by overving operations for at least 6 months. You can get these reports on demand from CSPs but may require you to sign an NDA.
                  - SOC 3: Similar to SOC 2 but intended for broader distribution and contains auditors general opinions.
                - It includes audit standards and suggested report formats to guide and assits auditors
                - Example a cloud service provider undergoes an SSAE 18 audit to prove to clients that their data is secure and managed properly. 
            - **ISAE (International Standard on Assurance Engagements)**:  ISAE is a set of standards issued by the International Auditing and Assurance Standards Board (IAASB) for assurance engagements, including reports on controls at service organizations. 
                - The board and its standards are both similar to those of SSAE.
                - ISAE 3402: The most relevant standard for cloud services, similar to SSAE 18, used internationally. it is roughly the equivalent of SOC 2 reports in SSAE.
            - **CSA (Cloud Security Alliance)**: CSA is an organization that defines best practices and provides certifications for securing cloud computing environments.
                - it offers the CSA STAR program: The Security, Trust, Assurance, and Risk (STAR) program is a certification for cloud service providers based on CSA's Cloud Controls Matrix (CCM).
                - STAR consists of two level of certification which provide increasing levels of assurance
                   - Level 1 Self-Assesment: is based on self-assessment where Providers assess their own security practices against the CCM. It documents the security offering provided by the CSP.
                   - Level 2 Third Party Audit: Requires the CSP to engage an independent auditor to evaluate the CSPs controls against the CSA standard. It is stronger.
                - Can be used by CSPs, cloud consumers, auditors or consultants
                - It is designed to demonstrate compliance to a desired level of assurance.
    - Hybrid:
      
- [6.6](#6.6) Software testing: Security Assessment and Testing (OSG-9 Chpt 15)
    - **Code Review**: Code review is the foundation of software assessment programs. During a code review, also known as a peer review, developers other than the one who wrote the code review it for defects. Static program reviews are typically performed by an automated tool. Program understanding, program comprehension, pair programming, software inspections, and software walk-throughs are all human-centric methods for reviewing code.
    - an example of Code review is by using the 6 steps Fagan process: 1.Planning, 2.Overview, 3.Preparation, 4.Inspection, 5.Rework, 6.Follow-­up
    - **Static Testing** SAST: evaluates the security of software without running it by analyzing either the source code or the compiled application
        - Developers use static code analysis tools network
    - **Dynamic Testing** DAST: evaluates the security of software in a runtime environment and is often the only option for organizations deploying applications written by someone else. In those cases, testers often do not have access to the underlying source code.
        - common example of dynamic software testing is the use of web application scanning tools to detect the presence of cross-­site scripting, SQL injection, or other flaws in web applications. Note📝 SQL injection is a web vulnerability.
        - Another example is the use of synthetic transactions to verify system performance. These are scripted transactions with known expected results.
    - **Fuzz Testng**: is a specialized dynamic testing technique that provides many different, and sometimes invalid types of input to software to stress its limits and find previously undetected flaws.  Fuzzing uses modified inputs to test software performance under unexpected circumstances.It is imited to detecting simple vulnerabilities.
    - zzuf is a fuzzing tool thats tests web browsers ability to handle unexpected data
    - Fuzzers are tools that are designed to provide invalid or unexpected input to applications, testing for vulnerabilities like format string vulnerabilities, buffer overflow issues, and other problems.
        - 🔔Mutation (Dumb) Fuzzing Takes previous input values from actual operation of the software and manipulates (or mutates) it to create fuzzed input. It uses bit flipping and other techniques to slightly modify previous inputs to a program in an attempt to detect software flaws. It  modifies known inputs to generate synthetic inputs that may trigger unexpected behavior
        - 🔔Generational (Intelligent) Fuzzing Develops data models and creates new fuzzed input based on an understanding of the types of data used by the program. It develops inputs based on models of expected inputs to perform the same task.
    - **Interface Testing**: assesses the performance of modules against the interface specifications to ensure that they will work together properly. Interfaces to be tested include
      - Application Programming Interfaces (APIs)
      - User Interfaces (UIs)
      - Physical Interfaces (For appliacations that manipulate machinery and logic controllers)

    - **Misuse Case Testing**: or abuse case testing to evaluate the vulnerability of their software to users attempt
to misuse the application
    - **Mutation Testing**: Mutation testing (automatically) modifies a program in small ways and then tests that mutant to determine if it behaves as it should or if it fails. This technique is used to design and test software tests through mutation.
    - **Regression Testing**: In cases where the project is releasing updates to an existing system, regression testing formalizes the process of verifying that the new code performs in the same manner as the old code, other than any changes expected as part of the new release. They Key performance measure of Regression testing is more specifically covered by defect recurrence rates.        
    - **Test Coverage Analysis**:
            - Test Coverage = number of use cases Tested/Total umber of use cases. ­Coverage rates are used to measure how effective code testing is.
            - Branch Coverage: Test all If/Esle Statements
            - Condition Coverage
            - Function Coverage
            - Loop Coverage
            - Statement Coverage

- Test coverage report measures how many of the test cases have been completed and is used as a way to provide test metrics when using test cases.
- Penetration test report is provided when a penetration test is conducted.
- Code coverage report covers how much of the code has been tested
- Line coverage report is a type of code coverage report.

**Time of Check to Time of Use**
- Computer systems perform tasks with rigid precision. Computers excel at repeatable tasks. Attackers can develop attacks based on the predictability of task execution. The common sequence of events for an algorithm is to check that a resource is available and then access it if you are permitted. The **time of check (TOC)** is the time at which the subject checks on the status of the object. There may be several decisions to make before returning to the object to access it. When the decision is made to access the object, the procedure accesses it at the **time of use (TOU)**. The difference between the TOC and the TOU is sometimes large enough for an attacker to replace the original object with another object that suits their own needs. Time of check to time of use (TOCTTOU or TOC/TOU) attacks are often called race conditions. When testing in a non-production environment, the changes from a testing environment with instrumentation inserted into the code and the production environment for the code can mask timing-related issues like race conditions.

**Time to remediate a vulnerability**is a commonly used key performance indicator for security teams.

**Common Audit Frameworks**
- SSAE 18 is the Statement on Standards for Attestation Engagements that is used by auditors when performing audits for SOC 2.
- ISO/IEC 15408-­1:2009, “Information technology —­Security techniques —­ Evaluation criteria for IT security,” is the foundation for the Common Criteria certification, which is a formal assessment process for technology products against a defined set of security functional requirements. This document and ISO/IEC 18045 are available free of charge.
- ISO/IEC 18045:2008, “Information technology —­Security techniques —­Methodology for IT security evaluation,” is a companion to ISO 15048 and provides standards for consistent criteria and evaluation methods.
- ISO/IEC 27006:2015, “Information technology —­Security techniques —­ Requirements for bodies providing audit and certification of information security management systems,” is the official set of requirements and guidance for auditors performing certification audits against ISO 27001.
- NIST Special Publication (SP) 800-­53A, “Assessing Security and Privacy Controls in Federal Information Systems and Organizations,” is a guide to assessing the controls outlined in NIST SP 800-­53. It introduces a simple set of testing procedures to assess control effectiveness: test, examine, or interview. 
- The NIST Cybersecurity Framework (CSF) and FedRAMP Security Assessment Framework (SAF) are both freely available as well and may be used to perform assessments with evaluation methods similar to those in NIST SP 800-­53A.
- COBIT the Control Objectives for Information and Related Technologies, is commonly used as an audit framework for organizations.

**Common Ports**
- Line Printer Daemon (LPD) protocol: Port 515 
- RAW or JetDirect protocol: Port 9100
- FTP (File Transfer Protocol): Port 20 (Data Transfer), Port 21 (Control)
- FTPS (FTP Secure): Ports 989 and 990
- SFTP (SSH File Transfer Protocol): Port 22
- SSH (Secure Shell): Port 22
- Telnet: Port 23
- SMTP (Simple Mail Transfer Protocol):Port 25
- IMAP (Internet Message Access Protocol): Port 143
- IMAPS (IMAP Secure): Port 993
- POP3 (Post Office Protocol version 3): Port 110
- POP3S (POP3 Secure): Port 995
- TFTP (Trivial File Transfer Protocol): Port 69
- SNMP (Simple Network Management Protocol): Port 161 (Agent), Port 162 (Manager)
- LDAP (Lightweight Directory Access Protocol): Port 389
- LDAPS (LDAP Secure): Port 636
- RDP (Remote Desktop Protocol): Port 3389
- SMB (Server Message Block): Port 445
- Syslog: Port 514
- Kerberos: Port 88
- SQL Server: Port 1433
- MySQL: Port 3306
- Oracle DB: Port 1521
- NTP (Network Time Protocol): Port 123
- BGP (Border Gateway Protocol): Port 179
- IKE (Internet Key Exchange): Port 500
- L2TP (Layer 2 Tunneling Protocol): Port 1701
- PPTP (Point-to-Point Tunneling Protocol): Port 1723
- RADIUS (Remote Authentication Dial-In User Service): Port 1812 (Authentication), Port 1813 (Accounting)
- NetBIOS: Ports 137-139
- TACAS: Port 49
- XMPP (Extensible Messaging and Presence Protocol): Port 5222
- VNC (Virtual Network Computing): Port 5900
- NFS (Network File System): Port 2049
- OpenVPN: Port 1194
- PostgreSQL: Port 5432

**NIST Special Publication (SP) 800 Series:**

- NIST SP 800-30: "Guide for Conducting Risk Assessments" - Provides guidance on conducting risk assessments.
- NIST SP 800-37: "Risk Management Framework for Information Systems and Organizations" - Outlines the Risk Management Framework (RMF) for federal information systems.
- NIST SP 800-39: "Managing Information Security Risk" - Provides guidelines for an integrated, organization-wide program for managing information security risk.
- NIST SP 800-53: "Security and Privacy Controls for Information Systems and Organizations" - Provides a catalog of security and privacy controls for federal information systems and organizations.
- NIST SP 800-61: "Computer Security Incident Handling Guide" - Offers guidelines for handling computer security incidents.
- NIST SP 800-82: "Guide to Industrial Control Systems (ICS) Security" - Provides guidance on securing industrial control systems.
- NIST SP 800-86: "Guide to Integrating Forensic Techniques into Incident Response" - Discusses how to integrate forensic techniques into incident response.
- NIST SP 800-94 Guide to Intrusion Detection and Prevention Systems provides comprehensive coverage of both IDS and IPS
- NIST SP 800-137: titled "Information Security Continuous Monitoring (ISCM) for Federal Information Systems and Organizations," provides guidelines for implementing continuous monitoring strategie
- NIST SP 800-115: titled "Technical Guide to Information Security Testing and Assessment," provides guidance on the planning, conducting, analyzing, and documenting information security/penetration testing and assessment activities. (Plan, Discover, Attack, Report _PDAC_)
- NIST SP 800-122: "Guide to Protecting the Confidentiality of Personally Identifiable Information (PII)" - Provides guidelines for protecting the confidentiality of PII.
- NIST SP 800-171: "Protecting Controlled Unclassified Information in Nonfederal Systems and Organizations" - Specifies requirements for protecting controlled unclassified information.

NIST Cybersecurity Framework (CSF): The NIST Cybersecurity Framework consists of standards, guidelines, and best practices to manage cybersecurity risk. It is organized into five core functions: Identify, Protect, Detect, Respond, and Recover.

**Federal Information Processing Standards (FIPS):**

- FIPS 199: "Standards for Security Categorization of Federal Information and Information Systems" - Establishes security categories for information and information systems.
- FIPS 200: "Minimum Security Requirements for Federal Information and Information Systems" - Specifies minimum security requirements for federal information systems.
- FIPS 140-2: "Security Requirements for Cryptographic Modules" - Specifies requirements for cryptographic modules.
- FIPS 140-3: is the successor to FIPS 140-2, providing updated requirements for cryptographic modules

**ISO/IEC 27000 Series:**

- ISO/IEC 27001: "Information Security Management Systems (ISMS) – Requirements" - Specifies the requirements for establishing, implementing, maintaining, and continually improving an information security management system.
- ISO/IEC 27002: "Code of Practice for Information Security Controls" - Provides guidelines and general principles for initiating, implementing, maintaining, and improving information security management in an organization.
- ISO/IEC 27005: "Information Security Risk Management" - Provides guidelines for information security risk management, including risk assessment and treatment.
- ISO/IEC 27017: "Code of Practice for Information Security Controls Based on ISO/IEC 27002 for Cloud Services" - Provides guidelines for information security controls applicable to the provision and use of cloud services.
- ISO/IEC 27018: "Code of Practice for Protection of Personally Identifiable Information (PII) in Public Clouds Acting as PII Processors" - Provides guidelines for the protection of PII in cloud computing environments.
- ISO/IEC 27031: "Guidelines for Information and Communication Technology Readiness for Business Continuity" - Provides guidelines for ICT readiness for business continuity.
- ISO/IEC 27035: "Information Security Incident Management" - Provides guidelines for the management of information security incidents, including planning and response.
- ISO/IEC 27701: "Privacy Information Management System" - Provides guidelines for establishing, implementing, maintaining, and continually improving a Privacy Information Management System (PIMS) based on the requirements of ISO/IEC 27001.

**ISO 31000 Series:**

- ISO 31000: "Risk Management – Guidelines" - Provides principles and generic guidelines on risk management.
- ISO 31010: "Risk Management – Risk Assessment Techniques" - Provides guidance on the selection and application of techniques for assessing risk in a wide range of situations.

**ISO/IEC 20000 Series:**

- ISO/IEC 20000-1: "Information Technology – Service Management – Part 1: Service Management System Requirements" - Specifies requirements for establishing, implementing, maintaining, and continually improving a service management system (SMS).
- ISO/IEC 20000-2: "Information Technology – Service Management – Part 2: Guidance on the Application of Service Management Systems" Provides guidance on the application of an SMS based on ISO/IEC 20000-1.

**SSAE 18:** "Attestation Standards: Clarification and Recodification" - This standard, effective since May 1, 2017, provides guidance on performing and reporting on examination, review, and agreed-upon procedures engagements. It includes guidelines for reports on controls at service organizations, consolidating and clarifying previous standards.
- SOC Reports under SSAE 18:
    - SOC 1 (which focuses on controls at a service organization relevant to user entities’ internal control over financial reporting) and SOC 2 (which controls relevant to security, availability, processing integrity, confidentiality, and privacy) both have Type I (provides an opinion on the operating effectiveness of those controls at a 🔥specific point in time) and Type II (provides opinion on the suitability and effectiveness of security controls after evaluating them over a 🔥specified period of time) reports.
    - SOC 3 does not have separate Type I or Type II reports; it provides a general-purpose report suitable for public distribution.
    - Note📝 There are only two types of SOC report: Type I and Type II. Both reports provide information on the suitability of the design of security controls.

