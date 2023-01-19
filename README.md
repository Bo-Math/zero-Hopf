# Zero-Hopf Bifurcations of Differential Systems
Software for computing the averaged functions of any order for polynomial differential systems

The main functions implemented in "Zero-Hopf-Averaging.mw" are:
# StandardForm(S, k) 
Computes the standard form of averaging
- S=[\dot{x}_1,\dot{x}_2,\ldots,\dot{x}_n] is a differential system of the form (2.2)
- k is the averaging order
# OrderKFormula(k, n)
Computes formula of the k-th order integral function y_k(\theta,Z)
# AveragedFunctions(SF, k)
Computes the k-th order averaged functions (The main process of the program)
- SF is the standard form of averaging obtained by StandardForm(S, k)
# Support
The codes are supported by the National Natural Science Foundation of China (NSFC 12101032 and NSFC 12131004).
