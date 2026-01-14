# PharmaSim-Switch (Supplementary Materials)

This repository contains supplementary resources for the study:

**Structuring versus Problematizing: How LLM-based Agents Scaffold Learning in Diagnostic Reasoning**

It includes the full prompt set used in the LLM-driven scaffolding system, as well as visual summaries of statistical analyses and behavioral metrics reported in the paper.

---

## Contents

### `RQ1: Prompts.xlsx`
Contains the complete set of prompt templates used by the AI agents in the two scaffolding conditions:

- **Structuring-heavy scaffolding**  
  Guided, supportive, and highly structured mentoring prompts.

- **Problematizing-heavy scaffolding**  
  Reflective, inquiry-based prompts encouraging learners to reason through uncertainty.

**How the prompts are organized**
- Prompts are grouped by **interaction state** in the learning sequence  
  (e.g., *General Instructions*, *Data Collection*, *Data Interpretation*).
- Prompts are provided in **both English and German**.
- **General Instructions** remain constant throughout the session.
- State-specific prompts dynamically switch based on learner progress, reflecting the study’s **state-machine design**.

---

### `Pretest Conceptual Knowledge.pdf`
A short pretest measuring learners’ baseline **conceptual knowledge** before interacting with the system.

---

### `RQ2: Mixed Linear Models for Strategy Learning Outcomes.png`
A visual summary of mixed-effects statistical models analyzing learning gains across three diagnostic reasoning strategies:

- **Checklist Strategy**
- **Interpersonal Strategy**
- **Possible Causes Strategy**

---

### `RQ3: Surface Level Metrics.png`
A descriptive and inferential comparison of engagement-related surface-level behavioral metrics between the two scaffolding conditions, including:

- switch ratios (client ↔ pharmacist)
- discussion duration
- utterance counts and word counts
- turn ratios
- interaction density

