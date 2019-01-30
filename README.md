# DeepLearning_DigitRecognition
The list of dependencies we will be needing for our project are as follows:

   1. tensorflow (1.5.0)
   2. Keras (2.1.4)
   3. Flask (0.12.2)
   4. h5py ( 2.7.1)

You can install these all at the same time using the command:

pip3 install tensorflow keras Flask h5py

Step 1. Run DigitRecognition.py using command: python3 DigitRecognition.py
After this command, training of model will start and it will take some time. And after successful completion you should see “model.h5″ and “model.json”  in the working directory. 

Step 2. Create the basic structure of a flask web application which looks like this:
$ tree deploy_mnist_flask/
deploy_mnist_flask/
|-- static
|-- templates

Step 3. Make a file named index.html inside the templates directory.

Step 4. Create index.js and style.css inside the static directory.

Step 5. copy the “model.h5″ and “model.json” files inside the model folder in the working directory.

Step 6. Create a directory named model and create load.py inside it.

