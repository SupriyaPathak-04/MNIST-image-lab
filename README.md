# MNIST-image-lab
A beginner-friendly project exploring image preprocessing techniques using Python, OpenCV, and NumPy.

I'm exploring image preprocessing using Python and the MNIST handwritten digit dataset.

The main idea of this project is to understand how an image changes when we apply different preprocessing techniques. Instead of just running the code, I'm trying to understand what each method does to the pixels and how the output changes.

## What I'm working on

So far, I've explored these techniques:

- Loading the MNIST dataset from a URL using NumPy
- Understanding image shapes, pixel values and data types
- Normalization (converting pixel values from 0–255 to 0–1)
- Gaussian blur
- Image rotation and translation
- Histogram equalization
- Edge detection using Canny
- Image reshaping&#x20;

I'm using visual comparisons to see the difference between the original image and the processed image.

## Dataset

I'm using the MNIST dataset, which contains handwritten digits from 0 to 9.

- 60,000 training images
- 10,000 testing images
- Each image is 28 × 28 pixels

I'm loading the dataset directly from its URL instead of using the built-in Keras dataset loader.

## Tools I'm using

- Python
- NumPy
- OpenCV
- Matplotlib
- Google Colab

## How to run it

1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Look at the outputs to compare how each preprocessing method changes the image.

## What I want to learn from this

I want to get comfortable working with image data and understand when different preprocessing methods are useful. I'm also learning that not every technique improves every image, so it's important to look at the results instead of assuming a method always helps.

This is a learning project, and I'll keep adding more techniques as I explore them.

