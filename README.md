# CIFAR 10 image classification project
This is a Deep learning project that allows to focus on building a convolutionnal neural networks that will be used to classify images.
It is based on Udacity deep learning nanodegree.

## Installing the environment

### Floyd compatibility
This project is better run on GPU hardware on the cloud. Floyd is the easiest platform to launch it.
You have the necessary files included in the repo.

Create a Floyd project in your Floyd dashboard, then initiate a Floyd project inside this repo:

        floyd init <your_floyd_project_name>

Then Run the project:

        floyd run --data mat_udacity/datasets/udacity-cifar-10/1:cifar --mode jupyter --gpu --env tensorflow-1.2

    It will be run on a machine with GPU (`--gpu`), using a Tenserflow environment (`--env tensorflow-1.2`), as a Jupyter notebook (`--mode jupyter`), with the cifar-10 dataset available (`--data mat_udacity/datasets/udacity-cifar-10/1:cifar`).
    
Wait for the Jupyter notebook to become available and then access the URL displayed in the terminal (described as "path to jupyter notebook"). You will see the notebook.

