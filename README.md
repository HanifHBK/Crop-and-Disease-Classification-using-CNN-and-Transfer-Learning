# Crop-and-Disease-Classification-using-CNN-and-Transfer-Learning
This repository contains the implementation of a **plant disease detection system** using deep learning, developed as part of a course project.   The work focuses on **Crop Classification** and **Disease Classification**, with additional experiments using **Transformer-based models** for explanation generation.

## Project Overview
The project applies **Convolutional Neural Networks (CNNs)** and **transfer learning** to classify:
- **Plant species (Crop Classification)** using EfficientNet  
- **Leaf diseases (Disease Classification)** using ResNet50  

Datasets used:
- **PlantVillage** (training set)  
- **PlantDoc** (testing set)  
- **Private dataset (Plumeria / Kamboja)** collected manually with smartphone camera  

Additional tasks include:
- **Image preprocessing** (segmentation via K-Means clustering)  
- **Image augmentation** (rotation)  
- **Transformer integration**: generating natural language explanations from CNN outputs using MBZUAI/LaMini-GPT  

---

## Repository Structure
```text
.
├── Comparison.ipynb                # Notebook comparing different models
├── Full Model with Transformers.ipynb  # Full pipeline + explanation with transformers
├── Full Model.ipynb                 # Main notebook: crop + disease classification (Google Colab)
├── Model for Plant Classification.ipynb  # Crop classification using EfficientNet
├── Model for Potato.ipynb           # Disease classification for potato leaves
├── Model for Tomato.ipynb           # Disease classification for tomato leaves
└── Presentasi Tugas Besar.pptx      # Final project presentation slides
```

## How to Run
All notebooks are designed to run on Google Colab.

Upload the notebook of interest (e.g., Full Model.ipynb) to Google Colab.

Mount your dataset (PlantVillage, PlantDoc, or custom dataset).

## Example Workflow
1. Crop Classification – Identify plant species (Tomato, Potato, Plumeria)

2. Disease Classification – Detect specific diseases in leaves

3. Evaluation – Compare performance across different pretrained models

4. Inference – Run detection on new leaf images

5. Explanation – Use transformers to generate human-readable descriptions of detected diseases

Results (Highlights)
Crop classification trained with EfficientNet achieved strong performance on PlantVillage dataset.

Disease classification with ResNet50 provided accurate detection for Tomato and Potato diseases.

Transformer integration generated contextual explanations for detected diseases, bridging CNN outputs with natural language.

## References
PlantVillage Dataset

PlantDoc Dataset

Scientific Reports – EfficientNet-based Plant Disease Classification

MBZUAI/LaMini-GPT: https://huggingface.co/MBZUAI/LaMini-GPT-774M

## Contributors
Muhammad Hanif Hibatullah (13220051) – Full model implementation (crop & disease classification, transformers)

Yansen Dwiputra (13220056)

Teddy Hidayat (33223002)

Nopi Ramsari (33223003)

A. Sumarudin (33222033)
Copy code

---
