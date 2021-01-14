# ImageCompressionByK-Means
Task 1: Introduction and Overview

  Import essential modules and helper functions from NumPy, Matplotlib, scikit-learn, and Jupyter Widgets.

Task 2: Data Pre-processing

   Import images from a local directory and store them as numpy arrays.
    Explore the image attributes.
    Normalize the pixel values and unroll the arrays into vectors.

Task 3: Visualizing the Color Space using Point Clouds

   Visualize the set of pixels from the original image as a two 2-D point clouds in color space.

Task 4: Visualizing the K-Means Reduced Color Space

   Understand the math and steps involved in the k-means clustering algorithm.
    Perform k-means clustering with scikit-learn's MiniBatchKMeans to reduce the number of possible colors in the image from over 16 million to 16.
    Compare and contrast the color space of the original image with that of the k-means compressed image.

Task 5: Creating Interactive Controls with Jupyter Widgets

   Use the interact function to automatically create UI controls for function arguments.
    Define an argument to control the value of k using a slider.
    Define an argument to pick any image from a specified directory.

Task 6: K-means Image Compression with Interactive Controls

   Ensures that k-means image compression is performed only on the slider widget's mouse release events.
    Repurpose the data pre-processing and k-means clustering logic from previous tasks to operate on images of your choice.
    Visualize how the image changes as the number of clusters fed to the k-means algorithm is varied.
