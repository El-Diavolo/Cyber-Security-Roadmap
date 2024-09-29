# Cyber Security Roadmap

---

**This is a compilation of resources I gathered while learning the essential skills needed to excel in cybersecurity.**

**I initially created this as a personal guide to help me navigate the various paths in the field, but then I thought, why not share it with everyone?**

**This roadmap is still a work in progress, as I'm continuously learning and updating it with new information. It’s not an exhaustive list, but it’s a great starting point.**

**🔗 Connect with me: [LinkedIn](https://www.linkedin.com/in/hamood-al-marhoubi-8baaa1260/)**
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

By building a strong foundational knowledge in these areas, you'll be better equipped to tackle more advanced cybersecurity topics and challenges in your career.


 
