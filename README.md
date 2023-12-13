# CUDA_Matrix_Number_Appearance_Counter
A code for counting the appearence of numbers in a massive matrix using CUDA Programming on GPU

#Program Abstract
A matrix with dimensions of 8192 × 8192 of integer numbers is available, and the values in it are within a specific numerical range. For example, all the numbers in the matrix are integers in the range of [1023, 0[. We intend to count the number of occurrences of each number in the desired matrix. As a result of the counting operation, a 1024-element array will be obtained, and the number of occurrences of each number in the matrix will be placed in each element of the array. To obtain the frequency of values ​​in this matrix using the GPU and with CUDA, write the code with the following two different scenarios:"
	1. Write the program in a way that each thread performs the counting 	operation for one of the values (one of the 1024 elements).
	2. Write the program in a way that the matrix is divided into blocks 	between threads (blocks of size 16 × 16), and each thread performs the 	counting operation for all values of the number of repetitions in the 	range (0 and 1023), but only in its own block. Note that the final 	result must be created by one thread. In this case, all calculations 	must be performed on the GPU.

i. In each of the two cases above, if there is a possibility of optimizing the program in terms of the number of accesses to the main memory of the GPU, apply it and explain the optimization you have done.

ii. Calculate and report the kernel execution time and the data transfer time between the CPU and GPU in different scenarios.

#Attention!!!this code is generated with respect to commands and functions mentioned and introduced in the Lecture PDF files.
certainly there is much more efficient and optimized ways to solve the problem but this code is limited with functions mentioned in PDF files





