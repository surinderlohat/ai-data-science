# Linear Algebra Basics: Scalars, Vectors, and Matrices

Understanding the **why** and **when** behind these concepts is essential for AI and deep learning.

---

## 🔹 1. Scalars

- **What**: A single number (just a magnitude).  
  **Example**: `5`, `-3.2`, or `π`

- **Why**: Scalars represent quantities like temperature, weight, or a model's learning rate.

- **When**: Use scalars when you only need **one** value.  
  Examples:
  - Setting a threshold
  - Scaling input features
  - Adjusting a model’s weights

---

## 🔹 2. Vectors

- **What**: An **ordered list** of numbers — essentially a 1D array.  
  **Example**:
  v = [2, 4, -1]


- **Why**: Vectors represent quantities with **direction and magnitude**, or features of a data point.

- **When**:
- Each **data point** in ML is usually a vector (e.g., `[height, weight, age]`)
- Word embeddings in NLP (e.g., `"king"` = `[0.2, -1.1, 3.0, ...]`)
- Gradients in optimization are vectors

---

## 🔹 3. Matrices

- **What**: A **2D array** of numbers — like a table.  
**Example**:  
A = [
[1, 2, 3],
[4, 5, 6]
]

- **Why**: Matrices represent **collections of vectors** or **linear transformations**.

- **When**:
- A dataset where each **row is a data point** and each **column is a feature**
- Neural network weights are matrices
- Used for transforming, rotating, or projecting data

---

## 🔍 Real-Life Example: AI / Deep Learning

Imagine you're building a model to predict **house prices**:

- Each house = a **vector** → `[size, bedrooms, age]`
- All houses = a **matrix** → each row = one house
- Model parameters = **vector or matrix** (weights)
- Learning = optimizing these **scalars and vectors** using gradients

---

Would you like to continue with **vector operations** like dot product and norm?
  
