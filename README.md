<p align="center">
  <img src="assets/banner.svg" alt="Hariharan S. Biomedical engineering and AI for healthcare." width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white" alt="MediaPipe">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit">
</p>

### 👋 About

Biomedical engineering student working where medicine meets machine learning. I care less about
a high number on a slide and more about whether a model would hold up in a clinic: tested on
hospitals and patients it has never seen, compared against honest baselines, and reported with
its failures.

### 🩺 Medical AI portfolio

Six end-to-end projects on open clinical datasets. Each has reproducible code, a paper-style
report, unit tests and an interactive app.

| | Project | What it does | Headline finding |
|---|---|---|---|
| 🫀 | [**CardioRisk**](https://github.com/hardxcry/cardiorisk-heart-disease-prediction) | Heart-disease risk from 13 clinical variables, 4 hospitals | AUROC 0.903 in cross-validation falls to 0.812 on a hospital the model never saw |
| 🧬 | [**TrialMatch**](https://github.com/hardxcry/trialmatch-clinical-trial-matcher) | Matches a patient description to recruiting clinical trials | Dense retrieval + age/sex rules (NDCG@10 0.539) beat the usual hybrid + re-ranker recipe (0.426) |
| 🚶 | [**StepSafe**](https://github.com/hardxcry/stepsafe-tug-fall-risk) | Times the CDC fall-risk walk test from ordinary video | Reads about 0.5 s short at typical camera noise and never over-flagged a patient in 2,000 simulated tests |
| 👶 | [**CrySense**](https://github.com/hardxcry/crysense-infant-cry-analysis) | Tests whether audio can reveal why a baby is crying | A negative result: the best model scores 0.226 balanced accuracy against 0.200 for guessing |
| 💊 | [**PillLens**](https://github.com/hardxcry/pilllens-pill-identification) | Identifies a pill from a phone photo among 4,902 types | Fine-tuning CLIP lifts top-1 accuracy from 20% to 71%; both sides of the pill reach 84% |
| 🔬 | **SurgiPhase** | Recognises the phases of keyhole surgery from video | Training on 66 Cholec80 operations. Coming soon |

### 🧪 How I work

- **Validate on the unseen.** Other hospitals, other patients, held-out operations.
- **Baselines first.** If "always predict the majority class" scores 84%, accuracy is the wrong metric.
- **Uncertainty is part of the result.** Confidence intervals and significance tests, not single numbers.
- **Hunt for leakage.** The same patient in train and test can double an apparent effect.
- **Say what does not work.** Every report has a limitations section, and one project is a negative result.

### 🔭 Interests

Clinical decision support · medical imaging and video · biosignals · wearable sensing · evaluation methodology

<p align="center"><sub>Research prototypes for education. None of these tools is a medical device.</sub></p>
