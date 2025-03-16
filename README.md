# Multimodal Code-Mixed Medical Query Summarization

## 🧑‍🤝‍🧑 **Project Mentor**

- **Dr. G Bharathi Mohan**

## 🧑‍🤝‍🧑 **Our Core Team**

- **Adithiyan PV - CH.EN.U4AIE22003**
- **Jeevan Sendur G - CH.EN.U4AIE22020**
- **Rahul K - CH.EN.U4AIE22044**

# 📄 Research Paper & Documents  

🔗 **Access our Paper write-up and other documents here:**  
[📂 Google Drive Link](https://drive.google.com/drive/folders/14vTr7KR8F_db55VtN203Kxfyy1slUKw2?usp=sharing)  


## 📌 **Project Overview**

In the healthcare domain, effective communication between patients and healthcare providers is crucial, especially when describing complex medical conditions. Our project, **Multimodal Code-Switching Medical Query Summarization**, aims to address this challenge by developing a lightweight model capable of summarizing codemixed Hindi-English medical queries using both textual and visual data.

We leverage a **Vision Transformer (ViT)** to process medical images and **DistilBART**, a distilled version of BART, to generate concise medical summaries. This approach not only enhances model efficiency but also ensures faster inference while maintaining high performance.

## 📊 **Key Features**

- **Multimodal Input:** Combines visual and textual data for richer context.
- **Lightweight Model:** Utilizes **DistilBART** for faster inference and reduced computational complexity.
- **Improved Generalization:** Incorporates advanced tokenization and diverse data augmentation techniques.
- **High Performance:** Outperforms existing benchmarks with superior evaluation metrics.
- **Scalable Solution:** Designed for real-time clinical applications in low-resource settings.

## 📈 **Methodology**

1. **Data Preprocessing:**
   - Utilized the **MMCQS** dataset, comprising **3,015 medically validated samples** categorized into four symptom groups: ENT, Eye, Limb, and Skin.
   - Applied resizing, cropping, flipping, and color jittering for data augmentation to improve model robustness.

2. **Model Architecture:**
   - **Vision Transformer (ViT):** Extracts visual features from medical images.
   - **DistilBART:** Generates accurate and concise medical summaries from multimodal inputs.

   Click here to download the Trained DistilBART model: https://drive.google.com/file/d/12yTMaYV3Af5Jn5PMY4xevR6PVBWKV9ew/view?usp=sharing

3. **Training & Evaluation:**
   - Fine-tuned on the **MMCQS** dataset.
   - Evaluated using standard NLP metrics (ROUGE, BLEU, BERTScore).

## 📊 **Results**

Our model achieved the following results on the extended MMCQS dataset:

- ROUGE-1: 60.09
- ROUGE-2: 38.27
- ROUGE-L: 51.69
- BLEU-1: 57.53
- BLEU-2: 46.65
- BLEU-3: 40.38
- BLEU-4: 36.20
- BERTScore: 0.919
- Readability: 69.85

These scores surpass the existing **MedSumm** model, demonstrating the effectiveness of our lightweight approach.

## 📂 **Dataset**

The **MMCQS dataset** used in this project is publicly available on Hugging Face:

🔗 [Access the dataset](https://huggingface.co/datasets/ArkaAcharya/MMCQSD)

## 📚 **Technologies Used**

- Python
- PyTorch
- Hugging Face Transformers
- Vision Transformer (ViT)
- DistilBART




## 🚀 **Future Work**

- Expand the dataset to cover additional symptom categories.
- Optimize the model for real-time deployment in resource-constrained environments.
- Explore multilingual support for broader accessibility.

## 📄 **References**

1. Arkadeep Acharya et al., "MedSumm: Multimodal Medical Query Summarization," *ECIR 2024*.
2. Vaswani et al., "Attention Is All You Need," *NeurIPS 2017*.
3. A. B. Abacha and D. Demner-Fushman. "On the summarization of consumer health questions." Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, pp. 2228–2234, 2019.
4. A. Das and B. Gambäck. "Identifying languages at the word level in code-mixed Indian social media text." arXiv preprint arXiv:2302.13971, 2014.
5. J.-B. Delbrouck, C. Zhang, and D. Rubin. "QIAI at MEDIQA 2021: Multimodal radiology report summarization." Proceedings of the 20th Workshop on Biomedical Language Processing, pp. 285–290, 2021.

---

> **Bridging the gap between patients and healthcare through advanced multimodal summarization.**
