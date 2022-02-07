# Zero-Hopf-Bifurcation
Software for computing the averaged functions of any order for polynomial differential systems

The main functions implemented in "Zero-Hopf-Averaging.mw" are
# StandardForm(P, k) 
Computes the standard form of averaging
- P=[\dot{x}_1,\dot{x}_2,\ldots,\dot{x}_n] 
- k is the averaging order
# BellSeqs(l, m) 
Determines a set of lists induced by the Bell polynomial
# LmultMap(m, n1, F, Y) 
Derives the explicit expansion of the m-multilinear map
- n1 is the number of variables in Z=[R,X_3,...,X_n]
- Y is a list of vectors
# LMNFBell(l, m, n1, F)
Computes the symbolic expression of an equation in (2.8), see the remark after Algorithm 4 in the paper
# OrderKFormula(k, n1)
Computes formula of the k-th order integral function y_k(\theta,Z)
# AveragedFunctions(SF, k)
Computes the k-th order averaged functions
# Support
The codes are supported by the National Natural Science Foundation of China (NSFC 12101032 and NSFC 12131004).
