# Neural Network Forward Pass

This repository contains a simple neural network implementation from scratch using NumPy. It demonstrates the forward propagation through 3 hidden layers and 1 output layer.

---

## 🧠 Architecture

- **Input Layer:** 3 features  
- **Hidden Layer 1:** 4 neurons with ReLU  
- **Hidden Layer 2:** 3 neurons with ReLU  
- **Hidden Layer 3:** 2 neurons with ReLU  
- **Output Layer:** 1 neuron with Sigmoid  

---

## 🔧 Technologies Used

- Python 3  
- NumPy  

---

## 🚀 How to Run

1. Clone the repository  
2. Open the notebook in [Google Colab](https://colab.research.google.com/) or Jupyter  
3. Run each cell sequentially  

---

## 📥 Input Example

```python
x1 = 101     # roll number
x2 = 5       # hours studied
x3 = 2       # practice tests

X = np.array([[x1], [x2], [x3]])
