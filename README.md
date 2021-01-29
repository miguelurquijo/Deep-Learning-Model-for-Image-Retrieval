# Deep-Learning-Model-for-Image-Retrieval
<p>Deep Learning Model for image clasification using deep features.</P>

<p>The objective of this scrip is to train a model with any set of images, using deep features obtained with the Transfer Learning technique from ImageNet Model, to retrieve iamges.</P>

</P>Following I display the first rows of the trianing data for better understanding the data set:</P>

<a href="https://ibb.co/sQb4WsZ"><img src="https://i.ibb.co/1K7NzRk/Screenshot-2021-01-29-120830.png" alt="Screenshot-2021-01-29-120830" border="0"></a>

<p>Here is an explanation of how I build the model:</P>
<ui>
  <li>First, we have to prepare the enviroment. I like to install and imprort all libraries at the top of my notebooks</li>
  <li>Import the data set on which we want to train the model. I store my in google dirve so I authenticate to get access the folders in Drive</li>
  <li>Get the depp features of each image. Here is where half of the "magic" happens. I used a technique called Transfer Learning to extract deep features of my images with a model build by ImageNet with over 14 million images. This is what will make our model accuarcy high since we can extract multiple layers of patterns within each image and then categorize them accordingly with the label of each image. I used a data set of 2,000 images (not much) of dogs, birds, cats and cars but you can use any type of iamges with the labels you want to use</li>
  <li>Once you have the depp features of each iamge, you can create your model. I used a logistic classifier using the deep features I just obtained in the previus stp</li>
</ui>
  
 <p>Thats it!! in that 4 short steps, you have your Image Retrievel Model ready, you can get creative to give it the value your project needs. I usually combine it with a k-nearest neighbors algorithm to retrieve similar object to a given iamge and use it as a recomeder system for a marketplace (like giving it pictures of shows you like and retrieve similar shows</p>
 
 <p>Hope you like it and adds some value to you :)</p>
