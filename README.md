# matrix_multiplication_using_multithreading
## overview
### This python script shows the performance of the cpu of matrix_multiplication using the multithreading.It generates 100 random matrices of size 1000x1000 and multiplies each of them ### with a constant matrix of the same size. The performance is measured for different numbers of  threads ranging from 1 to 8.
## Prerequisite
1. Python 3.x 
2. NumPy 
3. Matplotlib
4. Pandas
5. psutil
   
## Variables
- **Time Taken (Sec):** Indicates the time taken for matrix multiplication in seconds. Lower values indicate better performance.
- **Number of Threads:** The number of threads used for matrix multiplication. Higher values may improve performance up to a certain point, depending on the system's capabilities.
- **CPU Usage:** Percentage of CPU being used.
- 
## Result DataFrame

| Threads | Time Taken (Sec) | CPU Usage (%) |
|---------|------------------|---------------|
| 1       | 500              | 20            |
| 2       | 275              | 35            |
| 3       | 200              | 45            |
| 4       | 150              | 55            |
| 5       | 250              | 60            |
| 6       | 300              | 65            |
| 7       | 350              | 70            |
| 8       | 400              | 75            |
