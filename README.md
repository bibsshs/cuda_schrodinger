# cuda_schrodinger

Both programs focus on solving the two dimensional Schrödinger equation for a parabolic potential through the finite difference method. 
The CUDA program efficiency might be limited, once this method splits real and imaginary parts of the equation, so the communication between CPU and GPU is increased.
