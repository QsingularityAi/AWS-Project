# AWS-Project

Project Structure
Prepare custom script for Amazon Sagemaker
Train a TensorFlow model using Amazon Sagemaker
Deploy a TensorFlow model using Amazon Sagemaker

The hands on project on Using TensorFlow with Amazon Sagemaker is divided into following tasks:

Task 1: Introduction and Notebook Instance
Create a Notebook instance in Sagemaker

Task 2: Download the Data
Upload a starter notebook to the Sagemaker Notebook instance
Download the Oxford-IIIT Pet Dataset

Task 3: Prepare the Dataset
Extract list of images along with their classes
Create Training and Validation sets

Task 4: Create the Model
Create a custom training script
Define a function to create the CNN model

Task 5: Data Generators
In the custom training script, write a function to create data generators for training and validation sets

Task 6: Arguments
Write argument parser to parse the arguments sent by Sagemaker to the custom script

Task 7: Finalizing the Training Script
Create a model instance
Instantiate training and validation generators
Train the model
Export the trained model

Task 8: Upload Dataset to S3
The dataset prepared in Task 3 is uploaded to S3

Task 9: TensorFlow Estimator
Create a TensorFlow Estimator
Specify the entry point, execution role and other necessary arguments
Using the fit method on the Estimator to launch the training job

Task 10: Deploy the Model
Deploy the trained model artifact using the Estimator

Task 11: Inference and Deleting Endpoint
Write a function to preprocess input images and get predictions from the deployed model
Deleting the deployed model endpoint

