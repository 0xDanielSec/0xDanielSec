<h1 align="center">Daniel Gomes · 0xDanielSec</h1>
<p align="center">
  <b>AI Security Engineer · AI Red Team · Detection Engineering</b><br>
  Breaking LLM agents, then building the detections that catch it.
</p>

<p align="center">
  <a href="https://linkedin.com/in/danielgomes-cybersecurity"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"></a>
  <img src="https://img.shields.io/badge/Open%20to-remote%20AI%20Security%20roles-black?style=flat">
</p>

---

### whoami

- 6+ years in **detection engineering & purple teaming** — Microsoft Sentinel, Defender XDR, KQL, Carbon Black EDR.
- Now focused on **AI security**: prompt injection, jailbreaks, RAG data leakage, tool/agent abuse, and MCP attack surface.
- Day job: securing and building production AI systems (Azure OpenAI, Copilot Studio, MCP gateways) for a large public-sector organization.
- Completed the **HTB AI Red Teamer** path (12/12 modules). Next up: COAE.

### What I build

| Project | What it does |
|---|---|
| [**Talon Scanner**](https://github.com/0xDanielSec/talon-scanner) | Agentic offensive pipeline: intel → surface mapping → vuln scanning → impact chaining → constrained PoC. Found a patched CVE-class bug in `cilium/tetragon`. |
| [**DUEL Framework**](https://github.com/0xDanielSec/duel-framework) | Attacker LLM vs defender LLM. One emits MITRE ATT&CK telemetry, the other writes KQL detections — adversarial loop for detection coverage. |
| [**ai-redteam-lab**](https://github.com/0xDanielSec/ai-redteam-lab) | Hands-on labs and tooling for LLM red teaming: injection, jailbreaks, data exfil, agent abuse. |
| **Mulebench** *(WIP)* | Security testing framework for financial / fintech AI agents — red-team scenarios runnable in CI. |

### Security research

| Target | Issue | Status |
|---|---|---|
| `cilium/tetragon` | NULL pointer dereference (CWE-476) | ✅ Patched — [PR #4880](https://github.com/cilium/tetragon/pull/4880) |
| `cilium/cilium` | CEL expression DoS (CWE-94) | 🔒 Under coordinated disclosure |

> All findings follow responsible disclosure. PoCs are deliberately constrained — no shells, no destructive payloads.

### Stack

**AI / LLM** &nbsp;
![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Copilot Studio](https://img.shields.io/badge/Copilot%20Studio-5E5E5E?style=flat&logo=microsoft&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-111111?style=flat)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Detection & Response** &nbsp;
![Sentinel](https://img.shields.io/badge/Microsoft%20Sentinel-0078D4?style=flat&logo=microsoft&logoColor=white)
![Defender XDR](https://img.shields.io/badge/Defender%20XDR-0078D4?style=flat&logo=microsoft&logoColor=white)
![KQL](https://img.shields.io/badge/KQL-2C2C2C?style=flat)
![Carbon Black](https://img.shields.io/badge/Carbon%20Black-000000?style=flat)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-C8102E?style=flat)

**Cloud & Identity** &nbsp;
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra%20ID-0078D4?style=flat&logo=microsoft&logoColor=white)

### Currently

- 🔴 Red-teaming RAG pipelines and tool-using agents
- 🛡️ Turning those attacks into detections and guardrails
- 📚 Studying for COAE

---
<p align="center"><sub>Offense informs defense. Defense informs offense.</sub></p>
