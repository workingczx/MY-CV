# Hi, I'm Zixuan Chen 👋

🎓 **MSE in Robotics @ Johns Hopkins University**  
🤖 Research interests: **Robotics, Computer Vision, Multimodal AI, AR, UAV Systems, Embodied AI, and Probabilistic Robotics**  
📍 Currently working on research spanning **autonomous systems, predictive control, multimodal learning, and intelligent perception**

📧 **Email:** [zchen272@jh.edu](mailto:zchen272@jh.edu)

---

## 🎓 Education

### Johns Hopkins University
**Master of Science in Engineering (MSE) in Robotics**  
*Sep. 2026 – May 2027 (Expected)*

### Zhejiang Normal University — Sino-UK Program
**BEng in Software Engineering, Zhejiang Normal University**  
**BSc (Hons) in Computing, University of Worcester**  
*Sep. 2021 – Jun. 2025*

- GPA: **3.73/5.0**
- WES GPA: **3.86/4.0**
- Rank: **3/59**

### University of Washington
**Exchange Program**  
*Sep. 2024 – Dec. 2024*

- CSE 417 — Algorithms & Computational Complexity *(Graduate-level course)*

---

## 🔬 Research Interests

- Robotics & Autonomous Systems
- Computer Vision & Visual Localization
- Augmented Reality
- UAV Networks & Multi-Agent Systems
- Probabilistic Robotics
- Model Predictive Control
- Multimodal Foundation Models
- Embodied AI
- AI for Healthcare & Scientific Discovery
- Natural Language Processing

---

## 🧠 Research Experience

### Predictive Connectivity-Preserving UAV Relay Replacement for Post-Disaster WASH Networks
**Research Assistant — Duke University**  
*Supervised by ShaoCheng Luo | Feb. 2026 – Present*  
*Planning to submit to ICRA 2027*

**Topics:** MILP, GATv2, Foundation Models, Graph Optimization, UAV Networks

- Developed a unified predictive UAV relay replacement framework for maintaining uninterrupted WASH monitoring connectivity under anticipated UAV failures.
- Designed a two-phase recovery mechanism combining emergency handover and connectivity-preserving topology restoration.
- Formulated a lexicographic MILP framework optimizing UAV participation, relay positions, movement schedules, handover timing, restoration order, monitoring degradation, and energy use.
- Implemented graph-based connectivity constraints, candidate-position compatibility modeling, and recovery precedence rules.
- Built a MILP–trajectory verification loop with continuous connectivity checking and iterative no-good, timing, and precedence cuts.
- Extended the deterministic framework into an **FMG-MILP architecture** using a foundation-model semantic adapter and lightweight **GATv2** policy.
- Developed a deterministic safety compiler for monitoring coverage, geofencing, collision clearance, communication, route feasibility, and energy constraints.
- Established a graph-policy training pipeline using MILP-optimal and continuously validated schedules as supervision.

---

### A Unified Framework for Badminton Dynamics with Pose Perception and Parameter Adaptation
**Research Assistant — Xidian University Hangzhou Institute**  
*Feb. 2026 – Present*  
*Planning to submit to ICRA 2027*

**Topics:** ROS2, Gazebo, UKF, MPC, Dynamics Modeling, Probabilistic Robotics

- Developed an uncertainty-aware robotic shuttlecock interception framework integrating multi-view perception, probabilistic estimation, aerodynamic adaptation, contact modeling, and risk-sensitive control.
- Designed a physics-informed probabilistic shuttlecock dynamics model with learnable residual dynamics.
- Built a complete **ROS2 + Gazebo** simulation platform with stereo triangulation, UKF filtering, dynamic TF management, racket-contact evaluation, and online control triggering.
- Achieved:
  - **5.18 mm** mean triangulation error
  - **3.23 mm** mean filtered position error
  - **604** high-confidence interception frames
- Developed a candidate-pose MPC interception framework for automatic racket-pose selection.
- Proposed an **Actor–Critic-guided MPC acceleration strategy** to reduce online optimization cost.

---

### Camera-on-AR Posture-Aware Badminton Coaching System without External Court Cameras
**Research Assistant — Xidian University Hangzhou Institute**  
*Feb. 2026 – Present*

**Topics:** AR, Computer Vision, UKF, Dynamics Modeling, HCI

