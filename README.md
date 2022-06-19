# Msc_cc_coding3_final-project
### NEW SPECIES OF POKEMON

The DCGAN implementation is from the DCGAN Tutorial by Nathan Inkawhich.

This model for DCGAN uses the Celeb-A Faces dataset. It will train a generative adversarial network (GANs) to generate new celebrities after being shown many photos of real celebrities.

In week 5 of the class, we were introduced to GAN, which I found very interesting and could generate a completely new database by identifying and analysing existing ones. GANs are a framework for teaching the model to capture the training data which can generate new data, to create new or fake images. DCGAN is an extension of the GAN, but the difference between GANs is it uses convolutional and convolution-transmission layers in the discriminator and generator simultaneously.

I changed the celebrity dataset to a pokemon dataset downloaded from Kaggle to create new Pokemon species. I tried changing the image size from 64 to 128, but this did little to improve the training images and just made the training process slower. I also changed the different datasets to try and make the output images look better, but the results all seemed to be the same, without much change. In the end, I found that the only thing I could do was to increase the epoch to improve the quality of the final output image.

![download (2)](https://user-images.githubusercontent.com/92035097/174490661-5ab0e256-d1dd-47ae-aa77-26a311c973dc.png)
![download (1)](https://user-images.githubusercontent.com/92035097/174490666-d1146985-14cb-4402-bb94-0a40501f0e9f.png)

In addition to Nathan Inkawhich's tutorial, I also referred to other codes.

Vedio processes: https://youtu.be/WaioGSQoH-o

referrence link: https://github.com/pytorch/tutorials/blob/master/beginner_source/dcgan_faces_tutorial.py https://github.com/soumith/ganhacks
