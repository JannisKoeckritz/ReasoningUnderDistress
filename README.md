# Reasoning Under Distress: Mining Claims and Evidence in Mental Health Narratives
A BERT-based approach to classify argumentative elements in mental health Reddit posts using zero-shot transfer learning from persuasive essay training data.

# 🧠 Zero-Shot Argument Mining in Mental Health Narratives

This repository supports the research presented at the Workshop on Argument Mining @ ACL 2025 titled:
**"Reasoning Under Distress: Mining Claims and Evidence in Mental Health Narratives"**  by Jannis Köckritz, Bahar İlgen, Georges Hattab.

## 📝 Overview

This project explores how argument mining models trained on structured texts (e.g., persuasive essays) perform when applied to informal, affective mental health narratives. We demonstrate that while evidence sentences transfer reasonably well across domains, claim detection degrades significantly due to domain-specific expression styles.

## 📊 Core Contributions

- Fine-tuned a BERT model on the Persuade dataset (student essays).
- Achieved 69.1% macro-F1 on the Persuade test set.
- Applied the model zero-shot to CAMS (Reddit posts on mental health).
- Achieved 48.9% macro-F1 on a manually annotated CAMS subset.
- Identified structural differences in how claims and evidence are expressed in mental health narratives.

# 📚 Data

- Persuade dataset: Crossley, S. A, Baffour, P., Tian, Y., Franklin, A., Benner, M., & Boser., U. (in press). A large-scale corpus for assessing written argumentation: PERSUADE 2.0. Assessing Writing, 61.  [Paper](https://www.sciencedirect.com/science/article/pii/S1075293524000588)
- CAMS dataset: Garg, M., Saxena, C., Saha, S., Krishnan, V., Joshi, R., & Mago, V. (2022). CAMS: An annotated corpus for causal analysis of mental health issues in social media posts. Proceedings of the Thirteenth Language Resources and Evaluation Conference (pp. 6387–6396). Marseille, France: European Language Resources Association. [Paper](https://aclanthology.org/2022.lrec-1.686/)
