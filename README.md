# SigProd V1.0

Signature Product Code for Protein-Protein Interaction Prediction.  The SigProd V1.0 software consists of four programs which together allow the prediction of protein-protein interactions using only amino acid sequences and experimental data.  The first program is called kernel_mat and performs a pair-wise comparison between all proteins in a given set based on amino acid sequence.  The second and third programs are called svm_learn and svm_classify.  These programs use the comparisons made by kernel_mat to train and test a Support Vector Machine classifier.  The last program is called make_preds and allows the user to extrapolate from known protein-protein interactions in a certain organism to unknown interactions in another organism.

Dependency: https://www.cs.cornell.edu/people/tj/svm_light/

SCR# 764


