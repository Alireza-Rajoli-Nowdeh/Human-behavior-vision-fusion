# Human Behavior & Vision Fusion

A modular deep learning framework to predict pedestrian behavior using visual context and movement history. Built for research in smart mobility, autonomous systems, and human-aware AI.

---

##  Objectives

- Predict future human motion from past trajectory + scene image
- Combine vision-based context with deep sequential models
- Evaluate across real-world datasets (PIE, JAAD, ETH/UCY)
- Support modular extensions (e.g., scene semantics, IMU fusion)

---

##  Methods

| Task                       | Method                            |
|---------------------------|-----------------------------------|
| Feature extraction        | ResNet / Semantic Segmentation    |
| Sequence modeling         | LSTM, Transformer                 |
| Fusion mechanism          | Late fusion (vision + history)    |
| Evaluation                | ADE / FDE / Classification Acc.   |
| Visualization             | Trajectory overlay on scene       |



---

##  Datasets

- [PIE (Pedestrian Intention Estimation)](https://data.nvision2.eecs.yorku.ca/PIE_dataset/)
- [JAAD](https://data.nvision2.eecs.yorku.ca/JAAD_dataset/)
- [ETH/UCY](https://github.com/vita-epfl/social-force)

---

## 🛠 Tech Stack

- Python 3.10+
- PyTorch
- torchvision
- OpenCV
- NumPy, matplotlib
- PyYAML


