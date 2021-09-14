# Hyperparameter-Optimization-Using-PSO

Deep learning in the medical field has proven to be of tremendous importance due to its robutstness and efficiency. Early detection of malaria can be aided by using deep learning techniques. But this poses a problem. Due to large amount of data, CNN models take up a lot of time and computational resources. 

This code uses Particle Swarm Optimization to optimize CNN network hyperparameters in order to enhance performance and eliminate the requirement of searching manually for the best fit model for the classification of malarial cell images.

Particle Swarm Optimizer recommends using the personal best (pbest) and global best (gbest) and hence is less likely to become stuck in local minima. So, it does not suffer from premature convergence.

About the data: The images are in colored format and are divided into 2 classes namely: Parasitized and Uninfected.
This data is then divided into train and test data.
Total images : 27,558
Images for training : 22,046
Images for test  : 5,512

System flowhart:

![Capture](https://user-images.githubusercontent.com/67593609/133240381-a78e2a84-16e1-450c-bd8e-56b680b6a940.PNG)
