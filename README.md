# Task 1: Deep Neural Networks and Hyperparameter Optimization

## Objective
To design, implement, and evaluate multi-layer feed-forward neural networks from scratch using NumPy, focusing on forward/backward propagation mechanics, various activation functions, and optimizer convergence behaviors.

---

## 🛠️ Project Structure
- `task1_deep_neural_network.ipynb`: Executable Jupyter Notebook containing full NumPy implementation, execution logs, and hyperparameter plots.
- `main.py`: Modular Python implementation containing `ModularNeuralNetwork`, activation classes, and custom optimizers.
- `Task1_DNN_Hyperparameter_Report.pdf`: PDF report generated for submission to the L&T Edutech LMS Platform.

---

## 🚀 Key Features Implemented
1. **Propagation Engine:** Vectorized forward propagation and manual cross-entropy backpropagation from scratch.
2. **Activation Functions:** ReLU, Sigmoid, and Softmax with exact derivatives.
3. **Weight Initialization:** He Normal initialization for ReLU layers and Xavier for Sigmoid layers.
4. **Optimizers Built:**
   - Stochastic Gradient Descent (**SGD**)
   - Momentum Optimizer ($\beta = 0.9$)
   - **RMSProp** ($\beta = 0.99, \epsilon = 10^{-8}$)
   - **Adam** ($\beta_1 = 0.9, \beta_2 = 0.999, \epsilon = 10^{-8}$)

---

## 📊 Performance Comparison

| Optimizer | Initial Train Loss | Final Train Loss | Final Train Acc (%) | Final Val Acc (%) |
| :--- | :--- | :--- | :--- | :--- |
| **SGD** | 2.112 | 0.108 | 98.43% | 10.75% |
| **Momentum** | 2.631 | 1.648 | 51.12% | 10.75% |
| **RMSProp** | 1.314 | **0.009** | **100.00%** | **11.50%** |
| **Adam** | 1.916 | 0.021 | 99.81% | 8.50% |

---

## 📈 Convergence Visualizations

![Training Loss and Validation Accuracy vs Optimizer](assets/loss_curves.png)

---

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/nishthadighe-bit/Deep-Neural-Networks-and-Hyperparameter-Optimization.git](https://github.com/nishthadighe-bit/Deep-Neural-Networks-and-Hyperparameter-Optimization.git)
