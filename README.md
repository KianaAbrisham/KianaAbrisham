# Kiana Pilevar Abrisham

**Machine learning · Biomedical signal processing · Python**

My research focuses on estimating arterial stiffness and studying age-related vascular changes from photoplethysmography (PPG). I hold an M.Sc. in Mechatronics from the University of Tehran. This portfolio brings together the related research code and smaller projects in classification, clustering, and transfer learning.

[Email](mailto:kianaabrisham@gmail.com) · [Google Scholar](https://scholar.google.com/citations?user=69IoCyIAAAAJ&hl=en) · [ORCID](https://orcid.org/0009-0007-4569-3196)

## Research projects

| Project | Focus and current evidence |
| --- | --- |
| [Feature-based cf-PWV estimation — IEEE Access](https://github.com/KianaAbrisham/ppg-cfpwv-ieee-access) | PPG/SDPPG features and XGBoost regression. Five-fold evaluation on 4,333 eligible radial PWDB subjects: mean RMSE 0.1809 m/s and R² 0.9925. |
| [PPG age-category benchmark](https://github.com/KianaAbrisham/ppg-vascular-age-benchmark) | MLP, CNN1D, and CNN2D evaluated with five shared folds at two sites, using 4,374 PWDB subjects per site. VGG16 has separate artificial-data software checks. |
| [CNN–BiLSTM–Attention for cf-PWV](https://github.com/KianaAbrisham/ppg-cfpwv-attention) | Compare waveform and spectrogram representations with temporal attention. Both paths have training and checkpoint checks; public-data preparation is verified and full PWDB evaluation remains pending. |
| [ResNet-18 spectrogram regression](https://github.com/KianaAbrisham/ppg-cfpwv-resnet) | PyTorch regression with separate training, validation, and test subjects. The CPU demo and checkpoint checks pass; full PWDB evaluation remains pending. |

PWDB contains simulated virtual adults. The recorded public-data evaluations use the current refactored implementations; full reproduction of every published result and clinical validation have not been established. Each research repository links its paper, protocol, and validation evidence.

## Applied machine-learning examples

- [MobileNetV2 on CIFAR-10](https://github.com/KianaAbrisham/cv-transfer-learning-mobilenetv2): frozen-backbone transfer learning, held-out image classification, and checkpoint reuse in an executed notebook.
- [Stroke classification pipeline](https://github.com/KianaAbrisham/stroke-prediction-ml-pipeline): preprocessing inside cross-validation, imbalanced-class metrics, and model selection on a synthetic tabular example.
- NumPy implementations of [linear SVM](https://github.com/KianaAbrisham/svm-from-scratch), [multinomial Naive Bayes](https://github.com/KianaAbrisham/naive-bayes-sentiment), and [K-means](https://github.com/KianaAbrisham/kmeans-breast-cancer-portfolio), plus a [PyTorch tabular MLP](https://github.com/KianaAbrisham/mlp-pytorch-classifier).

## Technical focus

Signal preprocessing · PPG/SDPPG features · Spectrograms · Classification and regression · Subject-level evaluation · Saved-model inference

**Tools:** Python · NumPy · pandas · SciPy · scikit-learn · TensorFlow/Keras · PyTorch · Matplotlib

[Development notes](docs/DEVELOPMENT.md)

For collaboration or project enquiries: **[kianaabrisham@gmail.com](mailto:kianaabrisham@gmail.com)**.
