# Data-Classification-using-ML

The data set included 8 features, used for predicting the cellular localization sites of proteins.
The extracted yeast dataset includes 3 classes only. The class is the localization site. Classes 1, 2
and 3 denote CYT (cytosolic or cytoskeletal), NUC (nuclear), MIT (mitochondrial), respectively.

To classify the data we used Support Vector Machines (SVMs). 
The type of SVM i used was the C-SVC (Cost-Support Vector Classifier) and the kernel function was the Gaussian radial basis function (RBF).

When using the C-SVC SVM with the Gaussian radial basis kernel there are two tunable parameters, C (cost) and γ (gamma). 
I was given the following combinations to use: [C=10, γ=0.1], [C=50, γ=0.1], [C=100, γ=0.1], and [C=10, γ=0.01].

I then had to train an SVM model for each combination from the given 4 combinations and test it on the normalised validation set. 
The accuracy rate for each combination on the validation set was reported. 
And finally, I selected the best combination of parameters applied and tested again and reported the result.
