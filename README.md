**Note:** The work was published on https://www.learnopencv.com/. Link: [blog post](https://www.learnopencv.com/image-quality-assessment-brisque/).

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


## Citation

If you find this code useful in your research, please consider citing:

@misc{Kushashwa Ravi Shrimali,
Author = {Kushashwa Ravi Shrimali},
Title = {No Reference Image Quality Assessment in Spatial Domain},
Year = {2018},
Publisher = {GitHub},
journal = {Github repository},
howpublished = {\url{https://github.com/krshrimali/No-Reference-Image-Quality-Assessment-using-BRISQUE-Model}},
}