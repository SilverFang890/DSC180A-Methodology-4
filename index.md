# DSC 180A Methodology Assignment 4

**Name:** Samuel Eun  
**Email:** saeun@ucsd.edu  

**Section:** (Your section number)  
**Mentor:** (Your mentor’s name)

---

## 1. What is the most interesting topic covered in your domain this quarter?
The most compelling topic this quarter has been the concept of digital twins for personalized cardiovascular modeling. Integrating physiological signals like ECG and SCG with structured clinical data has revealed how multimodal fusion can bridge the gap between raw signal processing and clinical interpretability. I found it especially interesting how digital twins can evolve in real time to simulate patient health trajectories, a paradigm that transforms predictive medicine from static diagnostics into dynamic, individualized monitoring.

## 2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.
In Quarter 2, I’d like to explore cross-modal alignment between ECG waveforms and electronic health record (EHR) entities using transformer-based architectures. Specifically, I plan to investigate how clinical entity extraction and temporal modeling can improve the interpretability and robustness of digital-twin predictions. This investigation could involve using embeddings from large language models (LLMs) to align waveform segments with structured clinical terminology, such as SNOMED CT or UMLS codes, enabling a semantically grounded cardiac diagnostic model.

## 3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?
A major improvement would be to emphasize real-time personalization and model generalization rather than focusing solely on data integration. Our current pipeline processes ECG and EHR data separately before fusion, but a next step is to implement adaptive calibration that continuously updates model parameters for each patient. Incorporating Bayesian optimization or reinforcement-learning-based personalization could make the twin more responsive to evolving physiological states and reduce overfitting to static datasets.

## 4. What other techniques would you be interested in using in your project?
I’m interested in experimenting with attention-based multimodal encoders and Riemannian-geometry-based representations to capture latent relationships between time-series signals and clinical features. Additionally, incorporating explainability methods such as SHAP or Grad-CAM would help clinicians interpret the model’s reasoning and build trust in digital-twin recommendations. I’d also like to explore synthetic ECG generation using vector-quantized models for privacy-preserving model training and improved diagnostic coverage.
