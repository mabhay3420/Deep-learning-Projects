# Content
1. Gradient_descent_PyTorch
	- Gradient Descent Notebook 
		- Use linear regression and gradient descent algorithm on a small dataset. Implemented using python and some packages ( numpy,pandas and pyplot for visualization)
	- Student_Admission Notebook
		- Two layer neural network using python
	- PyTorch_part_1,2,3
		- Using PyTorch with numpy for matrix operations.
		- Linear regression using PyTorch
		- Single layer Neural network using PyTorch
		- Part 2 and 3 show impressive capability of even shallower networks to learn quickly as well as how they outperform simple regression models on Image data.
2. CNN_LeNet_Implementation
	- Convolution basics
		- Use PyTorch to do convolution operation on random 2d Images
		- Visualize Effect of padding and convolution operations
	- MNIST classification model
		- Classical digit recognition model using PyTorch
	- LeNet
		- Implement "LeNet" architecture and use it for digit recognition
		- Visualize training process and intermediate outputs.

3. Autoencoders NLP Basics (seq2seq)
	- Simple Autoencoder
		- Flatten image into 1-D vectors and then train the network to map them to themselves
		- Uses TensorFlow
	- Convolution Autoencoder
		- Use Encoder to obtain a hidden representation
		- Use Decoder to obtain output image from this representation.
		- Train the network to map to itself.Uses TensorFlow. ( Output of training part removed because they were too long.)
	- Skip Gram word2vec
		- Find more efficient representation ( Simple One Hot encoding involves a lot of zeroes and no information about contet.)
		- Uses Skip Gram Architecture. Find word embedding which places similar words near each other in vector space.
		- Uses TensorFlow
	- Seq2Seq
		- A model which maps a sequence of characters to another sequence
		- Model Architechture

				1. Encoder
    					- Embedding
    					- Encoder cell
				2. Decoder
    					a. Process decoder inputs
    					b. Set up the decoder
        					- Embedding
        					- Decoder cell
        					- Dense output layer
        					- Training decoder
        					- Inference decoder
				3. Seq2seq model connecting the 	encoder and decoder
				4. Build the training graph hooking up the model with the optimizer

		- Implemented Using TensorFlow . Character level Model.
4. Theory Reports
	- Assignment 1,2
		- Contains submissions for theoretical assignment.
