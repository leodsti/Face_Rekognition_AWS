# Face_Rekognition_AWS
Set up an API interface for AWS face rekognition service usage

This workshop has been done thanks to two Alumni: Jean Milpied and Anthony Jourdan

## Objective
You can follow this tutorial to set-up a simple API for face recognition (using your laptop webcam images) and the AWS 'rekognition service'. 
Nothing complicated. All files are shared in this github.

- on chrome, you may need to allow the site to get access to your webcam by going to the following option link:  
(chrome://flags/#unsafely-treat-insecure-origin-as-secure)  
![alt text](https://github.com/JeanMILPIED/Face_Rekognition_AWS/blob/master/webcam-google.JPG) 

- On Firefow you need to enable in about:config both media.devices.insecure.enabled and media.getusermedia.insecure.enabled

## Pre-requisites

You will need to create a private S3 bucket named 'image-for-reko'.

## Front End 

You will need to launch an EC2 instance with Ubuntu and install Apache server on it.
The file needed for the front end are in the "Frontend_machine" folder.

## Back end
You will need to launch an EC2 instance with Ubuntu and install :
- Conda 
- Create a virtual env with python 3.6
- install the packages "Flask", "flask_cors" and "boto3".

The file required for the back end are in the backend_machine folder

