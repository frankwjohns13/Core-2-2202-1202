<!-- Core 2 Notes -->
# <div style="text-align: center;">CompTIA A+ Core 2 (220-1202) Notes</div>

<!-- Domain 1 -->

## Domain 1.0 – Operating Systems (28%)

### 1.1 Explain common OS types and their purposes

**Windows**
- Most widely used desktop OS (75%+ market share)
- Versions for exam: Windows 10 & Windows 11
- Naming: Windows 10, Windows 11 (year-based in the past)
- Windows Server versions: 2016, 2019, 2022 (longer support lifecycle ~10 years)
- Key features: NTFS file system, EFS encryption, Group Policy, built-in security tools

**Linux**
- Open-source, highly customizable
- Major families: Red Hat (Fedora, CentOS), Debian (Ubuntu), SUSE
- Used heavily in servers (80%+ of web servers), IoT, embedded devices
- Release models: Standard (versioned, LTS) vs Rolling release (continuous updates)

**macOS**
- Proprietary, runs only on Apple hardware
- Based on Unix (Darwin kernel)
- Stable due to tight hardware/software integration
- Versions named after California locations (Big Sur, Monterey, Ventura, etc.)

**iOS / iPadOS**
- Proprietary Apple mobile OS
- iOS for iPhones, iPadOS for iPads (multitasking + Apple Pencil support)
- Strong security model, long support lifecycle (5–7 years)

**Android**
- Open-source, Linux-based
- Customized by manufacturers (Samsung, Google, etc.)
- Sideloading possible (security risk)
- Shorter support cycle (typically 3 years)

**Chrome OS**
- Lightweight, web-focused OS by Google
- Runs on Chromebooks/Chromeboxes
- Fast boot, automatic updates, strong security (sandboxing)

**File Systems**
- NTFS — Default for Windows, journaling, encryption, large volumes
- exFAT — Cross-platform (Windows, macOS, Linux), good for USB drives
- FAT32 — Old, limited file size (4GB max)
- ext4 — Standard for Linux
- APFS — Modern macOS/iOS file system

### 1.2 Compare and contrast common operating system features

**User Interface**
- GUI vs CLI (Command Line)
- Windows: Explorer + PowerShell/Command Prompt
- Linux: GNOME, KDE, or terminal (bash/zsh)
- macOS: Finder + Terminal

**File Management**
- Windows: File Explorer
- macOS: Finder
- Linux: Nautilus or terminal commands (ls, cp, mv, rm)

**Process Management**
- Task Manager (Windows)
- Activity Monitor (macOS)
- top / htop (Linux)

**Services & Daemons**
- Windows Services
- macOS LaunchDaemons
- Linux systemd

**Security Features**
- Windows: Windows Defender, BitLocker, UAC
- macOS: Gatekeeper, FileVault
- Linux: SELinux, AppArmor, firewall (ufw/firewalld)

**Patch Management**
- Windows Update
- macOS Software Update
- Linux package managers (apt, yum, dnf)
 
<!-- Domain 2 -->
## Domain 2.0 – Security (28%)

### 2.1 Summarize security concepts and best practices

**Threats & Vulnerabilities**
- Malware types: Viruses, worms, trojans, ransomware, spyware, rootkits, keyloggers
- Social engineering: Phishing, spear phishing, vishing, smishing, pretexting, tailgating
- Password attacks: Brute force, dictionary, rainbow table, credential stuffing
- Network attacks: MITM, DDoS, evil twin, rogue AP, ARP poisoning
- Physical threats: Shoulder surfing, dumpster diving, hardware theft

**Security Best Practices**
- Strong, unique passwords + password manager
- Multi-Factor Authentication (MFA)
- Principle of Least Privilege
- Regular software updates and patch management
- Antivirus / Anti-malware with real-time protection
- Firewall (host-based and network)
- Data encryption (BitLocker, FileVault, LUKS)
- Secure boot and TPM

### 2.2 Compare and contrast common security features

**Windows Security Features**
- Windows Defender Antivirus
- Windows Firewall
- BitLocker (full disk encryption)
- User Account Control (UAC)
- Secure Boot
- Windows Hello (biometrics)

**macOS Security Features**
- Gatekeeper (app verification)
- FileVault (disk encryption)
- XProtect & MRT (malware protection)
- Firewall
- System Integrity Protection (SIP)

**Mobile Device Security**
- Screen lock (PIN, pattern, biometric)
- Remote wipe / Find My Device
- App permissions management
- OS updates
- MDM (Mobile Device Management) for enterprise

### 2.3 Given a scenario, apply appropriate security features

**User Authentication**
- Passwords, PINs, biometrics, smart cards, tokens
- MFA (something you know + have + are)

**Device Hardening**
- Disable unnecessary services
- Disable AutoRun/AutoPlay
- Use strong passwords and lock screens
- Enable full disk encryption

**Network Security**
- Use WPA3 for Wi-Fi
- Disable WPS
- Use VPN for public networks
- Firewall rules

### 2.4 Explain common methods for securing devices

**Physical Security**
- Cable locks, locked cabinets, badge access
- Screen privacy filters
- Secure disposal (shredding, wiping)

**Mobile Device Security**
- MDM enrollment
- Containerization (work vs personal data)
- Remote lock/wipe
- App whitelisting

