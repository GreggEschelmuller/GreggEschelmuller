# Gregg Eschelmuller

**Quantitative Researcher — Probabilistic Modeling & Signal Processing**

PhD candidate (Kinesiology, Neuromechanics) at UBC. My research sits at the intersection of Bayesian inference, high-frequency physiological signal processing, and sensorimotor neuroscience. I build models that recover latent structure from noisy, high-dimensional biological data.

---

## What I work on

**Bayesian state estimation**  
I develop generative models of sensory integration — treating perception as an inference problem over noisy, partially conflicting signal sources. Current work: an inverse Bayesian observer model that recovers subject-specific sensory weights from behavioral endpoint error data, using joint optimization across experimental conditions with identifiability constraints.

**High-frequency signal processing pipelines**  
Production-grade ETL infrastructure for kHz-range physiological data streams (EMG, force, kinematic time series). Emphasis on automated artifact detection, alignment validation, and reproducible reprocessing across large longitudinal datasets.

**Statistical modeling & uncertainty quantification**  
Bootstrap confidence intervals, frequency-domain coherence and gain analysis, latent variable estimation, model validation against empirical data. I treat uncertainty as a first-class output, not an afterthought.

---

## Selected projects

**[bayesian-proprioception](https://github.com/GreggEschelmuller/bayesian-proprioception)** *(in progress)*  
Bayesian observer model of proprioceptive integration during reaching. Forward model: precision-weighted MLE over four conditionally independent sensory channels. Inverse model: L-BFGS-B joint optimization to recover σ (sensory noise) and δ (vibration bias) from behavioral data. Includes synthetic data generation, parameter recovery validation, and posterior predictive checks.

**[proprioceptive-recalibration](https://github.com/GreggEschelmuller/proprioceptive-recalibration)**  
Configuration-driven analysis pipeline for sensorimotor recalibration experiments. Modular `src/` layout, YAML-parameterized workflows, bootstrap CI estimation, automated data validation. Designed for reproducible reprocessing across multiple experimental conditions without code changes.

---

## Stack

**Modeling:** Python (NumPy, SciPy, PyTorch), MATLAB  
**Inference:** Bayesian inference, MLE, bootstrap methods, frequency-domain analysis (coherence, gain, phase)  
**Engineering:** Pandas, automated ETL pipelines, Git, pytest, uv, ruff  
**Database:** PostgreSQL *(in progress)*

---

## Credentials

- NSERC Canadian Graduate Scholarship – Doctoral (CGS-D)
- Killam Doctoral Scholarship
- UBC Four-Year Fellowship
- 6 peer-reviewed publications — [Google Scholar](https://scholar.google.com/citations?user=Sxvpo7YAAAAJ&hl=en)

---

📫 g.eschelmuller@gmail.com  
🌐 [greggeschelmuller.github.io](https://greggeschelmuller.github.io/personal-site/)  
💼 [linkedin.com/in/gregg-eschelmuller](https://www.linkedin.com/in/gregg-eschelmuller/)
