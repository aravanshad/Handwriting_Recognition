
The first thing we need to run this assigment is TensorFlow installation. 
I have summarized how to install, check, and load tensorflow on your mac. 
Here are the step-by-step process:

1. Download and install Anaconda or Miniconda

2. From the TensorFlow installation instructions:

  ```$ conda create -n tensorflow python=2.7 ```
  
  ```$ source activate tensorflow ```
  
  ```$ conda install -c conda-forge tensorflow ```
  
  ```$ conda install notebook ipykernel ```
  
3. Run Jupyter:

  ```$ jupyter notebook ```
  
4. Create a notebook and check if it has been installed correctly:

  ```$ import tensorflow as tf```
  
  ```$ hello = tf.constant('Hello, TensorFlow!')```
  
  ```$ sess = tf.Session()```
  
  ```$ print(sess.run(hello))```
