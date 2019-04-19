
CS231n Convolutional Neural Networks for Visual Recognition - Assignment Solutions
===============

The course website: http://cs231n.stanford.edu/

Here are my solutions for this above course (Spring 2017).

Assignment list:

 * Assignment #1
 	* Q1: k-Nearest Neighbor classifier (20 points)
 	* Q2: Training a Support Vector Machine (25 points) 
 	* Q3: Implement a Softmax classifier (20 points) 
 	* Q4: Two-Layer Neural Network (25 points) 
 	* Q5: Higher Level Representations: Image Features (10 points)
    * Q6: Cool Bonus: Do something extra! (+10 points)
    
 * Assignment #2
 	* Q1: Fully-connected Neural Network (25 points)
 	* Q2: Batch Normalization (25 points)
 	* Q3: Dropout (10 points)
 	* Q4: ConvNet on CIFAR-10 (30 points)
    * Q5: PyTorch / TensorFlow on CIFAR-10 (10 points)
    * Q6: Do something extra! (up to +10 points)
    
 * Assignment #3
 	* Q1: Image Captioning with Vanilla RNNs (25 points)
 	* Q2: Image Captioning with LSTMs (30 points)
    * Q3: Network Visualization: Saliency maps, Class Visualization, and Fooling Images (15 points)
 	* Q4: Style Transfer (15 points)
 	* Q5: Generative Adversarial Networks (15 points)
	
	
	I wanted to use google collaboration Jupiter Notebook.
	The assignment uses scripts from a folder you need to download.
	To overcome it you need to zip the folder. 
	Upload it as a file to google collaboration Jupiter Notebook.
	Then unzip it (you need to hit refresh) before the code starts.
	
	```
	if not os.path.isdir("cs231n"):
	  import zipfile
	  zip_ref = zipfile.ZipFile('cs231n.zip', 'r')
	  zip_ref.extractall('.')
	  zip_ref.close()		
	else:
	  print('already unzipped')	
	```
	
	
	
	
	
	
	
	
	