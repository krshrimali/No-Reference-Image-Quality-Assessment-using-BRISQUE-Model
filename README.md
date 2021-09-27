## Note

Please see https://github.com/krshrimali/No-Reference-Image-Quality-Assessment-using-BRISQUE-Model/issues/4 if you are looking to contribute. :)

**Note:** There have been many revisions, specially about the models used. Please check the work by @clunietp (https://github.com/clunietp) and myself on BRISQUE IQA committed to `opencv_contrib` here: https://github.com/opencv/opencv_contrib/tree/master/modules/quality

**Note:** This work was originally published on LearnOpenCV. For code: https://github.com/spmallick/learnopencv/tree/master/ImageMetrics

The work was published on https://www.learnopencv.com/. Link: [blog post](https://www.learnopencv.com/image-quality-assessment-brisque/). 

## Process

![Steps to Calculate Image Quality Score using BRISQUE Model](https://github.com/krshrimali/No-Reference-Image-Quality-Assessment-using-BRISQUE-Model/blob/master/Images/Process_BRISQUE_Calculation.png)

## Installation Instructions
**Python 2.x LIBSVM Installation**
`sudo apt-get install python-libsvm`

**Python 3.x LIVSVM Installation and C++ LIBSVM Installation**

For C++ :

1. `cd C++/libsvm/`
2. `cmake .`
3. `make`

For Python 3.x :

1. `cd Python/libsvm/`
2. `make`
3. `cd python`
4. `make`

## Usage 

**Python 2.x**

1. `python2 brisquequality.py <image_path>`

**Python 3.x** 

1. `cd Python/libsvm/python/`
2. `python3 brisquequality.py <image_path>`

**C++**

1. `cd C++/`
2. `./brisquequality <image_path>`

## Example

**Quality Score Comparison using BRISUQE Model**

![Quality Score Comparison using BRISQUE Model](https://github.com/krshrimali/No-Reference-Image-Quality-Assessment-using-BRISQUE-Model/blob/master/Images/Table_Comparison_BRISQUE.png)
