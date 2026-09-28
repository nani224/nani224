<div align="center">

# P. Sravan Kumar
### **Software Development Engineer (SDE) | Backend & Distributed Systems | Applied AI & Low-Level C/C++**
**Hyderabad, India · [sravanp224@gmail.com](mailto:sravanp224@gmail.com) · [github.com/nani224](https://github.com/nani224) · [Live Portfolio](https://nani224.github.io/sravanp/)**

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=19&duration=2800&pause=1200&color=00FF99&center=true&vCenter=true&width=700&lines=Information+Technology+%40+Vasavi+College+of+Engineering;Smart+India+Hackathon+2026+Finalist+(EviGraph+%26+MRPL+H2S);Backend+APIs+%7C+Distributed+Systems+%7C+Low-Level+Networking;Available+for+SDE+%2F+Backend+Engineering+Roles)](https://git.io/typing-svg)

<p align="center">
  <a href="mailto:sravanp224@gmail.com">
    <img src="https://img.shields.io/badge/Hire_Me-Direct_Email-00B4D8?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://evigraph.onrender.com">
    <img src="https://img.shields.io/badge/Production_App-EviGraph_Live-00C853?style=for-the-badge&logo=render&logoColor=white" />
  </a>
  <a href="https://github.com/nani224?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-Verified_Code-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

</div>

## 👨‍💻 Executive Summary

I am a Software Development Engineer with a strong foundation in **core computer science, high-concurrency systems, and full-stack architectures**. My work spans from low-level C network socket programming and $\mathcal{O}((V+E)\log V)$ graph algorithm implementations to production hackathon platforms utilizing **Hyperledger Fabric blockchain, FastAPI microservices, and React 18**.

* **Academic Background**: B.E. in Information Technology, **Vasavi College of Engineering (Autonomous, NAAC A++)**, Hyderabad (Affiliated to Osmania University).
* **Smart India Hackathon (SIH 2026)**:
  * **EviGraph**: Architected an AI-powered criminal network relationship engine and cryptographic evidence chain-of-custody platform on Hyperledger Fabric.
  * **H₂S Dosimeter**: Industrial wearable safety system monitoring toxic gas exposure using optical Kubelka–Munk colorimetry for problem sponsor **MRPL**.
* **Engineering Values**: Clean code, zero-memory-leak lifecycles, rigorous automated testing, and deterministic performance.

---

## 🛠️ Technical Competencies

<table>
  <tr>
    <td width="22%"><b>Languages</b></td>
    <td>
      <code>C</code> · <code>C++</code> · <code>Java 8/17</code> · <code>Python 3</code> · <code>TypeScript</code> · <code>JavaScript (ES6+)</code> · <code>SQL</code> · <code>Dart</code>
    </td>
  </tr>
  <tr>
    <td><b>Backend & Systems</b></td>
    <td>
      <code>FastAPI</code> · <code>Spring Boot</code> · <code>Node.js</code> · <code>Express</code> · <code>WebSocket API</code> · <code>Winsock2 Sockets</code> · <code>Win32 Threads</code>
    </td>
  </tr>
  <tr>
    <td><b>Distributed & Cloud</b></td>
    <td>
      <code>Hyperledger Fabric</code> · <code>Docker & Docker Compose</code> · <code>RESTful APIs</code> · <code>Microservices</code> · <code>JWT Authentication</code>
    </td>
  </tr>
  <tr>
    <td><b>Databases</b></td>
    <td>
      <code>MySQL (InnoDB)</code> · <code>MongoDB (Mongoose)</code> · <code>Flat-File Storage Engines</code> · <code>Hibernate / Spring Data JPA</code>
    </td>
  </tr>
  <tr>
    <td><b>Frontend & Mobile</b></td>
    <td>
      <code>React 18</code> · <code>Next.js</code> · <code>Tailwind CSS</code> · <code>Framer Motion</code> · <code>Java Swing</code> · <code>Flutter</code> · <code>Android CameraX</code>
    </td>
  </tr>
  <tr>
    <td><b>Core CS & Math</b></td>
    <td>
      <code>Data Structures & Algorithms</code> · <code>Graph Theory (Dijkstra, Min-Heap)</code> · <code>Operating Systems & Memory Management</code> · <code>Computer Networks (TCP/IP)</code>
    </td>
  </tr>
</table>

---

## 🚀 Highlighted Engineering Projects

### 1. [EviGraph](https://github.com/nani224/EviGraph) — AI Criminal Network & Cryptographic Evidence System
> **Smart India Hackathon 2026** · *Live Production Deployment on Render*
* **Architecture**: Distributed system establishing an immutable, cryptographically verifiable chain-of-custody for forensic digital evidence using **Hyperledger Fabric** blockchain.
* **Core Features**:
  * Graph analytics mapping co-occurrences, criminal ring hierarchies, and association matrices.
  * SHA-256 evidence hashing and immutable audit trails resisting tampering.
  * REST microservices built with **FastAPI**, containerized via **Docker**, and consumed by a **React/TypeScript** interactive canvas.
* **Tech Stack**: `TypeScript`, `FastAPI`, `Hyperledger Fabric`, `React`, `Docker`, `Python` · [**🌐 Live Demo**](https://evigraph.onrender.com)

---

### 2. [NETRA-X / TCS](https://github.com/nani224/TCS) — Real-Time NLP Dynamic Conversation & Escalation Engine
* **Architecture**: Low-latency WebSocket-driven natural language processing engine designed for live digital content surveillance and threat classification.
* **Core Features**:
  * Tracks multi-turn conversational trajectories and calculates dynamic temporal escalation metrics (`STABLE`, `INCREASING`, `DECREASING`).
  * Hybrid pipeline combining **spaCy** Named Entity Recognition, **scikit-learn** TF-IDF pattern matching, and external LLM contextual analysis with **100% offline local fallback**.
  * Integer-clamped risk scoring ($0–100$) mapped to operational threat tiers (`LOW` to `CRITICAL`).
* **Tech Stack**: `Python`, `FastAPI`, `WebSockets`, `spaCy`, `scikit-learn`, `Pytest`

---

### 3. [PathFinder](https://github.com/nani224/pathfinder) — High-Performance Graph Algorithm & K-Alternative Routes Engine
* **Architecture**: Production-grade Graph Theory engine in pure C implementing single-source shortest path and multi-route detour enumeration.
* **Engineering Highlights**:
  * Implemented Dijkstra's algorithm with a custom dynamic **Binary Min-Heap Priority Queue**, guaranteeing $\mathcal{O}((V + E) \log V)$ execution time.
  * Built an open-addressing string hash table with **djb2 hashing** for $\mathcal{O}(1)$ case-insensitive node lookups.
  * Developed dynamic edge-penalty blocking allowing instant extraction of $K$-alternative detour routes without redundant traversals.
  * Zero memory leaks: full allocation lifecycle managed via `free_graph()`.
* **Tech Stack**: `C`, `Graph Theory`, `Data Structures`, `Min-Heap`, `GCC`

---

### 4. [SmartLearn](https://github.com/nani224/smartlearn) — Desktop Educational Management & Assessment Platform
* **Architecture**: Full-stack multi-role desktop educational management system built with Java Swing and an ACID-compliant flat-file storage engine.
* **Engineering Highlights**:
  * Multi-role permissions model separating Student and Instructor workflows.
  * Interactive quiz assessment dialog (`QuizDialog`) featuring dynamic pagination, radio button group state, automated score tabulation, and completion feedback.
  * Self-healing file persistence layer (`FileManager`) with cross-platform relative path discovery across 20+ curriculum courses.
* **Tech Stack**: `Java 8`, `Swing GUI`, `OOP`, `Flat-File Persistence`

---

### 5. [LAN Chat Communication System](https://github.com/nani224/lan-chat) — Concurrent Multi-Threaded Sockets Engine
* **Architecture**: High-throughput multi-client TCP messaging server and interactive client built using native Windows Sockets (`Winsock2`) and Win32 threads.
* **Engineering Highlights**:
  * Supports up to 64 concurrent client connections with independent worker threads (`CreateThread`).
  * Guarded connection registries using Windows `CRITICAL_SECTION` mutexes to ensure complete thread-safety.
  * Full-duplex client architecture: asynchronous background listener thread displays incoming traffic without interrupting ongoing keyboard input.
  * Features private whispers (`/msg`), live roster enumeration (`/users`), and ANSI terminal color formatting.
* **Tech Stack**: `C`, `Winsock2`, `Multithreading`, `TCP/IP`, `Win32 API`

---

## 🏛️ Comprehensive Academic & Engineering Repository Index

| Repository | Focus / Domain | Primary Technologies | Key Metric / Deliverable |
| :--- | :--- | :--- | :--- |
| **[EviGraph](https://github.com/nani224/EviGraph)** | Blockchain & Forensics | React, FastAPI, Hyperledger | SIH 2026 Finalist System (Live on Render) |
| **[TCS / NETRA-X](https://github.com/nani224/TCS)** | AI & NLP Threat Analysis | Python, FastAPI, spaCy | Real-time WebSocket multi-turn risk scoring |
| **[pathfinder](https://github.com/nani224/pathfinder)** | Graph Theory & Algorithms | C, Min-Heap, Hashmap | $\mathcal{O}((V+E)\log V)$ Dijkstra & $K$-detour engine |
| **[smartlearn](https://github.com/nani224/smartlearn)** | Enterprise OOP Platform | Java, Swing, File IO | Multi-role assessment & curriculum portal |
| **[lan-chat](https://github.com/nani224/lan-chat)** | Systems & Networking | C, Winsock2, Win32 | 64-client concurrent full-duplex socket server |
| **[nids](https://github.com/nani224/nids)** | Network Security | Spring Boot, MySQL, Thymeleaf | Network log monitoring & rule-based intrusion alerts |
| **[drugshield](https://github.com/nani224/drugshield)** | Mobile & Computer Vision | Flutter, Dart, CameraX | Anti-counterfeit pharmaceutical verification |
| **[sravanp](https://github.com/nani224/sravanp)** | Personal Web Presence | HTML5, CSS3, JavaScript | Modern Emerald-Mint interactive portfolio |

---

## 📈 Activity & Technical Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nani224&show_icons=true&theme=radical&hide_border=true&title_color=00FF99&text_color=FFFFFF&icon_color=00B4D8" height="175" alt="GitHub Stats" />
  &nbsp;&nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nani224&layout=compact&theme=radical&hide_border=true&title_color=00FF99&text_color=FFFFFF" height="175" alt="Top Languages" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=nani224&theme=radical&hide_border=true&stroke=00FF99&ring=00B4D8&fire=00FF99" alt="GitHub Streak" />
</div>

---

## 📬 Open for Opportunities

I am actively interviewing for **Software Development Engineer (SDE), Backend Engineer, and Systems Engineering** roles. 

* 📧 **Email**: [sravanp224@gmail.com](mailto:sravanp224@gmail.com)
* 🌐 **GitHub**: [github.com/nani224](https://github.com/nani224)
* 💼 **Portfolio**: [nani224.github.io/sravanp](https://nani224.github.io/sravanp/)
* 📍 **Location**: Hyderabad, India (Open to Relocation & Remote)

<div align="center">
  <sub>© 2026 P. Sravan Kumar. Code with purpose. Build for scale.</sub>
</div>
