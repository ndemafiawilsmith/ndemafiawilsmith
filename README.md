# Hi there, I'm Ndemafia Wilsmith 👋
### Cybersecurity Researcher & Full-Stack Systems Engineer

<p align="left">
  <a href="https://ndemafiawilsmith.com"><img src="https://img.shields.io/badge/Website-ndemafiawilsmith.com-blue?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="mailto:hello@ndemafiawilsmith.com"><img src="https://img.shields.io/badge/Email-hello@ndemafiawilsmith.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://linkedin.com/in/ndemafiawilsmith"><img src="https://img.shields.io/badge/LinkedIn-ndemafiawilsmith-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/0xwixard"><img src="https://img.shields.io/badge/X-@0xwixard-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Focus-Offensive%20Security%20%26%20Hardened%20Systems-red?style=flat-square" alt="Focus" />
  <img src="https://img.shields.io/badge/Validated%20By-ngCERT%20%2F%20ONSA-blue?style=flat-square" alt="ngCERT" />
  <img src="https://img.shields.io/badge/Location-Nigeria%20%C2%B7%20Remote%20Worldwide-2ea44f?style=flat-square" alt="Location" />
</p>

> *"Writing production code keeps the research honest; the research keeps the code paranoid."*

---

### 🛡️ About Me

I am a security researcher and full-stack software engineer working both sides of the same problem. I specialize in finding critical access-control flaws in federal corporate registries, fintech infrastructure, and university platforms, one of which was officially validated by Nigeria's national CERT (**ngCERT / ONSA**) within 48 hours. 

Simultaneously, I architect and build hardened, high-throughput web platforms that clients put their name on. When I build systems, the authorization model is tested before the first endpoint is ever exposed.

- 🔍 **Security Research**: Broken Access Control (IDOR), API Reconnaissance, Threat Modeling, Zero-Knowledge Flows.
- 💻 **Engineering Architecture**: Resilient REST APIs, Role-Based Access Control (RBAC), Event-Driven Microservices, Security Header Middleware.
- 🤝 **Collaborator**: Engineering partner with [@Kelvinsiweh](https://github.com/Kelvinsiweh).

---

### 🚨 Security Research & Responsible Disclosures

| Target & Sector | Vulnerability Class | Impact & Scope | Channel & Validation |
| :--- | :--- | :--- | :--- |
| **Corporate Affairs Commission (CAC)**<br>*Federal Corporate Registry* | **Critical IDOR / Broken Access Control**<br>Unauthenticated document retrieval path exposing incorporation records, director IDs, and resolutions. | **21M+ Entities**<br>Systemic national corporate verification exposure. | Reported via **ngCERT (NCCC / ONSA)**<br>Ticket: `ngCERT/zJgH/2025`<br>**Validated within 48h** |
| **Miva Open University**<br>*EdTech Learning Platform* | **Critical Student Data Disclosure**<br>Unauthorised access vector placing student data privacy at risk. | Campus-wide student records | Direct to CTO<br>**Acknowledged same day**<br>**Bug Bounty Awarded** |
| **BillPoint (B-Lord Group)**<br>*Payments / Fintech* | **Broken Access Control**<br>Account lookup returning full profile, phone numbers, and wallet balances by email query. | All registered user wallets | Direct to Product Team<br>**Coordinated Disclosure** |

#### 🔐 Responsible Disclosure Practice
1. **Minimum Necessary Access**: Enough evidence to prove the flaw exists and not one record more. Nothing retained, copied, or shared.
2. **Private Report First**: The organization that owns the risk, or the relevant national CERT, hears about it before anyone else, with complete remediation guidance attached.
3. **Publish Only What Is Safe**: Write-ups go live only after full remediation and describe vulnerability classes and architectural lessons, never endpoints, payloads, or exploit chains.

---

### 🛠️ Technical Stack & Security Arsenal

<p align="left">
  <!-- Security Tools -->
  <img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white" alt="Burp Suite" />
  <img src="https://img.shields.io/badge/OWASP%20Top%2010-000000?style=flat-square&logo=owasp&logoColor=white" alt="OWASP" />
  <img src="https://img.shields.io/badge/Nmap-002B36?style=flat-square" alt="Nmap" />
  <img src="https://img.shields.io/badge/Threat%20Modelling-8A2BE2?style=flat-square" alt="Threat Modeling" />
  <img src="https://img.shields.io/badge/RBAC%20Design-007ACC?style=flat-square" alt="RBAC" />
</p>

<p align="left">
  <!-- Languages & Runtimes -->
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL" />
</p>

<p align="left">
  <!-- Frameworks & Frontend -->
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Slim%204-68B030?style=flat-square&logo=php&logoColor=white" alt="Slim 4" />
</p>

---

### 📦 Key Projects & Engineering Platforms

- 🛡️ **[composer-sentinel-guard](https://github.com/Kelvinsiweh/composer-sentinel-guard)**: Cryptographic HMAC request verification and PSR-15 security header middleware engineered for paranoid PHP microservice defense.
- ⚡ **[task-orchestrator-core](https://github.com/Kelvinsiweh/task-orchestrator-core)**: Distributed workflow execution engine with strict state serialization, exponential backoff retries, and failure recovery.
- 🧩 **[ts-kit-monad](https://github.com/Kelvinsiweh/ts-kit-monad)**: Strongly-typed Result and Option monadic primitives eliminating unhandled null dereferences and exception leakage in TypeScript.
- 🌐 **[B-Lord Group Corporate Platform](https://blordgroup.ng)**: Sole developer. Mobile-first corporate architecture with zero exposed data paths, optimized for high-performance content delivery.
- 🛠️ **Disclosure Automation Tooling**: Custom Python automation suites turning raw access-control findings into reproducible technical reports for national CERTs.

---

### 🏆 Honors & Recognition

- **2025 National CERT Validation & Bug Bounty**: Technical research acknowledged by Nigeria's national CERT (**ngCERT / ONSA**) under the Office of the National Security Adviser, and rewarded by Miva Open University.
- **2019 MILSET Expo-Sciences International, Abu Dhabi**: Fully-funded national delegate and technical exhibitor representing Nigeria among elite young scientists and technologists worldwide.

---

### 📊 GitHub Activity & Metrics

<p align="center">
  <img src="https://img.shields.io/badge/Total%20Contributions-1%2C300%2B-2ea44f?style=for-the-badge&logo=github" alt="Total Contributions" />
  <img src="https://img.shields.io/badge/Maintained%20Projects-6%20Active-blue?style=for-the-badge&logo=git" alt="Maintained Projects" />
  <img src="https://img.shields.io/badge/Security%20Focus-Offensive%20%26%20Defensive-red?style=for-the-badge" alt="Security Focus" />
  <img src="https://komarev.com/ghpvc/?username=ndemafiawilsmith&color=007acc&style=for-the-badge&label=Profile%20Views" alt="Profile Views" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ndemafiawilsmith&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="98%" />
</p>

---

*Available for security research, smart contract / API penetration testing, and hardened backend engineering engagements.*
