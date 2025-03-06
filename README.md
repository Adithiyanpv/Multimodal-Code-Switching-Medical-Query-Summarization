# Multimodal Code-Mixed Medical Query Summarization

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

3. **Training & Evaluation:**
   - Fine-tuned on the **MMCQS** dataset.
   - Evaluated using standard NLP metrics (ROUGE, BLEU, BERTScore).

## 📊 **Results**

Our model achieved the following results on the extended MMCQS dataset:

- **ROUGE-1:** 0.6009
- **ROUGE-2:** 0.3827
- **ROUGE-L:** 0.5169
- **BLEU-4:** 0.3620
- **BERTScore (F1):** 0.9192

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

## 🧑‍🤝‍🧑 **Project Mentor**

- **Dr. G Bharathi Mohan**

## 🧑‍🤝‍🧑 **Our Core Team**

- **Adithiyan P.V. - CH.EN.U4AIE22003**
- **Jeevan Sendur G - CH.EN.U4AIE22020**
- **Rahul K - CH.EN.U4AIE22044**



## 🚀 **Future Work**

- Expand the dataset to cover additional symptom categories.
- Optimize the model for real-time deployment in resource-constrained environments.
- Explore multilingual support for broader accessibility.

## 📄 **References**

1. Arkadeep Acharya et al., "MedSumm: Multimodal Medical Query Summarization," *ECIR 2024*.
2. Vaswani et al., "Attention Is All You Need," *NeurIPS 2017*.

---

> **Bridging the gap between patients and healthcare through advanced multimodal summarization.**
