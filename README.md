# Style-Transfer-using-C.N.N.

I built the project using Pytorch and I used vgg19 network architecture and their research paper on style transfer. 

For extracting the style features, I am using the first layer of each of the 5 batches of convolutional layers 
(conv1_1, conv2_1, conv3_1, conv4_1, conv5_1). 

For extracting the content features, 
I am using the second layer of the fourth batch (conv4_2).  

The program accepts both HTTP links and locally stored images
