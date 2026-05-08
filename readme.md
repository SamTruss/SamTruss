<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,2,20&height=210&section=header&text=Sam%20Truss&fontSize=70&fontColor=ffffff&fontAlignY=34&desc=PhD%20Researcher%20·%20Keele%20University&descAlignY=56&descSize=18&animation=fadeIn)

[![Typing](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3800&pause=900&color=FF6B35&center=true&vCenter=true&width=780&lines=Agentic+%26+Generative+AI+for+Autonomous+VAPT;OT+%2F+IIoT+Security+%C2%B7+MCP-Mediated+Tool+Orchestration;observe+%E2%86%92+reason+%E2%86%92+decide+%E2%86%92+act+%E2%86%92+store)](https://git.io/typing-svg)

[![Keele](https://img.shields.io/badge/Keele%20University-C73E1D?style=for-the-badge&logoColor=white)](https://www.keele.ac.uk)
[![ORCID](https://img.shields.io/badge/ORCID-E55934?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0006-4694-0606)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-FF6B35?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/samuel-truss)

</div>

---

## `~$ whoami`

```diff
@@ Sam Truss — PhD Researcher · Keele University @@

+ Thesis: A Novel Agentic & Generative AI Model for Conducting
+         Vulnerability Assessment and Penetration Testing in
+         Operational Technology (OT) Environments
+ Field:  Agentic VAPT · LLM-driven offensive security
- Patience for predictable attack surfaces
```

> *Security is not a tooling problem — it's a thinking problem.*
> *Break assumptions. Test everything. Trust nothing — especially not the thing you just assumed was safe.*

---

## `~$ cat research.md`

🔬 **Research question:** *what happens when the attacker reasons, plans, and learns?*

The field of **Agentic VAPT** sits at the intersection of large language model reasoning, sequential decision-making, and offensive security. My work builds an end-to-end framework where an LLM-driven agent performs reconnaissance, vulnerability analysis, and exploitation under formal governance — extended to the OT/IIoT environments where conventional automated tooling breaks down.

| | |
|---|---|
| 🧠 **Domain** | Agentic & Generative AI for autonomous VAPT |
| 🏭 **Setting** | OT / IIoT convergence environments |
| 🧩 **Architecture** | Four-layer Agentic–Generative VAPT model |
| 🔌 **Control plane** | MCP-mediated tool orchestration with policy governance |
| 📏 **Evaluation** | VAPT Autonomy Benchmark — task success, action validity, policy compliance, interpretability, operational safety |
| 🎯 **Testbed** | SWaT-inspired Modbus environment with seeded vulnerabilities |

```yaml
research_pillars:
  - autonomous_decision_loops:    "observe → reason → decide → act → store"
  - tool_governance:              "MCP control-plane · policy-constrained execution"
  - safety_under_autonomy:        "zero physical-process deviations target"
  - evaluation_methodology:       "reproducible benchmark across IT and OT"
```

---

## `~$ ls ./publications`

📑 **Systematic Literature Review** — *in revision · Elsevier (Computers & Security / JISA)*

> Truss, S. R. A., Ghanem, M. C., Lacerda, M. J., Kheddar, H., Alshawki, M., Kenaza, T., Kalganova, T.
> **"Agentic and Generative AI for Intelligent Autonomous Vulnerability Assessment and Penetration Testing: A Systematic Analysis."** 2026.

PRISMA-guided review of 72 included studies. Introduces (i) the unified four-layer Agentic–Generative VAPT model, (ii) the MCP threat abstraction, and (iii) the VAPT Autonomy Benchmark. OSF archive: `osf.io/d7p8j`.

---

## `~$ ls ./projects`

🤖 **[Pathfinder AI](https://github.com/SamTruss/Pathfinder-AI)** — single-agent prototype implementing the four-layer model

The empirical instantiation of the SLR's analytical framework. A single-agent system running observe → reason → decide → act → store, with MCP-governed tool integration for reconnaissance, vulnerability scanning, and bounded exploitation.

```
agent/         decision loop · planner · governance hooks
tools/         MCP-wrapped Nmap · pymodbus · NVD lookup
memory/        JSON Lines audit trail · SHA-256 content hashing
```

🏭 **[Multi-PLC Water Treatment Testbed](https://github.com/SamTruss/Multi-PLC-Water-Treatment-Testbed)** — SWaT-inspired OT evaluation environment

Companion artefact to Pathfinder AI. A reproducible Modbus-enabled water-treatment testbed for evaluating agentic and generative AI in autonomous VAPT of OT/ICS environments. OpenPLC, simpy process simulation, Docker Compose, seeded vulnerabilities matching the published benchmark specification.

---

## `~$ ls ./stack`

<div align="center">

![Python](https://img.shields.io/badge/Python%203.11+-C73E1D?style=for-the-badge&logo=python&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic%20API-D8572A?style=for-the-badge&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-E55934?style=for-the-badge&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-FF6B35?style=for-the-badge&logo=docker&logoColor=white)
![OpenPLC](https://img.shields.io/badge/OpenPLC-C73E1D?style=for-the-badge&logoColor=white)
![pymodbus](https://img.shields.io/badge/pymodbus-A4243B?style=for-the-badge&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-E55934?style=for-the-badge&logo=pytest&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-FF6B35?style=for-the-badge&logo=latex&logoColor=white)
![Git](https://img.shields.io/badge/Git-C73E1D?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## `~$ ./current_focus`

```
┌─[ PATHFINDER AI ]────────────────────────────────────────┐
│  ▸ Single-agent prototype build-out                      │
│  ▸ MCP tool layer · governance hooks · audit trail       │
│  ▸ observe → reason → decide → act → store               │
└──────────────────────────────────────────────────────────┘
┌─[ TESTBED ]──────────────────────────────────────────────┐
│  ▸ SWaT-inspired Modbus environment                      │
│  ▸ OpenPLC · simpy process simulation · Docker Compose   │
│  ▸ Seeded vulnerabilities · benchmark run protocol       │
└──────────────────────────────────────────────────────────┘
```

---

## `~$ ./stats`

<div align="center">

<a href="https://github.com/SamTruss">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=SamTruss&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&bg_color=0d1117&title_color=FF6B35&icon_color=E55934&text_color=c9d1d9&ring_color=C73E1D&cache_seconds=1800" alt="GitHub Stats" />
</a>
<a href="https://github.com/SamTruss">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SamTruss&layout=compact&hide_border=true&bg_color=0d1117&title_color=FF6B35&text_color=c9d1d9&langs_count=8&cache_seconds=1800" alt="Top Languages" />
</a>

<a href="https://github.com/SamTruss">
  <img src="https://github-profile-trophy.vercel.app/?username=SamTruss&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=8" alt="Trophies" />
</a>

</div>

---

<div align="center">

### `~$ ./status`

🟠 **ONLINE** · *still compiling_*

![Visitors](https://komarev.com/ghpvc/?username=SamTruss&style=for-the-badge&color=FF6B35&label=VISITORS)

</div>
