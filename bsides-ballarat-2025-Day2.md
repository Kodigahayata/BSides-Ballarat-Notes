# BSides Ballarat 2024 Security Conference
## Day 2: Sunday, 4th May 2024

## 1. Running K7 Cyberdetective Game
**Presenter:** Simon Lavigne, Microsoft

### Key Takeaways:
- K7 Cyber is a free cybersecurity training platform built by Microsoft engineers
- Designed specifically for Engineers and Analysts to develop practical security skills
- Offers interactive, game-based learning experiences to improve cybersecurity competencies

### Resources:
- **Main Website:** [KC7 Cyber](https://kc7cyber.com/modules)
- **Community:** [KC7 Community](https://kc7cyber.com/community)
- **Introduction:** [KC7 Intro](https://kc7cyber.com/intro/927)
- **Quick Access:** [KC7 Direct Link](https://kc7cyber.com/go/DHM6AA)
- **Pivots Documentation:** [KC7 Pivots](https://kc7cyber.com/pivots)

### Practical Value:
This platform provides an engaging way for your team to practise and enhance their cybersecurity skills through realistic scenarios. Consider scheduling regular team sessions to work through modules together, which could strengthen collaborative problem-solving skills whilst building individual expertise.

---

## 2. Understanding the Cyber World of Attackers and Defenders
**Presenter:** Anurag Khanna

### Key Takeaways:
- **Social Engineering Techniques and MFA Bypass:** Sophisticated attackers are targeting authentication systems through social manipulation
- **FIDO Security:** Physical authentication devices (USB keys, smart cards) provide stronger protection than traditional password-based methods
- **Password Manager Vulnerabilities:** Password managers themselves are becoming high-value targets
- **Directory Service Attacks:** NTDS.DIT files contain valuable credential data that attackers seek to extract
- **Identity Provider Targeting:** IdPs represent a central point of compromise for accessing multiple systems
- **Blind Spots in Security:** Some systems (like DVR recorders and ESXi hosts) may not support EDR solutions, creating security gaps
- **Covert Communication Channels:** Residential proxies are being sold as services to mask attacker origins
- **LOST (Living Off Security Tooling):** Attackers repurposing legitimate security tools for malicious purposes
- **Remote Management Tools:** RMM tools present both operational benefits and security risks
- **Modern Network Structures:** Software-defined networks like Tailscale changing the security landscape
- **Exfiltration Methods:** Cloud-based exfiltration using an organisation's native tools to avoid detection

### Resources:
- **Presentation Slides:** [RudraSec.io Talks](https://www.rudrasec.io/talks/)
- **NTDS.DIT Extraction Reference:** [Extracting Password Hashes from NTDS.DIT](https://blog.netwrix.com/2021/11/30/extracting-password-hashes-from-the-ntds-dit-file/)

### Practical Value:
This session highlights critical attack vectors your team should be aware of, particularly how attackers are evolving to bypass modern security controls. Consider reviewing your organisation's MFA implementation, assessing security blind spots where EDR cannot be deployed, and evaluating the security of your identity providers and remote management tools.

---

## 3. IoT Cybersecurity Rules, Regulations, Code, Guidelines & Standards
**Presenter:** Matt Tett, Enex Testlab

### Key Takeaways:
- **Regulatory Framework:** Overview of various standards, recommendations, guidelines, and codes governing IoT security
- **Upcoming Legislation:** Cybersecurity Bill introducing mandatory security standards for smart devices, effective 4th March 2026
- **Certification Programmes:** Introduction of Cyber Trust Mark programme for IoT device certification

### Resources:
- **IoT Security Certification:** [IoT Security Trust Mark](https://iotsecuritytrustmark.org)

### Practical Value:
For teams working with IoT devices or those in compliance roles, this session provides crucial information about upcoming regulatory requirements. Begin preparing now for the 2026 security standards by assessing your IoT device inventory and establishing compliance roadmaps.

---

## 4. Cyber Supply Chain Risk
**Presenter:** Narain Singh, Telstra

### Key Takeaways:
- **Supply Chain Attack Components:** The complex relationship between threat actors, vendors, compromised products, and targeted systems
- **Hidden Impacts:** Organisations may be affected by supply chain breaches even without direct compromise
- **Attribution Challenges:** Distinction between claimed and unclaimed cyber attacks complicates response and analysis

### Practical Value:
This session emphasises the need for comprehensive vendor security assessments and third-party risk management practices. Consider developing or enhancing your supply chain risk assessment framework, particularly focusing on critical vendors with access to sensitive systems or data.

---

## 5. Detecting Scattered Spider: Mitre Attack Perspective
**Presenter:** Aditya Patil, Telstra (Cyber Instructor)

### Key Takeaways:
- **Scattered Spider Tactics:** This threat actor group employs various techniques including:
  - SMS and voice phishing
  - SIM swapping attacks
  - MFA bombing (push notification fatigue)
  - Credential theft operations
- **MITRE ATT&CK Framework:** Using MITRE's classification to understand and defend against micro-attacks
- **Responsible AI Disclosure:** Considerations for AI usage in security contexts

### Practical Value:
Understanding specific threat actor methodologies can help your team develop targeted defence strategies. Consider conducting tabletop exercises based on Scattered Spider's tactics to test your organisation's resilience against these specific attack methods, particularly focusing on your MFA implementation and response to potential notification fatigue attacks.

---

## 6. Case Study: How We Hacked and Translated The Great Ace Attorney
**Presenter:** Adib Surani, Scarlet Study

### Key Takeaways:
- Detailed reverse engineering demonstration similar to techniques used for game cheats
- Live demonstration of penetration testing techniques

### Resources:
- **Presenter's Website:** [adib.au](https://adib.au/)

### Practical Value:
While focused on game hacking, this session demonstrates practical reverse engineering techniques that have broader application in security testing. The methodologies shown can inform your team's approach to application security testing and vulnerability research.

---

## 7. Behind the Breach: Exploring Digital Forensics and Incident Response
**Presenter:** Richard Grainger, Triskele Labs

### Key Takeaways:
- **Real-world Breach Response:** Case studies of actual security incidents and response measures
- **Ransom Negotiations:** Recorded examples of C-level executives negotiating with threat actors to prevent public disclosure

### Practical Value:
These real-world examples provide valuable insights into breach handling and executive communication during security incidents. Consider using these scenarios to develop or refine your incident response playbooks and executive communication plans for security incidents.

---

## 8. Your Identity is Under Attack: How to Fight Back and Win
**Presenter:** Kanik Sachdeva, Medibank

### Key Takeaways:
- **Identity Security Fundamentals:** The critical importance of identity protection in modern security
- **Identity Hygiene Practices:** Essential maintenance for identity systems
- **Assessment Tools:**
  - BloodHound: Maps attack paths to critical assets
  - AzureHound: BloodHound equivalent for Azure environments
  - Hatchet: Tool for cracking password hashes
- **Attack Path Analysis:** Emphasis on attackers targeting the weakest identity link to gain access
- **Blue Team Tools:** FalconHound for defensive teams

### Practical Value:
This session provides practical tools and techniques for assessing and improving your organisation's identity security posture. Consider implementing regular BloodHound assessments to identify potential attack paths through your identity infrastructure, and evaluate FalconHound for your blue team operations.

---

## 9. Web Hacking for Beginners
**Presenter:** Chuanshu Jiang, Shea Security

### Key Takeaways:
- **Application Security Fundamentals:** Introduction to web application security concepts
- **Security Standards:** Overview of OWASP and MITRE CWE frameworks
- **CSRF Attacks:** Focus on Cross-Site Request Forgery (1-click attacks) via GET requests
- **Protection Mechanisms:** Discussion of SameSite cookie attributes as a defensive measure

### Resources:
- **Presenter Information:** [Shea Security Team](https://sheasecurity.com.au/team/)

### Practical Value:
This session provides foundational knowledge for teams looking to improve their web application security practices. Consider reviewing your web applications for CSRF vulnerabilities and implementing appropriate SameSite cookie policies across your web properties.

---

## Action Items for Your Team

Based on these conference sessions, consider the following action items:

1. **Skill Development:**
   - Explore the KC7 Cyber platform for team training exercises
   - Schedule regular security training sessions using interactive platforms

2. **Defensive Measures:**
   - Review and enhance MFA implementation to resist bypass techniques
   - Evaluate FIDO implementation for critical systems
   - Assess security coverage for devices that cannot run EDR (like DVR systems)
   - Implement SameSite cookie attributes for web applications

3. **Tool Adoption:**
   - Test BloodHound/AzureHound to map potential attack paths
   - Evaluate FalconHound for blue team operations

4. **Process Improvements:**
   - Enhance vendor security assessment processes
   - Update incident response playbooks based on real-world examples
   - Prepare for upcoming IoT security regulations (2026 deadline)

5. **Risk Assessment:**
   - Identify systems vulnerable to "Living Off Security Tooling" attacks
   - Review remote management tool security configurations
   - Assess identity provider security posture

---

## Image Gallery

*Consider adding your conference photos here with appropriate captions. Below is a suggested format for including images in your GitHub Markdown document:*

```markdown
### Session 1: K7 Cyberdetective Game
![Simon Lavigne presenting the K7 Cyberdetective platform](./images/session1-k7cyber.jpg)
*Caption: Simon Lavigne demonstrating the interactive elements of the K7 Cyberdetective training platform*

### Session 2: Understanding the Cyber World of Attackers and Defenders
![Anurag Khanna discussing social engineering techniques](./images/session2-attackers-defenders.jpg)
*Caption: Anurag Khanna explaining how attackers bypass MFA through social engineering*

... and so on for each session ...
```

*For optimal results, consider creating an "images" folder in your repository and using relative paths to reference your photos as shown above.*