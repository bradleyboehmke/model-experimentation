# ModelOps and Model Experimentation Workshop Spec (Final)

## Overview
Create a Quarto RevealJS presentation titled:
**ModelOps and Model Experimentation: From Training Runs to Managed Models**

This is a 60–90 minute applied workshop combining:
- conceptual framing
- practical workflow
- Rossmann project demo using MLflow

---

## Resources
The following resources can be accessed and context used to build this presentation:

- From Notebook to Production: Building Reliable Data Pipelines. Example presentation we want to follow for structure. Repo located at ~/Desktop/UC/Applied Workshops/notebook-to-production-data
- Introduce the concepts of ModelOps as discussed in this chapter:  ~/Desktop/UC/uc-bana-7075/book/05-modelops-role.qmd
- Introduce the concepts of model training and experiment tracking as discussed in this chapter: ~/Desktop/UC/uc-bana-7075/book/06-modelops-experimenting.qmd
- Demonstrate how this looks in practice with the Rossmann forecasting project located here: ~/Desktop/Projects/rossmann-forecasting. Specifically, we will discuss how we can use MLFlow to track experiments and then demo what this looks like by launching MLFlow and running some new experiments and see what this looks like in MLFlow as documented in ~/Desktop/UC/uc-bana-7075/docs/modelops/overview.md and ~/Desktop/UC/uc-bana-7075/docs/modelops/tracking.md

---

## Design Principles

### Slide Philosophy
- Minimal text
- Key takeaway focused
- Instructor-driven explanation

### Speaker Notes
- Medium-light detail
- Talking points, not scripts

### Visuals
- Mermaid for workflows
- Use placeholders for illustrations:
  - [IMAGE: chaotic notebooks]
  - [IMAGE: MLflow dashboard]

---

## Core Learning Goals
- Understand ModelOps
- Understand structured experimentation
- Understand experiment tracking
- Apply concepts with MLflow

---

## Slide Structure

## Section 1 — Framing

### 🔬 Micro-Spec: Opening Hook

Slide:
“How do you currently track your models?”

[IMAGE: messy notebook files]

Notes:
- Ask students directly
- Make it relatable

---

## Section 2 — ModelOps

### 🔬 Micro-Spec: ModelOps Definition

Slide:
“ModelOps = managing models as lifecycle assets”

Notes:
- Not just training
- Focus on reproducibility and lifecycle

---

## Section 3 — Experimentation

### 🔬 Micro-Spec: Chaos → Structure

Slide 1:
“How do you track experiments today?”
[IMAGE: chaotic notebooks]

Slide 2:
Problems:
- Which run is best?
- What changed?
- Can you reproduce?

Slide 3:
“Good modeling = structured experimentation”

Slide 4:
Track:
- Parameters
- Metrics
- Artifacts

[MERMAID: simple flow]

Slide 5:
Benefits:
- Compare
- Reproduce
- Explain

---

## Section 4 — MLflow

### 🔬 Micro-Spec: MLflow Mental Model

Slide:
“A run = one experiment attempt”

Notes:
- Emphasize comparison

[MERMAID: logging workflow]

---

## Section 5 — Rossmann

### 🔬 Micro-Spec: Workflow

[MERMAID: baseline → tuning → best model]

Notes:
- Connect concept to real project

---

## Section 6 — Demo

### 🔬 Micro-Spec: Demo Framing

Slide:
“What to watch for”

- runs
- metrics
- comparisons

---

## Section 7 — Wrap-Up

Slide:
Key Takeaways

- ModelOps = lifecycle
- Experiments need structure
- MLflow enables tracking

---

## Claude Code Instructions

- Keep slides minimal
- Use notes for detail
- Use Mermaid where helpful
- Insert image placeholders
- Align with Rossmann repo

---

## Success Criteria

Students:
- understand ModelOps
- understand experiment tracking
- can apply concepts
