# DeepBrucell
## DeepBrucell: Automatic detection of Brucellosis risk in cattle farms using multivariate techniques
Brucellosis is an infectious-contagious disease produced by the Brucella abortus bacterium, which causes abortion, infertility, decreased milk production, and mortality in cattle, sheep, goats, and pigs and can even affect humans. For this reason, in recent years, it has become a subject of study of high interest to the scientific community for the development of detection techniques and treatments for its control. This paper presents a new detection technique for Brucellosis risk diagnosis in cattle farms based on identifying the risk factors involved in this pathology. The study and identification of these risk factors allowed the creation of an instrument made up of 51 categorical variables that include: the location of the farm, generalities of the farm, reproduction system, reproductive pathologies, diagnosis, sanitary calendar, milking, workers, and food consumption risk. This instrument was applied to 632 cattle farms in the Carchi province, which allowed the creation of a database to implement and compare classifiers based on multivariate techniques contemplating regression mechanisms and neural networks. Furthermore, through a broad primary experimentation protocol, it was possible to identify the most influential variables and the appropriate topology for neural networks, where the Deep Learning sequential model with three hidden layers outperformed the evaluated methods. As a result, the best automatic classification model reached an accuracy of 98.437%, an MSE of 0.00604, and a Loss of 0.03923 and is openly available for free download, constituting a powerful and accessible alternative for Brucellosis diagnosis.

You can use the deep neural network provided by downloading the file threehidden_model.zip, and uncompressing the folder in the same directory where the provided RSicript is placed. You also must insert the data of a farm in the provided file data.csv, coding all the information as Dummy variables.
Finally, run the whole code.
We recommend to use the Anaconda Environment with the following package versions:
1. Python 3.10.9
2. Tensorflow 2.11.0
3. Numpy 1.24.1

You can use tensorflow GPU if desired, but we tested that the model works perfectly in tensorflow CPU.

Here we present the training process:
![alt text](https://github.com/erickherreraresearch/DeepBrucell/blob/main/images/training.JPG)

And the achieved performance metrics:
![alt text](https://github.com/erickherreraresearch/DeepBrucell/blob/main/images/performance.JPG)
