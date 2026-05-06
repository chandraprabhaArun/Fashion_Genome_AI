# 🧬 Fashion Genome AI
### Intelligent Outfit DNA Analysis System

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=flat-square&logo=tensorflow)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?style=flat-square&logo=streamlit)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

> **Fashion Genome AI** decodes the DNA of fashion — extracting style attributes, color combinations, fabric textures, and trend patterns from clothing images to power next-generation fashion intelligence.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [System Architecture](#system-architecture)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results & Visualizations](#results--visualizations)
- [Future Scope](#future-scope)
- [License](#license)

---

## 🧠 Overview

Fashion Genome AI is an advanced AI system that analyzes millions of clothing images to build a **fashion genome** — a structured digital representation of fashion elements. Unlike traditional virtual try-on systems, this project focuses on *deeply understanding* fashion through:

- **Computer Vision** — extracting visual attributes from clothing images
- **Deep Learning** — building semantic embeddings for each fashion item
- **NLP** — linking visual features with textual metadata
- **Trend Forecasting** — predicting emerging fashion patterns from data

---

## ✨ Features

| Feature | Description |
|---|---|
| 👗 Attribute Extraction | Detects color, texture, sleeve type, fit, and fabric |
| 🔍 Fashion Vector Embedding | Converts clothing into a unique digital DNA fingerprint |
| 🧲 Similarity Retrieval | Finds visually similar outfits using cosine similarity |
| 📈 Trend Forecasting | Predicts emerging styles using LSTM / Prophet |
| 📊 Analytics Dashboard | Interactive Streamlit dashboard for fashion insights |
| 🏷️ Automated Tagging | AI-based category and attribute labeling |

---

## 📦 Dataset

This project uses the **DeepFashion Dataset** — a large-scale fashion image database containing:

- 50+ clothing categories and 1,000+ fine-grained attributes
- Fashion landmark keypoints (collar, sleeve, hem)
- Consumer-to-shop image pairs for real-world matching
- Annotations for category, attributes, landmarks, segmentation, and pose

---

## 🏗️ System Architecture

```
Input Image
     ↓
Feature Extraction (CNN / Vision Transformer)
     ↓
Attribute Classification (Category, Color, Texture)
     ↓
Fashion Genome Creation (Embeddings + Metadata)
     ↓
Trend Analysis Engine
     ↓
Streamlit Dashboard (Search, Analytics, Visualization)
```

---

## 🛠️ Technology Stack

| Layer | Technology |
|---|---|
| Language | Python 3.8+ |
| Deep Learning | TensorFlow, PyTorch |
| Computer Vision | OpenCV, Vision Transformer (ViT) |
| NLP & Metadata | LangChain, Hugging Face |
| Visualization | Streamlit, Plotly, Matplotlib |
| Database | MongoDB / PostgreSQL |
| Deployment | Streamlit Cloud / Docker |

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/chandraprabhaArun/Fashion_Genome_AI.git
cd Fashion_Genome_AI

# Create and activate virtual environment
python -m venv venv
venv\Scripts\activate        # Windows
# source venv/bin/activate   # macOS/Linux

# Install dependencies
pip install -r requirements.txt
```

---

## 🚀 Usage

```bash
# Run EDA
python final_eda.py

# Launch Streamlit dashboard
streamlit run app.py

# Run model development notebook
jupyter notebook Model_development.ipynb
```

---

## 📁 Project Structure

```
Fashion_Genome_AI/
│
├── 📓 EDA.ipynb                      # Exploratory Data Analysis
├── 📓 EDA_Details.ipynb              # Detailed EDA
├── 📓 Final_EDA.ipynb                # Final EDA notebook
├── 📓 Model_development.ipynb        # Model training & evaluation
├── 📓 RAG_Layer.ipynb                # Retrieval-Augmented Generation layer
│
├── 🐍 final_eda.py                   # EDA script
├── 🐍 eda_details.py                 # Detailed EDA script
├── 🐍 test.py                        # Testing script
│
├── 📊 image_level_features.csv       # Per-image feature data
├── 📊 category_level_features.csv    # Category-wise features
├── 📊 deep_learning_features.csv     # Deep feature embeddings
├── 📊 text_features.csv              # Text-based features
├── 📊 feature_importance.csv         # Feature importance scores
├── 📊 trend_analysis.csv             # Trend analysis results
│
├── 🖼️ pca_visualization.png          # PCA plot
├── 🖼️ feature_correlation.png        # Feature correlation heatmap
├── 🖼️ class_distribution.png         # Class distribution chart
├── 🖼️ trend_*.png                    # Trend visualizations
│
└── 📄 requirements.txt               # Python dependencies
```

---

## 📊 Results & Visualizations

The project includes comprehensive EDA and feature analysis:

- **PCA Visualization** — dimensionality reduction of fashion embeddings
- **Feature Correlation Heatmap** — relationships between extracted features
- **Class Distribution** — category balance across the dataset
- **Trend Analysis** — emerging patterns (Butter Yellow, Suede & Leather, Tailored Outerwear)
- **Deep Feature Distributions** — visualization of learned representations

---

## 🔮 Future Scope

- 🎨 Integrate **Stable Diffusion** for generative fashion design
- 🌐 Build a **Fashion Genome API** for designers and e-commerce platforms
- 🎙️ Multi-modal understanding — image + text + audio reviews
- 🤖 Real-time AI fashion assistant

---

## 👤 Author

**Chandraprabha Arun**
- GitHub: [@chandraprabhaArun](https://github.com/chandraprabhaArun)

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

<p align="center">Built with ❤️ for the future of fashion intelligence</p>
