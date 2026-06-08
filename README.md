# 🚀 Hybrid Parallel Computing Framework (MPI + CUDA)

## 📌 Overview

This project implements a **Hybrid Parallel Computing Framework** that combines **MPI (Message Passing Interface)** for distributed computing and **CUDA** for GPU acceleration. The framework efficiently performs image processing and matrix operations using a two-level parallelization strategy to improve performance and scalability.

---

## 🎯 Objectives

* Combine MPI and CUDA for hybrid parallel execution.
* Improve the performance of large-scale computations.
* Implement two-level data partitioning:

  * **MPI:** Inter-node data distribution.
  * **CUDA:** Intra-node GPU computation.
* Optimize image processing and matrix operations.

---

## 🧠 Architecture

```text
Input Data
    ↓
MPI Distribution
    ↓
Parallel Processes
    ↓
CUDA GPU Computation
    ↓
MPI Result Gathering
    ↓
Final Output
```

---

## 🛠️ Tools & Technologies

* Google Colab (GPU-enabled environment)
* CUDA C / CUDA Toolkit
* OpenMPI
* Python / C++
* NumPy

---

## 📊 Implemented Features

### 🖼️ Image Processing

* Brightness Adjustment
* Contrast Enhancement
* 2D Convolution (Edge Detection)

### 🔢 Matrix Operations

* Matrix Multiplication (Hybrid MPI + CUDA)
* Matrix Transpose (Parallel Execution)

---

## ⚙️ Methodology

* MPI divides data among multiple processes.
* CUDA performs GPU-accelerated computation.
* Results are aggregated using MPI communication.
* Different partitioning strategies are used for workload balancing.

---

## 📈 Performance Evaluation

Performance is measured by comparing the hybrid model with a traditional single-CPU implementation.

**Speedup Formula:**

```text
Speedup = Time(Single CPU) / Time(Hybrid)
```

The hybrid framework demonstrates significant improvements in execution time and scalability compared to single-CPU execution.

---

## ✅ Conclusion

The Hybrid MPI + CUDA framework effectively combines distributed computing and GPU acceleration to enhance the performance of computationally intensive image processing and matrix operations.

