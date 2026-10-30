# Robby

I build low-level software that operates close to the hardware.  
Currently working on **Self-Encrypting Drive (SED) firmware based on TCG Opal SSC**, focusing on secure storage behavior, protocol-level implementation, and firmware-side state management.

I enjoy digging into technical specifications and translating strict requirements into deterministic firmware logic. For me, the fun is in the details—where even a tiny behavioral difference can impact interoperability, security, or compliance.

---

### 🧭 Focus Area & Architecture

```text
Architecture
│
├── 📜 Standards & Protocols
│   ├── Storage Security Specs: TCG Core, Opal SSC, IEEE 1667, OCP
│   ├── Opal Feature Sets: SUM, CNL, Block SID
│   └── Interface & Transport: NVMe (Security Send/Receive), SIIS
│
├── 🔑 Features
│   ├── Protocol: ComPacket/Packet/DataSubpacket Processing
│   ├── Session Manager: Session Lifecycle & ComID Management, Transaction
│   ├── Authority & Access Control: Admin SP / Locking SP, Roles & ACLs
│   ├── Locking Mechanism: Locking Ranges (L0–Ln), Read/Write Locking States, CNL
│   ├── Pre-Boot & Recovery: Shadow MBR (PBA), PSID Revert
│   └── Lifecycle States: Manufactured-Inactive, Manufactured
│
├── 🔐 Cryptography & Key Hierarchy
│   ├── Key Architecture: Key Hierarchy
│   ├── Key Lifecycle: Media Encryption Key (MEK/DEK), Intermediate Keys, KDF
│   └── Crypto Erase: Cryptographic Erase (Key Invalidation & Re-keying)
│
└── 🛠️ Reliability
    ├── Deterministic FSM Design
    └── Error Handling
```

---

### 🔧 What I'm Working On
My day-to-day work centers around designing and implementing firmware features for TCG Opal-based SED systems:

- **TCG Opal Protocol Engine**: Processing Opal SSC commands and methods, managing session lifecycles, and parsing payload structures.
- **SP Architecture**: Managing behavior, tables, and method execution across **Admin SP** and **Locking SP**.
- **Access Control & Locking**: Implementing authorities, access control models, and dynamic **Locking Range** configurations and state transitions.
- **Protocol Interoperability**: Handling **NVMe** security protocol commands (Security Send / Receive) and **SIIS** interactions.
- **Robustness**: Ensuring strict firmware state consistency, robust error recovery, and clean state machine flow.

---

### 🛠 Domains & Tech Stack
- **Storage Security**: TCG Core & Opal SSC, SED, SIIS, IEEE 1667, OCP
- **Firmware & Systems**: Embedded Architecture, State Machine Design, Low-level Debugging, Access Control
- **Languages**: C, C++, Python
- **Problem Solving**: I regularly practice algorithmic problem solving to stay sharp with edge-case analysis and implementation discipline.

---

### 🎓 Background & Experience
- **SED / TCG Opal Firmware Development** `2024.04 – Present`
  - Focus on TCG Opal SSC, NVMe security protocols, and state management
- **Intel SW Training Program (2nd)** `2023.07 – 2024.02`
  - Embedded & FW & Edge AI
  - Team project lead & collaboration
- **Software Engineer Intern** `2022.11 – 2023.05`
  - Android & BE service development
- **Republic of Korea Army (ROKA)** `2020.03 – 2022.06`
  - 1st Lieutenant, Signal Corps (35th Infantry Div.)
- **Chonnam National University** `2016.03 – 2020.02`
  - B.S. in Electronic Engineering

---

### 📫 Contact
- Email: [roby238_dev@naver.com](mailto:roby238_dev@naver.com)
