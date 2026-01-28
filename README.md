Each task's results are stored in separate folders. The Monk folder contains our code for running three tasks for neural networks (keras, scikit learn), KNN, SVM, and Random Forest. Monk 1, 2, and 3 are first processed with no L2 processing, which can be found in the files keras_monk_1, keras_monk_2, keras_monk_3, and sklearn-monk1-2-3. Then we apply L2 processing in the files sklearn-monk3-reg and keras_monk_3_reg.

For CUP, the cup folder contains our results and code files.

First, the understanding file shows the reasons why we applied 4-way PCA, along with explanations in the code. Then, SVR-KNN-XG-RF-FINAL is the complete gridsearch process for these algorithms. Finally, when approaching neural networks, we split Keras, PyTorch, and SciKitLearn into different files with a detailed gridsearch process. For SciKitLearn and PyTorch, each optimizer, Adam and SGD, had its own separate code file.
