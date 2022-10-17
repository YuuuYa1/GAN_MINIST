# GAN(DCGAN)_MINIST
This project is used to generate the handwritten number images based on Deep Convolutional Generated Adversarial Network(DCGAN) and MINIST database.

This project is written by Python - Tensorflow.

## Mini Introduction of Generative Adversarial Networks(GAN)
GAN is a generative model which creates the new data instance by training existing database. In addition, GAN is an unsupervised 
learning which means that human gives the sample data to the machine without labels. The generator and the discriminator are two 
neural networks that compose the GAN. The generator is used to generate some data instances from its own ‘knowledge’, whereas the 
discriminator is operated to estimate data instances and calculate the probability of both data instances, the fake one and the 
real one. 

<img width="449" alt="image" src="https://user-images.githubusercontent.com/97501259/196076078-bd413192-6d91-43b3-96aa-533af0b17419.png">

## Mini Introduction of Deep Convolutional Generative Adversarial Networks(DCGAN)
There is a generative adversarial network architecture called Deep Convolutional Generative Adversarial Networks (DCGAN). 
This network is developed by GAN and Convolutional Neural Networks (CNN). Involve CNN in the generator and the discriminator. 
DCGAN uses the convolutional layer in the discriminator and the transpose-convolutional layer in the generator. 

<img width="452" alt="image" src="https://user-images.githubusercontent.com/97501259/196076810-537d342c-327a-44bd-ad0d-67292a38454f.png">

# Results

Epoch_0                    |  Epoch_10                 |  Epoch_20
:-------------------------:|:-------------------------:|:-------------------------:
![EPOCH_0](https://user-images.githubusercontent.com/97501259/196077294-26f2ba6e-19ce-4eea-99ee-508a3c0cc193.JPG)  |  ![EPOCH_10](https://user-images.githubusercontent.com/97501259/196077316-cc9d258e-21cd-4af6-bdda-9d88f5c9dabf.JPG) | ![EPOCH_20](https://user-images.githubusercontent.com/97501259/196078076-631456f3-eb66-4f34-a56d-30c3f10e3d64.JPG)

![EPOCH_50](https://user-images.githubusercontent.com/97501259/196078255-59e2c247-cbee-4ea5-a97a-0348286c7af7.JPG)

Epoch_30                   |  Epoch_40                 |  Epoch_50
:-------------------------:|:-------------------------:|:-------------------------:
![EPOCH_30](https://user-images.githubusercontent.com/97501259/196078175-da174fe3-8cd2-43be-91df-fc3286d16d3b.JPG)  |  ![EPOCH_40](https://user-images.githubusercontent.com/97501259/196078202-68048cb3-c00e-4b7d-be88-fe1748d983ef.JPG) | ![EPOCH_50](https://user-images.githubusercontent.com/97501259/196078255-59e2c247-cbee-4ea5-a97a-0348286c7af7.JPG)
