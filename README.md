# NIH Chest X-ray Multi-Label Classification (FastAI + ResNet50)

This project implements a multi-label chest pathology classification pipeline using the NIH ChestXray14 dataset.  
A transfer learning approach is applied using FastAI with a ResNet backbone for multi-label disease prediction.

---

## Key Highlights
- Multi-label classification on NIH ChestXray14
- Transfer learning using ResNet50 / ResNet34
- FastAI training pipeline using `vision_learner`
- Multi-label evaluation using `accuracy_multi`
- Threshold tuning for improved predictions
- GPU training on Google Colab

---

## Dataset
- NIH ChestXray14 dataset
- Labels provided in a CSV file (multi-label format)

> Note: Dataset files are not uploaded to GitHub due to size restrictions.

---

## Model
- Backbone: ResNet50 (transfer learning)
- Framework: FastAI

---

## Results
- Validation performance (accuracy_multi): **90.5%**
- Training: Google Colab GPU

---

## How to Run (Google Colab)
1. Open the notebook from `notebooks/`
2. Mount Google Drive (if dataset is stored in Drive)
3. Run all cells sequentially

---

## Project Structure
