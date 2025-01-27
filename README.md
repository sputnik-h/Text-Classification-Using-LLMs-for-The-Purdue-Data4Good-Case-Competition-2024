# Text Classification Using LLMs for The Purdue Data4Good Case Competition 2024

## Project Overview
This project was developed for the **Purdue Data4Good Case Competition 2024**, which centers on applying cutting-edge generative AI (GenAI) techniques to tackle pressing social issues. Participants were tasked with analyzing datasets and deriving actionable insights to create positive social impact.

This year’s challenge focused on **The Tragedy Assistance Program for Survivors (TAPS)**, an organization supporting families grieving the loss of loved ones in military service. Central to their mission is a "survivor journey map," a framework outlining key stages in the grief process to help survivors navigate their emotions while guiding TAPS staff in providing tailored care. However, maintaining and updating this map manually is a time-intensive process, limiting its potential to quickly connect survivors with the most relevant resources. The competition aimed to solve this by creating an **AI-powered solution** for "Automated Journey Mapping," which automatically classifies survey responses into stages of the journey map. This innovation enables TAPS to allocate resources efficiently, deliver personalized support, and evolve services to better address the needs of grieving families.

---

## Dataset
The dataset includes **23 columns**, where each column represents a synthesized answer to a survey question. Each row corresponds to a single survey response, capturing the unique experiences of survivors.

---

## Methodology and Highlights
Our approach involved leveraging **Meta’s Llama LLM** for classification tasks, using innovative techniques to enhance performance and stability:

1. **Few-Shot Learning:**
   - Splitting the dataset into a training set with labeled examples to enable the LLM to learn the context and relationships between survey responses and journey map stages.

2. **Ensembling:**
   - Combining predictions from multiple model runs to achieve consistent and accurate classifications.

3. **Prompt Engineering:**
   - Crafting multi-turn conversations with the LLM to add richer context to the classification process, improving the model's understanding of nuanced responses.

4. **Process Automation:**
   - **API Integration:** Leveraged PredictionGuard's GenAI API for seamless access to LLM capabilities.
   - **Failure Mitigation:** Developed automated scripts to save intermediate classification results and retry processes in case of network instability or server failures.

---

## Results and Highlights
The final model was evaluated using the **F1 score**, with significant improvements over traditional machine learning approaches:

- **Highest F1 Score Achieved:** 0.88319 (a 13% improvement over the best-performing traditional ML model)

This result underscores the potential of LLMs in addressing complex, real-world challenges with high sensitivity and precision.

---

## Team Members
- **Ethan Liu:** Responsible for pipeline development, programming, and modeling.
- **Tsubasa Lin**
- **Katherine Wang**

---

## Files Included
1. **Ensembled-Few-Shot-Model-202411021359.ipynb:** Notebook detailing ensembled few-shot learning and classification.
2. **Prompt-Engineering-Model.ipynb:** Notebook detailing prompt engineering approach.

---
