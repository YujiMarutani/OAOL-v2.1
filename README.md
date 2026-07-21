# OAOL v2.1 — Autonomous Orchestration Operating Layer

OAOL (Autonomous Orchestration Operating Layer) v2.1 is a multi‑agent orchestration architecture designed to transform human sovereign intent into executable task graphs, manage dynamic phase states, detect instability, harmonize multi‑agent outputs, recover from failures, and retrieve canonical knowledge from immutable academic sources.

This repository provides the **canonical (authoritative) specification** for OAOL v2.1.

---

## 📁 Repository Structure

OAOL-v2.1/
├── specs/                     # All canonical JSON specifications for OAOL v2.1
│     OAOL_v2_1_Runtime_Spec.json
│     OAOL_Intent_v2.json
│     OAOL_Agent_Prompts_v2.0.json
│     OAOL_Orchestration_v2.json
│     OAOL_Orchestration_Flow_v2_1.json
│     OAOL_Execution_Bindings_v2_1.json
│     OAOL_Canonical_KB_v2_1.json
│
├── docs/                      # Theory, design notes, and documentation
├── figures/                   # Architecture diagrams, emblem, visual materials
└── runtime/                   # Execution layer (future extensions)


---

## 🧠 OAOL Architecture Overview

OAOL is structured into four layers:

### **L4 — Sovereign Intent Layer**
Defines human sovereign goals, ethical boundaries, constraints, and priority.  
`OAOL_Intent_v2.json`

### **L3 — Orchestration & Semantic Layer**
Task graph generation, phase management, agent routing.  
`OAOL_Orchestration_v2.json`  
`OAOL_Orchestration_Flow_v2_1.json`

### **L2 — Boundary & Security Layer**
Phase state machine, agent channels, audit hooks.  
`OAOL_v2_1_Runtime_Spec.json`

### **L1 — Execution Layer**
Bindings to external systems, simulations, and canonical knowledge sources.  
`OAOL_Execution_Bindings_v2_1.json`

---

## 🎼 Philharmonia Agents (8 Agents)

| Agent | Role |
|-------|------|
| **G** | Transform intent → task graph |
| **C** | Harmonization and integration |
| **N** | Final narrative generation |
| **E** | Risk probing and instability detection |
| **Phi** | Phase state management |
| **M** | Canonical knowledge retrieval (Zenodo/GitHub) |
| **X** | External data acquisition |
| **R** | Recovery, fallback, rerouting |

Detailed prompts are defined in `OAOL_Agent_Prompts_v2.0.json`.

---

## 📚 Canonical Knowledge Base (Agent M)

Agent M retrieves authoritative knowledge from **Zenodo DOI** and **GitHub Release**.

### Zenodo DOI  
(To be updated after publication)  


---

## 🧠 OAOL Architecture Overview

OAOL is structured into four layers:

### **L4 — Sovereign Intent Layer**
Defines human sovereign goals, ethical boundaries, constraints, and priority.  
`OAOL_Intent_v2.json`

### **L3 — Orchestration & Semantic Layer**
Task graph generation, phase management, agent routing.  
`OAOL_Orchestration_v2.json`  
`OAOL_Orchestration_Flow_v2_1.json`

### **L2 — Boundary & Security Layer**
Phase state machine, agent channels, audit hooks.  
`OAOL_v2_1_Runtime_Spec.json`

### **L1 — Execution Layer**
Bindings to external systems, simulations, and canonical knowledge sources.  
`OAOL_Execution_Bindings_v2_1.json`

---

## 🎼 Philharmonia Agents (8 Agents)

| Agent | Role |
|-------|------|
| **G** | Transform intent → task graph |
| **C** | Harmonization and integration |
| **N** | Final narrative generation |
| **E** | Risk probing and instability detection |
| **Phi** | Phase state management |
| **M** | Canonical knowledge retrieval (Zenodo/GitHub) |
| **X** | External data acquisition |
| **R** | Recovery, fallback, rerouting |

Detailed prompts are defined in `OAOL_Agent_Prompts_v2.0.json`.

---

## 📚 Canonical Knowledge Base (Agent M)

Agent M retrieves authoritative knowledge from **Zenodo DOI** and **GitHub Release**.

### Zenodo DOI  
(To be updated after publication)  

10.5281/zenodo.21471508/zenodo.OAOL_v2_1

### GitHub Release  

https://github.com/YujiMarutani/OAOL-v2.1/releases/tag/v2.1


Canonical KB specification: `OAOL_Canonical_KB_v2_1.json`

---

## 🔧 How to Build the Canonical Release

1. Save all JSON specs into the `specs/` directory  
2. Create GitHub Release `v2.1`  
3. Enable GitHub → Zenodo integration  
4. Publish the Zenodo record and obtain DOI  
5. Update `OAOL_Canonical_KB_v2_1.json` with the DOI

---

## 📄 License

MIT License (recommended)  
You may adjust as needed.

---

## ✒ Author

Y.Marutani  
Independent Researcher — AI Agents / OS-level System Design / Civilization-scale Architectures

