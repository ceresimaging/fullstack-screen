# Ceres Full Stack Tech Screen

## Project
We have images (.png) and a file containing image metadata (.txt) stored on s3. We would like you to write a Python API that can answer the following queries:

- Get list of all images available
- Download specific image
- For a specific image, get associated metadata from the metadata file

Feel free to download these files and write the API to read from your local drive. Then, create a simple frontend to select an image and display its metadata.

## Stretch Goals

- Pull files directly from s3 using the boto3 library.
- Add functionality to return a list of images contained in a specific time window.
- Add functionality to download all images in a zip file.

## Instructions
This project should take no more than 4 hours to complete. Please organize your code into a Github repository and send us the link for submission. We’ll evaluate the exercise by looking at the end result and the code.

The s3 bucket with images and metadata is located here:
https://s3.console.aws.amazon.com/s3/buckets/ceres-technical-challenge?region=us-west-2&tab=objects
