# Human Behavior & Vision Fusion

This project explores the prediction of human motion (e.g., pedestrian movement) by combining scene context and vision-based deep learning models. The goal is to understand behavior in real-world environments like crosswalks, sidewalks, or intersections using datasets and models like LSTM and Transformers.

##  Motivation
Understanding human behavior is critical for applications in autonomous driving, smart cities, and safety monitoring. This repo explores scene-aware modeling that fuses visual context with temporal predictions.

##  Structure
- `notebooks/`: Main Jupyter notebooks for exploration and experiments.
- `src/`: Model architecture (LSTM/Transformer).
- `data/`: Notes or links to datasets used.
- `requirements.txt`: Python package dependencies.

##  Example Datasets
- [PIE Dataset (Pedestrian Intention Estimation)](https://data.nvision2.eecs.yorku.ca/PIE_dataset/)
- [JAAD Dataset](https://data.nvision2.eecs.yorku.ca/JAAD_dataset/)
- [ETH/UCY Dataset](https://github.com/vita-epfl/social-force)

## 🔧 Tech Stack
- Python 
- PyTorch
- NumPy
- OpenCV
- Matplotlib / Seaborn

## 🚀 Goals
- Preprocess and visualize pedestrian behavior datasets.
- Build models (LSTM, Transformer) to predict motion trajectory.
- Fuse scene semantics into prediction pipeline.
