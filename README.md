# Udacity-Capstone

In this project, I got to develop a dog breed classifier module. I learned how to build a pipeline to process images. Then, given the image, the algorithm estimated the breed of the dog. If the image was a human, it was able to successfully predict it to be a human too. 

# Libraries Used
 Sklearn
 Keras
 Glob
 Numpy
 Random
 Cv2
 Matplotlib
 Tdqm
 PIL
 Extract_Bottleneck_features
 
 # Files Used
 Jupyter notebook - where all my code was written
 Bottleneck features - VGG-16 and VGG19 - pre-trained models as a fixed feature extractor
 Sample images to test the algorithm
 
 # Steps to the Project
 1. Import Datasets - Imported dog and human datasets
 2. Detect Humans - Wrote a human detector to evaluate whether an image is a human's face 
 3. Detect Dogs - Wrote a dog detector to evaluate whether an image is a dog
 4. Create a CNN to Classify Dog Breeds (from Scratch) - Created a CNN to classify dog breeds and attained a test accuracy of 1.1962%
 5. Use a CNN to Classify Dog Breeds (using Transfer Learning) - With the Udacity CNN transfer learning algorithm (using VGG-16), it attained a test accuracy of 42.2249%
 6. Create a CNN to CLassify Dog Breeds (using Transfer Learning) - I created a CNN transfer learning algorithm (using VGG-19) and attained a test accuracy of 71.4115%
 7. Write the algorithm - I wrote an algorithm to accept a file path of an image, determine whether it is a human or dog, and then estimate the dog breed of the image.
 8. Test the algorithm - Happy to say that with my 6 test images, the algorithm correctly identified all 6 as either human or dog. The specific breed had more mixed results. 

Blogpost can be found here: https://medium.com/@scott.helberg/when-is-a-dog-a-dog-2bac24e09348

# Acknowledgements
Thank you to Udacity and RSM for giving me the opportunity to expand my understanding of data science and attain this nanodegree. 
