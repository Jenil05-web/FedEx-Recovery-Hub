# 📦 FedEx Recovery Hub: Intelligent Debt Orchestration

![Status](https://img.shields.io/badge/Status-UI%2FUX_Prototype-orange?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Enterprise_Governance_&_AI-4D148C?style=for-the-badge&logo=fedex&logoColor=white)
![Hackathon](https://img.shields.io/badge/Event-FedEx_Hackathon_2026-blue?style=for-the-badge)

> **Reimagining the DCA management process with AI-driven prioritization, centralized governance, and seamless automation.**

---

## 📸 The "Smart Bridge" Experience

This repository hosts the **High-Fidelity Frontend Prototype** for the FedEx Recovery Hub. Below is the end-to-end user journey designed to solve the challenge of opaque, manual debt collection.

### 1. Secure Role-Based Access
*Enterprise-grade security starts at the door. Distinct login paths for FedEx Administrators and external DCA Agents ensure strict data segregation.*

![Login Screen](Screenshots/login.png)

---

### 2. The Command Center (FedEx View)
*Replacing spreadsheets with real-time insights. The Admin Dashboard provides an instant snapshot of Total Debt, Recovery Rates, and Agency Performance.*

![Admin Dashboard](Screenshots/DCA%20admin%20dashboard.png)

#### Intelligent Ingestion
*Automated CSV processing that cleanses data, validates entries, and prepares cases for AI scoring immediately upon upload.*

![Upload Screen](Screenshots/CSV%20upload%20Debator.png)

---

### 3. Automated Case Allocation
*The "Master List" where rules-based logic automatically assigns cases to the right agency (Alpha, Beta, Gamma) based on debt size and location—eliminating manual email coordination.*

![Master List](Screenshots/Master%20Case%20List%20DCAs.png)

---

### 4. The Agent Workspace (AI-Powered)
*Agents no longer call blindly. The "Prioritized Call List" uses **Propensity to Pay** scoring (Green/Yellow/Red) to direct effort where it matters most.*

![Agent Workspace Top](Screenshots/AI%20Prioritized%20callback%20system.png)
![Agent Workspace List](Screenshots/AI%20Priority%20system.png)

---

### 5. AI Copilot & Strategy
*When an agent selects a case, the **AI Recovery Engine** analyzes the debtor's history to recommend a specific strategy (e.g., "Non-aggressive") and even generates the script.*

![AI Modal](Screenshots/AI%20Recovery%20System.png)

---

### 6. Governance & Compliance
*Every action is immutable. The Audit Trail logs system events ("Payment Failed") and human actions ("Script Generated"), ensuring 100% compliance transparency.*

![Audit Trail](Screenshots/Audit%20Trail.png)
![Timeline Detail](Screenshots/Case%20History%20Audit%20Trail%20.png)

---

## 🚩 The Problem Solved
FedEx currently relies on fragmented processes involving emails and spreadsheets to manage external Debt Collection Agencies (DCAs). This prototype addresses:
* **Opaque Operations:** Solved via the *Real-time Admin Dashboard*.
* **Inefficient Recovery:** Solved via *AI Propensity Scoring* (Targeting high-value recovery first).
* **Weak Governance:** Solved via the *Immutable Audit Timeline*.

---

## 🛠️ Technical Implementation

This prototype is built using modern web standards to demonstrate the visual fidelity and user experience of the proposed solution.

* **Structure:** HTML5 Semantic Markup
* **Styling:** CSS3 (Flexbox/Grid) & Enterprise Design System (FedEx Colors)
* **Interactivity:** Vanilla JavaScript (ES6+) for Modal/Tab interactions

### How to Run Locally
Since this is a frontend design prototype, no complex backend installation is required to view the concept.

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/FedEx-Recovery-Hub.git](https://github.com/YOUR_USERNAME/FedEx-Recovery-Hub.git)
    ```
2.  **Launch**
    * Navigate to the project folder.
    * Open `index.html` in Chrome, Firefox, or Edge.

---

## 🔮 Future Roadmap (Backend Integration)

* **Phase 1 (Current):** UI/UX Design & Process Validation.
* **Phase 2:** Connect React Frontend to Node.js/Express Middleware.
* **Phase 3:** Integrate OpenAI API for real-time script generation (currently mocked in UI).
* **Phase 4:** MongoDB implementation for persistent Case History storage.

---

**Submitted by [Git Resolvers]**
