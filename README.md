# Lab04-XOR-Neural-Network-TensorFlow
🔮 TensorFlow implementation of XOR gate using neural networks | Solution to Lab 4 Exercise 2 | Neural Network Fundamentals



# Lab 04: XOR Neural Network Implementation with TensorFlow

[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)](https://www.tensorflow.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Overview
Neural network implementation solving XOR gate problem using TensorFlow. Created as solution for Exercise 2 in Logic Gates & Neural Networks Lab (Lab 04).

![XOR Architecture](https://miro.medium.com/v2/resize:fit:1400/1*a6XXvcW8V6S3xM4MHla4DA.png)

## ✨ Features
- 🧠 XOR logic implementation with neural networks
- 📈 Training progress visualization
- 🔍 Detailed parameter analysis
- ✅ 100% accuracy verification
- 🧩 Maintains original lab structure

## 🚀 Installation
```bash
git clone https://github.com/yourusername/Lab04-XOR-Neural-Network-TensorFlow.git
cd Lab04-XOR-Neural-Network-TensorFlow
pip install -r requirements.txt
```

## 🧮 Usage
```bash
python lab04_xor.py
```

**Sample Output:**
```
Epoch    0 | Loss: 0.2712 | Accuracy: 0.5000
Epoch 1000 | Loss: 0.0093 | Accuracy: 1.0000

Final Predictions:
[0 0] → 0 (confidence: 98.7%)
[0 1] → 1 (confidence: 99.2%)
[1 0] → 1 (confidence: 97.8%)
[1 1] → 0 (confidence: 99.1%)
```

## 🧠 Implementation
### Network Architecture
```
Input Layer (2) 
  ↓ 
Hidden Layer (2 neurons, sigmoid) 
  ↓ 
Output Layer (1 neuron, sigmoid)
```

### Training Parameters
| Parameter       | Value    |
|-----------------|----------|
| Epochs          | 10,000   |
| Learning Rate   | 0.5      |
| Loss Function   | MSE      |
| Optimizer       | Gradient |

## 📊 Results Table
| Input | Target | Prediction | Confidence |
|-------|--------|------------|------------|
| 0, 0  | 0      | 0          | 98.7%      |
| 0, 1  | 1      | 1          | 99.2%      |
| 1, 0  | 1      | 1          | 97.8%      |
| 1, 1  | 0      | 0          | 99.1%      |

## 📚 Academic Context
**Lab 04 Exercise Solution** demonstrating:
- Limitations of single-layer perceptrons
- Importance of hidden layers
- Backpropagation implementation
- Non-linear decision boundaries

## 📄 License
MIT License - See [LICENSE](LICENSE) for details
```


