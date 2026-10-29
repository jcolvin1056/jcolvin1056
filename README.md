# Josh Colvin

### Cybersecurity Engineer · AI Security Researcher · Open-Source Maintainer

> Securing AI agents before they press send. 20 years in security operations, now building the tools I wish I had in the SOC.

---

### What I Do

I build **AegisGate** — a suite of 5 open-source AI security tools that protect every layer where AI agents interact with systems: HTTP APIs, MCP tool calls, A2A agent communication, browser extensions, IDE plugins, and CI/CD pipelines.

Everything is **Apache 2.0**, **no telemetry**, **air-gapped capable**. Built for environments where security can't phone home.

---

### By the Numbers

| Metric | Value |
|--------|-------|
| Products | 5 (Platform, Rampart, Lens, Scanner, MCP Server) |
| Lines of Go | ~830,000 |
| Tests | 16,400+ (100% detection on real-world payloads, 0% false positives) |
| Detection Patterns | 1,248 (regex + MITRE ATLAS + CharCNN-BiLSTM ML) |
| Compliance Frameworks | 31 (2,043 controls, 1,457 automated) |
| ML Model | CharCNN-BiLSTM, 1.6M params, 100/100 evasion resistance |
| Provisional Patents | 8 (AI agent identity, multi-protocol interception, compliance mapping, three-layer detection, response scanning, static analysis, federated IOC, agent lifecycle) |
| Published Research | SSRN — [AegisGate: A Multi-Layered Security Architecture for AI Agent Communication](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7652138) |

---

### The Five Products

| Product | What It Does | Stack |
|---------|-------------|-------|
| **[Platform](https://github.com/aegisgatesecurity/aegisgate-platform)** | Enterprise AI security gateway — reverse proxy with regex + ATLAS + ML detection, 31 compliance frameworks, SIEM integration | Go, gRPC, PostgreSQL, ONNX |
| **[Rampart](https://github.com/aegisgatesecurity/aegisgate-rampart)** | IDE security — VS Code, Cursor, JetBrains plugin that scans prompts before they reach the LLM | Go, LSP |
| **[Lens](https://github.com/aegisgatesecurity/aegisgate-lens)** | Browser extension — Chrome/Firefox, scans ChatGPT/Claude/Gemini traffic in real-time | JavaScript, WebExtensions |
| **[Scanner](https://github.com/aegisgatesecurity/aegisgate-scanner)** | CLI/CI scanner — static analysis of AI artifacts, SARIF output, GitHub Action | Go, SARIF |
| **[MCP Server](https://github.com/aegisgatesecurity/aegisgate-mcp)** | MCP guardrails — tool-call interception for Model Context Protocol agents | Go, MCP |

---

### Experience

- **~20 years** in cybersecurity — SOC, incident response, threat intelligence, SIEM engineering
- **Security stacks**: Splunk, QRadar, XSIAM, Cortex XDR, Cribl, Recorded Future, CyberArk
- **Compliance**: HIPAA, PCI-DSS, SOC 2, NIST CSF, NIST AI RMF, ISO 27001, ISO 42001, EU AI Act, FISMA, CSA AICM
- **Cloud**: AWS (GovCloud), Azure (GCC-Moderate, GCC-HIGH), GCP, Docker, Kubernetes, Helm
- **Languages**: Go, Python, with CI/CD, DevSecOps, SBOM, Cosign, Sigstore

### Certifications

Palo Alto Networks (PCSAE, PMXdS, PMXdR, PMXrC) · Cribl (Level 2 Admin) · Arista (Edge Threat Management) · Recorded Future (Intelligence Fundamentals)

---

### Connect

- 📧 josh_colvin@proton.me
- 🌐 [aegisgatesecurity.io](https://aegisgatesecurity.io)
- 📄 [SSRN Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7652138)
- 🐦 [@AegisGateSec](https://x.com/AegisGateSec)
- 💼 [LinkedIn](https://www.linkedin.com/in/joshcolvin/)

---

### Sponsor My Work

If my open-source work helps your team, consider [sponsoring me on GitHub](https://github.com/sponsors/aegisgatesecurity). Every dollar goes to development, CI/CD, and keeping all five products free.

---

*Looking for senior security engineering, AI security, or security architect roles. Open to remote, hybrid, or on-site in the Midwest.*
