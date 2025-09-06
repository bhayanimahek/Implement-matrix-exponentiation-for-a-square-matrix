# 📊 Matrix Exponentiation Project

This project demonstrates **Matrix Exponentiation** using three different approaches — with a detailed analysis of their **time complexities** and **performance**.

---

## 📂 Project Structure
```bash
├── exponentiation-square-matrix-using-numpy.ipynb # Jupyter Notebook containing full code
├── Matrix_Exponentiation_Report.docx # Detailed report (implementation + analysis)
└── README.md


---

## 📝 Overview

Matrix Exponentiation is a powerful mathematical technique used to compute **Aᵏ** (where `A` is a square matrix and `k` is an integer power).  
It is widely used in:

- **Computer Graphics**
- **Dynamic Programming**
- **Markov Chains**
- **Graph Theory (Path Counting)**

This project explores **three approaches**:

| Function             | Algorithm Used             | Time Complexity      | Best Use Case                     |
|---------------------|------------------------|-------------------|----------------------------------|
| `mat_pow_builtin()` | NumPy’s Optimized `matrix_power` | **O(n³ log k)** | Best for production, large k |
| `mat_pow_naive()`   | Repeated Multiplication | **O(n³ k)**       | Good for learning, very small k |
| `mat_pow_fast()`    | Binary Exponentiation  | **O(n³ log k)**  | Best for understanding + custom logic |

---

## 💻 Code Implementation

You can open and run the **Jupyter Notebook** `Implement-matrix-exponentiation-for-a-square-matrix.ipynb` to explore:
- Validation of square matrices
- Naive implementation with repeated multiplication
- Fast implementation using **binary exponentiation**
- Example execution on test matrices
- Runtime comparison between all three methods

---

## 📑 Report

The `Matrix_Exponentiation_Report.docx` includes:

- **Introduction** (Concept & Applications)
- **Step-by-Step Implementations**
- **Example Outputs**
- **Time Complexity Analysis**
- **Comparison Table**
- **Conclusion & Recommendations**

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/bhayanimahek/Implement-matrix-exponentiation-for-a-square-matrix.git
   cd Task_01
2. Open Jupyter Notebook:
   ```bash
   jupyter notebook exponentiation-square-matrix-using-numpy.ipynb
3. Run all cells and view results.

   ## 📌 Author

**👤 Mahek Bhayani**  
🎓 *GTU Student | Data Science Enthusiast*  
📧 *Email: [bhayanimahhek@gmail.com]* 
