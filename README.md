# Hi, I'm Joel Chinta 👋

### Platform & MLSecOps Engineer | Building Immutable, Secure Cloud Infrastructure

I engineer automated CI/CD pipelines, secure cloud infrastructure, and hardened Machine Learning deployments. I focus on the intersection of **Systems Engineering, Automation, and Zero-Trust Security**.

> **My Engineering Philosophy:** Infrastructure should be defined in code, security should be automated in the pipeline, and models should be containerized.

---

## 🏗️ The Unified Flagship Architecture: Operation Last Ride

I don't build fragmented tutorial projects. I am currently engineering a single, enterprise-grade ML inference platform deployed securely to the cloud. This project demonstrates end-to-end capabilities across three domains: **Platform Engineering, DevSecOps, and MLSecOps**.

### 1. ☁️ The Platform Layer (Infrastructure as Code)
**Goal:** Zero-touch provisioning of secure compute environments.
*   **IaC:** Writing modular **Terraform** configurations to provision isolated VPCs and compute instances on Floci.
*   **Configuration:** Using **Bash** scripts to enforce strict `iptables` rules, `chmod 600` access controls, and non-root user isolation at boot.
*   **Observability:** Deploying **Prometheus** and **Node Exporter** to monitor CPU/RAM utilization and network socket health in real-time.

### 2. 🔐 The DevSecOps Layer (Automated CI/CD Gates)
**Goal:** Shift-left security that blocks vulnerabilities before production.
*   **Pipeline:** Orchestrating automated build, test, and deploy workflows using **GitHub Actions**.
*   **Container Security:** Writing multi-stage, distroless `Dockerfiles` and halting builds if **Trivy** detects `CRITICAL` CVEs in base images or dependencies.
*   **Infrastructure Scanning:** Validating Terraform state against security misconfigurations using **Checkov / tfsec**.

### 3. 🧠 The MLSecOps Layer (Secure AI Deployment)
**Goal:** Hardening machine learning models against adversarial attacks.
*   **Inference API:** Wrapping supervised Scikit-Learn/PyTorch models inside optimized asynchronous **FastAPI** endpoints.
*   **SAST:** Enforcing strict static analysis via **Bandit** to prevent unsafe `pickle` loading (arbitrary code execution vulnerabilities).
*   **AI Red Teaming:** Utilizing **Garak** and **NVIDIA NeMo Guardrails** to test and defend LLM endpoints against prompt injections and data leaks.

---

## 🛠️ Core Technology Stack

| Domain | Tools & Technologies |
| :--- | :--- |
| **Platform / Cloud** | Linux (Ubuntu/Debian), Bash, Terraform, Docker, Floci Cloud |
| **DevSecOps** | GitHub Actions, Trivy, Bandit, Checkov, Vault (Secrets) |
| **AI / MLOps** | Python, FastAPI, Scikit-Learn, NeMo Guardrails, Garak |
| **Observability** | Prometheus, Grafana, Systemd Journalctl, Network (`ss`, `netstat`) |

---

## 📊 Current Execution Focus (Oct - Nov 2026)

I am currently executing a rigorous 60-day engineering sprint utilizing **KodeKloud** laboratory environments and official documentation to finalize the flagship architecture.

- [x] **Week 1:** Hardened Linux baseline, automated bash provisioning, and isolated Python `venv` setup.
- [ ] **Week 2:** Containerizing FastAPI inference logic and integrating Trivy scanning.
- [ ] **Week 3:** Automating GitHub Actions CI/CD and Bandit SAST integration.
- [ ] **Week 4:** Terraform IaC provisioning and automated cloud deployment.
- [ ] **Week 5+:** Active AI Red Teaming, Open-Source Security PRs, and Chaos Testing.

---

## 🤝 Let's Connect

*   **LinkedIn:** [linkedin.com/in/thedarknight-w](https://linkedin.com/in/thedarknight-w)
*   **Email:** [joelchinta7@gmail.com](mailto:joelchinta7@gmail.com)

> *Building systems that can't be broken by accident, and are too expensive to break on purpose.*
