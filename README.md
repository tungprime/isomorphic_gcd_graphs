# Isomorphic gcd-graphs over polynomial rings

This Git repository contains the code we wrote in order to generate data and conduct experiments with gcd-graphs over the polynomial rings, as discussed in our paper:

**[1]** Ján Mináč, Tung T. Nguyen, Nguyen Duy Tan  *Isomorphic gcd graphs over the polynomial rings* (preprint, 2024).

Part of the code originates from the former project 

https://github.com/tungprime/gcd_graphs

This new repository, however, contains more specialized functions that we need to generate data and verify our conjectures. These include but are not limited to the following 

(1) A function to calculate the characteristic polynomial. 

(2) A function to calculate the Ramanujan sums using formula 2.1 in the cited paper. 

(3) A function to create the powerset of Div(f). This function is used to classify the isomorphic/isospectral classes of gcd-graphs where $f$ is fixed but $D$ varies. 


## Description

Our code uses the SageMath 9.4 kernel and the Python library NetworkX. 

## License

This project is licensed under the MIT License. 
