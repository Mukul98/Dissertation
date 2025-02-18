# Iris Detection and Face Recognition with Final Fusion

This project integrates **Iris Detection** and **Face Recognition** using Siamese Neural Networks, culminating in a final fusion process for biometric authentication. It includes three Jupyter Notebooks:

1. **Iris Detection** (`Iris_Detection.ipynb`)
2. **Face Recognition** (`Face_Recog.ipynb`)
3. **Final Fusion** (`Final_fusion_code.ipynb`)

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This project demonstrates a multimodal biometric system that uses both **iris** and **facial features** for authentication. The system achieves high accuracy through score-level fusion of the two modalities. The notebooks guide you through:
- Preprocessing and detecting iris and face features.
- Training Siamese networks for each modality.
- Combining results through a final fusion mechanism.

---

## Features

- **Iris Detection**: Detects iris features for biometric recognition.
- **Face Recognition**: Identifies facial features using a Siamese Neural Network.
- **Final Fusion**: Combines scores from iris and face recognition models for robust authentication.
- **Reusable Models**: Saves model weights for future use.

---

## Prerequisites

Ensure the following are installed:

- Python 3.x
- Jupyter Notebook
- A virtual environment manager (e.g., `venv`)
- Required Python libraries (specified in `requirements.txt`)

---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
