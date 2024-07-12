# 14030423

**Automatic Hyperparameter tunning based on Hyperas**

Binary cat and dog picture classification projectct using Hyperas toolbox to tune hyperparameters automatically.

In this method, I used Hyperas[2] toolbox that is very helpful to specify the best amount of hyperparameters. I used this in my research[2] and could simply find the best hyperparameters.

The Hyperas toolbox was utilized for the implementation of a Bayesian hyperparameter optimization algorithm. That Hyperas is a very simple convenience wrapper around the Hyper­opt toolbox for fast tuning the models[3]. Among some pre-defined values for each hyperparameter, one is suggested by Hyperas as the best value for that hyperparameter.

It is crucial to note that HYPERAS identifies the optimal hyperparameters, enhancing the model's speed in response time to its maximum potential.

This is the procedures:
1. Download data base (Block 1)
2. Extract data to the directory (Block 2)
3. All of requirment imports (Block 3)
4. Load Validation and train data of Cat and Dog (Block 4)
5. Define the best and desired model (Block 5)
6. Installing HYPERAS (Block 6)
7. Require imports (Block 7)
8. Definition model for HYPERAS (Block 8)
9. Saving ipython (Block 9)
10. Running HYPERAS model (Block 10)



** The GPU and Python 3 are needed**
**Note 1**: At the first of each block, some explanation is brought to show the role of this.
**Note 2**: all of the model and data must be defined in the form of a function.
**Note 3**: the parameters of notebook_name and title must be varied to the name of the project.



**References**

[1] J. Bergstra, D. Yamins, D.D. Cox, Hyperopt: a python library for optimizing the hyperparameters of machine learning algorithms, Proceedings of the 12th Python in Science Conference 13 (2013) 20 (Citeseer).

[2] “Temporal-Spatial Convolutional Residual Network for Decoding Attempted Movement Related EEG Signals of Subjects with Spinal Cord Injury”, H. Mirzabagherian, M.B. Menhaj, A.A.
Suratgar, N. Talebi, M.A. Sardari, A. Sajedin, Computers in Biology and Medicine Journal, 164 (2023):
107159.

[2] https://github.com/maxpumperla/hyperas
