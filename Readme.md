# Using Siamese Networks to recommend similar clothing articles
The objectives of this project are to do a deep-dive into siamese networks and implementing and end-end solution

<u> Model output </u>

![Alt text](./static/img/Modeloutput.jpg?raw=true "Title")

This repo contains 3 different Siamese Networks for the MNIST, fashion_mnist, and tops data set.
The tops data is our clothing database. The 3 models can be found in their respective folder. 

MNIST and Tops use Triplet Loss:

![Alt text](./static/img/tripletloss.png?raw=true "Title")

While Fashion MNIST uses Contrastive Loss:

![Alt text](./static/img/contrastive loss.png?raw=true "Title")

## Requirements
All notebooks were run on Google Colab, and using the GPU runtime is highly recommended:
- [Colab](https://colab.research.google.com/notebooks/intro.ipynb?utm_source=scs-index)
- [Clothing Data](https://console.cloud.google.com/storage/browser/fynd-open-source/research/MILDNet)

## Setup
Import the ipynb in your respective environment and run, each notebook contains explicit details regarding the models used:

## Code
- `Siamese_Network_Contrastive_Loss_Fashion_MNIST`: This notebook shows Contrastive Loss on the Fashion MNIST dataset
- `Siamese_Network_Triplets_MNIST`:  This notebook shows Triplet Loss on the MNIST dataset
- `Siamese_Network_Final`:  This notebook recommends similar clothing items 
- `Dockerfile`: Anaconda base, the docker image was going to be deployed on GCP to run the predictions from the similar clothing (WIP)
- `get_data.py`: You can use this script to download the stock history for S&P500
- `app.py`: This file contains the main for the Flask server. (See Docker)

## References
See reference folder for different references that were used in the notebook and repo creation





 
