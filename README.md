![Roadmap Banner](https://github.com/NullTrace67/NullTrace/blob/main/RedTeam.png)

# Roadmap: From Offensive Security to Red Teaming

A structured learning path for building strong **offensive security fundamentals** and progressing toward **red teaming** in a realistic, skill-first way.

## Table of Contents

- [Important Notes & Expectations](#important-notes--expectations)
- [How to Use This Roadmap (Learning Guidance)](#how-to-use-this-roadmap-learning-guidance)
- [Phase 0: Cybersecurity Orientation](#phase-0-cybersecurity-orientation-mandatory)
- [Phase 1: Networking Fundamentals](#phase-1-networking-fundamentals-non-negotiable)
- [Phase 2: Linux Fundamentals](#phase-2-linux-fundamentals)
- [Phase 3: Windows Fundamentals](#phase-3-windows-fundamentals)
- [Phase 4: How Attacks Actually Work](#phase-4-how-attacks-actually-work-conceptual)
- [Phase 5: Initial Access & Reconnaissance](#phase-5-initial-access--reconnaissance)
- [Phase 6: Privilege Escalation](#phase-6-privilege-escalation)
- [Phase 7: Post-Exploitation & Supporting Skills](#phase-7-post-exploitation--supporting-skills)
- [Phase 8: Transition to Red Teaming](#phase-8-transition-to-red-teaming)
- [Practice Platforms](#practice-platforms)
- [Learning Resources](#learning-resources)
- [Courses & Training](#courses--training)
- [Tools & Utilities](#tools--utilities)
- [Conclusion](#conclusion)

---

## Important Notes & Expectations

This roadmap is **not exhaustive** and is **not a checklist**.  
It provides **direction**, not depth. Mastery is your responsibility.

If your goal is **red teaming**, you **cannot start here directly**.  
You must first build a strong foundation in **offensive security / penetration testing**.

If your priority is **fast employability**, SOC or blue team roles are acceptable entry points.  
However, they **do not replace offensive fundamentals**.

> This roadmap does not list every single topic or point within each phase.
> You are expected to go deep until concepts are fully understood.

This roadmap assumes **little to no prior cybersecurity knowledge**, so it starts from fundamentals.

The listed points are **examples**, not complete syllabi.
Each phase requires additional self-directed learning beyond what is written here.

Roadmaps are **directional**, not universal.  
Adapt this roadmap to your learning style and goals.

This roadmap was written by me, with help from ChatGPT for structure and cleanup.  
It is **not auto-generated**.  
If you believe something should be added or corrected, feel free to reach out via the contact details in my **[About Me repository](https://github.com/NullTrace67/NullTrace)**.

---

## How to Use This Roadmap (Learning Guidance)

This roadmap focuses on **what to learn**, not prescribing exact courses or platforms.

Use learning resources to:
- Build conceptual understanding
- Validate knowledge through hands-on practice
- Fill gaps using documentation and technical write-ups

Beginner-friendly courses can help you understand workflows and terminology,
but **no single course is sufficient** for mastery.

Do not mistake course completion for skill.
If you cannot explain a concept without notes or reproduce it manually,
you do not understand it yet.

Choose learning resources based on clarity and depth,
not popularity or hype.

AI tools may be used to clarify concepts and challenge understanding,
but they must **not replace independent thinking or experimentation**.



## Phase 0: Cybersecurity Orientation (Mandatory)

Before learning attacks or tools, you must understand the field.

### You must understand:
- What cybersecurity actually is
- Major roles: SOC, Blue Team, Pentesting, Red Teaming
- Difference between pentesting and red teaming
- Attacker vs defender workflows
- High-level attack lifecycles

Skipping this phase often leads to weak fundamentals and over-reliance on tools.

---

## Phase 1: Networking Fundamentals (Non-Negotiable)

You must understand how systems communicate.

### Core topics:
- TCP/IP, UDP
- DNS, DHCP
- HTTP / HTTPS
- Routing, NAT, firewalls, VLANs
- Common ports and protocols

If you skip networking, you will only understand **tool output**, not environments.

---

## Phase 2: Linux Fundamentals

Linux is an attacker’s primary operating environment.

### Recommendations:
- Use Linux in a VM or as your OS
- Do **not** use Kali or Parrot as your main OS initially
- Start with a Debian-based distro; specialize later

### Required skills:
- Command-line proficiency
- File permissions
- Processes and services
- Package management
- Shell usage

### Strongly recommended:
- Bash scripting for automation

If you are not comfortable in a terminal, red teaming is unrealistic.

---

## Phase 3: Windows Fundamentals

Most enterprise targets are Windows-based.

### Required knowledge:
- Windows file system
- Registry basics
- Users, groups, and permissions
- Services and scheduled tasks
- Basic PowerShell

Learn **only enough** to navigate and operate confidently.

> Do **not** learn Active Directory here.  
> Active Directory is introduced later.

---

## Phase 4: How Attacks Actually Work (Conceptual)

Before exploitation, understand **attack logic**, not tools.

### Focus on:
- Attacker objectives
- Initial access concepts
- Privilege escalation concepts
- Lateral movement concepts
- Persistence concepts

No tools yet.  
**Conceptual understanding first.**

---

## Phase 5: Initial Access & Reconnaissance

Learn how attackers gain entry.

### Reconnaissance:
- Passive vs active recon
- Enumeration
- OSINT fundamentals
- Understanding *why* data is collected before collecting it

Reconnaissance should be learned **alongside** initial access.

### Initial access domains:
- Web exploitation
- Credential-based attacks
- Misconfigurations
- Network-based attacks

Hands-on labs are critical here.  
Avoid passive learning.

---

## Phase 6: Privilege Escalation

Learn:
- Linux privilege escalation
- Windows privilege escalation
- Active Directory fundamentals
- Active Directory privilege escalation

Active Directory is introduced here so fundamentals and escalation are learned together.

---

## Phase 7: Post-Exploitation & Supporting Skills

Learn:
- Cryptography basics
- Lateral movement
- Post-exploitation techniques
- Report writing (critical for real engagements and exams)

---

## Phase 8: Transition to Red Teaming

If your focus is red teaming, additional depth is required.

### Core requirements:
- OPSEC (mandatory)
- Adversary emulation
- Detection awareness and evasion
- Blue team fundamentals
- Log awareness (avoid careless log deletion)

### Programming:
- Python (basic scripting and code comprehension)
- Reading-level familiarity with:
  - C
  - C++
  - Rust
  - HTML
  - Java

### Cloud:
- Cloud pentesting during offensive security phase
- Cloud AD and cloud attack paths during red teaming

At this stage, you should be capable of planning your own progression.

---

## Practice Platforms

- TryHackMe
- Hack The Box
- PortSwigger Academy
- PicoCTF
- VulnHub
- PentesterLab
- OverTheWire
- GOAD
- DVWA
- Mutillidae
- WebGoat
- bWAPP
- Damn Vulnerable Bank
- Acunetix Test Site

---

## Courses & Training

- [SANS](https://dl.liangroup.net/SANS/) → Free SANS course materials (mirrored)
- [Downloadly](https://downloadlynet.ir/) → Community-archived technical courses (use selectively)
- [Elhacker](https://elhacker.info/) → Large collection of security-related courses and materials
- Telegram channels → Community-shared resources (search and evaluate independently)

## Tools & Utilities
> These are tools I commonly use for learning and practice.  

### Privilege Escalation & Enumeration
- [linPEAS](https://github.com/peass-ng/PEASS-ng/tree/master/linPEAS) → Linux privilege escalation enumeration
- [winPEAS](https://github.com/peass-ng/PEASS-ng/tree/master/winPEAS) → Windows privilege escalation enumeration

### Active Directory
- SharpHound / BloodHound → Active Directory attack path enumeration and analysis

### Shells & Payload Utilities
- [revshells](https://www.revshells.com/) → Reverse shell generation for multiple languages and environments


## Learning Resources

- [ired.team](https://www.ired.team/) → Notes, techniques, and red team tradecraft
- [HackTricks](https://book.hacktricks.xyz/) → Practical security notes and methodologies

> The following GitHub repositories may be useful for learning and reference during your progression.

### Offensive Security & Red Teaming Repositories
- [Awesome Red Teaming](https://github.com/NullTrace67/Awesome-Red-Teaming) → Curated red teaming resources
- [Pentest Notes](https://github.com/NullTrace67/pentest) → Offensive security and penetration testing references

---

## Conclusion

This roadmap is not meant to make you feel confident — it is meant to make you **competent**.

Offensive security and red teaming are not about tools, shortcuts, or running prebuilt payloads. They are about understanding systems, attacker tradecraft, and defender behavior at a fundamental level.

There is no fixed timeline, no guaranteed job outcome, and no course that will carry you through this field. Anyone claiming otherwise is selling motivation, not skill.

Certifications are optional; **capability is not**. If you pursue certifications, prioritize those that test real-world problem solving rather than memorization.

Most people quit because they underestimate the discipline required. This field rewards those who:
- Learn independently
- Read more than they watch
- Think more than they execute
- Rebuild assumptions instead of protecting ego

If you use this roadmap as a guide — not a checklist — and take responsibility for depth, consistency, and honest self-assessment, you will be on the correct path.

Everything else is noise.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.

