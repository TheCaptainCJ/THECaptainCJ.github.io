---
layout: default
---

# Chris's Cybersecurity Portfolio

_Showcase My Skills for My Future Employer_

---

## Links

Here are some useful links related to my work and learning:

- [GitHub](https://github.com/yourusername)
- [LinkedIn](https://linkedin.com/in/yourprofile)
- [TryHackMe Profile](https://tryhackme.com/p/yourprofile)

---

## Photos/Screenshots

### Project Screenshot 1
![Screenshot 1](path/to/screenshot1.png)

### Project Screenshot 2
![Screenshot 2](path/to/screenshot2.png)

*Add more images as needed to highlight your projects.*

---

## Skills

Here is a list of the skills I bring to cybersecurity:

- Python scripting and automation
- Cloud security assessments
- Penetration testing
- Vulnerability management
- Network security monitoring
- Data encryption and decryption
- Incident response planning
- Ethical hacking and tools
- Security information and event management (SIEM)

---

## Security+ Terminology

Here’s an organized list of key cybersecurity terms:

1. **Confidentiality**: Ensuring information is not disclosed to unauthorized individuals.
2. **Integrity**: Protecting data from being altered or tampered with.
3. **Availability**: Ensuring systems and data are accessible when needed.
4. **Encryption**: Converting data into a secure format to prevent unauthorized access.
5. **Firewall**: A security device that monitors and controls incoming and outgoing network traffic.
6. **Phishing**: A cyberattack where attackers trick individuals into providing sensitive information.
7. **Zero-Day Exploit**: A vulnerability that is exploited before a patch is available.
8. **Authentication**: Verifying the identity of a user, system, or entity before granting access.
9. **Authorization**: Granting permissions and access to resources based on authenticated identity.
10. **Multi-Factor Authentication (MFA)**: Using two or more authentication methods to verify identity.
11. **Malware**: Software designed to disrupt, damage, or gain unauthorized access to systems.
12. **Ransomware**: Malware that encrypts a victim’s files and demands payment for their release.
13. **Denial-of-Service (DoS)**: An attack that disrupts services by overwhelming them with traffic.
14. **Botnet**: A network of infected devices controlled by an attacker to perform malicious tasks.
15. **Social Engineering**: Manipulating individuals to divulge confidential information or perform actions.
16. **Man-in-the-Middle (MitM) Attack**: Intercepting communication between two parties to steal data.
17. **Public Key Infrastructure (PKI)**: A framework for managing digital certificates and encryption keys.
18. **Intrusion Detection System (IDS)**: Monitors network traffic for suspicious activity and potential threats.
19. **Intrusion Prevention System (IPS)**: Actively blocks detected threats in real time.
20. **Patch Management**: Updating software to fix vulnerabilities or improve functionality.

---

## File Organizer Python Script

This Python script organizes files in a folder by their file types, creating separate directories for each type.

```python
import os
import shutil

def organize_files(directory):
    for filename in os.listdir(directory):
        file_extension = filename.split('.')[-1]
        folder = os.path.join(directory, file_extension)
        if not os.path.exists(folder):
            os.makedirs(folder)
        shutil.move(os.path.join(directory, filename), folder)

if __name__ == "__main__":
    organize_files("path_to_your_folder")
    print("Files organized by type!")
