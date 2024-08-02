[Domain 1](#domain1-top) **Security and Risk Management**

[1.1](#1.1) Understand, adhere to, and promote professional ethics (OSG-9 Chpts 1,19)

- As a CISSP, you must understand and follow the (ISC)² code of ethics, as well as your organization’s own code
- 1.1.1 (ISC)² Code of Professional Ethics
  - (ISC)² Code of Professional Ethics -- take the time to read the [code of ethics](www.isc2.org/Ethics)
  - At a minimum, know and understand the ethics canons:
    - **I: Protect society, the common good, necessary public trust and confidence, and the infrastructure**
      - this is “do the right thing”; put the common good ahead of yourself 
      - ensure that the public can have faith in your infrastructure and security
    - **II: Act honorably, honestly, justly, responsibly, and legally**
      - always follow the laws 
      - but if you find yourself working on a project where conflicting laws from different countries or jurisdictions apply, you should prioritize the local jurisdiction from which you are performing the services
      - Treat all members fairly. In resolving conflicts, consider public safety and duties to principals, individuals and the profession in that order.
    - **III: Provide diligent and competent service to principles** 
      - avoid passing yourself as an expert or as qualified in areas that you aren’t 
      - maintain and expand your skills to provide competent services
    - **IV: Advance and protect the profession**
      - don’t bring negative publicity to the profession 
      - provide competent services, get training and act honorably 
      - think of it like this: If you follow the first three canons in the code
  of ethics, you automatically comply with this one
- 1.1.2 Organizational code of ethics
  - You must also support ethics at your organization; this can be interpreted to mean evangelizing ethics throughout the organization, providing documentation and training around ethics, or looking for ways to enhance the existing organizational ethics 
    - some organizations might have slightly different ethics than others, so be sure to familiarize yourself with your org’s ethics and guidelines

   - **Code of Ethics Complaints**: (ISC)2 members who encounter a potential violation of the Code of Ethics may report the
possible violation to (ISC)2 for investigation by filing a formal ethics complaint, identifying the specific canon of the Code of Ethics that the member believes has been violated. Complaints under the Code of Ethics must be in writing and in the form of a sworn affidavit. Furthermore, complaints are only accepted from those who believe they have been injured by the alleged behavior. This personal injury provides standing to file a complaint and is determined based on the canon involved:
  - Any member of the general public may file a complaint involving canons I or II.
  - Only an employer or someone with a contracting relationship with the individual may file a complaint under canon III.
  - Other professionals may file a complaint under canon IV. It is important to note that this is not limited to cybersecurity professionals. Anyone who is certified or licensed as a professional and subscribes to a code of ethics as part of that licensure or certification is eligible to file a canon IV complaint.

- **Ten Commandments of Computer Ethics**: The Computer Ethics Institute created its own code of ethics (http://cpsr.org/issues/ethics/cei). The Ten Commandments of Computer Ethics are as follows:
     - 1. Thou shalt not use a computer to harm other people.
       2. Thou shalt not interfere with other people’s computer work.
       3. Thou shalt not snoop around in other people’s computer files.
       4. Thou shalt not use a computer to steal.
       5. Thou shalt not use a computer to bear false witness.
       6. Thou shalt not copy proprietary software for which you have not paid.
       7. Thou shalt not use other people’s computer resources without authorization or proper compensation.
       8. Thou shalt not appropriate other people’s intellectual output.
       9. Thou shalt think about the social consequences of the program you are writing or the system you are designing.
       10. Thou shalt always use a computer in ways that ensure consideration and respect for your fellow humans.

[1.2](#1.2) Understand and apply security concepts (OSG-9 Chpt 1)
- 1.2.1 Confidentiality, integrity, and availability, authenticity and nonrepudiation (5 Pillars)
  - **Confidentiality**:
    - Concept of measures used to ensure the protection of the secrecy of data, objects, and resources
    - is the duty to ensure privacy. It focuses on data
    - It is a legal obligation in regulatory scenarios and a due care obligation in U.S law
    - Confidentiality protections prevent disclosure while protecting authorized access
    - Preserving authorized restrictions on information access and disclosure, including the means for protecting personal privacy and prioprietary information
    - Sensitive data, including personally identifiable information (PII) must be kept confidential; confidentiality is different from secrecy
    - Preserving confidentiality means protecting an asset or data, even if it's not a secret
  
  - **Integrity**:
    - Concept of protecting the reliability and correctness of data; guarding against improper info modification/destruction; includes ensuring non-repudiation and authenticity
    - Integrity protection prevents unauthorized alterations of data
    - Preventing unauthorized subjects from making modifications
    - Preventing authorized subjects from making unauthorized modifications, such as mistakes
    - Maintaining the internal and external consistency of objects

  - **Availability**:
    - Authorized subjects are granted timely and uninterrupted access to objects
    - To ensure high availability of services and data, use techniques like failover clustering, site resiliency, automatic failover, load balancing, redundancy of hardware and software components, and fault tolerance

  - **Authenticity**: ensuring a transmission, message or sender is legitimate (Proof of Origin)   
    - See the NIST glossary for examples: https://csrc.nist.gov/glossary/term/authenticity

  - **Nonrepudiation**: 
    - Ensures that the subject of activity or who caused an event cannot deny that the event occurred
    - Nonrepudiation is made possible through identification, authentication, authorization, accountability, and auditing

  - **AAA Services**:
    - Identification: claiming to be an identity when attempting to access a secured area or system
    - Authentication: proving that you are that claimed identity via one or more factors (something you have, something you know, something you are)
    - Authorization: defining the needed resources, permissions (i.e. allow/grant and/or deny) to a resource, and object access for a specific identity or subject
    - Auditing: recording a log of the events and activities related to the system and subjects
    - Accounting: (aka accountability) access control process which records info about attempts by all entities to access resources; reviewing log files to check for compliance and violations in order to hold subjects accountable for their actions, especially violations of organizational security policy
 
[1.3](#1.3) Evaluate and apply security governance principles (OSG-9 Chpt 1)
 
- **Security governance**: the collection of policies, roles, processes/practices used to make security decisions in an org; related to supporting, evaluating, defining, and directing the security efforts of an org 
  - Security governance is the implementation of a security solution and a management method that are tightly interconnected
  - Security governance seeks to compare the security processes and infrastructure used within the organization with knowledge and insight obtained from external sources.
  - There are numerous security frameworks and governance guidelines, including the National Institute of Standards and Technology (NIST) SP 800-53 and SP 800-100
- **The security function**: the aspect of operating a business that focuses on the task of evaluating and improving security over time 
  - To manage security, an org must implement proper and sufficient security governance
  - The act of performing a risk assessment to drive the security policy is the clearest and most direct example of management of the security function
- **Third-party governance**: external entity oversight that may be mandated by law, regulation, industry standards, contractual obligation, or licensing requirement; outside investigator or auditors are often involved
- 1.3.1 Alignment of security function to business strategy, goals, mission, and objectives
  - **Security Management Planning**: ensures proper creation/implementation/enforcment of a security policy, and alignment with org strategy, goals, mission, and objectives
  - **Strategic Plan**: a strategic plan is a long-term plan (useful for 5 years); it defines the org's security purpose 
    - A strategic plan should include risk assessment
  - **Tactical Plan**: mid-term plan (1 year or less) developed to provide more details on accomplishing the goals set forth in the strategic plan or can be crafted ad hoc based on unpredicted events
  - **Operational Plan**: a short-term, highly detailed plan based on strategic or tactical plans 
    - Strategy, goals, missions,and objectives — support each other in a heirarchy
    - **Objectives**: are closest to the ground-level and represent small efforts to help you achieve a mission 
    - **Missions**: represent a collection of objectives, and one or more missions lead to goals; when you reach your goals, you are achieving the strategy
  - A security framework must closely tie to mission and objectives, enabling the business to complete its objectives and advance the mission while securing the environment based on risk tolerance
- 1.3.2 Organizational processes (e.g., acquistions, divestitures, governance committees)
  - Security governance should address every aspect of an org, including organizational processes of acquisitions, divestitures, and governance
  - Be aware of the risks in acquisitions (since the state of the IT environment to be integrated is unknown, due diligence is key) and divestitures (how to split the IT infrastructure and what to do with identities and credentials)
  - Acquisitions and mergers place an organization at an increased level of risk. Such risks include inappropriate information disclosure, data loss, downtime, and failure to achieve sufficient return on investment (ROI)
  - Understand the value of governance committees (vendor governance, project governance, architecture governance, etc.)
  - Executives, managers and appointed individuals meet to review architecture, projects and incidents (security or otherwise),and provide approvals for new strategies or directions 
    - The goal is a fresh set of eyes, often eyes that are not purely focused on information security
  - When evaluating a third-party for your security integration, consider the following:
    - on-site assessment
    - document exchange and review
    - process/policy review
    - third-party audit
- 1.3.3 Organizational Roles and Responsibilities
  -  Senior Manager: has a responsibility for organizational security and to maximize profits and shareholder value
  - Security Professional: has the functional responsibility for security, including writing the security policy and implementing it
  - Asset Owner: responsible for classifying information for placement or protection within the security solution
  - Custodian: responsible for the task of implementing the proscribed protection defined by the security policy and senior management
  - Auditor: responsible for reviewing and verifying that the security policy is properly implemented
- 1.3.4 Security control frameworks **Focuses on the HOW**
  - A **security control framework**: It is a prescriptive set of cybersecurity safeguards and best practices to protect an organizations assets. It helps in implementing risk managment strategy. outlines the org's approach to security, including a list of specific security processes, procedures, and solutions used; it is important in planning the structure of an org's security solution; many frameworks to choose from, such as:
    -  **Control Objectives for Information Technology (COBIT)** ("moderately referenced" on the exam)
        - COBIT is a documented set of best IT security practices by ISACA
        - Six key principles (Sally Has Daring Goals To Excel SHDGTE) :
          - provide stakeholder value
          - holistic approach
          - dynamic governance system
          - governance distinct from management
          - tailored to enterprise needs
          - end-to-end governance system   
    -  ISO 27000 series (27000, 27001, 27002, etc.).
          - 15408 evaluation Criteria
          - 22301  security and resilience
          - **27001 (Focuses on WHAT and WHY)** information security standards/controls: Outlines a framework for implementing, maintaining and continually improving ISMS Information Security Management System (ISMS is a set of policies, processes and controls that helps organization protect thier information assets). ISO 27001 Guides organizations in identifying assets and assessing thier values and information risks AND implementing mitigating security controls based on ISO 27002. CLoud platforms all have ISO 27001.
          - **27002 (Focuses on HOW)** information security guidance: Offers best practices and ontrol objectives related to key aspects of cybersecurity in support of ISO/IEC 27001. Focuses on cryptography, human resource security, operational security, and incident response. Serves as an official blueprint for orgs aiming to effectively safeguard information assets from cyber threats.
          - 27031 Business continuity    
    -  **SABSA (Sheerwood Applied Business Security Architecture):**  is a framework and methodology for developing risk-driven enterprise information security architectures. It integrates security into the business processes and aligns security measures with business goals. provides a structured method for designing, implementing and managing security architectures.
    -  It provides a holistic, business-­driven approach to security architecture, encompassing everything from assessing business requirements to implementation and metrics.
    -  It is recognized for its comprehensive life cycle approach to security architecture, from assessing business requirements to establishing a “chain of traceability” through strategy, concept, design, implementation, and metrics stages
    -  SABSA Lifecycle Phases:
        - Strategy Phase: Understanding business context and defining security goals.
        - Design Phase: Developing the detailed architecture.
        - Implementation Phase: Deploying the security solutions.
        - Management Phase: Ongoing management and adaptation of the security architecture.  
    -  **FedRAMP (Federal Risk and Authorization Managment Programme)** regulates cloud security for US Gov. FedRAMP specifies a set of security controls based on NIST SP 800-53. It provides a standardized approach to security assessment, authorization, and continuous monitoring for cloud products and services.
    -  FIPS 140-3 Security requirement for cryptographic modules
    -  NIST
          - 800-37 Risk Managment Framework
          - 800-47 Certification and Acreditation
          - 800-92 Log Management
          - 800-162 Guide to ABAC
          - 800-53 Cybersecurity Framework
          - 800-53A is titled “Assessing Security and Privacy Controls in Federal Information Systems and Organizations: Building Effective Assessment Plans
          - 800-12 is an introduction to computer security
          - 800-34 covers contingency planning
          - 800-86 is the “Guide to Integrating Forensic Techniques into Incident Response.”
    -  NIST **CyberSecurity Framework (CSF)**
        - designed for commerical orgs and critical infrastructure, CSF 1.1 consists of five functions:
          - identify
          - protect
          - detect
          - respond
          - recovery
        - note: updated (2024) CSF 2.0 functions 800-53: (Great Ideas Propel Dreams Rapidly, Right GIPDRR)
          - govern
          - identify
          - protect
          - detect
          - respond
          - recover
- 1.3.5 Due care/due diligence
  - **Due diligence**: establishing a plan, policy, and process to protect the interests of the organization; due diligence is about understanding your security governance principles (policies and procedures) and the risks to your organization; actions taken by a vendor to demonstrate or provide due care
    - Due diligence often involves:
      - gathering information through discovery, risk assessments and review of existing documentation 
      - developing a formalized security structure containing a security policy, standards, baselines guidlines, and procedures 
      - documentation to establish written policies
      - disseminating the information to the organization
      - Due diligence is knowing what should be done and planning for it.
      - Due diligence is developing a formalized security structure containing a security policy, standards, baselines, guidelines, and procedures.
  - **Due care**: practicing the individual activities that maintain the due diligence effort; due care is about your legal responsibility within the law or within org policies to implement your org’s controls, follow security policies, do the right thing and make reasonable choices
  - Security documentation is the security policy
  - Due care is doing the right action at the right time.
  - exercise reasonable security measures to protect assets
  - Due care is the continued application of a security structure onto the IT infrastructure of an organization.
  - After establishing a framework for governance, security awareness training should be implemented, including all new hires, who complete the security awareness training as they come on board, and existing employees who should recertify regularly (typically yearly)
  - ***The Prudent Man Rule*** requires that a fiduciary, such as a senior executives and trustee, act with the care, skill, prudence, and diligence that a prudent person acting in a like capacity would use. FOrmalised by the Federal Sentencing Guidelines released in 1991 provided punishment guidelines to help federal judges interpret computer crime laws.


[1.4](#1.4) Determine compliance and other requirements (OSG-9 Chpt 4)
- 1.4.1 Contractual, legal, industry standards, and regulatory requirements
  - Understand the difference between criminal, civil, and administrative law.
    - **Criminal law**: protects society against acts that violate the basic principles we believe in; violations of criminal law are prosecuted by federal and state governments
    - **Civil law**: provides the framework for the transaction of business between people and organizations; violations of civil law are brought to the court and argued by the two affected parties
    - **Administrative law**: used by government agencies to effectively carry out their day-to-day business
    	- Administrative laws do not require an act of the legislative branch to implement at the federal level. Administrative laws consist of the policies, procedures, and regulations promulgated by agencies of the executive branch of government. Although they do not require an act of Congress, these laws are subject to judicial review and must comply with criminal and civil laws enacted by the legislative branch. 
  - **Compliance**: Organizations may find themselves subject to a wide variety of laws, and regulations imposed by regulatory agencies or contractual obligation
    - **Payment Card Industry Data Security Standard (PCI DSS)** - governs the security of credit card information and is enforced through the terms of a merchant agreement between a business that accepts CC payments, and the bank that processes the business' transactions
    - **Sarbanes-Oxley (SOX)** - financial systems may be audited to ensure security controls are sufficient to ensure compliance with SOX. It protects investors.  required publicly traded companies to implement a wide range of controls intended to minimize conflicts of interest, provide investors with appropriate risk information, place civil and criminal penalties on executives for providing false financial disclosures, and provide protections for whistleblowers who report inappropriate actions to regulators.
    - **Gramm-Leach-Bliley Act (GLBA)** - affects banks, insurance companies, and credit providers; included a number of limitations on the types of information that could be exchanged even among subsidiaries of the same corp, and required financial institutions to provide written privacy policies to all their customers
    - **Health Insurance Portability and Accountability Act (HIPAA)** - privacy and security regulations requiring strict security measures for hospitals, physicians, insurance companies, and other organizations that process or store private medical information about individuals; also clearly defines the rights of individuals who are the subject of medical records and requires organizations that maintain such records to disclose these rights in writing
    - Organizations subject to HIPAA may enter into relationships with service providers as long as the provider’s use of protected health information is regulated under a formal business associate agreement (BAA). The BAA makes the service provider liable under HIPAA.
    - **Federal Information Security Management Act (FISMA)** - ) includes provisions regulating information security at federal agencies. Requires federal agencies to implement an information security program that covers the agency's operations and contractors
    - **Computer Fraud and Abuse Act (CFAA)** (as amended) - protects computers used by the government or in interstate commerce from a variety of abuses
    - **ITIL**  British Government standard that describes IT service managment and the structured fitting of security into an organization. It focuses on change management, configuration management and SLAs. Helps information technology (IT) organizations with reducing cost, mitigating risk, and improving customer service.
    - **Electronic Communications Privacy Act (ECPA)** - passed in 1986 to expand and revise federal wiretapping and electronic eavesdropping provisions, making it a crime to intercept or procure electronic communications, and includes important provisions that protect a person’s wire and electronic communications from being intercepted by another private individual
    - **Personal Information Protection Law (PIPL)**: effective since 2021 aims to establish a comprehensive framework for the protection of personal information in China
    - **Protection of Personal Information Act (POPIA)**: enacted in 2013, establishes regulatios for the responsible processing of personal information by both public and private entities in South Africa.
    - The **Privacy Act of 1974** limits the ways government agencies may use information that private citizens disclose to them under certain circumstances. The Privacy Act regulates what information government agencies may collect and maintain about individuals.
    - **The Lanham Act** regulates the issuance of trademarks to protect intellectual property.
    - **Digital Millennium Copyright Act** - prohibits the circumvention of copyright protection mechanisms placed in digital media and limits the liability of internet service providers for the activities of their users
    - **The Wassenaar Arrangement** on Export Controls for Conventional Arms and Dual-Use Goods and Technologies is a multilateral export control regime established on 12 July 1996, in Wassenaar, near The Hague, Netherlands. According to the Wassenaar Arrangement document, it was "established to contribute to regional and international security and stability by promoting transparency and greater responsibility in transfers of conventional arms and dual-use goods and technologies, thus preventing destabilizing accumulations. Participating states seek, through their national policies, to ensure that transfers of these items do not contribute to the development or enhancement of military capabilities which undermine these goals, and are not diverted to support such capabilities. It also addresses cyber weapons, including malicious software, Command and Control (C2) software, and internet surveillance software.
    - **Information Assurance Technical Framework (IATF)** The IATF is a framework developed by the International Organization for Standardization (ISO) to provide guidelines for assessing the security and privacy aspects of information technology systems provides and technical guidance for protecting the information infrastructures of the United States U.S. Government and industry. It covers various areas such as risk management, security controls, and data privacy. The four major technology focus areas of the Defense-in-Depth Strategy are to Defend the Network and Infrastructure, Defend the Enclave Boundary, Defend the Computing Environment, and Defend Supporting Infrastructures. 
- 1.4.2 Privacy requirements
    - European Union's **General Data Protection Regulation (GDPR)** - replaced Data Protection Directive (DPD), purpose is to provide a single, harmonized law that covers data throughout the EU
      - Lawfulness, fairness, and transparency
      - Purpose Limitation
      - Data Minimization
      - Accuracy
      - Storage Limitation
      - Security
      - Accountability
    - California Consumer Privacy Act (CCPA)
    - Be familiar with the EU Data Protection Directive
    - Be familiar with the requirements around healthcare data, credit card data and other PII data as it relates to various countries and their laws and regulations
    - The European Union provides **standard contractual clauses** that may be used to facilitate data transfer. That would be the best choice in a case where two different companies e.g one in Europe and one in the United States are sharing data.
    - If the data were being shared internally within a company, **binding corporate rules** would also be an option

[1.5](#1.5) Understand legal and regulatory issues that pertain to information security in a holistic context (OSG-9 Chpt 4)
- 1.5.1 Cybercrimes and data breaches
  - Understand the notification requirements placed on organizations that experience a data breach
  - California's SB 1386 implemented the first statewide requirement to notify individuals of a breach of their personnel information; all other states eventually followed suit with similar laws
  - Currently, federal law only requires notification of individuals when a HIPAA-covered entity breaches their protected health information (likely to soon change)
  - Before an org expands to other countries, perform due diligence to understand legal systems and what changes might be required to the way that data is handled and secured
  - In particular, be familiar with:
    - **Council of Europe Convention on Cybercrime**: a treaty signed by many countries that establishes standards for cybercrime policy 
    - Laws about data breaches, including notification requirements
    - In the US, the **Health Information Technology for Economic and Clinical Health (HITECH)** Act requires notification of a data breach in some cases, such as when the personal health information was not protected as required by HIPAA
    - **GLBA (Gramm-Leach-Bliley Act)****** applies to insurance and financial orgs, requiring notification to federal regulators, law enforcement agencies and customers when a data breach occurs 
    - Certain states also impose their own requirements concerning data breaches 
    - the EU and other countries have their own requirements, for instance, the GDPR has very strict data breach notification requirements: A data breach must be reported to the competent supervisory authority within 72 hours of its discovery
    - Some countries do not have any reporting requirements
- 1.5.2 Licensing and intellectual property (IP) requirements
  - **Intellectual property**: intangible assets (e.g. software, data)
  - **Trademarks**: words, slogans, and logos used to identify a company and its products or services.
  - **Patents**: a temporary monopoly for producing a specific item such as a toy, which must be novel and unique to qualify for a patent. Patents have expiration date. U.S. patent law provides for an exclusivity period of 20 years beginning at the time a utility patent application is submitted to the Patent and Trademark Office.
    - **Utility**: protect the intellectual property rights of inventors
    - **Design**: cover the appearance of an invention and last for 15 years; note design patents on't protect the idea of an invention only its form, and are generally seen as weaker
    - Software: area of on-going controversy; Google vs Oracle; given to rise of "patent trolls"
  - **Copyright**: exclusive use of artistic, musical or literary works which prevents unauthorized duplication, distribution or modification. Also can include software code published in academic journal. Copyright and patent protection both have expiration dates. Copyright protection generally lasts for 70 years after the death of the last surviving author of the work
  - **Licensing**: a contract between the software producer and the consumer which limits the use and/or distribution of the software
  - **Trade Secrets**: intellectual property that is critical to a business, and significant damage would result if it were disclosed to competitors or the public
  - When you file application for protection, until registration is granted, you can use the **TM** symbol to inform others that it is protected under trademark law. Once the application is approved, the name becomes a registered trademark, and
you can begin using the **®** symbol. The **©** symbol is used to represent a copyright.
- 1.5.3 Import/export controls
  -  Every country has laws around the import and export of hardware and software; e.g. the US has restrictions around the export of cryptographic technology, and Russia requires a license to import encryption technologies manufactured outside the country
  -  The _Bureau of Industry and Security_ within the Department of Commerce sets regulations on the export of encryption products outside of the United States.
- 1.5.4 Transborder data flow
  -  Orgs should adhere to origin country-specific laws and regulations, regardless of where data resides
  -  Also be aware of applicable laws where data is stored and systems are used
- 1.5.5 Privacy: Right of an individual to have control over how their info is collected & used/disclosed
  - Many laws include privacy protections for personal data 
    - The EU’s GDPR has strong privacy rules that apply to any org anywhere that stores or processes the personal data of EU residents; these individuals must be told how their data is collected and used, and they must be able to opt out 
  - The privacy guidelines of the **Organization for Economic Co-operation and Development (OECD)** require orgs to avoid unjustified obstacles to trans-border data flow, set limits to personal data collection, protect personal data with reasonable security and more
       - The OECD Privacy Guidelines on the Protection of Privacy and Transborder Flows of Personal Data, provide a framework for the protection of personal information and the management of data flows across borders.
       - First adopted in 1980 and revised in 2013. They key principles are
       - 1. Collection Limitation: Organizations should collect only the data that is needed for their purposes and should do so fairly and lawfully.
         2. Data Quality: Organizations should ensure that personal data is relevant and accurate, and should update it as necessary to maintain its quality.
         3. Purpose Specification: Organizations must clearly state the purposes for data collection and use, and any subsequent use should be consistent with these purposes.
         4. Use Limitation: Data should be used only for the purposes for which it was collected, and any new use should require additional consent or legal justification.
         5. Security Safeguards: Organizations should implement appropriate security measures to protect personal data from unauthorized access and misuse.
         6. Openness: Organizations should be transparent about their data collection and processing practices, and individuals should be informed about these practices.
         7. Individual Participation: Data subjects should have the right to access their personal data, request corrections, and ensure that their data is accurate and up-to-date.
         8. Accountability: Organizations should ensure compliance with the guidelines and be able to demonstrate their adherence to these principles. 
  - **Fourth Amendment** to the US Constitution: the right of the people to be secure in their persons, houses, papers, effects against unreasonable search and seizure
  - It sets the “probable cause” standard that law enforcement officers must follow when conducting searches and/or seizures of private property. It also states that those officers must obtain a warrant before gaining involuntary access to such property. 
  - **Electronic Communication Privacy Act (ECPA)**: as amended, protects wire, oral, and electronic communications while those communications are being made, are in transit, and when they are stored on computers; makes it a crime to invade electronic privacy of an individual, and it broadened the Federal Wiretap Act
  - HIPAA: see above
  - HITECH: see above
  - California SB 1386 (2002): immediate disclosure to individuals for PII breach
  - **California Consumer Privacy Act (CCPA)**: The CCPA applies to: 
    - For-profit businesses that collect consumers’ personal information (or have others collect personal information for them),
    - was the first sweeping data privacy law enacted by a U.S. state.
    - Determine why and how the information will be processed, 
    - Do business in California and meet any of the following: 
      - have a gross annual revenue > $25 million;
      - buy, sell, or share the personal information of 100k or more California residents or households; or
      - get 50% or more of their annual revenue from selling or sharing California residents’ personal information
    - The CCPA imposes separate obligations on service providers and contractors (who contract with businesses to process personal info) and other recipients of personal information from businesses
    - The CCPA does not generally apply to nonprofit orgs or government agencies
    - California residents have the right to:
      - (L)imit use and disclosure of personal info
      - (O)pt-out of sale or cross-context advertising
      - (C)orrect inaccurate info
      - (K)now what personal info business have and share
      - (E)qual treatment / nondiscrimination
      - (D)elete info business have on them

  - **Children's Online Privacy Protection Act (COPPA)** of 1998:
    - COPPA makes a series of demands on websites that cater to children or knowingly collect information from children:
      - Websites must have a privacy notice that clearly states the types of info they collect and what it's used for (including whether infor is disclosed to third parties); must also include contact infor for site operators
      - Parents must be able to review any info collected from children and permanently delete it from the site's records
      - Parents must give verifiable consent to the collection of info about children younger than the age of 13 prior to any such collection
  - GLBA: see above
  - US Patriot Act of 2002: enacted following the September 11 attacks with the stated goal of tightening U.S. national security, particularly as it related to foreign terrorism
    - The act included three main provisions:
      - expanded surveillance abilities of law enforcement, including by tapping domestic and international phones
      - easier interagency communication to allow federal agencies to more effectively use all available resources in counterterrorism efforts
      - increased penalties for terrorism crimes and an expanded list of activities which would qualify for terrorism charges
  - **Family Education Rights and Privacy Act (FERPA)**: Grants privacy rights to students over 18, and the parents of minor students
  - EU's Data Protection Directive (DPD): see above
  - EU's General Data Protection Regulation (GDPR): key provisions
    - lawfulness, fairness, and transparency
    - purpose limitation
    - data minimization
    - accuracy
    - storage limitation
    - security
    - accountability
  - The EU-US **Privacy Shield** (formerly the EU-US Safe Harbor agreement): controls data flow from the EU to the United States; the EU has more stringent privacy protections and without the Privacy Shield, personal data flow from the EU to the United States would not be allowed. It is no longer valid
  - **The Communications Assistance for Law Enforcement Act (CALEA)** required that communications carriers assist law enforcement with the implementation of wiretaps when done under an appropriate court order. CALEA only applies to communications carriers
  - **Privacy Impact Assesment (PIA)**: is designed to identify the privacy data being collected, processed or stored by a system, and assess the effects of a data breach. Several privacy laws require PIA as a planning tool for identifying and implementing required privacy controls including GDPR and HIPPA
  - Conducting a PIA typically begins when a system or process is being evaluated.
  - Evolving privacy regulations neccessitates assessment of existing systems
  - PIA involves defining assessment scope, data collection methods and plan for data retention
  - Internation Association of Privacy Professionals (IAPP) publishes guids and resources related to privacy efforts including PIA

- **Geographic Considerations**: Different laws and regulations may apply depending on the location (data residency) of the
 - data subject
 - data collector
 - cloud service provider
 - subcontractors processing the data
 - company headquaters of the entities involved
 - Legal concerns can 
  - prevent the utilization of a cloud service provider
  - add to costs and time to market
  - can drive changes to technical architectures required to deliver services
  - Never replace complaince with convinience when evaluating services as this increases risk
 - Conflicting internation legislation: Example GDPR forbids the transfer of data to countries that lack adequate privacy protections. and the **Clarifying Lawful Overseas Use of Data (CLOUD) Act** requires cloud service proviproviders to hand over data to aid in investigation of serious crimes, even if stored in another country.
  - Situations like this requires collaboration and legal counsel
  - Cloud practitioners must be aware of multiple sets of laws and regulations and the risk introduced by conflicting legislation across geography and jurisdiction e.g copyright and intellectual property laws, data residency and safeguards for required for privacy compliance, data breaches and data breach notifications, internation import/export laws

- **Cyber Kill/Attack Chain** a seven-steps to identify and stop attacks: (RWDEICA Reckless Wizards Delve Eagerly Into Crytic Arcanum)
  - Stage I: Reconnaisance
  - Stage II: Weaponization
  - Stage III: Delivery
  - Stage IV: Exploit
  - Stage V: Installation
  - Stage VI: Command and Control (C&C)
  - Stage VII: Actions

[1.6](#1.6) Understand requirements for investigation types (i.e., administrative, criminal, civil, regulatory, industry standards) (OSG-9 Chpt 19)

- An investigation will vary based on incident type; e.g. for a financial services company, a financial system compromise might cause a regulatory investigation; a system breach or website compromise might cause a criminal investigation; each type of investigation has special considerations:
  - **Administrative**: an administrative investigation has a primary purpose of providing the appropriate authorities with incident information; thereafter, authorities will determine the proper action, if any 
    - Administrative investigations are often tied to HR scenarios, such as when a manager has been accused of improprieties
  - **Criminal**: a criminal investigation occurs when a crime has been committed and you are working with a law enforcement agency to convict the alleged perpetrator; in such a case, it is common to gather evidence for a court of law, and to share the evidence with the defense
    - You need to gather and handle the information using methods that ensure the evidence can be used in court
    - In a criminal case, a suspect must be proven guilty beyond a reasonable doubt; a higher bar compared to a civil case, which is showing a preponderance of evidence
  - **Civil**: in a civil case, one person or entity sues another; e.g. one company could sue another for a trademark violation 
    - A civil case is typically about monetary damages, and doesn't involve criminality
    - In a civil case, a preponderance of evidence is required to secure a victory; differing from criminal cases, where a suspect is innocent until proven guilty beyond a reasonable doubt
  - **Industry Standards**: an industry standards investigation is intended to determine whether an org is adhering to a specific industry standard or set of standards, such as logging and auditing failed logon attempts 
    - Because industry standards represent well-understood and widely implemented best practices, many orgs try to adhere to them even when they are not required to do so in order to improve security, and reduce operational and other risks
  - **Regulatory**: A regulatory investigation is conducted by a regulatory body, such as the Securities and Exchange Commission (SEC) or Financial Industry Regulatory Authority (FINRA), against an org suspected of an infraction 
    - Here the org is required to comply with the investigation, e.g., by not hiding or destroying evidence

[1.7](#1.7) Develop, document, and implement security policy, standards, procedures and guidelines (OSG-9 Chpt 1)
- The top tier of a formalized hierarchical organization security documentation is the security policy
  - **Policy**: docs created by and published by senior management describing organizational strategic goals
  - A security policy is a document that defines the scope of security needed by the org, discussing assets that require protection and the extent to which security solutions should go to provide the necessary protections
  - Policies are high-level documents, usually written by the management team; policies are mandatory, and a policy might provide requirements, but not the steps for implementation
    - A policy is a document that defines the scope of security needed by the organization and discusses the assets that require protection and the extent to which security solutions should go to provide the necessary protection.
  - It defines the strategic security objectives, vision, and goals and outlines the security framework of the organization
- **Acceptable User Policy**: the AUP is a commonly produced document that exists as part of the overall security documentation infrastructure 
  - This policy defines a level of acceptable performance and expectation of behavior and activity; failure to comply with the policy may result in job action warnings, penalties, or termination

- Security Standards, Baselines and Guidelines: once the main security policies are set, the remaining security docuemntation can be crafted from these policies
  - **Standards**: specific mandates explicity stating expections of performance/conformance; more descriptive than policies, standards define compulsary requirements for the homogenous use of hardware, software, technology, and security controls, uniformly implemented throughout the org. It could be internal or external.
    - A standard defines compulsory requirements for the homogenous use of hardware, software, technology, and security controls. 
  - **Baseline**: defines a minimum level of security that every system throughout the organization must meet; baselines are usually system specific and refer to industry / government standards. It is often related to configuration. 
    - e.g. a baseline for  server builds would be a list of configuration areas that should be applied to every server that is built 
    - A Group Policy Object (GPO) in a Windows network is sometimes used to comply with standards; configuration management solutions can also help you establish baselines and spot configurations that are not in alignment
  - **Guideline**: offers recommendations on how standards and baselines and other security requirements should be implemented & serves as an operational guide for security professionals and users 
    - Guidelines are flexible, and can be customized for unique systems or conditions; they state which security mechanism should be deployed instead of prescribing a specific product or control; they are not complusory; suggested practices and expectations of activity to best accomplish tasks and goals
    - **Framework** are a set of guidlines
  - **Procedure** (AKA Standard Operating Procedure or SOP): detailed, step-by-step how-to doc that describes the exact actions necessary to implement a specific security mechanism, control, or solution
  - **Laws** Legal rules created by government entities e.g legislature. Must be followed or can result in civil or criminal penalties
  - **Regulations** rules created by governmental agencies. Must be followed or can result in civil or criminal penalties

[1.7.2](#1.7.2) External Dependencies (New in 2024)
Factors, entities or conditions outside the organisation upon which the organisations business continutiy plans and operation resilience may depend. EG suppliers, vendors, utilities, transportation. Do not rely on one supply that may be affected by the same disaster.

[1.8](#1.8) Identify, analyze, and prioritize Business Continuity (BC) requirements (OSG-9 Chpt 3)

- **Business Continuity Planning (BCP)**: involves assessing the risk to organizational processes and creating policies, plans, and procedures to minimize the impact those risks might have on the organization if they were to occur
  - BCP is used to maintain the continuous operation of a business in the event of an emergency, with a goal to implement a combination of policies, procedures, and processes
  - Business continuity requires a lot of planning and preparation; actual implementation of business continuity processes occur quite infrequently
  - business organization analysis is the first step of the process, and the results are used to aid in the selection of team members and the design of the BCP process.
  - The primary facets of business continuity are:
    - Resilience: (e.g. within a data center and between sites or data centers) 
    - Recovery: if a service becomes unavailable, you need to recover it as soon as possible
    - Contingency: a last resort in case resilience and recovery prove ineffective

- BCP vs DR: 
  - BCP activities are typically strategically focused at a high level and center themselves on business processes and operations
  - DR plans tend to be more tactical and describe technical activities such as recovery sites, backups, and fault tolerance. It ensures sufficient technical controls in place to recover operations after a disruption

- The overall goal of BCP is to provide a quick, calm, and efficient response in the event of an emergency and to enhance a company's ability to quickly recover from a distruptive event

- 1.8.2 Develop and document the scope and the plan
  - The BCP process has four main steps (Project scope and planning, Business Impact Analysis, Continuity planning, and Approval and implementation):
    - **Project scope and planning**: Developing the project scope and plan starts with gaining support of the management team, making a business case (cost/benefit analysis, regulatory or compliance reasons etc.) and gaining approval to move forward. 
      - Next, you need to form a team with representatives from the business as well as IT
      - Next, start with a business continuity policy statement, then conduct a business impact analysis (see next item), and then develop the remaining components: 
        - preventive controls
        - relocation
        - the actual continuity plan 
        - testing
        - training and maintenance
- 1.8.1 Business Impact Analysis (BIA)
    - **Business impact analysis (BIA)**: Identify the systems and services that the business relies on and assess the impacts that a disruption or outage would cause, including the impacts on business processes like accounts receivable and sales 
      - Also decide which systems and services you need to get things running again (think foundational IT services such as the network and directory, which many other systems rely on)
      - The “business impact” asset valuation method involves evaluating the potential impact on the organization’s operations, reputation, or bottom line if the asset is compromised. The other options correspond to different asset valuation methods: “✏️financial value,” “✏️market value,” and “✏️intangible value,” respectively.
      - Finally, prioritize the order in which critical systems and services are recovered or brought back online. 
      - As part of the BIA, establish:
        - **Recovery Time Objectives (RTO)** (how long it takes to recover) The maximum acceptable amount of time that a system, application, or function can be down after a failure or disaster.
        - **Recovery Point Objectives (RPO)** (the maximum tolerable data loss/maximum amount of time for which loss of data is acceptable)
        - **Mean time to Failure (MTTF)**: is the expected typical functional lifetime of the device given a specific operating environment.
        - **Mean Time Between Failures (MTBF)** The predicted elapsed time between inherent failures of a system during operation. e.g A server might have an MTBF of 10,000 hours.
        - **Mean Time to Repair (MTTR)** The average time required to repair a failed component or system.
        - **Maximum tolerable downtime (MTD)**, (how long an org can survive an interruption of critical functions) along with the costs of downtime and recovery; AKA MTD (maximum tolerable downtime)
        - Some mitigation actions during BIA include:
        - Hardening systems:  securing systems by reducing their attack surface of vulnerability
        - Defining systems: identifying and describing the various systems within an organization, including their roles, functions, and interdependencies.
        - Reducing systems: Consolidation and removal of complexity
        - Alternative systems: refers to backup systems, redundant systems 
    - **Continuity planning**: The first two phases of the BCP process (project scope and planning and the business impact analysis) focus on determining how the BCP process will work and prioritizing the business assets that need to be protected against interruption
      - The next phase of BCP development, continuity planning, focuses on the development and implementation of a continuity strategy to minimize the impact realized risks might have on protected assets
      - There are two primary subtasks involved in continuity planning:
        - Strategy development
        - Provisions and processes: In the provisions and processes phase, the BCP team also designs the procedures and mechanisms to mitigate risks that were deemed unacceptable during the strategy development phase.
      - The goal of this process is to create a **continuity of operations plan** (COOP), which focuses on how an org will carry out critical business functions starting shortly after a disruption occurs and extending up to one month of sustained operations
    - **Approval and implementation**:
      - BCP plan now needs sr. management buy-in (should be endorsed by the org's top exec)
      - You should strive to have the highest-­ranking person possible sign the BCP’s statement of importance.
      - BCP team should create an implementation schedule, and all personnel involed should receive training on the plan

- The top priority of BCP and DRP is people: **Always prioritize people's safety**; get people out of harm's way, and then address IT recovery and restoration issues

[1.9](#1.9) Contribute to and enforce personnel security policies and procedures (OSG-9 Chpt 2)

- People are often considered the weakest element in any security solution; no matter what physical or logical controls are deployed, humans can discover ways of to avoid them, circumvent/subvert them, or disable them 
  - Malicious actors are routinely targeting users with phishing and spear phishing campaigns, social engineering, and other types of attacks, and everybody is a target
  - Once attackers compromise an account, they can use that entry point to move around the network and elevate their privileges 
  - People can also become a key security asset when they are properly trained and are motivated to protect not only themselves but the security of the organization as well

- 1.9.1 Candidate screening and hiring
  - The following strategies can reduce your risk:
    - **Candidate screening and hiring**: To properly plan for security, you shold have standards in place for job descriptions, job classification, work tasks, job responsibilities, prevention of collusion, candidate screening, background checks, security clearances, employment agreements, and nondisclosure agreements 
      - screening employment candidates thoroughly is a key part of the hiring process
      - be sure to conduct a full background check that includes a criminal records check, job history verification, education verification, certification validation and confirmation of other accolades when possible
      - all references should be contacted
- 1.9.2 Employement agreements and policies
  - **Employment agreement**: specifies job duties, expectations, rate of pay, benefits and info about termination; sometimes, such agreements are for a set period (for example, in a contract or short-term job). 
    - Employment agreements facilitate termination when needed for an underperforming employee 
    - The more info and detail in an employment agreement, the less risk (risk of a wrongful termination lawsuit, for example) the company has during a termination proceeding
    - e.g. a terminated employee might take a copy of their email with them without thinking of it as stealing, but they are less likely to do so if an employment agreement or another policy document clearly prohibits it
    - example employee agreements:
      - non-compete 
      - codes of conduct such as an acceptable use policy (AUP), which defines what is and isn’t acceptable acitivty, practice, or use for company equipemnt and resources
      - nondisclosure agreement (NDA), which is a doc used to protect confidential information from being disclosed by a current or former employee
- 1.9.3 Onboarding, transfers and termination processes   
  - **Onboarding**: process of bringing a new employee into the org
    - creating documented processes allowing the new employee to be intgrated quickly and consistently
  - **Transfer**: an employee moves from one job to another, likely requiring adjusted account access to maintain appropriate least privilege
  - **Termination or offboarding**: offboarding is the removal of an employee's identity from the IAM system, once that person has left the org; can also be an element used when an employee transfers into a new role
    - whether cordial or abrupt, the ex-employee should be escorted off the premises and not allowed to return
- 1.9.4 Vendor, consultant, and contractor agreements and controls
  - Orgs commonly outsource many IT functions, particularly data center hosting, contact-center support, and application development
  - Info security policies and procedures must address outsourcing secuity and the use of service providers, vendors and consultants 
    - e.g. access control, document exchange and review, maintenance, on-site assessment, process and policy review, and Service Level Agreements (SLAs) are examples of outsourcing security considerations
- 1.9.5 Compliance policy requirements
    - **Compliance**: the act of confirming or adhering to rules, policies, regulations, standards, or requirements
      - on a personnel level, compliance is related to individual employees following company policies and procedures
      - employees need to be trained on company standards as defined in the security policy and remain in compliance with any contractual obligations (e.g. with PCI DSS)
    - Compliacne is a form of administrative or managerial security control
    - **Compliance enforcement**: the application of sanctions or consequences for failing to follow policy, training, best practices, or regulations
- 1.9.6 Privacy policy requirements    
    - Personally identifiable information (PII) about employees, partners, contractors, customers and others should be stored in a secure way, accessible only to those who require the information to perform their jobs
    - Orgs should maintain a documented privacy policy outlining the type of data covered by the policy and who the policy applies to 
    - Employees and contractors should be required to read and agree to the privacy policy upon hire and on a regular basis thereafter (such as annually)

[1.10](#1.10) Understand and apply risk management concepts (OSG-9 Chpt 2)
- 1.10.1 Privacy policy requirements
  - **Threats**: any potential occurrence that many cause an undersirable or unwanted outome for a specific asset; they can be intentional or accidental; loosely think of a threat as a weapon that could cause harm to a target
  - **Vulnerability**: the weakness in an asset, or weakness (or absense) of a safeguard or countermeasure; a flaw, limitation, error, frailty, or susceptibility to harm
  - Threats and vulnerabilities are related: a threat is possible when a vulnerability is present
    - Threats exploit vulnerabilities, which results in exposure 
    - Exposure is risk, and risk is mitigated by safeguards 
    - Safeguards protect assets that are endangered by threats
    - **Threat Agent/Actors**: intentionally exploit vulnerabilities
    - **Threat Events**: accidential occurrences and intentinoal exploitations of vulnerabilities
    - **Threat Vectors**: AKA attack vector is the path or means by which an attack or attacker can gain access to a target in order to cause harm
    - **Exposure**: being susceptible to asset loss because of a threat; the potential for harm to occur; quantitative risk analysis value of **exposure factor (EF)** is derived from this concept
    - **Risk**: the possiblity or likelihood that a threat will exploit a vulnerability to cause harm to an asset and the severity of damage that could result; the > the potential harm, the > the risk
- 1.10.1 Risk assessment/analysis
  - **Risk Assessment**: used to identify the risks and set criticality priorities, and then risk response is used to determine the best defense for each identified risk
  - The primary goal of a security risk assessment is to identify and analyze risks and then develop strategies to reduce them to an acceptable level.
  - Risk is threat with a vulnerability
  - Risk = threat * vulnerability (or probability of harm * severity of harm)
  - Addressing either the threat or threat agent or vulnerability directly results in a reduction of risk (known as threat mitigation)
  - All IT systems have risk; all orgs have risk; there is no way to elminiate 100% of all risks. Risk is typically composed of three Components:
  - **🔥Threat** (a potential cause of an incident that may result in harm)
  - **🔥Vulnerability** (a weakness that can be exploited by a threat)
  - **🔥Impact** (the potential harm caused by a threat exploiting a vulnerability)
  - Instead upper management must decide which risks are acceptable, and which are not; There are two primary risk-assessment methodologies:
      - **Quantitative Risk Analysis**: assigns real dollar figures to the loss of an asset and is based on mathematical calculations e.g FAIR (Factor Analysis of Information Risk) is a quantitative risk management framework
      - **Qualitative Risk Analysis**: assigns subjective and intangible values to the loss of an asset and takes into account perspectives, feelings, intuition, preferences, ideas, and gut reactions. It relies on subjective judgments to rank risk.
    - Most orgs employ a hybrid of both risk assessment methodologies
    - The goal of risk assessment is to identify risks (based on asset-threat parings) and rank them in order of criticality

- 1.10.3 Risk response
  - **Risk response**: the formulation of a plan for each identified risk; for a given risk, you have a choice for a possible risk response:
    - **Risk Mitigation**: reducing risk, or risk mitigation, is the implementation of safeguards, security controls, and countermeasures to reduce and/or eliminate vulnerabilities or block threats
    - **Risk Assignment**: assigning or transferring risk is the placement of the responsibility of loss due to a risk onto another entity or organization; AKA assignment of risk and transference of risk
    - **Risk Deterrence**: deterrence is the process of implementing deterrents for would-be violators of security and policy 
      - the goal is to convince a threat agent not to attack; 
      - e.g. implementing auditing, security cameras, and warning banners; using security guards
    - **Risk Avoidance**: determining that the impact or likelihood of a specific risk is too greate to be offset by potential benefits, and not performing a particular business function due to that determiniation; the process of selecting alternate options or activities that have less associated risk than the default, common, expedient, or cheap option
    - **Risk Acceptance**: the result after a cost/benefit analysis determines that countermeasure costs would outweigh the possible cost of loss due to a risk 
      - also means that management has agreed to accept the consequences/loss if the risk is realized
      - For acceptable risks, the documentation should include a rationale for that decision and a list of potential future events that might warrant a reconsideration of that determination. The documentation would not include controls used to mitigate acceptable risks, since acceptable risks do not require mitigation.
    - **Risk Rejection**: an unacceptable possible response to risk is to reject risk or ignore risk; denying that risk exists and hoping that it will never be realized are not valid prudent due care/due diligence responses to risk
    - **Risk Transference**: paying an external party to accept the financial impact of a given risk
  - **Inherent Risk**: the level of natural, native, or default risk that exists in an environment, system, or product prior to any risk management efforts being performed (AKA initial or starting risk); this is the risk identified by the risk assessment process
  - **Residual Risk**: consists of threats to specific assets against which management chooses not to implement (the risk that management has chosen to accept rather than mitigate); risk remaining after security controls have been put in place
  - **Total Risk**: the amount of risk an org would face if no safeguards were implemented
  - **Conceptual Total Risk Formula**: threats * vulnerabilities * asset value = total risk
  - **Controls Gap**: amount of risk that is reduced by implementing safeguards
  - **Conceptual Residual Risk Formula**: total risk - controls gap = residual risk
  - Risk should be reassessed on a periodic basis to maintain reasonable security because security changes over time
- 1.10.4 Countermeasure selection and implementation
  - **Countermeasure**: AKA a "control" or "safeguard" can help reduce risk
    - For exam prep, understand how the concepts are integrated into your environment; this is not a step-by-step technical configuration, but the process of the implementation — where you start, in which order it occurs and how you finish
    - When developing an organization's information security budget, it is important that the  expected risk can be managed appropriately with the funds allocated.
    - Bear in mind that security should be designed to support and enable business tasks and functions
      - security controls, countermeasures, and safeguards can be implemented administratively, logically / technically, or physically 
      - these 3 categories should be implemented in a conceptual layered defense-in-depth manner to provide maximum benefit
      - based on the concept that policies (part of administrative controls) drive all aspects of security and thus form the initial protection layer around assets
      - Defense in depth is simply the use of multiple controls in a series. No one control can protect against all possible threats. Using a multilayered solution allows for numerous, different controls to guard against whatever threats come to pass. Some of the terms that relate to or are based on defense in depth include: Layering, Classifications, Zones, Realms, Compartments, Silos, Segmentations, Lattice structure, Protection rings
      - then, logical and technical controls provide protection against logical attacks and exploits 
      - then, physical controls provide protection against real-world physical attacks against facilities and devices
- 1.10.5 Applicable types of controls (e.g., preventive, detective, corrective)
  - **Administrative**: the policies and procedures defined by an org's security policy and other regulations or requirements
  - **Physical**: security mechanisms focused on providing protection to the facility and real world objects
  - **Preventive**: a preventive or preventative control is deployed to thwart or stop unwanted or unauthorized activity from occurring
  - **Deterrent**: a deterrent control is deployed to discourage security policy violations; deterrent and preventative controls are similar, but deterrent controls often depend on individuals being convinced not to take an unwanted action
  - **Detective**: a detective control is deployed to discover or detect unwanted or unauthorized activity; detective controls operate after the fact
  - **Compensating**: a compensating control is deployed to provide various options to other existing controls, to aid in enforcement and support of security policies
    - they can be any controls used in addition to, or in place of, another control
    - they can be a means to improve the effectiveness of a primary control or as the alternative or failover option in the event of a primary control failure
  - **Corrective**: a corrective control modifies the environment to return systems to normal after an unwanted or unauthorized activity as occurred; it attempts to correct any problems resulting from a security incident
  - **Recovery**: An extension of corrective controls but have more advanced or complex abilities; a recovery control attempts to repair or restore resources, functions, and capabilities after a security policy violation 
    - recovery controls typically address more significant damaging events compared to corrective controls, especially when security violations may have occurred
  - **Directive**: A directive control is deployed to direct, confine, or control the actions of subjects to force or encourage compliance with security policies
- 1.10.6 Control assessments (security and privacy)
  - Periodically assess security and privacy controls: what’s working, what isn’t 
    - As part of this assessment, the existing documents should be thoroughly reviewed, and some of the controls tested randomly 
    - A report is typically produced to show the outcomes and enable the org to remediate deficiencies 
    - Often, security and privacy control assessment are performed and/or validated by different teams, with the privacy team handling the privacy aspects
- 1.10.7 Monitoring and measurement
  - Monitoring and measurement are closely aligned with identifying risks 
  - While monitoring is used for more than security purposes, monitoring should be tuned to ensure the org is notified about potential security incidents as soon as possible 
  - If a security breach occurs, monitored systems and data become valuable from a forensics perspective; rrom the ability to derive root cause of an incident to making adjustments to minimize the chances of reoccurance 
- 1.10.8 Reporting
  - Risk Reporting is a key task to perform at the conclusion of risk analysis (i.e. production and presentation of a summarizing report) 
  - A Risk Register or Risk Log is a document that inventories all identified risks to an org or system or within an individual project 
    - A risk register is used to record and track the activities of risk management, including:
      - identifying risks
      - evaluating the severity of, and prioritizing those risks
      - prescribing responses to reduce or eliminate the risks
      - track the progress of risk mitigation
- 1.10.9 Continuous improvement (e.g., Risk maturity modeling)
  - Risk analysis is performed to provide upper management with the details necessary to decide which risks should be mitigated, which should be transferred, which should be deterred, which should be avoided, and which should be accepted
  - Effective risk communication and reporting should be clear, timely, and consistent.
  - An **Enterprise Risk Management** (ERM) program can be evaluated using an RMM 
  - **Risk Maturity Model (RMM)**: assesses the key indicators and activities of a mature, sustainable, and repeatable risk management process, typically relating the assessment of risk maturity against a five-level model such as:
    - **Ad hoc**: a chaotic starting point from which all orgs initiate risk management
    - **Preliminary**: loose attempts are made to follow risk management processes, but each department may perform risk assessment uniquely
    - **Defined**: a common or standardized risk framework is adopted organization-wide
    - **Integrated**: risk management operations are integrated into business processes, metrics are used to gather effectiveness data, and risk is considered an element in business strategy decisions
    - **Optimized**: risk management focuses on achieving objectives rather than just reacting to external threats; increased strategic planning is geared toward business success rather than just avoiding incidents; and lessons learned are re-integrated into the risk management process
- 1.10.10 Risk frameworks **Focuses on the 📝WHY**
  - A risk framework is a guide or recipe for how risk is to be accessed, resolved, and monitored
  - provide a structured approach to identifying, assessing, prioritizing and manging risk to guide decision making
  - provides the overaching structure for making risk informed decisions
  - NIST established the **Risk Management Framework** (RMF) and the **Cybersecurity Framework** (CSF): the CSF is a set of guidelines for mitigating organizational cybersecurity risks, based on existing standards, guidelines, and practices
  - **Risk management** facilitates the balance of operational and economic costs of protective measures with gains in mission capability.  Risk management is a systematic approach to identifying, assessing, and prioritizing risks to organizational operations, assets, or individuals resulting from the operation of information systems and the information processed, stored, or transmitted by those systems. It involves evaluating the likelihood and impact of risks and implementing cost-effective measures to reduce them to an acceptable level. By considering the costs of implementing protective measures against the benefits of mission capability, risk management helps organizations make informed decisions about how to allocate their resources to achieve their security goals. Performance testing, security audit, and risk assessment are all important components of a risk management program.
  - CSF is aimed at ✏️private (commercial) businesses and purely optional
  - RMF's audience is ✏️federal government agencies and is mandatory for thosie to which it applies
  - The RMF is intended as a risk management process to identify and respond to threats, and is defined in three core, interrelated Special Publications: 
    - SP 800-37 Rev 2, Risk Management Framework for Information Systems and Organizations
    - SP 800-39, Managing Information Security Risk
    - SP 800-30 Rev 1, Guide for Conducting Risk Assessments
    - The **📝RMF 800-37 has 7 steps**, and **six cyclical phases**: (PCSIAAM People Can See I AM ALWAYS Monitoring)
      - **🔥Prepare** to execute the RMF from an organization and system-level perspective by establishing a context and priorities for managing security and privacy risk
      - **🔥Categorize** the system and the information processed, stored, and transmitted by the system based on an analysis of the impact of loss
      - **🔥Select** an initial set of controls for the system and tailor the controls as needed to reduce risk to an acceptable level based on an assessment of risk
      - **🔥Implement** the controls and describe how the controls are employed within the system and its environment of operation
      - **🔥Assess** the controls to determine if the controls are implemented correctly, operating as intended, and producing the desired outcomes with respect to satisfying the security and privacy requirements
      - **🔥Authorize** the system or common controls based on a determination that the risk to organizational operations and assets, individuals, and other organizations, and the nation is acceptable
      - **🔥Monitor** the system and associated controls on an on-going basis to include assessing control effectiveness, documenting changes to the system and environment of operation, conducting risk assessments and impact analysis, and reporting the security and privacy posture of the system
    - See my overview article, [The NIST Risk Management Framework](https://blog.balancedsec.com/p/the-nist-risk-management-framework)
  - There are other risk frameworks, such as the British Standard BS 31100 -- be familiar with frameworks and their goals
  - Regular risk monitoring and review involves tracking risk treatment progress, reviewing risk assessments, and analyzing incident reports.

[1.11](#1.11) Understand and apply threat modeling concepts and methodologies (OSG-9 Chpt 1)
- **Threat Modeling**: security process where potential threats are identified, categorized, and analyzed; can be performed as a proactive measure during design and development or as an reactive measure once a product has been deployed   
  - Threat modeling identifies the potential harm, the probability of occurrence, the priority of concern, and the means to eradicate or reduce the threat
    - Proactive Approach: This is a proactive approach to threat modeling, which is also known as the defensive approach.
    - Reactive approach or adversarial approach to threat modeling takes place after a product has been created and deployed.
- Microsoft uses the **Security Development Lifecycle** (SDL) with the motto: "Secure by design, secure by default, secure in deployment and communication" (also known as SD3+C)
  - It has two objectives:
    - Reduce the number of security-related design and coding defects
    - Reduce the severity of any remaining defects
- A defensive approach to threat modeling takes place during the early stages of development; the method is based on predicting threats and designing in specific defenses during the coding and crafting process
  - Security solutions are more cost effective in this phase than later; this concept should be considered a proactive approach to threat management
- Microsoft developed the **STRIDE threat model**: Also useful for threat categorization during aplication threat modeling
  - Spoofing: an attack with the goal of gaining access to a target system through the use of falsified identity
  - Tampering: any action resulting in unauthorized changes or manipulation of data, whether in transit or in storage
  - Repudiation: the ability of a user or attacker to deny having performed an action or activity by maintaining plausible deniability
  - Information Disclosure: the revelation or distribution of private, confidential, or controlled information to external or unauthorized entities
  - Denial of Service (DoS): an attack that attempts to prevent authorized use of a resource; this can be done through flaw exploitation, connection overloading, or traffic flooding
  - Elevation of privilege: an attack where a limited user account is transformed into an account with greater privileges, powers, and access
- **Process for Attack Simulation and Threat Analysis (PASTA)**: PASTA is a risk-­centric approach that aims at selecting or developing countermeasures in relation to the value of the assets to be protected. A seven-stage threat modeling methodology: _(Our Technical Application Tackles Vulnerabilities And Risks)_
  - Stage I: Definition of the Objectives (DO) for the Analysis of Risk
  - Stage II: Definition of the Technical Scope (DTS)
  - Stage III: Application Decomposition and Analysis (ADA)
  - Stage IV: Threat Analysis (TA)
  - Stage V: Weakness and Vulnerability Analysis (WVA)
  - Stage VI: Attack Modeling and Simulation (AMS)
  - Stage VII: Risk Analysis and Management (RAM)
- Each stage of PASTA has a specific list of objectives to achieve and deliverables to produce in order to complete the stage
- **DREAD**: The DREAD model, developed in 2002, is a quantitative risk analysis model that involves rating the severity of security threats by assigning numeric values (typically from 1 to 10) that represent different levels of severity.
     - Damage: What is the total amount of damage the threat is capable of causing to your business?
     - Reproducibility: How easily can an attack on the particular threat be replicated?
     - Exploitability: How much effort is required for the threat to be exploited by an attacker?
     - Affected users: How many people, either inside or outside of your organization, will be affected by the security threat?
     - Discoverability: How easily can the vulnerability be found?
- **Visual, Agile, and Simple Threat (VAST)**: a threat modeling concept that integrates threat and risk management into an Agile programming environment on a scalable basis
- Part of the job of the security team is to identify threats, using different methods:
   - Focus on attackers: this is a useful method in specific situations;
    - e.g. suppose that a developer’s employment is terminated, and that post-offboarding and review of developer’s computer, a determination is made that the person was disgruntled and angry
      - understanding this situation as a possible threat, allows mitigation steps to be taken
   - Focus on assets: an org’s most valuable assets are likely to be targeted by attackers
   - Focus on software: orgs that develop applications in house, and can be viewed as part of the threat landscape; the goal isn’t to identify every possible attack, but to focus on the big picture, identifying risks and attack vectors
- Understanding threats to the org allow the documentation of potential attack vectors; diagramming can be used to list various technologies under threat
- **Reduction Analysis** (Also known as Decomposiing the application, system or environment): The purpose is to gain a greater understanding of the logic of a product, its internal components as well as its interactions and external elements: The five key concepts of decomposition are
  - trust boundaries
  - dataflow paths
  - input points
  - privileged operations
  - Details about security stance and approach.

[1.12](#1.12) Apply Supply Chain Risk Management (SRM) concepts (OSG-9 Chpt 1)
- 1.12.1 Risks associated with hardware, software, and services
  - **Supply Chain Risk Management (SCRM)**: the means to ensure that all of the vendors or links in the supply chain are: 
    - reliable, 
    - trustworthy, 
    - reputable organizations that disclose their practices and security requirements to their business partners (not necessarily to the public)
  - Each link in the chain should be responsible and accountable to the next link in the chain; each handoff is properly organized, documented, managed, and audited
    - The goal of a secure supply chain is that the finished product is of sufficient quality, meets performance and operational goals, provides stated security mechanisms, and that at no point in the process was any element counterfeited or subject to unauthorized or malicious manipulation or sabotage
  - The supply chain can be a threat vector, where materials, software, hardware, or data is being obtained from a supposedly trusted source but the supply chain behind the source could have been compromised and asset poisoned or modified
  - Void **Authorization to operate (ATO)**: The situation of voiding the ATO of a vendor describes the fact that the vendor is not meeting minimal security requirements which are necessary to the protection of the service and its customers.
  - When dealing with suppliers, a Minimum security requirements should be modeled on your existing security policy. This is based on the idea that when working with a third party, that third party should have at least the same security as your organization.
  - The **Silicon Root of Trust (SRoT)** refers to the security mechanisms embedded directly into the silicon of hardware components e.g IoT device, typically within a computer's processor or specialized security chip. Contains unique unchangable cryptographic key/identity (immutable fingerprint) established during manufaturing process that servers as a Trust Anchor. This embedded trust anchor is immutable and forms the foundation for all higher-level security functions and assurances within the system. If firmware is compromised, SRoT will changeand prevent system from booting because signature no longer matches.
  - A **Physically Unclonable Function (PUF)** is a hardware-based security feature that generates a unique identifier or response based on the microscopic variations in the physical properties of an integrated circuit or chip. These variations arise naturally during the manufacturing process and are not replicable, making each PUF unique. When PUF is queried, it responds with a unique output based on this variations. This response is like a fingerprint that is impossible to clone or recreate in another device. Used in secure key generation, device authentication, anti-tampering and secure boot.
  - A **Software Bill of Materials (SBOM)** is a comprehensive list of all the components, libraries, modules, and dependencies included in a software application. It is akin to a list of ingredients in a recipe, detailing everything that goes into the software. SBOMs are crucial for understanding and managing the composition of software, ensuring transparency, security, and compliance. Attack in 2020 lead to US Govt requirement for SBOM in the 2021 Executive Order on Improving the Nations Cybersecurity.
  - **Hardware Root of Trust (HRoT)**: A line of defense against executing unathorized firmware on a system. Establishes a chain of trust starting from hardware up through firmware and software layers (Trust Anchor). When certificates ares used for Full Disk Encryption (FDE), they use a hardware root of trust for key storage, which verifies the keys match before the secure boot process takes place. SRoT and PUF are also implemnetations of Hardware Root of trust. Componenets include
   - 🔥Trusted Platform Module (TPM): ✏️A hardware component that securely stores cryptographic keys and performs cryptographic operations. TPMs are built into many modern computers and can securely generate, store, and manage cryptographic keys, ensuring that private keys are kept safe from extraction or compromise. e.g bitlocker
   - 🔥Hardware Security Module (HSM): A dedicated hardware device designed to 🧠manage and protect digital keys and 🧠perform encryption and decryption.
   - 🔥Secure Enclave or Trusted Execution Environment (TEE): An isolated area within the main processor that ensures the confidentiality and integrity of code and data loaded within it.

- 1.12.2 Third-party assessment and monitoring
  - Before doing business with another company, an org needs to perform due-dilligence, and third-party assessments can help gather information and perform the assessment 
  - An on-site assessment is useful to gain information about physical security and operations 
    - During document review, your goal is to thoroughly review all the architecture, designs, implementations, policies, procedures, etc. 
    - A good understanding of the current state of the environment, especially to understand any shortcomings or compliance issues prior to integrating the IT infrastructures
    - The level of access and depth of information obtained is usually proportional to how closely the companies will work together 
- 1.12.3 Minimum security requirements
  - As part of assessment, the minimum security requirements must be established; in some cases, the minimum security requirements are your company’s security requirements, in other cases, new minimum security requirements need to be established 
    - In such scenarios, the minimum security requirements should have a defined period
- 1.12.4 Service-level requirements
  - **Service Level Agreements (SLAs)**: companies have SLAs for internal operations (such as how long it takes for the helpdesk to respond to a new ticket), for customers (such as the availability of a public-facing service) and for partner orgs (such as how much support a vendor provides a partner) 
    - All SLAs should be reviewed; a company sometimes has an SLA standard that should be applied, when possible, to the service level agreements as part of working with another company
      - this can sometimes take time, as the acquiring company might have to support established SLAs until they expire or are up for renewal 

[1.13](#1.13) Establish and maintain a security awareness, education, and training program (OSG-9 Chpt 2)
- 1.13.1 Methods and techniques to present awareness and training (e.g., social engineering, phishing, security champions, gamification)
  - Before actual training takes place, user security awareness needs to take place; from there, training, or teaching employees to perform their work tasks and to comply with the security policy can begin
  - **Training** is teaching employees to perform their work tasks and to comply with the security policy. Training is typically hosted by an organization and is targeted to groups of employees with similar job functions. 
    - All new employees require some level of training so that they will be able to comply with all standards, guidelines, and procedures mandated by the security policy
    - Training should be mandatory and provided both to new employees and yearly (at a minimum) for ongoing training
    - Program effectiveness evaluation, such as giving a quiz or monitoring security incident rate changes over time, can be used to measure whether the training is beneficial or a waste of time and resources
  - **Education** is a more detailed endeavor in which students/users learn much more than they actually need to know to perform their work tasks 
    - Education is most often associated with users pursuing certification or seeking job promotion
  - **Awareness** establishes a common baseline or foundation of security understanding across the entire organization and focuses on key or basic topics and issues related to security that all employees must understand. Although it
is provided by the organization, it is not targeted to groups of workers since it applies to all
employees.
  - Employees need to understand what to be aware of (e.g. types of threats, such as phishing and free USB sticks), how to perform their jobs securely (e.g. encrypt sensitive data, physically protect valuable assets) and how security plays a role in the big picture (company reputation, profits,and losses) 
    - Routine tests of operational security should be performed (such as phishing test campaigns, tailgating at company doors and social engineering tests)
    - Social engineering: while many orgs don’t perform social engineering campaigns (testing employees using benign social engineering attempts) as part of security awareness, it is likely to gain traction. 
      - outside of campaigns, presenting social engineering scenarios and information is a common way to educate
    - Phishing: phishing campaigns are popular, and many orgs use third-party services to routinely test their employees with fake phishing emails 
      - such campaigns produce valuable data, such as the percentage of employees who open the phishing email, the percentage who open attachments or click links, and the percentage who report the fake phishing email as malicious
    - **Security champions**: the term “champion” has been gaining ground; orgs often use it to designate a person on a team who is a subject matter expert in a particular area or responsible for a specific area
      - e.g. somebody on the team could be a monitoring champion — they have deep knowledge around monitoring and evangelize the benefits of monitoring to the team or other teams
      - a security champion is a person responsible for evangelizing security, helping bring security to areas that require attention, and helping the team enhance their skills
      - Security champions are often
non-­security employees who take up the mantle to encourage others to support and adopt more security practices and behaviors.
    - **Gamification**: legacy training and education are typically based on reading and then answering multiple-choice questions to prove knowledge; gamification aims to make training and education more fun and engaging by packing educational material into a game
      - gamification has enabled organizations to get more out of the typical employee training
      - Gamification is a means to encourage compliance and engagement by integrating common elements of game play into other activities, such as security compliance and behavior change. This can include rewarding compliance behaviors and potentially punishing violating behaviors. Many aspects of game play can be integrated into security training and adoption, such as scoring points, earning achievements or badges (i.e., earn recognition), competing with others, cooperating with others (i.e., team up with coworkers), following a set of common/standard rules, having a defined goal, seeking rewards, developing group stories/experiences, and avoiding pitfalls or negative game events

- **Social Engineering Attacks**
	- **Phishing**: This involves sending fraudulent emails that appear to come from reputable sources. The goal is to trick recipients into providing sensitive information such as usernames, passwords, and credit card details.
	- **Spear Phishing**: A more targeted form of phishing, spear phishing involves sending emails to specific individuals or organizations, often using personal information to make the attack more convincing.
	- **Whaling**: This type of phishing targets high-profile individuals like executives or important decision-makers within an organization. The emails are crafted to look like critical business communications.
	- **Vishing**: This is voice phishing, where attackers use phone calls to trick individuals into providing sensitive information. Often, attackers pose as legitimate entities like banks or government agencies.
	- **Smishing**: Similar to phishing but conducted via SMS (text messages), smishing involves sending texts that appear to come from trusted sources, prompting recipients to click on a link or provide personal information.
	- **Pretexting**: In this attack, the attacker creates a fabricated scenario (pretext) to obtain information or perform actions that benefit the attacker. This often involves impersonating someone in authority or a trusted individual.
	- **Baiting**: Baiting involves enticing a victim with something appealing (the "bait"), such as free software or music downloads, to trick them into providing personal information or downloading malware.
	- **Quid Pro Quo**: In this attack, the attacker offers a service or benefit in exchange for information. For example, an attacker might pose as an IT support person offering to help with a technical issue in exchange for login credentials.
	- **Tailgating (or Piggybacking)**: This involves an attacker gaining physical access to a restricted area by following closely behind an authorized person. The attacker relies on the person in front to hold the door open for them.
	- **Dumpster Diving**: This attack involves searching through an organization’s trash to find sensitive information that has not been properly disposed of. This could include discarded documents, hard drives, or other media.
	- **Impersonation**: Attackers pose as someone trustworthy, such as a co-worker, IT support, or a vendor, to gain the trust of the victim and extract information or gain access to systems.
	- **Shoulder Surfing**: This is the practice of spying on the user of an electronic device to obtain confidential information, such as passwords, PINs, or other sensitive data, by looking over their shoulder.
  
- 1.13.2 Periodic content reviews
  - Threats are complex, so training needs to be relevant and interesting to be effective; this means updating training materials and changing out the ways which security is tested and measured 
    - if you always use the same phishing test campaign or send it from the same account on the same day, it isn’t effective, and the same applies to other materials. 
    - instead of relying on long/detailed security documentation for training and awareness, consider using internal social media tools, videos and interactive campaigns
- 1.13.2 Program effectiveness evaluation 
  - Time and money must be allocated for evaluating the company’s security awareness and training; the company should track key metrics, such as the percentage of employees who click on a fake phishing campaign email links

Also see my articles on risk management: 
- [Part 1](https://blog.balancedsec.com/p/risk-concepts-from-the-cissp-part-1)  introduces risk and risk terminology from the lens of the (ISC)² Official Study Guide
- Since the primary goal of risk management is to identify potential threats against an organizaton's assets, and bring those risks into alignment with an organization's risk appetite, in [Part2](https://blog.balancedsec.com/p/risk-concepts-from-the-cissp-part-2), we cover the threat assessment -- a process of examining and evaluating cyber threat sources with potential system vulnerabilities
  - we look at how a risk assessment helps drive our understanding of risk by pairing assets and their associated potential threats, ranking them by criticality
  - we also discuss quantitative analytic tools to help provide specific numbers for various potential risks, losses, and costs
- In the [third installment](https://blog.balancedsec.com/p/risk-concepts-from-the-cissp-part-3), we review the outcome of the risk assessment process, looking at total risk, allowing us to determine our response to each risk/threat pair and perform a cost/benefit review of a particular safeguard or control
  - we look at the categories and types of controls and the idea of layering them to provide several different types of protection mechanisms 
  - we also review the important step of reporting out our risk analysis and recommended responses, noting differences in requirements for messaging by group


**TCB Common Criteria ISO/IEC 15408-1 Evaluation Assurance Levels (IFSMMSSF) "Ice Fishermen Sing Merry Melodies, So Stay Friendly!"**
- EAL0 –Inadequate assurance
- EAL1 –Functionally tested
- EAL2 –Structurally tested
- EAL3 –Methodically tested and checked
- EAL4 –Methodically designed, tested and reviewed
- EAL5 –Semi formally designed and tested
- EAL6 –Semi formally verified design and tested
- EAL7 –Formally verified design and tested

 - **System and Organization Controls (SOC)**: A security audit systematically evaluates an organization’s security policies,
standards, and procedures to ensure compliance with established security requirements.
- SOC 1: An audit and compliance report that focuses strictly on a company’s financial statements and controls that can impact a customer’s financial statements. A company that performs credit card processing is likely to require a SOC
1 audit and compliance report.
- SOC 2: An audit and compliance report that evaluates an organization based on AICPA’s five “Trust Services principles”: privacy, security, availability, processing integrity, and confidentiality. Many organizations undergo SOC 2 auditing and present a SOC 2 report to regulators and customers to demonstrate compliance with industry standard security controls.
- SOC 3: This is a “lite” version of a SOC 2 report and abstracts or removes all sensitive details. A SOC 3 report generally indicates whether an organization has demonstrated each of the five Trust Services principles without disclosing specifics (like exactly what they do or don’t do). Companies make SOC 3 reports available to the public and restrict SOC 2 reports to trusted parties.

- **QUANTITATIVE RISK MANAGEMENT**:

- **EF**: The exposure factor is the percentage of the facility that risk managers expect will be damaged if a risk materializes. It is calculated by dividing the amount of damage by the asset value. 
  - EF is the percentage of an asset's value that is expected to be lost if a specific threat event occurs.
  - Formula: EF = (Loss due to the threat event / Total asset value) * 100
  - Example: If a fire destroys 40% of a building's value, the EF is 40%.
    
- **ARO**: The annualized rate of occurrence is the number of times that risk analysts expect a risk to happen in any given year. The annualized loss expectancy (ALE) represents the amount of money a business expects to lose to a given risk each year.
  - ARO is the expected frequency with which a specific threat will occur within a year.
  - ARO can be a whole number or a fraction, representing the number of occurrences per year.
  - Example: If historical data suggests that a power outage happens twice a year, the ARO is 2. If a flood is expected to occur once every 10 years, the ARO is 0.1.
    
- **SLE**: The single loss expectancy (SLE) is the product of the asset value (AV) and the exposure factor (EF).
  - SLE is the monetary loss expected from a single occurrence of a threat event.
  - Formula: SLE = Asset Value (AV) * Exposure Factor (EF)
  - Example: If the asset value of a server is $10,000 and the EF for a fire is 40%, the SLE is $10,000 * 0.40 = $4,000.

- **ALE**: The annualized loss expectancy is calculated by multiplying the single loss expectancy (SLE) by the annualized rate of occurrence (ARO).
  - ALE is the expected monetary loss for an asset due to a specific threat over a one-year period.
  - Formula: ALE = Single Loss Expectancy (SLE) * Annualized Rate of Occurrence (ARO)
  - Example: If the SLE for a fire affecting a server is $4,000 and the ARO is 0.1, the ALE is $4,000 * 0.1 = $400.

- **Cost/Benefit Equation for Safeguards**: Anything that removes a vulnerability or protects against one or more specific threats is considered a safeguard or a countermeasure.
  -Formula: ALE before safeguard – ALE after implementing the safeguard – annual cost of safeguard [(ALE1 – ALE2) – ACS]. 

- **Example Calculation**
  - Identify Asset Value (AV): Let's say the value of a database server is $50,000.
  - Determine the Exposure Factor (EF): A fire might destroy 30% of the server’s value. i.e EF = 30% = 0.30
  - Calculate the Single Loss Expectancy (SLE): SLE = AV * EF i.e SLE = $50,000 * 0.30 = $15,000
  - Estimate the Annualized Rate of Occurrence (ARO): Based on historical data, a fire might occur once every 25 years. i.e ARO = 1/25 = 0.04
  - Calculate the Annualized Loss Expectancy (ALE): ALE = SLE * ARO, i.e ALE = $15,000 * 0.04 = $600

**ISO 28000:2007,** “Specification for security management systems for the supply chain,” provides a broad framework for managing supply chain risk.
  - ISO 28000:2007 relies heavily on the continuous process improvement model of plan, do, check, act (PDCA or Deming cycle) to improve the security management system and to assure organizational conformance to the security practice.