- Developed an AR-based sports intelligence framework integrating onboard perception, state estimation, shuttlecock dynamics prediction, uncertainty propagation, and real-time coaching.
- Designed monocular 3D shuttlecock tracking using continuous vision, AR SLAM localization, court geometry constraints, and UKF filtering.
- Built uncertainty-aware landing prediction with covariance propagation and probabilistic rollout.
- Designed AR interfaces for:
  - trajectory overlays
  - landing confidence regions
  - recommended positioning
  - movement guidance
  - optimal hitting-window visualization
- Proposed an accessibility-oriented coaching paradigm for deaf and hard-of-hearing athletes and novice players.

---

### AI Agent for Meteorological Forecasting and Decision Support
**Research Assistant — Xidian University Hangzhou Institute**  
*Feb. 2026 – Present*

**Topics:** Knowledge Graphs, LLMs, RAG, Neo4j, Rule-Based Reasoning

- Developed **GasAI-Agent**, a domain-specific AI agent for meteorological and environmental monitoring equipment selection.
- Designed a Neo4j-based scenario–variable–product knowledge graph.
- Implemented hybrid reasoning combining graph retrieval, rule-based filtering, and LLM generation.
- Built a multi-source data integration pipeline with entity normalization and relation inference for:
  - similarity
  - alternatives
  - upgrades
  - complementary products
- Supported explainable scenario-aware recommendation and RAG workflows.

---

### Multiple Myeloma Prognosis Prediction — MO-RiskVAE
**Research Assistant — Binjiang Institute of Zhejiang University**  
*Supervised by Prof. Meng Han | Dec. 2025 – Present*

**Topics:** Multimodal Learning, VAE, Survival Analysis, Multi-Omics

- Developed **MO-RiskVAE**, a survival-supervised multimodal VAE for multiple myeloma risk stratification.
- Studied latent regularization scale, posterior geometry, and latent structure under survival supervision.
- Developed a hybrid continuous–discrete latent space using **Gumbel–Softmax**.
- Improved validation C-index from **0.7419 → 0.7788**.
- Improved latent risk alignment from Spearman \(|ρ| = 0.516 → 0.637\).
- Implemented multi-omics integration, missing-modality imputation, and survival modeling pipelines.

---

### Beyond Language: Large Multimodal Foundation Models for Scientific Discovery
**Research Assistant — Binjiang Institute of Zhejiang University**  
*Supervised by Prof. Meng Han | Dec. 2025 – Present*

- Conducted a review of multimodal embodied AI systems including **Gato, PaLM-E, RT-1, RT-2**, and ReAct-style reasoning systems.
- Analyzed dominant paradigms in:
  - multimodal policy unification
  - LLM-centric reasoning and planning
  - language-conditioned robotic control
- Studied limitations in physical grounding, long-horizon closed-loop reasoning, and safety-constrained real-world interaction.
- Investigated future directions toward autonomous scientific discovery and self-driving laboratories.

---

### Real-World C2E Translation with Semantic Simplification
**Research Project**  
*Supervised by Rui Wu | Jun. 2024 – Sep. 2025*

**Topics:** NLP, Machine Translation, Semantic Simplification, Information Extraction

- Designed a dual-stage Chinese-to-English pipeline combining semantic simplification and high-precision translation.
- Used GloVe embeddings and fine-tuned T5-Pegasus-Chinese for semantic and structural simplification.
- Achieved:
  - **ROUGE-1: 0.9562**
  - **ROUGE-2: 0.9157**
- Developed a BERT-MRC key-information extraction pipeline with Dynamic Self-Critique.
- Achieved **F1 = 93.77**.
- Benchmarked M2M-100, MarianNMT, and mBART on WMT19; mBART achieved **BLEU = 33.32**.

---

### Dynamic Study of Plant Community Adaptation to Drought
*Mar. 2024 – Sep. 2025*

- Calculated SPEI drought indices using 55 years of meteorological data.
- Built a MATLAB NAR neural network for time-series prediction.
- Applied M-K testing, grey-system modeling, and nonlinear programming.
- Proposed an optimized plant-community composition improving stability by **8.7%**.

---

### Quantitative Modeling of Network Security Awareness
**Supervised by Dr. MdShaiful Islam Babu**  
*Dec. 2023*

- Built a simulated cybersecurity attack website using HTML, CSS, and JavaScript.
- Designed a 22-question cybersecurity awareness questionnaire.
- Collected **430 valid responses**.
- Conducted PCA and factor analysis using SPSS.
- Extracted 8 components explaining **50.91%** of total variance.

---

## 📚 Publications

