# Omatillo Fazliddinov
 
**Computational pathology · whole-slide image analysis · calibration under distribution shift**
 
Final-year CS undergrad (B.Eng., Xuzhou University of Technology, June 2027). I work on weakly supervised and multiple-instance learning over whole-slide images, and on the part that usually goes unreported: whether a pathology model still holds up outside the cohort it was built on.
 
Mostly interested in prevalence shift, deferral thresholds, and what "safe to automate" actually means at a site with no labels and no specialist.
 
---
 
### Selected work
 
| Project | What it is | Outcome |
|---|---|---|
| **[EGFR prediction from H&E WSIs](https://github.com/FOmadbek/SYSU-2026)** | EAGLE replication (Campanella et al., *Nat Med* 2025) on TCGA-LUAD. Frozen UNI2-h + attention MIL. | AUC 0.727 ± 0.015 / 0.736 ens. Deferral raised missed positives **1.65–2.29×** — traced to cohort prevalence (π 0.386 vs 0.113), not architecture. |
| **[ClaraSight](Clarasight.uz)** | Offline edge-AI TB chest X-ray triage. ESP32-P4 / RPi5+Hailo-8L / Jetson Orin Nano, nine-language UI. | Working prototype. Built around cross-population calibration, not aggregate accuracy. |
| **[Micropapillary adenocarcinoma segmentation](https://github.com/FOmadbek/REPO)** | U-Net over ~19,000 lung histopathology image–mask pairs. Focal loss, patch oversampling. | Dice/IoU + Grad-CAM attribution. PyTorch, OpenCV. |
| **[BreakHis classifier](https://github.com/FOmadbek/breast-cancer-binary-multiclass)** | ResNet-18, binary malignancy + 8-subtype. FastAPI service behind Spring Boot. | Macro-F1 **0.882** (8-subtype). |
| **[ML-Contest-2026](https://github.com/FOmadbek/ML-Contest-2026)** | CatBoost + LightGBM + XGBoost, Optuna-tuned. | Private AUC 0.8938 (post-deadline, unranked). |
| **[BinoGo](https://binogo.uz)** | Android app, site and backend for a construction-materials marketplace. | Shipped. |
 
---
 
### Stack
 
```
languages   python · c++ · java · sql
ml/dl       pytorch · scikit-learn · xgboost · lightgbm · catboost · optuna
pathology   attention MIL · u-net · UNI2-h · CONCH · Virchow · openslide
backend     fastapi · spring boot · postgresql · mysql · vue.js
hpc         parallel workflows · cluster computing
tools       git · linux (wsl2)
```
 
---
 
### Currently
 
- Writing on **prevalence-indexed deferral for slide-level triage at sites without labels** — setting an abstention threshold when deployment prevalence is unknown, and propagating that estimation error into a bound on missed positives.
- Applying to postgraduate research in computational pathology / trustworthy ML for health.
- TA for C++, SQL & databases, and Java web development at XUT.
- Open to collaborations in medical imaging and applied ML.
---
 
[LinkedIn](https://linkedin.com/in/fomadbek) · [Kaggle](https://www.kaggle.com/omadbekfazliddinov) · [Telegram](https://t.me/f_omadbek_vlog) · [Email](mailto:fazliddinovomadbek@gmail.com) · WeChat `F_Omadbek`
