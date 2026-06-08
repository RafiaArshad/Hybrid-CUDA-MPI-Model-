🚀 Hybrid Parallel Computing Framework (MPI + CUDA)
----

📌 Overview
This project implements a Hybrid Parallel Computing Framework combining MPI (distributed computing) and CUDA (GPU acceleration) to efficiently process large-scale image and matrix operations using a two-level parallel strategy.

----

🎯 Objectives

Combine MPI + CUDA for hybrid parallel execution
Improve performance of large-scale computations
Implement two-level data partitioning:
MPI → inter-node distribution
CUDA → intra-node GPU processing
Optimize image processing and matrix operations

----

🧠 Architecture
Input Data
   ↓
  MPI
   ↓
Nodes (Parallel Processes)
   ↓
CUDA GPU Computation
   ↓
MPI Result Gathering
   ↓
Final Output

----

🛠️ Tools & Technologies:

Google Colab (GPU)
CUDA C / CUDA Toolkit
OpenMPI
Python / C++
NumPy

----

📊 Implemented Features

🖼 Image Processing:
Brightness Adjustment
Contrast Enhancement

2D Convolution:
🔢 Matrix Operations
Matrix Multiplication (Hybrid MPI + CUDA)
Matrix Transpose (Parallel Execution)

----

⚙️ Methodology

MPI divides data across processes
CUDA performs GPU-based computation
Results are merged using MPI
Multiple partitioning strategies used for load balancing

----

📈 Performance

Speedup is calculated as:
Speedup = Time(Single CPU) / Time(Hybrid)

The hybrid model shows significant improvement in execution time and scalability compared to traditional CPU execution.

----

✅ Conclusion
The framework demonstrates that combining MPI + CUDA significantly enhances performance for compute-intensive image and matrix operations by leveraging both distributed and GPU parallelism.
