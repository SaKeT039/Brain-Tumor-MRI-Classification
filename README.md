# Brain Tumor MRI Classification

This project focuses on brain tumor classification from MRI images using
Convolutional Neural Networks (CNN) and transfer learning techniques.

## Motivation
In medical image classification, relying only on accuracy can be misleading.
A model with high accuracy but low tumor recall can be dangerous in real-world
clinical scenarios. Therefore, this project emphasizes **recall and F1-score**
along with accuracy to improve medical reliability.

## Model Overview
- CNN-based architecture
- Transfer learning (pretrained model with frozen and fine-tuned layers)
- Binary classification: Tumor vs Non-Tumor
- Careful evaluation using confusion matrix, precision, recall, and F1-score

## Key Metrics (Approx.)
- Accuracy: ~82%
- Tumor Recall: ~0.83
- F1-score evaluated for balanced performance

## Implementation
The complete model architecture, training pipeline, and evaluation logic
were **originally implemented by Satyam**.

This repository is shared for academic collaboration and documentation purposes.

## Notes
- Dataset is not included due to size and licensing constraints.
- This repository focuses on model design, training strategy, and evaluation.

## License
This project is licensed under the MIT License.
