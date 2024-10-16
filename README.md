# JupICL - Jupyter-Notebook-based Image Class Labeler

JupICL, pronounced 'joop-pickle', is a super easy-to-use, customizable, light-weight image labelling tool running entirely inside a Jupyter notebook and is primarily intended for training image classification models.
Additionally, you can use it for reviewing images and taking free-form notes on each image.

## Overview

JupICL makes it blazingly fast, easy, and fun to label tens of thousands of images on your own. 
You can even customize your keyboard shortcuts without writing any additional code.
But if you know some python, you can easily extend and customize the tool even further to suit your particular needs.

JupICL is NOT for labelling bounding boxes, or labelling pixels as is commonly done for object detection and image segmentation tasks.

**JupICL is completely agnostic of any particular deep learning framework.**
However, if you are using SAS Deep Learning Framework with [SAS-DLPy](https://github.com/sassoftware/python-dlpy) then you will find that for image-classification models, images are labelled in a manner that makes it easy to load into a CASTable with standard DLPy utilities.

### Prerequisites

- Jupyter Notebook (or Jupyter Lab)
- python >= 3.6.10
- python packages: cv2 (opencv) and PIL (pillow)

### Installation

JupICL is designed to use the features of Jupyter and hence you need either Jupyter Notebook or Jupyter Lab to get started.

Your python environment also needs the cv2 (opencv) and PIL (pillow) image processing packages.

## Getting Started

Try the ImageDisplay.ipynb to display some images from the ./data directory and optionally take some notes on the images you are viewing.
This notebook is also useful for doing some quality review or general data exploration.

OR try running the ImageAnnotator.ipynb for labelling images.  

Note: The ImageAnnotator.ipynb actually moves files around from the source directory into a target directory that gets set-up when running it, which is why it is recommended to make a copy of the './data' directory and to use the copy instead as a source directory.
This has already been done for you, as the './images' directory is a copy of './data'.

Attribution: The sample data provided here is an extremely small subset of the [Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist) dataset.

## Contributing

We welcome your contributions! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to submit contributions to this project. 

## License

This project is licensed under the [Apache 2.0 License](LICENSE).

## Additional Resources

* A community article is coming soon.
