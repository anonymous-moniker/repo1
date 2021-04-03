# repo1
## Content
This repository consists of the notebooks and results used in our experiment.
- The `Notebook` directory contains the ipython notebooks used in our experiments.
- The `dataset` directory has the dataset used for 3, 4, 5 class classification. For 10 class classification we directly download the dataset in the notebook from `keras.datasets`. It also contains the latent space acquired from the Variational Autoencoder.
- The `result` directory has the `.npy` files for all our experiments.
- The `analysis` directory has the images in `.pdf` format for the accuracy comparisons among all the sampling techniques.
- The `model` directory has the saved weights for the Neural Netowrk used in the Variational autoencoder.


## Running the notebooks
- The notebooks named `* class classification Unscented Transform.ipynb` contain the calculation of ***Sigma point sampling*** and active learning accuracies
- The notebooks named `* class classification-accuracies.ipynb` contain the calculation of ***Uniform sampling*** and ***Random coreset sampling***. They also have the code for active learning accuracies.
- The notebook named `*Corestting MNIST.ipynb` contain the code for ***Sensitivity sampling***. The only thing that needs to be chnaged in this notebook is in cell number 3. Change `MNIST_train_latent_space_z7.npy` to `MNIST4_train_latent_space_z5.npy` etc. for other classification tasks.
