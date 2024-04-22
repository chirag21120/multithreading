# Multi-Threading

The "Matrix Multiplication Performance Benchmark" initiative assesses how multi-threading influences the efficiency of matrix multiplication operations. By utilizing Python modules such as NumPy, threading, and Pandas, the project creates random matrices and assesses the time taken for multiplication with different thread counts (equal to the number of cores present in the system). The findings are scrutinized and presented visually to gain insights into enhancing the performance of computational tasks involving matrix calculations.

## Function explanation:

### generate_random_matrices(n, size):

Generates n random matrices of size `size x size.`
### multiply_matrices(matrices):

Multiplies a list of matrices together, starting with a constant matrix.
### perform_multiplication_with_threads(num_threads):

Performs matrix multiplication using multiple threads, dividing the task among them for parallel computation.

**Multiprocessing** library is used to fetch the number of cores present in the system
```
import multiprocessing
num_cores = multiprocessing.cpu_count()
```
The table corresponding to the time taken with respect to number of threads is as follows:

<img width="586" alt="Thread Time" src="https://github.com/chirag21120/multithreading/blob/master/No_of_threads_vs_time.png">

Graph:

<img width="586" alt="Graph Thread vs Time Taken" src="https://github.com/chirag21120/multithreading/blob/master/Time%20Taken%20vs%20Number%20of%20Threads.png">

Cores Utilization:

<img width="405" alt="Cores" src="https://github.com/chirag21120/multithreading/blob/master/Cpu%20Cores.png">
<img width="405" alt="Cores Graph" src="https://github.com/chirag21120/multithreading/blob/master/Cpu%20Cores%202.png">

## Submitted By:
### Chirag Mohan Gupta
### 102103554
### 3CO20