1. **Zixuan Chen.**  
   *Dynamic Study of Plant Community Adaptation to Drought under Nonlinear Programming Model.*  
   Accepted by **BIC 2026**.

2. **Zixuan Chen.**  
   *Quantitative Modeling of Network Security Awareness via Questionnaire Analysis and Dimensionality Reduction Techniques.*  
   Accepted by **2026 3rd International Conference on Algorithms, Software Engineering and Network Security**.

3. **Zixuan Chen.**  
   *MO-RiskVAE: A Multi-Omics Variational Autoencoder for Survival Risk Modeling in Multiple Myeloma.*  
   Submitted to **EMNLP 2026**.

4. **Zixuan Chen.**  
   *Real-World C2E Translation with Semantic Simplification: A Dual-Stage Approach for Practical NLP Applications.*  
   Submitted to **SMC 2026**.

5. **Zixuan Chen.**  
   *Accurate Pronunciation in Classical Chinese Speech Synthesis: A Retrieval-Augmented Pinyin Generation Approach.*  
   Submitted to **IJCAI**.

---

## 💼 Internship Experience

### Hangzhou Yalong Intelligent Technology Co., LTD
**Software Engineer**  
*Mar. 2025 – May 2025*

- Optimized TTS pronunciation and naturalness for Chinese polyphonic characters and classical Chinese.
- Evaluated open-source TTS systems and selected **F5-TTS** as the final solution.
- Integrated RAG with an external pronunciation knowledge base.
- Improved ASR using **FunASR** for Chinese and **Whisper + Pyannote** for English.
- Evaluated speaker-separation systems including MossFormer, NeMo, and ClearerVoice-Studio.

---

### SpacemiT (Hangzhou) Technology Co., LTD
**Technical Engineer**  
*Jun. 2024 – Aug. 2024*

- Built semantic understanding and QA models using **PyTorch** and **Transformers**.
- Conducted parameterized validation experiments with metric tracking.
- Converted models to **ONNX** for efficient inference and deployment.
- Evaluated models on **MMLU, RTE, and SST-2**.

---

### Wenzhou Yineng Information Technology Co., LTD
**Software Engineering Developer**  
*Jun. 2023 – Jul. 2023*

#### Personal Blog System
- Built frontend pages with **Vue 3 Composition API**.
- Implemented reusable article loading and pagination logic.
- Used Vue Router and Axios for navigation and API requests.

#### National Health Commission Unified Portal
- Built page structure and interactions using HTML, CSS, and JavaScript.
- Refactored static pages into reusable Vue 3 components.
- Implemented shared component state for improved maintainability.

---

## 🏆 Scholarships & Awards

- **Special Award of Overseas Exchange Scholarship**, Zhejiang Normal University — Top 5% *(2024)*
- **Zhejiang Provincial Government Scholarship** — Top 3% *(2023)*
- **First-Class Scholarship for Outstanding Students**, ZJNU — Top 3% *(2023)*
- **Third Prize**, 13th MathorCup University Mathematical Modeling Challenge *(2023)*
- **Meritorious Winner**, Certificate Authority Cup International Mathematical Contest in Modeling *(2023)*
- **Second Prize — Zhejiang Province**, National College Students Mathematical Contest in Modeling *(2022)*
- **Second-Class Scholarship for Outstanding Students**, ZJNU — Top 8% *(2022)*

---

## 🛠️ Technical Skills

### Programming
`Python` `C` `Java` `JavaScript` `HTML` `CSS` `MATLAB`

### AI / Machine Learning
`PyTorch` `Transformers` `VAE` `RAG` `LLMs` `GATv2` `Computer Vision` `NLP`

### Robotics
`ROS2` `Gazebo` `UKF` `MPC` `AR SLAM` `Multi-Agent Systems` `Trajectory Planning`

### Optimization & Data
`MILP` `Graph Optimization` `Nonlinear Programming` `SPSS` `Neo4j`

### Deployment
`ONNX`

---

## 🚀 Current Focus

I am currently interested in developing intelligent robotic systems that combine:

- **visual perception**
- **probabilistic state estimation**
- **model-based control**
- **multimodal foundation models**
- **AR-based human–robot interaction**
- **safe autonomous decision-making**

My long-term goal is to build autonomous systems that can **perceive, reason, plan, and act reliably in complex real-world environments**.

---

## 📫 Contact

**Zixuan Chen**  
MSE Robotics, Johns Hopkins University  
📧 [zchen272@jh.edu](mailto:zchen272@jh.edu)
