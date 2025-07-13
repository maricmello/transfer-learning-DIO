# Projeto de Transfer Learning com FER2013 (Happy vs Sad)

Este projeto utiliza **Transfer Learning** com a rede **MobileNetV2** para classificar emoções faciais no dataset **FER2013**, focando apenas nas classes **"happy"** e **"sad"**.

## 🔍 Descrição

- **Base de Dados**: [FER2013 - Kaggle](https://www.kaggle.com/datasets/msambare/fer2013)
- **Técnica**: Transfer Learning com rede pré-treinada no ImageNet
- **Classes utilizadas**: `happy` e `sad`
- **Ambiente**: Google Colab com GPU

## 📁 Estrutura esperada do dataset

```text
fer2013/
├── train/
│   ├── happy/
│   └── sad/
└── test/
    ├── happy/
    └── sad/