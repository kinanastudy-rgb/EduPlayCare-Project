# EduPlayCare: Project Methodology Framework

This document outlines the three foundational pillars of the EduPlayCare platform. This methodology integrates my background in Clinical Psychopedagogy with technical skills in AI and Data Science (Microsoft DP-100, Alura AI Immersion).

---

## Pillar 1: Psychopedagogical Foundation

The platform is not just a game; it is a clinical tool. Each mini-game will be a "gamified translation" of validated assessment principles for identifying markers of:

* **Dyscalculia:** Assessing number sense, subitizing, and logical-mathematical reasoning through resource management or puzzle-solving games.
* **Dyslexia:** Assessing phonological awareness and processing speed through auditory and visual matching quests.
* **ADHD/Executive Functions:** Assessing working memory, inhibition control, and cognitive flexibility through rapid, adaptive challenges.
* **Autism Spectrum Disorder (ASD) Traits:** Assessing social cognition and flexible thinking through choice-based narrative scenarios. (Informed by "Clinical Care for Autistic Adults" - Harvard Medical School).

## Pillar 2: Gamification & Engagement Design

To ensure engagement and valid data, the platform will be built on a "Retro RPG" aesthetic (inspired by *Stardew Valley*, *Pokémon*).

* **Core Loop:** The user (child) is a "hero" on a quest. Mini-games are "challenges" to unlock new areas or "helpers."
* **Intrinsic Motivation:** Focus on mastery and exploration over simple points.
* **Data Collection:** Gameplay is the data. The system logs:
    * Time-to-task (initiation and completion).
    * Error types and frequencies.
    * Adaptive path (how the scaffolding model adjusted difficulty).
    * Hesitation metrics (e.g., mouse-hover patterns before a choice).

## Pillar 3: AI & Technical Framework

This is the project's technical core.

* **Model:** A supervised machine learning model (e.g., Random Forest or a simple Neural Network) will be trained on data from validated assessments and gameplay patterns.
* **Objective:** The model's goal is **classification**—to predict the probability of risk markers for a specific learning difficulty based on the gameplay data profile.
* **Adaptive Scaffolding:** This is the key research interest. The system will use real-time performance data to adjust the level of support (e.g., visual cues, simpler numbers, extended time), creating a personalized "Zone of Proximal Development." This is directly related to the research I intend to pursue at Yonsei University.
* **Tech Stack (Proposed):**
    * **Engine:** Unity or Godot (for 2D game development).
    * **AI/ML:** Python (Scikit-learn, TensorFlow/PyTorch) for model development. (Informed by Microsoft DP-100 Bootcamp).
    * **Backend:** A simple database (like Firebase or SQL) to store anonymized user data and gameplay logs.