**Data Destruction Methods**
- Formatting (basic)
- Overwriting (secure erase)
- Degaussing (magnetic media)
- Physical destruction (shredding, incineration)
 
<!-- Domain 3 -->
## Domain 3.0 – Software Troubleshooting (23%)

### 3.1 Given a scenario, troubleshoot common operating system problems

**Common Windows Issues**
- Boot problems (blue screen, black screen, boot loop)
- Slow performance (high CPU/disk usage)
- Application crashes or not responding
- Driver issues (yellow exclamation in Device Manager)
- Update failures
- Corrupted user profiles
- Missing DLL errors

**Troubleshooting Tools**
- Safe Mode — Minimal drivers and services
- System Restore — Roll back to previous state
- Startup Repair — Automatic boot fix
- Event Viewer — Check logs for errors
- Task Manager — End tasks, check performance
- Resource Monitor — Detailed resource usage
- Command Prompt tools (sfc /scannow, chkdsk, DISM)

**Common Linux/macOS Issues**
- Permission errors
- Package manager problems (apt, yum)
- Kernel panics (macOS)
- Application compatibility issues

### 3.2 Given a scenario, troubleshoot common security problems

**Malware Symptoms**
- Excessive pop-ups and ads
- Slow performance / high resource usage
- Unexpected program behavior
- Browser redirects
- Disabled security software
- High network traffic

**Security Troubleshooting Steps**
- Run full antivirus scan
- Use Malwarebytes or AdwCleaner for adware
- Boot into Safe Mode for scanning
- Check for rogue browser extensions
- Review installed programs for suspicious entries
- Check Task Manager for unknown processes

### 3.3 Given a scenario, troubleshoot common mobile OS and application issues

**Common Mobile Issues**
- Device won’t boot or is stuck in boot loop
- Apps crashing or not responding
- Battery drain
- Overheating
- Slow performance
- Connectivity issues (Wi-Fi, Bluetooth, cellular)
- Touch screen not responding

**Mobile Troubleshooting Steps**
- Force restart
- Update OS and apps
- Clear app cache
- Check for malware (Android)
- Factory reset as last resort
- Check for physical damage

### 3.4 Given a scenario, troubleshoot common mobile OS and application security issues

**Mobile Security Problems**
- Device is rooted/jailbroken (security risk)
- Unauthorized sideloading
- Excessive app permissions
- Fake security warnings
- High data usage (possible spyware)
- Unexplained account activity

**Mobile Security Troubleshooting**
- Check app permissions
- Remove suspicious apps
- Run malware scan (Android)
- Update OS and apps
- Factory reset if needed
- Use MDM for enterprise devices
 
<!-- Domain 4 -->
## Domain 4.0 – Operational Procedures (21%)

### 4.1 Given a scenario, use appropriate documentation and communication techniques

**Documentation Best Practices**
- Create detailed service tickets
- Document symptoms, steps taken, and resolution
- Use company templates
- Include screenshots when helpful
- Maintain change logs for important modifications

**Communication Techniques**
- Use professional language
- Avoid jargon with non-technical users
- Actively listen and take notes
- Set clear expectations and timelines
- Follow up after resolution

### 4.2 Explain basic safety procedures

**Electrical Safety**
- Unplug devices before servicing
- Use grounded outlets
- Avoid working on live circuits
- Use proper ESD protection (wrist strap, mat)

**Physical Safety**
- Lift with legs, not back
- Use proper cable management
- Keep workspace clean and organized
- Follow lockout/tagout procedures

**Environmental Safety**
- Proper disposal of batteries and electronics (e-waste)
- Follow local regulations for hazardous materials
- Use proper ventilation when working with chemicals

### 4.3 Explain environmental impacts and appropriate controls

**Environmental Concerns**
- E-waste and proper recycling
- Energy consumption
- Heat generation in data centers
- Chemical hazards from toner and cleaning supplies

**Green IT Practices**
- Power management settings
- Use energy-efficient hardware
- Virtualize servers to reduce physical footprint
- Proper recycling programs

### 4.4 Explain policies and procedures for addressing prohibited content/activity

**Company Policies**
- Acceptable Use Policy (AUP)
- Data handling and confidentiality policies
- Chain of custody for evidence
- Incident response procedures

**Handling Prohibited Content**
- Do not view or copy illegal content
- Report to appropriate personnel
- Follow legal and company guidelines
- Maintain professionalism and discretion

### 4.5 Explain the importance of prohibited content and activity reports

**Why Documentation Matters**
- Legal protection
- Compliance requirements
- Track recurring issues
- Improve future troubleshooting

**Incident Reporting**
- Document what was found
- Who was involved
- Actions taken
- Outcome and recommendations

### 4.6 Explain the purpose of standard operating procedures (SOP)

**Benefits of SOPs**
- Consistency in troubleshooting
- Training new technicians
- Compliance and auditing
- Faster problem resolution

**Common SOP Topics**
- Hardware installation
- Software deployment
- Security procedures
- Backup and recovery
- Onboarding/offboarding

<!-- Link to Core 1 Notes -->
**View Core 1 Notes** → [View Core  Notes](https://github.com/frankwjohns13/Core-1-220-1201/)

<!-- Link to A+ Main Page -->
**View A+ Main Page** → [View A+ Main Page](https://github.com/frankwjohns13/CompTIA-A-Plus-Notes)









