# Pneumonia detection and active learning project
Course: Image Processing and Computer Vision, graduate study Computer Science, Mentor: Dr.sc. Marin Benčević

## Project description:
This project investigates the application of Active Learning in combination with Transfer Learning for pneumonia detection on chest X-rays. The main goal was to compare the performance of smart data selection (uncertainty strategy) compared to standard random sampling.
<img width="1489" height="428" alt="image" src="https://github.com/user-attachments/assets/b75543f1-2615-4103-9e00-a59d45b096e4" />
<img width="1489" height="400" alt="image" src="https://github.com/user-attachments/assets/f7a9233b-5f18-4cf3-b156-87b55a1a243c" />



##Technologies used: 
- Python
- Google Colab
- PyTorch
- basic architecture for transfer learning: VGG16
- Kaggle dataset: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

## Main motivation:
The goal of this approach is to develop a system that requires intervention from experts only in borderline cases, thereby optimizing the workflow in radiology.

## Main functionalities:
- Human-in-the-loop implementation: A system is developed that iteratively selects the most informative unlabeled examples for annotation, instead of randomly selecting data.
- Uncertainty Sampling strategies: Using advanced data selection methods (such as least confidence or entropy) to train the model on "difficult" cases that the system does not recognize with high confidence.
- Comparative performance analysis: A detailed comparison between active learning and traditional learning (Random Sampling) was conducted, proving the superiority of AL in conditions with limited data.
- Transfer Learning: Using pre-trained neural network architectures optimized for working with medical images (X-ray images of the lungs).
- Robust evaluation of medical metrics: Model analysis is not limited to accuracy only, but also focuses on recall and F1-measure, which is critical for reducing false negatives in medical diagnostics.
- Resource efficiency: Achieving high model performance with only 100 labeled samples, simulating real-world conditions where the work of a physician (annotator) is expensive and time-constrained.
- Results visualization: Integrated graphical representations of learning curves that clearly show the speed of model convergence through active learning iterations.

## Project launch:
Link to original code and experiment replication: https://colab.research.google.com/drive/1pUwzNZyrKn3oheruNbkOzbNNRQJwGLVQ#scrollTo=ZGmyf6oRUMMq

## Results:
A detailed description and analysis of the results are presented in chapter 3.

AUTHOR: Ivona Pranjić, 2025./2026. 

<img width="1990" height="1190" alt="image" src="https://github.com/user-attachments/assets/19cee60c-1bed-4e75-833d-e0d9d86bcfb6" />


