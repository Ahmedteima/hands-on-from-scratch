
---

##  Artificial Neural Network — From Scratch

This folder contains a simple implementation of an Artificial Neural Network (ANN) built **from scratch using NumPy** — without deep-learning frameworks.
The goal is to understand how forward propagation, backpropagation, and gradient-based learning really work under the hood.

---

###  Contents

* **ANN From Scratch.ipynb** — full notebook (training + explanations)
* **Forward Propagation For ANN.jpeg** — diagram explaining forward pass
* **BackPropagation_ANN.jpeg** — diagram explaining gradients
* **Sigmoid & derivative graphs** — visual intuition for the activation function

---

###  Model Architecture

* Input layer: features
* Hidden layer: sigmoid activation
* Output layer: sigmoid (binary classification)



---

###  Learning (Backpropagation)

Weights are updated using gradient descent:

[
W := W - \alpha \cdot \frac{\partial L}{\partial W}
]

where ( \alpha ) is the learning rate and ( L ) is binary cross-entropy loss.

---

###  What you will learn

forward propagation step-by-step
computing gradients manually
implementing backpropagation
training a network on small datasets
evaluating predictions with metrics

---

###  How to run

1. Open the notebook in Jupyter or VS Code
2. Run cells in order
3. Try changing:

* hidden layer size
* learning rate
* number of epochs

…and observe how the model behaves.

---

###  Next steps (planned)

* add multi-class version
* add ReLU activation
* compare with logistic regression
* visualization of loss curve over epochs

---

لو تحب، أعدّل النص بحيث يكون:
🔹 عربي بالكامل — أو
🔹 أقصر/أطول — أو
🔹 مخصص بالظبط لشرح كودك خطوة خطوة.

وقولّي كمان لو عايز README للريبو كله بشكل احترافي 👍
