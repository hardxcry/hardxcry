<p align="center">
  <img src="assets/banner.svg" alt="Hariharan S, hardxcry. AI engineering, cybersecurity, automobiles, healthcare tech." width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-0f2a2a?style=for-the-badge&logo=python&logoColor=5eead4" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-0f2a2a?style=for-the-badge&logo=pytorch&logoColor=5eead4" alt="PyTorch">
  <img src="https://img.shields.io/badge/Hugging%20Face-0f2a2a?style=for-the-badge&logo=huggingface&logoColor=5eead4" alt="Hugging Face">
  <img src="https://img.shields.io/badge/OpenCV-0f2a2a?style=for-the-badge&logo=opencv&logoColor=5eead4" alt="OpenCV">
  <img src="https://img.shields.io/badge/scikit--learn-0f2a2a?style=for-the-badge&logo=scikitlearn&logoColor=5eead4" alt="scikit-learn">
  <img src="https://img.shields.io/badge/Streamlit-0f2a2a?style=for-the-badge&logo=streamlit&logoColor=5eead4" alt="Streamlit">
  <img src="https://img.shields.io/badge/Git-0f2a2a?style=for-the-badge&logo=git&logoColor=5eead4" alt="Git">
</p>

### `> whoami`

AI engineering geek. I like taking a model from an idea to something that runs, then finding
out where it breaks. Engineering student, constant tinkerer.

### `> ls interests/`

| | | |
|---|---|---|
| 🤖 | **AI engineering** | Training and fine-tuning models, retrieval systems, evaluation that holds up |
| 🛡️ | **Cybersecurity** | How systems fail, and how to build ones that do not |
| 🏎️ | **Automobiles** | Cars, how they work, and the tech inside them |
| 🩺 | **Healthcare AI** | Vision, audio and clinical-data models tested the way medicine tests things |
| ⚙️ | **Tech in general** | Local AI setups, automation, anything worth taking apart |

### `> cat featured.md`

**Med-AI portfolio.** Six end-to-end projects on open clinical datasets, each with reproducible
code, a paper-style report, tests and an interactive app.

| | Project | What it does | Headline finding |
|---|---|---|---|
| 🫀 | [**CardioRisk**](https://github.com/hardxcry/cardiorisk-heart-disease-prediction) | Heart-disease risk from 13 clinical variables, 4 hospitals | AUROC 0.903 in cross-validation falls to 0.812 on a hospital the model never saw |
| 🧬 | [**TrialMatch**](https://github.com/hardxcry/trialmatch-clinical-trial-matcher) | Matches a patient description to recruiting clinical trials | Dense retrieval + age/sex rules (NDCG@10 0.539) beat the usual hybrid + re-ranker recipe (0.426) |
| 🚶 | [**StepSafe**](https://github.com/hardxcry/stepsafe-tug-fall-risk) | Times the CDC fall-risk walk test from ordinary video | Reads about 0.5 s short at typical camera noise and never over-flagged a patient in 2,000 simulated tests |
| 👶 | [**CrySense**](https://github.com/hardxcry/crysense-infant-cry-analysis) | Tests whether audio can reveal why a baby is crying | A negative result: the best model scores 0.226 balanced accuracy against 0.200 for guessing |
| 💊 | [**PillLens**](https://github.com/hardxcry/pilllens-pill-identification) | Identifies a pill from a phone photo among 4,902 types | Fine-tuning CLIP lifts top-1 accuracy from 20% to 71%; both sides of the pill reach 84% |
| 🔬 | **SurgiPhase** | Recognises the phases of keyhole surgery from video | Training on 66 Cholec80 operations. Coming soon |

### `> cat principles.txt`

- **Test on the unseen.** A model is only as good as its worst new environment.
- **Baselines first.** If "always guess the majority" scores 84%, accuracy is the wrong metric.
- **Hunt for leakage.** The same subject in train and test can double an apparent result.
- **Report what breaks.** Limitations go in the README, not in a footnote.

<p align="center"><sub>The medical projects are research prototypes for education, not medical devices.</sub></p>
