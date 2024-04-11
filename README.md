# MULTITHREADING
## NAME: RAMJAS LANGDI
## GROUP: 3CS6
## ROLL NO.: 102117159

### METHODOLOGY:
1. **Matrix Multiplication Function:** multiply() function conducts matrix multiplication of matrices A and B using np.dot(). The answer is stored at a specific index of result array.

2. **Function for Multiplication using Threads:** Implement run_threads() to execute matrix multiplication using n (1-10) number of threads. Initialize a list threads to store thread objects. Iterate over the list of matrices, creating a new thread for each matrix multiplication operation using threading.Thread() constructor. Start each thread using the start() method. After creating all threads, wait for all threads to complete using the join() method. Return the time taken for the multiplication operations.

3. **Matrices Generation:** Generating a constant matrix A of size 1000x1000 using numpy.random.rand(). Creating a list of 100 random matrices of the same size.

4. **Execution Procedure:** Invoke run_threads() for each number of threads in the range from 1 to 10, recording the time taken for each operation. The results are stored in the results_table list along with the corresponding number of threads.

5. **Results Presentation:** Results are displayed in a tabular format using tabulate(). Number of threads are plotted against corresponding time taken using matplotlib.pyplot.plot().

### OBSERVATIONS: 
  The minimum time taken is for 6 threads.
![image](https://github.com/Ramjas-Langdi/Multithreading-assn/assets/99790640/6f066916-d96e-40ef-8bd0-1537a94ca454)

![Screenshot 2024-04-10 134538](https://github.com/Ramjas-Langdi/Multithreading-assn/assets/99790640/1415a891-6f88-4498-b079-c7e075ca54a7)
