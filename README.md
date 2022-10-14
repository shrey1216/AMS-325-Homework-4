# AMS-325-Homework-4
#This repository contains two tasks. 

#Task 1: Mandelbrot Sets
The first task is relating to Mandelbrot sets. The function mandelbrot takes in the arguments n, N_max, and threshold, 
and computes the Mandelbrot fractal with a Mandelbrot iteration on each point. 
The output is a figure which also saves to a png file. It is titled mandelbrot.png.
The figure displays a similar looking graphic to that given in the task. 
At the bottom of the file, there is a call to the function which allows the reader to
change the input parameters to output a different figure. 




#Task 2: Markov Chains
The second task is relating to Markov Chains. 
A transition matrix P is generated out of random numbers, as well as probability distribution
p which is shown as a vector. 
The sum of each row in transition matrix is equal to 1, as well as the sum of the elements in the matrix. 
Using a loop, P.T * p is calculated N times until the p stops changing. 
Separate from this process, np.linalg.eig is used to compute the eigenvector of P.T corresponding to the
largest eigenvalue. This eigenvector, when scaled to a sum of 1, should equal the p found earlier. 
To show the convergence of p on the eigenvector, the norm difference is graphed using a loop.
This graph is shown using many different n and N values, and all of them are outputted when the code is run.
