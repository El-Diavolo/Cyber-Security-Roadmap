# Cyber Security Roadmap

---

**This is a compilation of resources I gathered while learning the essential skills needed to excel in cybersecurity.**

**I initially created this as a personal guide to help me navigate the various paths in the field, but then I thought, why not share it with everyone?**

**This roadmap is still a work in progress, as I'm continuously learning and updating it with new information. It’s not an exhaustive list, but it’s a great starting point.**

**🔗 Connect with me: [LinkedIn](https://www.linkedin.com/in/hamood-al-marhoubi-8baaa1260/)** [Instagram](https://www.instagram.com/hamood.marhubi/)
---


# Chapter 1: Introduction and Overview

## 1.1 Purpose of the Roadmap
This roadmap is designed to guide beginners through the complex world of cybersecurity, providing a structured pathway to help you build a strong foundation and advance in your chosen field. It covers key areas like Red Team (offensive security), Blue Team (defensive security), Governance, Risk, and Compliance (GRC), Cloud Security, and more. The roadmap is divided into sections that will help you understand what skills to acquire, what tools to learn, and how to gain hands-on experience.

**How to Use This Roadmap:**
- **Follow Your Interest:** Start with the basics and choose the path that aligns with your career goals.
- **Hands-On Learning:** Engage in labs, capture-the-flag (CTF) challenges, or simulations wherever possible.
- **Certifications and Courses:** Identify certifications that are beneficial for your chosen path, which will be highlighted in each section.
- **Stay Updated:** Cybersecurity is constantly evolving, so staying current with the latest trends, tools, and vulnerabilities is crucial.

## 1.2 Why Cybersecurity?
Cybersecurity is one of the most critical fields today, protecting organizations and individuals from cyber threats like hacking, data breaches, and malware. The importance of cybersecurity continues to grow with the increasing reliance on technology in all sectors. As a cybersecurity professional, you'll have the opportunity to safeguard systems, detect and respond to incidents, and contribute to the resilience of the digital world.

**Potential Career Paths:**
- **Red Team (Offensive Security):** Engage in ethical hacking, penetration testing, and vulnerability assessments to identify and exploit weaknesses in systems.
- **Blue Team (Defensive Security):** Focus on defense mechanisms, incident response, and threat hunting to protect against attacks.
- **Governance, Risk, and Compliance (GRC):** Ensure organizations comply with regulations, manage risks, and develop policies and procedures to safeguard information.
- **Cloud Security:** Specialize in securing cloud environments, understanding the unique challenges of protecting data in the cloud.
- **Digital Forensics:** Analyze cyber incidents, collect evidence, and support investigations related to cybercrime.

Cybersecurity offers a wide range of exciting and rewarding career opportunities, with roles that are both technically challenging and critically important. Whether you’re interested in offense, defense, policy, or management, this roadmap will help you navigate your journey in this ever-evolving field.

## 1.3 Structure of the Roadmap

### Roadmap Layout
This roadmap is designed to guide you from beginner to advanced levels:

- **Foundational Knowledge**: Begin with basic IT skills, networking, and the fundamentals of cybersecurity.
- **Specialized Tracks**: Choose your path—whether it’s Red Team, Blue Team, GRC, or Cloud Security—based on your interests and career goals.
- **Skill Building and Continuous Learning**: Sharpen your skills with hands-on projects, labs, certifications, and by engaging with the community.

### Levels of Expertise
- **Beginner**: Get started with networking basics, core security concepts, and essential skills.
- **Intermediate**: Dive deeper into specific tools, techniques, and practical applications.
- **Advanced**: Tackle advanced topics, work on complex projects, and gear up for professional roles.

## 1.4 Key Tips for Beginners

- **Consistency is Key**: Set a regular study schedule and stick to it. Consistent, small steps add up to big progress over time.
- **Hands-On Practice**: Theory is important, but getting hands-on with labs, CTFs, and personal projects is where the real learning happens.
- **Community Engagement**: Join cybersecurity communities, engage in forums, and network with others. Learning from peers can speed up your progress and keep you motivated.

## 1.5 Setting Goals and Tracking Progress

### Goal Setting
Define clear goals for your journey. Set short-term targets, like finishing a specific course or lab, and aim for long-term achievements, like getting certified or landing your first job in cybersecurity.

### Tracking Progress
Keep an eye on what you’ve learned and what’s next. Use study logs, task management apps, or GitHub projects to track your progress. Regularly review your goals and tweak your learning plan as needed.

# 2. Foundational Knowledge

So now let us start on the foundational knowledge you need for cybersecurity. This section will cover essential concepts in IT and networking, key cybersecurity principles, Linux fundamentals, and basic programming skills, all of which are crucial for building a solid foundation for your cybersecurity career.

### Basics of IT and Networking
Understanding IT and networking is vital in cybersecurity. Here are the key topics you should focus on:

- **Networking Concepts**: Learn about how networks operate, including how devices communicate with one another. Familiarize yourself with concepts like **LAN** (Local Area Network), **WAN** (Wide Area Network), **VPN** (Virtual Private Network), and the different types of network topologies.

- **OSI Model**: The OSI (Open Systems Interconnection) Model is a framework that helps understand how data travels across networks. It consists of seven layers: 
  1. **Physical Layer**: Hardware transmission.
  2. **Data Link Layer**: Node-to-node data transfer.
  3. **Network Layer**: Routing and forwarding.
  4. **Transport Layer**: End-to-end communication.
  5. **Session Layer**: Managing sessions between applications.
  6. **Presentation Layer**: Data translation and encryption.
  7. **Application Layer**: End-user software interaction.

- **TCP/IP**: Understand the TCP/IP (Transmission Control Protocol/Internet Protocol) model, which is the foundation of the internet. It includes protocols for various functions, like **IP addressing**, **subnetting**, and **routing**.

- **DNS**: Learn about the Domain Name System, which translates human-readable domain names (like www.example.com) into IP addresses. This is crucial for navigating the internet.

- **HTTP/HTTPS**: Understand how the Hypertext Transfer Protocol (HTTP) and its secure version, HTTPS, work. Recognize the importance of HTTPS in securing data transmitted over the internet.

- **Resources**: To dive deeper, look for free online courses on platforms like Coursera, edX, or YouTube. Many tutorials and videos explain these concepts clearly, making it easier to grasp the fundamentals.

#### References and Where to Learn More
- Cisco Networking Academy. (n.d.). [Networking Basics](https://www.netacad.com/courses/packet-tracer/networking-fundamentals)
- Youtube CCNA Course by NetworkChuck [CCNA-Cource](https://www.youtube.com/watch?v=S7MNX_UD7vY&list=PLIhvC56v63IJVXv0GJcl9vO5Z6znCVb1P)
- TryHackMe Networking Fundamentals lab [Network Fundamentals](https://tryhackme.com/module/network-fundamentals)
- Cybrary Lab [Cisco Certified Network Associate (CCNA 200-301) Labs](https://www.cybrary.it/practice-lab/cisco-certified-network-associate-ccna)

### Introduction to Cybersecurity Concepts
Once you have a grasp of IT and networking, it’s time to explore key cybersecurity concepts:

- **CIA Triad**: Familiarize yourself with the CIA Triad, which represents the core principles of cybersecurity:
  - **Confidentiality**: Ensuring that sensitive information is only accessible to authorized users.
  - **Integrity**: Protecting data from being altered or tampered with by unauthorized individuals.
  - **Availability**: Ensuring that information and resources are accessible to authorized users when needed.

- **Security Principles**: Understand fundamental security principles, such as least privilege (users should have only the access necessary to perform their job), defense in depth (implementing multiple layers of security), and security by design (integrating security into the development process).

- **Threat Models**: Learn about various threat models that describe potential risks and vulnerabilities in systems. Familiarize yourself with common threats like malware, phishing, denial-of-service attacks, and insider threats.

#### References and Where to Learn More
- Youtube [What is Cyber Security](https://www.youtube.com/watch?v=inWWhr5tnEA)
- Rouse, M. (2020). [CIA Triad](https://www.techtarget.com/search/query?q=CIA+triad)
- Cyber Security Concepts [The 5 Concepts of Cyber Security](https://www.ebcgroup.co.uk/news-insights/the-5-concepts-of-cyber-security)
- Try Hack Me Lab [Introduction to Cyber Security](https://tryhackme.com/module/introduction-to-cyber-security)

### Linux Fundamentals
Linux is a critical operating system in the cybersecurity field, so it’s essential to become familiar with it:

- **Command Line Basics**: Get comfortable using the command line interface (CLI). Learn basic commands for navigating directories, managing files, and executing scripts.

- **File Systems**: Understand how Linux file systems work, including file permissions, ownership, and structure (like the root directory and common directories such as `/bin`, `/etc`, and `/usr`).

- **Basic Security Tools**: Explore essential Linux security tools like `iptables` for firewall management, `fail2ban` for protecting against brute-force attacks, and `Wireshark` for network traffic analysis.

#### References and Where to Learn More
- Linux Foundation. (n.d.). [Introduction to Linux](https://www.edx.org/course/introduction-to-linux)
- OverTheWire [Linux Challenges](https://overthewire.org/wargames/)
- Geeksforgeeks [Linux/Unix Tutorial](https://www.geeksforgeeks.org/linux-tutorial/)
- TCM Security Free Course [Linux 100: Fundamentals](https://academy.tcm-sec.com/p/linux-fundamentals)


### Programming and Scripting
Programming skills are vital for automating tasks and understanding how software vulnerabilities work:

- **Basics of Python**: Start with Python, a versatile programming language often used in cybersecurity. Learn about data types, control structures, functions, and libraries. Python is useful for scripting and automating tasks, such as writing simple security tools or data analysis scripts.

- **Bash Scripting**: Familiarize yourself with Bash scripting for automating tasks in a Linux environment. Understand how to write scripts that perform repetitive tasks, manage files, and interact with system commands.

- **Other Relevant Languages**: Depending on your area of interest, you may want to explore other languages, such as JavaScript for web security or C/C++ for understanding lower-level programming concepts and software vulnerabilities.

#### References and Where to Learn More
- Youtube Bash Scripting [Bash Scripting Tutorial](https://www.youtube.com/watch?v=tK9Oc6AEnR4&pp=ygUOQmFzaCBzY3JpcHRpbmc%3D)
- Codecademy [Learn Bash](https://www.codecademy.com/learn/learn-the-command-line)
- TCM Security Free Course [Programming 100:Fundamentals](https://academy.tcm-sec.com/p/programming-100-fundamentals)
 - Codecademy [Learn Python](https://www.codecademy.com/catalog/language/python)

# 3. Pathways into Cybersecurity
Cybersecurity is a broad field with numerous specialized departments, each offering unique career opportunities. Whether you're interested in policy, offensive security, defending networks, or working with cloud systems, there’s a role for you. Below, we’ll explore different departments and the skills, tools, and certifications that align with each.

### 3.1 Governance, Risk, and Compliance (GRC)

**Governance, Risk, and Compliance (GRC)** is one of the most vital, yet often less flashy, aspects of cybersecurity. It focuses on the policies, processes, and controls that help organizations manage risk, adhere to regulatory requirements, and establish a comprehensive cybersecurity governance framework. GRC plays a strategic role in ensuring that organizations not only protect their systems and data but also operate in accordance with industry standards and legal mandates.

#### What is GRC?
GRC is the integrated collection of capabilities that enable an organization to reliably achieve objectives, address uncertainty, and act with integrity. It ensures that businesses align their IT goals with business objectives while managing risks and complying with regulatory demands. The three pillars of GRC—Governance, Risk Management, and Compliance—are closely intertwined, with each playing a critical role in the overall security strategy:

- **Governance**: Governance refers to the system of rules, practices, and processes by which an organization is directed and controlled. In cybersecurity, governance ensures that an organization's cybersecurity activities align with its business goals and regulatory requirements. It involves setting policies, establishing accountability, and ensuring leadership oversight.

- **Risk Management**: Risk management involves identifying, assessing, and mitigating risks to the organization. Cybersecurity risk management includes evaluating potential threats like data breaches, malware, and insider threats, and taking steps to minimize their impact on business operations. This process typically includes risk assessments, vulnerability management, and ongoing monitoring of risks.

- **Compliance**: Compliance refers to adhering to laws, regulations, and industry standards. Organizations need to follow various security standards depending on their industry and location, such as **ISO/IEC 27001**, **GDPR**, **HIPAA**, and **PCI-DSS**. Compliance ensures that an organization meets these regulatory requirements, which often include strict guidelines for data protection, privacy, and information security.

---

#### Key Responsibilities of GRC Professionals

Professionals working in GRC play a strategic role, ensuring that cybersecurity measures are not only effective but also compliant with legal and regulatory requirements. Here are some of the main responsibilities:

1. **Developing Cybersecurity Policies and Procedures**:
   - GRC professionals create and maintain policies that govern how cybersecurity should be implemented within an organization. These policies may cover a wide range of areas, including data protection, incident response, password management, encryption, and user access control. These policies serve as a blueprint for the entire organization, guiding employees and stakeholders on how to handle sensitive data, manage access, and respond to potential threats.

2. **Risk Assessments and Risk Management**:
   - One of the primary responsibilities is to perform risk assessments. This involves identifying the cybersecurity risks that an organization faces, such as potential data breaches, vulnerabilities in the network, and compliance risks. After identifying these risks, the GRC team evaluates their likelihood and potential impact, allowing the organization to prioritize and address high-risk areas. Effective risk management strategies are then developed to mitigate identified risks. GRC professionals work with other teams to ensure that risk management processes are continually updated and improved.

3. **Regulatory Compliance and Audits**:
   - GRC professionals ensure that the organization complies with relevant industry standards and government regulations. Failure to comply with regulations like **GDPR** (for data protection) or **HIPAA** (for healthcare data) can result in hefty fines and legal issues. GRC teams prepare the organization for audits by documenting processes, maintaining logs, and generating reports that demonstrate compliance. They often work with internal and external auditors to ensure that the organization passes compliance audits without issues.

4. **Vendor Risk Management**:
   - Many organizations work with third-party vendors, who may access sensitive data or interact with the organization's network. GRC professionals assess the cybersecurity practices of these vendors to ensure they don’t introduce additional risks. Vendor risk management involves evaluating the security controls of third parties and ensuring that contracts include clauses that protect the organization from liabilities arising from a vendor's security breach.

5. **Incident Response Planning**:
   - While incident response is often handled by the Blue Team, the GRC team plays a critical role in developing and maintaining an incident response plan. This plan outlines the steps that the organization will take in the event of a cybersecurity incident, such as a data breach or malware attack. The GRC team ensures that the plan complies with regulatory requirements and industry best practices. They also ensure that all employees are aware of their roles and responsibilities during an incident.

6. **Business Continuity and Disaster Recovery**:
   - GRC professionals ensure that cybersecurity measures align with the organization's business continuity and disaster recovery (BC/DR) plans. These plans outline how the organization will continue to operate during and after a major incident, such as a cyberattack or natural disaster. GRC teams ensure that cybersecurity controls are in place to protect critical systems and data, allowing the business to recover quickly.

---

#### Core Skills Required for GRC

1. **Understanding of Regulatory Frameworks**:
   - GRC professionals need a deep understanding of various regulatory frameworks and standards, such as:
     - **ISO/IEC 27001**: An international standard for information security management systems (ISMS).
     - **General Data Protection Regulation (GDPR)**: The EU regulation for data privacy and protection.
     - **Payment Card Industry Data Security Standard (PCI-DSS)**: A security standard for organizations that handle credit card information.
     - **Health Insurance Portability and Accountability Act (HIPAA)**: U.S. regulations for safeguarding healthcare information.

2. **Risk Management**:
   - Risk management is a cornerstone of GRC. GRC professionals must be skilled in identifying, assessing, and mitigating risks. They use frameworks like **NIST Risk Management Framework** and tools like **Archer** to assess and manage risk effectively.

3. **Communication and Reporting**:
   - Strong communication skills are essential for GRC roles, as professionals must articulate complex cybersecurity risks and regulatory requirements to non-technical stakeholders, including executives and board members. This often involves preparing detailed reports, presentations, and audits to demonstrate the organization’s compliance and risk posture.

4. **Project Management**:
   - GRC initiatives often require large-scale project management, especially when implementing new compliance measures or responding to regulatory changes. Professionals need to manage timelines, coordinate with various departments, and ensure that projects are completed efficiently.

5. **Policy Writing and Documentation**:
   - Writing clear and concise policies, procedures, and guidelines is a significant part of the GRC role. These documents ensure that all staff members understand and adhere to the organization’s security and compliance requirements.

---

#### Common Tools Used in GRC

- **GRC Platforms**: 
  - Tools like **Archer GRC**, **RiskWatch**, **SAP GRC**, and **MetricStream** are commonly used for managing governance, risk, and compliance initiatives. These platforms help automate processes, track compliance status, and generate reports for auditors and management.

- **Audit and Compliance Tools**:
  - Tools like **Qualys** and **Tenable** are used for vulnerability assessments and continuous compliance monitoring. They help ensure that the organization is meeting regulatory requirements and adhering to security best practices.

- **Risk Management Tools**:
  - **Archer**, **RiskWatch**, and other platforms allow GRC professionals to conduct risk assessments, track remediation efforts, and continuously monitor risks.

---

#### Certifications for GRC Professionals

- **Certified Information Systems Auditor (CISA)**:
  - This certification is ideal for those looking to focus on IT auditing, risk assessment, and regulatory compliance. It teaches essential skills in auditing information systems and managing cybersecurity risks.

- **Certified in Risk and Information Systems Control (CRISC)**:
  - CRISC is specifically focused on IT risk management and control. It’s designed for professionals who want to manage risks, design control frameworks, and ensure compliance with regulatory standards.

- **Certified Information Security Manager (CISM)**:
  - CISM is targeted at those in security management roles, focusing on governance, risk management, incident response, and security strategy.

- **Certified Information Systems Security Professional (CISSP)**:
  - While CISSP covers a broad range of topics, its governance and risk management sections are especially relevant to GRC professionals. It’s highly respected across the cybersecurity industry and is often seen as a gateway to senior management positions.

---

#### Career Paths in GRC

1. **GRC Analyst**: 
   - Entry-level role focused on assisting with policy development, performing risk assessments, and ensuring compliance with regulatory standards.

2. **GRC Manager**: 
   - Oversees the organization’s overall GRC strategy, manages a team of analysts, and ensures that the organization complies with all relevant regulations.

3. **Chief Risk Officer (CRO)**: 
   - A senior executive role responsible for managing the organization's risk management strategy. The CRO often reports directly to the board of directors and works closely with other C-suite executives.

4. **Chief Compliance Officer (CCO)**:
   - The CCO is responsible for ensuring that the organization complies with all relevant laws, regulations, and internal policies. This role typically requires extensive experience in compliance management.

---

#### Why GRC is Crucial for Cybersecurity

GRC ensures that organizations can manage their cybersecurity risks while staying compliant with regulations. Without GRC, companies might face hefty fines, data breaches, and reputational damage. GRC is not just about following the rules; it’s about creating a culture of security that permeates every level of the organization.

---


