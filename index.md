---
layout: default
title: Methodology Assignment 4
---

# Methodology Assignment 4 — GitHub Pages

**Name / Email**  
Josh Osofsky — <josofsky@ucsd.edu>

**Section & Mentor**  
Section: (e.g., Domain X, Tue/Thu 2–3pm)  
Mentor: (Name)

---

**What is the most interesting topic covered in your domain this quarter?**  
I found the exploration of visual anomaly detection for wildfire cameras particularly compelling—especially how self-supervised representations can surface rare events with minimal labels.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
I would like to evaluate a Vision Transformer encoder paired with a metric-learning objective (e.g., triplet margin loss) to flag off-distribution frames, comparing embedding drift over time against human-labeled incidents.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
I would extend training duration, perform a principled hyperparameter sweep (batch size, margin, temperature), and incorporate stronger augmentations to improve invariance to lighting and weather artifacts.

**What other techniques would you be interested in using in your project?**  
I’m interested in contrastive pretraining (SimCLR/InfoNCE), lightweight temporal models for short clips, and calibration methods to translate anomaly scores into actionable, human-interpretable alerts.
