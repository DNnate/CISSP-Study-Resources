[Domain 2](#domain2-top) **Asset Security**

- Domain 2 of the CISSP exam covers asset security making up ~10% of the test 
- Asset security includes the concepts, principles, and standards of monitoring and securing any asset important to the organization
- Anything that removes a vulnerability or protects against one or more specific threats is considered a safeguard or a countermeasure. The annual costs of safeguards should not exceed the expected annual cost of asset value loss.

- The Asset Security domain focuses on collecting, handling, and protecting information throughout its lifecycle; the first step is classifying information based on its value to the organization
- **Asset**: anything of value owned by the organization
  - **Intangible Assets**: Patents, databases, and formulas
  - **Tangible Assets**: hardware, cables, and buildings
  - **Personnel Assets**: Employees
- **Asset lifecycle**: phases an asset goes through, from creation (or collection) to destruction
- **Threat** is any _potential occurrence_ that may cause an undesirable or unwanted outcome for an organization or for a
specific asset. e.g threat/likelihood of fire
- **Vulnerability** is the _weakness_ in an asset, or the absence or the weakness of a safeguard or countermeasure. e.g lack of fire extinguishers
- **Exposure** is being _susceptible_ to asset loss because of a threat; there is the possibility that a vulnerability can or will be exploited. It is the presence of a vulnerability when a related threat exists
- **Risk** is the _possibility, probability, chance or likelihood_ that a threat will exploit a vulnerability to cause harm to an asset and the severity of damage that could result. e.g damage to equipment.
  - Risk = Threat * Vulnerability
  - Every instance of exposure is a risk

[2.1](#2.1) Identify and classify information assets (OSG-9 Chpt 5)

- 2.1.1 Data classification
  - Managing the data lifecycle refers to protecting it from cradle to grave -- steps need to be taken to protect data when it's first created until it's destroyed
  - One of the first steps in the lifecycle is identifying and classifying information and assets, often within a security policy
  - In this context, assets include sensitive data, the hardware used to process that data, and the media used to store/hold it
  - **Data categorization**: process of grouping sets of data, info or knowledge that have comparable sensativities (e.g. impact or loss rating), and have similar law/contract/compliance security needs
  - **Sensitive data**: any information that isn't public or unclassified, and can include anything an org needs to protect due to its value, or to comply with existing laws and regulations
  - **Personally Identifiable Information (PII)**: any information that can identify an individual
    - more specifically, info about an individual including (1) any info that can be used to distinguish or trace an individual‘s identity, such as name, social security number, date and place of birth, mother‘s maiden name, or biometric records; and (2) any other information that is linked or linkable to an individual, such as medical, educational, financial, and employment information ([NIST SP 800-122](https://csrc.nist.gov/publications/detail/sp/800-122/final))
  - **Protected Health Information (PHI)**: any health-related information that can be related to a specific person
  - **Proprietary data**: any data that helps an organization maintain a competitive edge
  - Organizations classify data using labels
    - government classification labels include:   
      - **Top Secret**: if disclosed, could cause massive damage to national security, such as the disclosure of spy satellite information
      - **Secret**: if disclosed, can adversely affect national security
      - **Confidential**: Confidential data is usually data that is exempt from disclosure under laws such as the Freedom of Information Act but is not classified as national security data.
      - **Sensitive**: But Unclassified (SBU): SBU data is data that is not considered vital to national security, but its disclosure would do some harm. Many agencies classify data they collect from citizens as SBU. In Canada, the SBU classification is referred to as protected (A, B, C).
      - **Unclassified**: not sensitive
    - non-government organizations use labels such as:
      - **Confidential/Proprietary**: only used within the org and, in the case of unauthorized disclosure, it could suffer serious consequences
      - **Private**: may include personal information, such as credit card data and bank accounts; unauthorized disclosure can be disastrous
      - **Sensitive**: needs extraordinary precautions to ensure confidentiality and integrity
      - **Public**: can be viewed by the general public and, therefore, the disclosure of this data would not cause damage
    - labels can be as granular and custom as required by the org
  -  It is important to protect data in all states: at rest, in transit, or in use
  -  The best way to protect data confidentiality is via use of strong encryption
- **Declassification** is the process of moving an object into a lower level of classification once it is determined that it no longer justifies being placed at a higher level. In a Bell-LaPadula implementation, for example, Only a trusted subject can perform declassification because this action is a violation of the verbiage of the star property of Bell–LaPadula, but not the spirit or intent, which is to prevent unauthorized disclosure.

- 2.1.2 Asset Classification
  - It's important to identify and classify assets, such as systems, mobile devices etc.
  - **Classification**: derived from compliance mandates, the process of recognizing organizational impacts if information suffers any security compromise (whether to confidentiality, integrity, availability, non-repudiation, authenticity, privacy, or safety)
  - Asset classifications should match data classification, i.e. if a computer is processing top secret data, the computer should be classified as a top secret asset
  - **Clearance**: relates to access of certain classfication of data or equipment, and who has access to that level or classification
  - A **formal access approval process** should be used to change user access; the process should involve approval from the data/asset owner, and the user should be informed about rules and limits
    - before a user is granted access they should be educated on working with that level of classification
  - Classification levels can be used by businesses during acquisitions, ensuring only personnel who need to know are involved in the assessment or transition
  - In general, classification labels help users use data and assets properly, for instance by restricting dissemination or use of assets by their classification

[2.2](#2.2) Establish information and asset handling requirements (OSG-9 Chpt 5)

- **Asset handling**: refers to secure transport of media through its lifetime
- The data and asset handling key goal is to prevent data breaches, by using:
  - **Data Maintenance**: on-going efforts to organize and care for data through its life cycle
  - **Data Loss Prevention (DLP)**: systems that detect and block data exfiltration attempts; two primary types:
    - network-based DLP
    - endpoint-based DLP
- **Marking**: (AKA labeling) sensitive information/assets ensures proper handling (both physically and electronically)
- **Data Collection Limitation**: prevent loss by not collecting unnecessary sensitive data
- **Data Location**: keep dup copies of backups, on- and off-site
- **Storage**: define storage locations and procedures by storage type; use physical locks for paper-based media, and encrypt electronic data
- **Destruction**: destroy data no longer needed by the organization; policy should define acceptable destruction methods by type and classification ([see NIST SP-800-88 for details](https://csrc.nist.gov/publications/detail/sp/800-88/rev-1/final))
  - **Erasing**: usually refers to a delete operation on media, leaving data remanence. It rarely remove the data from media but instead mark it for deletion
  - **Clearing**: removal of sensitive data from a storage device such that there is assurance data may not be reconstructed using normal functions or software recovery or software recovery utilities; over-writing existing data or scrubbing un-needed data
  - **Purging (Sanitization)**: removal of sensitive data from a system or device with the intent that data cannot be reconstructed by any known technique; usually refers to mutliple clearing passes combined with other tools (see below) -- not considered acceptable for top secret data.
      - Purging overwrites the media with random bits multiple times and includes additional steps to ensure that data is removed. It ensures there isn’t any data remanence.
      - Sanitization methods (such as clearing, purging, and destroying) help ensure that data cannot be recovered
- **Data Remanence**: data remaining on media after typical erasure; to ensure all remanence is removed, the following tools can help:
  - **Degaussing**: used on magentic media. Degaussing the disks often damages the electronics but doesn’t reliably remove the data.
  - **Overwriting**: Same as Clearing and also known as purging. Overwriting the disks multiple times will remove all existing data. This is called purging, and purged media can then be used again.
  - **(Physical) destruction**: used for SSD/electronic components, or in combination with other less-secure methods. Due to problems with remnant data, the U.S. National Security Agency requires physical destruction of SSDs
  - **Cryptographic Erasure**: AKA cryptoshedding, basically destroying encryption key; may be only secure method for cloud storage
  - The standard methods for clearing magnetic tapes, according to the NIST Guidelines for Media Sanitization, are overwriting the tape with nonsensitive data, degaussing, and physical destruction via shredding or incineration. Reformatting a tape does not remove remnant data.

[2.3](#2.3) Provision resources securely (OSG-9 Chpt 16)

- The primary purpose of security operations practices is to safeguard assets such as information, systems, devices, facilities, and apps; these practices help to identify threats, vulnerabilities, and implement controls to reduce the risk to these asssets
- Implementing common security operations concepts, along with performing periodic security audits and reviews demonstrates a level of due care
- **Need-to-know**: a principle that imposes the requirement to grant users access only to data or resources they need to perform assigned work tasks
- **Least privilege**: a principle stating that subjects are granted only the privileges necessary to perform assigned work tasks and no more

- 2.3.1 Information and asset ownership
  - **Data owner**: the person who has ultimate organizational responsibility for data; usually sr. manager (CEO,president, dept. head); data owners typically delegate data protection tasks to others in the org

- 2.3.2 Asset inventory (e.g., tangible, intangible)
  - **Inventory**: complete list of items
  - **Tangible assets**: include hardware and software assets owned by the company
  - **Intangible assets**: things like patents, copyrights, a company’s reputation, and other assets representing potential revenue
    - an org should keep track of intangible assets, like intellectual property, patents, trademarks, and company’s reputation, and copyrights to protect them
    - note: patents in the US are valid for 20 years

- 2.3.3 Asset management
  - Asset management refers to managing both tangible and intangible assets; this starts with inventories of assets, tracking the assets, and taking additional steps to protect them throughout their lifetime
  - **Accountability**: ensures that account management has assurance that only authorized users are accessing a system and using it properly
  - **Hardware assets**: IT resources such as computers, servers, routers, switches and peripherals
    - use an automated configuration management system (CMS) to help with hardware asset management
    - use barcodes, RFID tags to track hardware assets
  - **Software assets**: operating systems and applications 
    - important to monitor license compliance to avoid legal issues
    - software licensing also refers to ensuring that systems do not have unauthorized software installed
  - To protect intangible inventories (like intellectual property, patents, trademarks, and company’s reputation, and copyrights), they need to be tracked

[2.4](#2.4) Manage data lifecycle (OSG-9 Chpt 5)
- 2.4.1 Data roles (i.e., owners, controllers, custodians, processors, users/subjects)
  - **System owner**: controls the computer storing the data; usually includes software and hardware configurations and support services (e.g. cloud implementation)
    - data owner is the person respsonible for classifying, categorizing, and permitting access to the data; the data owner is the person who is best familiar with the importance of the data to the business
    - system owners are responsible for the systems that process the data
    - system owner is responsible for system operation and maintenance, and associated updating/patching as well as related procurement activities
  - **Data Subject**: the person who the information is about.
  - **Data Owner**: the entity that collects/creates the PII and is legally responsible and accountable for protecting it and educating others about how to protect the data through dissemination of intellectual property rights documentation, policies and regulatory requirements,
       - specific protective measures that are expected of custodians, and compliance requirements.
       - Data owners are tasked with making decisions about data, such as who receives access to it and how it is used.
       - The data owner has ultimate responsibility for data belonging to an organization and is typically the CEO, president, or another senior employee
       - The data owner is the person responsible for classifying data.
       - A data controller decides what data to process and directs the data processor to process the data.
  - **Data controller**: decide what data to process and how to process it
    - the data controller is the person or entity that controls the processing of the data - deciding what data to process, why this data should be processed, and how it is processed
    - e.g. a company that collects personal information on employees for payroll is a data controller (but, if they pass this info to a third-party to process payroll, the payroll company is the data processor, see below)
  - **Data processor**: an entity working on behalf (or the direction) of the data controller, that processes PII; they have a responsibility to protect the privacy of the data and not use it for any purpose other than directed by the data controller; generally, a data processor is any system used to process data
    - a controller can hire a third party to process data, and in this context, the third party is the data processor; data processors are often third-party entities that process data for an org at the direction of the data controller
    - note GDPR definition: "a natural or legal person, public authority, agency, or other body, which processes personal data soley on behalf of the data controller"
      - GDPR also restricts data tranfers to countries outside EU, with fines for violations
      - many orgs have created dedicated roles to oversee GDPR data laws are followed
  - **Data custodian**: a custodian is delegated, from the system owner, day-to-day responsibilities for properly storing and protecting data; responsible for the protection of data through maintenance activities, backing up and archiving, and preventing the loss or corruption and recovering data
  - **Data Steward**: a newer concept related to users of the data; those who use the data for the business purpose.
  - **Business/Mission Owners**:-  Typically own processes or programs. they ensure that all operations fit within the business goals and mission. This task includes ensuring that collected data is necessary for the business to function. Collecting unnecessary data wastes time and resources. Because the business/mission owner is primarily concerned with the overall business, conflicts between data owners, data custodians, and system owners may need to be resolved by the business/mission owner, who will need to make the best decision for the organization.
  - **Security administrator**: responsible for ensuring the overall security of entire infrastructure; they perform tasks that lead to the discovery of vulnerabilities, monitor network traffic and configure tools to protect the network (like firewalls and antivirus software) 
    - security admins also devise security policies, plans for business continuity and disaster recovery and train staff
  - **Supervisors**: responsible for overseeing the activities of all the above entities and all support personnel; they ensure team activities are conducted smoothly and that personnel is properly skilled for the tasks assigned
  - **Users**: any person who accesses data from a computer device or system to accomplish work (think of users as employees or end users)
    - users should have access to the data they need to perform tasks; users should have access to data according to their roles and their need to access info
    - must comply with rules, mandatory policies, standards and procedures
    - users fall into the category of subjects, and a subject is any entity that accesses an object such as a file or folder 
      - note that subjects can be users, programs, processes, services, computers, or anything else that can access a resource (OSG-9 Chpts 8, 13)
- 2.4.2 Data Collection
  - One of the easiest ways of preventing the loss of data is to simply not collect it
  - The **data collection guideline**: if the data doesn't have a clear purpose for use, don't collect it, and don't store it; this is why many privacy regulations mention limiting data collection
- 2.4.3 Data location
  - **Data location**: in this context, refers to the location of data backups or data copies
  - If a company's system is on-prem, keeps data on-site, but regularly backups up data, best practice is to keep a backup copy on site and backup copy off-site
  - Consider distance between data/storage locations to mitigate potential mutual (primary and backup) damage risk

- 2.4.4 Data maintenance
  - **Data maintenance**: managing data through the data lifecycle (creation, usage, retirement); data maintenance is the process (often automated) of making sure the data is available (or not available) based on where it is in the lifecycle
  - Ensuring appropriate asset protection requires that sensitive data be preserved for a period of not less than what is business-required, but for no longer than necessary
  - Encrypt sensitive data
  - Safeguard assets via basic security controls to enforce appropriate levels of confidentiality, integrity and availability and act per security policies, standards, procedures and guidelines
- 2.4.5 Data retention
  - Retention requirements apply to data or records, media holding sensitive data, systems that process sensitive data, and personnel who have access to sensitive data. Record retention policies define the amount of time to keep data, and laws or regulations often drive these policies.
    - **record retention**: retaining and maintaining info as long as it is needed, and destroying it when its no longer needed
      - note: a current trend in many orgs is to reduce legal liabilities by implementing short retention policies with email
  - Three fundamental retention policy questions:
    - **how to retain**: data should be kept in a manner that makes it accessible whenever required; take taxonomy (or the scheme for data classification) into account
    - **how long to retain data**: general guidelines for business data is 7 years (but can vary by country/region/regulation)
    - **what data**: to retain per org requirements
- 2.4.6 Data remanence
  - **Data remanence**: the data remaining on media after the data is supposedly erased
    - typically refers to data on a hard drive as residual magnetic flux or slack space (unused space within a disk cluster)
      - note that many OSs store files in clusters, which are groups of sectors (the smallest storage unit on a hard disk drive)
    - if media includes any type of private and sensitive data, it is important to eliminate data remanence
    - note that some OSs fill slack space with data from memory, which is why personnel should never process classified data on unclassified systems
    
- 2.4.7 Data destruction
  - Destroy sensitive data when it is no longer needed
  - An org's security or data policy should define the acceptable methods of destroying data based on the data's classification
  - a degausser can be used on a hard disk drives/magnetic media
  - the best SSD wiping method is destruction -- even when using manufacturers SSD wiping tools, data can remain, and therefore the best SSD wipe method is destruction
  - **Defensible destruction**: eliminating data using a controlled, legally defensible and regulatory compiant way

[2.5](#2.5) Ensure appropriate asset retention (e.g. End-of-Life EOL, End-of-Support (EOS)) (OSG-9 Chpt 5)
- Hardware: even if you maintain data for the appropriate retention period, it won’t do you any good if you don’t have hardware that can read the data
- Personnel: beyond retaining data for required time periods and maintaining hardware to read the data, you need personnel who know how to operate the hardware to execute restoraton processes

- **End-Of-Life (EOL)**: often identified by vendors as the time when they stop offering a product for sale
- **End-Of-Support (EOS)/End-Of-Service-Life (EOSL)**: often used to identify when support ends for a product
- EOL,EOS/EOSL can apply to either software or hardware

[2.6](#2.6) Determine data security controls and compliance requirements (OSG-9 Chpt 5)

- You need security controls that protect data in each possible state: at rest, in transit or in use
- Each state requires a different approach to security; note that there aren’t as many security options for data in use as there are for data at rest or data in transit
  -  keeping the systems patched, maintaining a standard computer build process, and running anti-virus/malware are typically the real-world primary protections for data in use

- 2.6.1 Data states (e.g., in use, in transit, at rest)
  - The three data states are at rest, in transit, and in use
    - **Data at rest**: any data stored on media such as hard drives or external media: Protecting Data at Rest: AES encryption, Access Control, redundancy/backup, Bitlocker, FileVault, symmetric encrytion e.g Serpent, IDEA

    - **Data in transit**: any data transmitted over a network: Protecting Data in Motion: TLS encryption, email encrytion (SMIME, PGP), IPSEC, VPN, SSH
        - SSH-2: Provides improved security with more robust encryption e.g AES and key exchange mechanisms. It also adds support for simultaneous shell sessions over a single SSH connection and Supports optional compression of data to improve  performance
        - IPsec: Provides strong encryption and is used in many VPNs. Operates at the Network layer. Transport Mode: Encrypts only the payload of the IP packet, leaving the header intact. Tunnel Mode: Encrypts both the payload and the header, creating a new IP header.
        - L2TP: Provides tunneling but requires IPsec for encryption. Operates at the Data link layer. perates at the data link layer and provides a framework for tunneling protocols. L2TP alone does not offer encryption or security but is typically used with IPsec to provide these features (L2TP/IPsec). often used in Point-to-Point Protocol PPP scenarios.
        - L2TPV3: L2TPv3 (Layer 2 Tunneling Protocol version 3) is an extension of L2TP (Layer 2 Tunneling Protocol) designed to provide more advanced features and improved capabilities. Extends L2TP to support tunneling of Layer 2 frames over IP networks, similar to the original L2TP but with additional features and improvements. Primarily used to carry Layer 2 traffic (e.g., Ethernet frames) over IP networks. It is useful for applications that require the transmission of Layer 2 protocols across an IP backbone.
        - PPTP: Older and less secure, generally not recommended. Operates at the Data link layer. Encapsulates PPP (Point-to-Point Protocol) frames into IP packets for transmission over the internet. PPTP itself provides encryption but is considered less secure compared to more modern protocols.
        - SSL/TLS: Strong encryption, often used in remote access VPNs. Operates at the Application link layer. Often used in remote access VPNs (SSL VPNs) and for securing web traffic (HTTPS).
        - IKEv2: Enhances IPsec with better performance and security. Operates at the Network layer (enhances IPsec).  Provides strong security and supports features like NAT traversal and seamless connection resumption.
        - OpenVPN: Flexible and secure with strong encryption, highly configurable. Operates at the Application layer (uses SSL/TLS).      
      - encryption methods protect data at rest and in transit
      - Asymmetric encryption (along with symmetric encryption) protects data in transit.
    - **Data in use**: data in memory and used by an application
      - applications should flush memory buffers to remove data after it is no longer needed: Protecting Data in Use (Harder to protect): RAM/memory data,
      - pervasive encryption,
      - prevent shoulder surfing,
      - parameter checking against buffer overflow,
      - Address space layout randomization (ASLR) is a memory-protection process for operating systems (OSes) that guards against buffer-overflow attacks by randomizing the location where system executables are loaded into memory
      - Purging memory buffers removes all remnants of data after a program has used it.
- **Type of RAM**: Static RAM and dynamic RAM are types of real memory and thus are all the same concept in relation to being volatile—­meaning they lose any data they were holding when power is lost or cycled.
    - Static RAM SRAM: Stores data using flip-flops. This means the data is retained as long as power is supplied. Faster because it doesn’t need to refresh. It can quickly read and write data. More expensive because it uses more transistors per bit of data and consumes more power.
    - Dynamic RAM DRAM: Stores data using capacitors and transistors. The data needs to be refreshed periodically to maintain its integrity. Slower due to the need for periodic refreshing of the data stored in capacitors. cost-effective for larger memory capacities and consumes less power.
    - Secondary memory is a term used to describe magnetic, optical, or flash media (i.e., typical storage devices like HDD, SSD, CD, DVD, and thumb drives). These devices will retain their contents after being removed from the computer and may later be read by another user.

- 2.6.2 Scoping and tailoring
  - **Baseline**: documented, lowest level of security config allowed by a standard or org
  - After selecting a control baseline, orgs fine-tune with tailoring and scoping processes; a big part of the tailoring process is aligning controls with an org's specific security requirements
  - **Tailoring**: refers to modifying the list of ✏️ security controls ✏️ within a baseline to align with the org's mission
    - includes the following activities:
      - identifying and designating common controls; specificaion of organization-defined parameters in the security controls via explicit assignment and selection statements
      - applying scoping guidance/considerations
      - selecting/specifying compensating controls
      - assigning control values
  - **Scoping**: limiting the general baseline recommendations by removing those that do not apply; part of the tailoring process and refers to reviewing a list of baseline ✏️ security controls ✏️ and selecting only those controls that apply to the systems you're trying to protect
    - scoping processes eliminate controls that are recommended in a baseline
    - Scoping is a part of the tailoring process and refers to reviewing a list of security controls and selecting the security controls that apply.

- 2.6.3 Standards selection
  - Organizations need to identify the standards (e.g. PCI DSS, GDPR etc) that apply and ensure that the security controls they select fully comply with these standards
  - Even if the org doesn't have to comply with a specific standard, using a well-designed community standard can be helpful (e.g. NIST SP 800 documents)
  - **Standards selection**: the process by which organizations plan, choose and document technologies or architectures for implementation
    - e.g. you evaluate three vendors for a security control; you could use a standards selection process to help determine which solution best fits the org
  - Vendor selection is closely related to standards selection but focuses on the vendors, not the technologies or solutions
  - The overall goal is to have an objective and measurable selection process 
    - if you repeat the process with a totally different team, the alternate team should come up with the same selection

- 2.6.4 Data protection methods (e.g., Digital Rights Management (DRM), Data Loss Prevention (DLP), Cloud Access Security Broker (CASB)) 
  - **Data protection methods** include: 
    - **digital rights management (DRM)**: methods used in attempt to protect copyrighted materials. there is hardware and software based DRMs. Methods used with DRM include:
         - Persistent online authentication
         - Automatic expiration
         - Continuous audit trail  
    - **Cloud Access Security Brokers (CASBs)**: software placed logically between users and cloud-based resources ensuring that cloud resources have the same protections as resources within a network
         - A cloud access security broker (CASB) is software placed logically between users and cloud-­based resources, and it can enforce security policies used in an internal network.
      - note that entities must comply with the EU GDPR, and use additional data protection methods such as pseudonymization, tokenization, and anonymization
  - One of the primary methods of protecting the confidentiality of data is encryption
  - Options for protecting your data vary depending on its state:
    - **Data at rest**: consider encryption for operating system volumes and data volumes, and backups as well
      - be sure to consider all locations for data at rest, such as tapes, USB drives, external drives, RAID arrays, SAN, NAS, and optical media
      - DRM is useful for data at rest because DRM "travels with the data" regardless of the data state
        - DRM is especially useful when you can’t encrypt data volumes
    - Data in transit: think of data in transit wholistically -- moving data from anywhere to anywhere; use encryption for data in transit 
      - e.g. a web server uses a certificate to encrypt data being viewed by a user, or IPsec encrypting a communication session 
      - most important point is to use encryption whenever possible, including for internal-only web apps
      - DLP solutions are useful for data in transit, scanning data on the wire, and stopping the transmission/transfer, based on the DLP rules set (e.g. outbound data that contains numbers matching a social security number pattern, a DLP rule can be used to block that traffic)
    - **Data in use**: 
      - CASB solution often combines DLP, a web application firewall with some type of authentication and authorization, and a network firewall in a single solution; A CASB solution is helpful for protecting data in use (and data in transit)
  - **Pseudonymization**: refers to the process of using pseudonyms or alias to represent other data
    - A pseudonym is an alias, and pseudonymization can prevent data from directly identifying an entity (i.e. person)
    - the process can be reversed
  - **Tokenization**: use of a token, typically a random string of characters, to replace other data
    - note that tokenization is similar to pseudonymization in that they are both used to represent other data, and the token or pseudonym have no meaning or value outside the process that creates and links them to that data
    - If company are reselling products to the same customers, they can use tokenization to save tokens that match the credit card data, instead of saving and storing credit card data.
    - example of tokenization used in CC transactions:
    - registration: app on user's smart phone securely sends CC info to the credit card processor (CCP)
    - The CCP sends the CC info to a tokenization vault, creating a token and associating it with the user's phone
    - usage: when the user makes a purchase, the POS system sends the token to the CCP for authorization
    - validation: the CCP sends the token to the tokenization vault; the vault replies with the CC info, the charge is processed
    - completing the sale: the CCP sends a reply to the POS indicating the charge is approved
    - this system prevents CC theft at the POS system
    - Tokenization replaces other data with a random string of characters. These tokens are then matched to the actual values for secure lookups as needed. 
- **Anonymization** removes all personally identifiable data to ensure that the original subject cannot be identified.
    -  Anonymization techniques remove all personal data and make the data unusable for
reuse on the website.
- **Data masking** obscures some, but not all, data.
- **Perturbation** is the use of false or misleading data in a database management system in order to redirect or thwart information confidentiality attacks.

🥇 Sometimes it is better to collect limited information 🥇

- **Policy ▶️ Standard ▶️ Baseline ▶️ Guideline ▶️Procedure**
    - **Policy**: Policy is High level from Management 
    - **Standard** mandatory, must meet EXACTLY, no more, no less e.g DoD 8570, AR 25-2, NIST SP , 800 53
    - **Baseline** mandatory, must meet AT LEAST, can do more than it requires e.g CIS Benchmarks
    - **Guideline** suggested practices, not mandatory e.g DoD STIGs, Microsoft NSA, PCI DSS, NIST 800-88

