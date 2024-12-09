# NNQS_for_Klein-Gordon-Fock_equation
NNQS for the Klein--Gordon--Fock equation

In this article, we present a method for finding quantum stationary states of the Klein–Gordon–Fock (KGF) equation using neural networks (NNs). The method has been tested on two well-known systems: a relativistic spinless particle in a Coulomb potential, and a one-dimensional relativistic harmonic oscillator. The results of training the neural network for these two systems are presented, as well as the analysis of the training process. The neural network method shows a good agreement with analytical calculations (if they can be found explicitly), providing a promising approach for solving more complex problems in quantum physics and quantum chemistry.

See https://en.num-meth.ru/index.php/journal/article/view/1379/1301

A. M. Kalitenko and P. I. Pronin, “On the possibility of using the NNQS for the Klein–Gordon–Fock equation,” Numerical Methods and Programming 25, no. 4 (2024): 464–475, https://doi.org/10.26089/NumMet.v25r435


## Equation 
$$[E-V]^2 \psi(x) = \left[ -\hbar^2 c^2 \frac{d^2}{dx^2}+ m^2c^4 \right]\psi(x)$$

## Example
<img src="./1.png"  width="700" 
     height=auto>

The neural network architecture used in our study and the optimization
process are illustrated in the feedback loop.

<img src="./NN.png"  width="500" 
     height=auto>
