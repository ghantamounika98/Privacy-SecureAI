# Privacy & Security in AI

A collection of hands-on implementations covering privacy-preserving machine learning techniques and adversarial security in deep learning.

## Topics Covered

### Privacy-Preserving ML
| Notebook | Description |
|----------|-------------|
| `7_differential_privacy_solution.ipynb` | Differential privacy fundamentals and DP-SGD |
| `Privacy_Preserved_Federated_Learning.ipynb` | Federated learning with privacy guarantees |
| `Privacy_Preserving_Training_of_CNN_for_Image_Classification.ipynb` | DP training for CNNs |
| `Optimizing_Federated_Learning_for_Image_Classification.ipynb` | Federated learning optimization strategies |
| `dpfl.ipynb` | Differential privacy + federated learning combined |
| `Tensorflow_Federated.ipynb` | Federated learning with TensorFlow Federated (TFF) |

### Secure Computation
| Notebook | Description |
|----------|-------------|
| `SMC_Encrypted_Tensors_1.ipynb` | Secure Multi-Party Computation with encrypted tensors using CrypTen |
| `Crypten_Logistic_regression.ipynb` | Privacy-preserving logistic regression via CrypTen |
| `Secure_Inference_with_Fully_Homomorphic_Encryption_(FHE).ipynb` | Neural network inference on encrypted data using FHE |

### Adversarial Attacks & Defenses
| Notebook | Description |
|----------|-------------|
| `Evasion.ipynb` | Evasion attacks on ML models |
| `Evasion_Attack_CNN.ipynb` | Adversarial examples (FGSM, PGD) against CNNs |
| `Evasion_Defense_CNN.ipynb` | Adversarial training and defense strategies |
| `Membership_inference_attack.ipynb` | Membership inference attacks on trained models |
| `NLP_simple_attack.ipynb` | Adversarial attacks on NLP models |
| `AIPart_2(3).ipynb` | Deep learning security analysis |

## Key Techniques

- **Differential Privacy**: DP-SGD, privacy budgets (ε, δ), sensitivity analysis
- **Federated Learning**: FedAvg, privacy-utility tradeoff, TensorFlow Federated
- **Secure Computation**: CrypTen (PyTorch-based), SMC, homomorphic encryption
- **Adversarial ML**: FGSM, PGD attacks; adversarial training defenses
- **Membership Inference**: Shadow model attacks, defense via DP

## Tech Stack

Python · PyTorch · TensorFlow · CrypTen · TensorFlow Federated · Concrete-ML (FHE) · scikit-learn

## Context

Developed as part of graduate coursework and independent research in trustworthy AI at Tennessee Technological University.
