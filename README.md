# LoneStarkN-V1 CTF  
*An Immersive Beginner Cybersecurity Challenge*  

## 🌟 Project Overview  
**Developed:** June 2023 | **Published:** [June 25/2023]  
**Author:** Ajay Kumar  
**Target Audience:** Cybersecurity beginners & enthusiasts  

Originally created for hands-on penetration testing practice and later submitted to **Vulnweb** and **TryHackMe**, this CTF is now publicly available to help aspiring security professionals develop essential skills through practical challenges.  

---
```mermaid
%%{init: {'theme': 'dark', 'themeVariables': {
  'primaryColor': '#0a192f',
  'primaryBorderColor': '#64ffda',
  'lineColor': '#64ffda',
  'nodeTextColor': '#e6f1ff',
  'fontFamily': 'Courier New'
}}}%%
flowchart TD
    ROOT[[LoneStarkN-V1 CTF\n(June 2023)]]:::root

    ROOT --> OSINT
    ROOT --> BRUTE
    ROOT --> STEGO
    ROOT --> PRIVESC

    OSINT[OSINT Challenge\n• Find hidden credentials\n• Analyze metadata]:::osint
    BRUTE[Brute Force\n• Crack passwords\n• Hydra/John attacks]:::brute
    STEGO[Steganography\n• Extract hidden data\n• Use steghide/binwalk]:::stego
    PRIVESC[Privilege Escalation\n• Linux/Windows\n• Sudo misconfigs]:::privesc

    classDef root fill:#1a1a2e,stroke:#64ffda,stroke-width:3px,font-size:18px
    classDef osint fill:#3a0ca3,stroke:#4cc9f0
    classDef brute fill:#f8961e,stroke:#f3722c
    classDef stego fill:#7209b7,stroke:#b5179e
    classDef privesc fill:#d90429,stroke:#ef233c
```
---

## 🔥 Key Learning Objectives  
This CTF is designed to teach foundational techniques through realistic scenarios:  

| Category              | Skills Demonstrated                          | Tools/Techniques                     |
|-----------------------|---------------------------------------------|--------------------------------------|
| **Brute Forcing**     | Password cracking, credential harvesting    | Hydra, John the Ripper, wordlists    |
| **Steganography**     | Data hiding & extraction from files         | steghide, binwalk, EXIF tools        |
| **OSINT**            | Open-source intelligence gathering          | Metadata analysis, social profiling  |
| **Privilege Escalation** | System privilege exploitation            | Linux sudo misconfigs, Windows token manipulation |

---

## 🛠️ CTF Contents  
The challenge package includes:  
- `LoneStarkN-V1.ova`: Pre-configured virtual machine (VM) for testing   
- `ScreenShots`: Proff ScreenShots 

> 📌 **Note:** Solutions are intentionally omitted to preserve the learning experience. Contact me directly for verified solve paths.

---

## 🚀 Getting Started  
### Method 1: Virtual Machine  
1. Download the [.ova file](https://drive.google.com/file/d/1qmSTWjXgdth26Euc7TPKNIfBTSo9tKri/view)  
2. Import into VirtualBox/VMWare  
3. Network settings: **Host-Only or NAT**  

### Method 2: Standalone Challenges  
Extract individual components from the VM:  
- Web apps for brute forcing  
- Image files for steganography  
- Fake social profiles for OSINT  

---

## 📜 Certification & Validation  
This CTF has been:  
✅ Accepted by **Vulnweb** for training purposes ([Proof](Screenshots/vulnweb_confirmation.png))  
✅ Deployed on **TryHackMe** for public testing ([Proof](Screenshots/thm_submission.png))  

---

## 💼 Professional Value  
### Why This Matters for Your Career  
- **Demonstrates Technical Skills:** Real-world applicable techniques  
- **Teaching Ability:** Designed with beginner-friendly hints  
- **Community Impact:** Used by platforms like TryHackMe  

---

## 📬 Contact & Contribution  
Found issues or want to expand this project?  
- Email: [Your Professional Email]  
- LinkedIn: [Your Profile Link]  

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
