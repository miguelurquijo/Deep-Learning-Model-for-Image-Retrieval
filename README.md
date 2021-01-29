# Deep-Learning-Model-for-Image-Retrieval
<p>Deep Learning Model for image clasification using deep features.</P>

<p>The objective of this scrip is to train a model with any set of images, using deep features obtained with the Transfer Learning technique from ImageNet Model, to retrieve iamges.</P>

</P>Following I display the first rows of the trianing data for better understanding the data set:</P>

<a href="https://ibb.co/sQb4WsZ"><img src="https://i.ibb.co/1K7NzRk/Screenshot-2021-01-29-120830.png" alt="Screenshot-2021-01-29-120830" border="0"></a>

<p>Here is an explanation of how I build the model:</P>
<ui>
  <li>First, we have to prepare the enviroment. I like to install and imprort all libraries at the top of my notebooks</li>
  <li>Import the data set on whiich we want to train the model. I store my in google dirve so I authenticate to get access the folders in Drive</li>
  <li>Get the depp features of each image. Here is where half of the "magic" happens. I used a technique called Transfer Learning to extract deep features of my images with a moduled build by ImageNet with over 14 million images. This is what will make our model accuarcy hight since we can extract multiple layers of patterns within each picture and then categorize them accordingly with the label of each image</li>
