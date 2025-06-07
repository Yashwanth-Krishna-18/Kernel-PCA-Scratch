# Kernel-PCA-Scratch
Implemented Kernel PCA scratch Code
# Kernel PCA from Scratch (NumPy Implementation)

This repository contains a complete implementation of **Kernel Principal Component Analysis (Kernel PCA)** using only NumPy, built step-by-step as part of my learning process.

---

## 📌 What is Kernel PCA?

Kernel PCA is an extension of Principal Component Analysis (PCA) that allows for **non-linear dimensionality reduction** by mapping data to a higher-dimensional space using **kernel functions**.

It's especially useful when the original dataset is **not linearly separable**, and helps in revealing complex structures in the data.

---

## 💻 What's Implemented?

- Polynomial kernel function
- Kernel matrix computation
- Centering the kernel matrix
- Ensuring symmetry for numerical stability
- Eigenvalue decomposition using `np.linalg.eig`
- Sorting eigenvalues and eigenvectors
- Filtering negative/small eigenvalues
- Projection to lower dimensions using top eigenvectors

---

## ⚙️ Technologies

- Python
- NumPy
- Jupyter Notebook / Google Colab

---

## 📈 Example

This implementation can be tested on any 2D dataset (e.g., toy datasets like `make_moons`, or custom matrices) and visualized after projection.

---

## 🧠 Learning Source

This is part of my ML learning journey — I built this code by listening to lectures, understanding the math behind Kernel PCA, and implementing each step manually. The derivation of the kernel trick and eigen decomposition was studied carefully to ensure full understanding.

---

## ✅ Status

✔️ Working and tested  
✔️ Numerically stable with eigenvalue filtering  
✔️ Ready to be extended with other kernels (like RBF)

---

## 🚀 Future Plans

- Add RBF (Gaussian) kernel support  
- Add 2D visualization using Matplotlib  
- Try on real datasets like Iris or Digits  

---

## 📚 Author

Yashwanth Krishna — B.Tech CSE + IIT Madras Data Science Diploma  
