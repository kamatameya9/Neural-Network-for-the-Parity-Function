# Neural-Network-for-the-Parity-Function


The parity function takes as input a vector of 2n bits and checks if the number of 0's (and 1's) in the input is even. It is more convenient to think of the input as a vector (x1, x2, …, x2n) where each xi ∈ {-1,+1}. The parity function then reports the product x1x2…x2n, which is +1 if the parity is even and -1 if it is odd.

Trained a DNN for the parity function on 64-bit inputs. Used randomly generated training sets of sizes 2000 and 5000 and tested the results on a suitable validation set.

Manually designed a good network for the parity function and compared its results with respect to the DNNs that were learned from training data.

