# LLM Evaluation Toolkit

Research-oriented toolkit for building **reliable evaluation pipelines for LLM systems**.

Modern AI systems rely heavily on automated evaluation.
However, evaluation itself is a complex measurement problem.

This toolkit explores three key aspects:

1. Evaluation reliability
2. Adversarial behavior during evaluation
3. Calibration of LLM judges

---

## Components

### 1. Reliability

llm-evaluator-reliability

Tools for measuring evaluation stability and variance.

---

### 2. Adversarial Evaluation

llm-eval-adversarial

Experiments for detecting **evaluation awareness** in LLM systems.

When models detect evaluation conditions,
they may optimize for the measurement process rather than the task.

---

### 3. Judge Calibration

llm-judge-calibration

Tools for evaluating agreement between automated judges:

• Cohen's kappa  
• inter-rater agreement  
• judge drift

---

## Motivation

LLM evaluation can be viewed as a **measurement system**.

This project explores evaluation pipelines from a measurement science perspective.

---

## Author

Ekaterina Taratuta  
PhD | AI Architect  
LLM Systems & Reliable AI
