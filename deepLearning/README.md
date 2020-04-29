# Deep Learning - Convolutional Neural Networks

This sub-library details some of my explorations into deep neural networks. In particular into convolutional neural networks built in Pytorch
I have also utilised the wrapper Pytorch Lightning as a tool to simplify my code when teaching DL to beginners https://github.com/PyTorchLightning/pytorch-lightning
The projects are Jupyter notebook files run in Google Colab to take advantage of their remote GPU for quicker training.

## Deep Learning tutorial

A project designed at introducing deep neural networks and related concepts to Shell Machine Learning practioners who have never done any Deep Learning

Powerpoint is available in this repository. The following projects were all designed with these in mind. The simpler MNIST example was used initially with the others developed as personal projects.

## Mini projects

1. MNIST number classification using Pytorch Lightning

    Using Yan Lecun's famous handwritten numbers dataset. Performance is relatively low due to the fact we don't use any convolutional        layers.
    Google Colab link: https://colab.research.google.com/drive/190zAQjjNuSzOByeSJOXZt5G_hFJ_ibba

2. Cat and Dog Image Classification using Pytorch Lightning

    **Installation instructions**:
    ```
        1- Download attached files
        2- Install Anaconda if needed: https://docs.anaconda.com/anaconda/install/windows/
        3- From Anaconda Prompt, navigate to folder with these files and execute
        conda create -n deeplearningtut python=3.6
        conda activate deeplearningtut
        conda install pytorch
        conda install torchvision -c pytorch
        conda install pillow=6.1
        pip install -r requirements.txt
        python -m ipykernel install --user --name=deeplearningtut     
    ```


3. VGG16 Cat and Dog Image Classification using pure Pytorch

    Much more complex model. Based around the Oxford VGG project https://www.robots.ox.ac.uk/~vgg/research/very_deep/  
    Google Colab link: https://colab.research.google.com/drive/1WbixZzZYiRPASMVlqbV3br8_axVipHpG

