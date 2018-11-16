# Female innovation day - Image recognition

## Intro

Recognizing a face on a picture/photo and doing awesome stuff with it. 

## Recommended pre-knowledge

* Some experience in python is recommended (though not required as starting code is provided and it is possible to team up).
* A creative mind :)

## Possible endgoals

Let's look at some of the stuff we might be doing:

* Making pictures with faces "funny" by changing the faces in them:
  * Make the faces red 
  * Substitute them with something else like a pumpkin, apple, etc.
  * Put a black bar over the eyes
* Funny filters on the face: big mouth, popping eyes, etc.
* Cropping an image with an arbitrary width-height ratio

These are just some suggestions, feel free to be creative yourself and experiment.


## Starting points

Some possible starting points are provided, but feel free to experiment with anything else if you're feeling adventurous. 

1. `face_detection.ipynb` provides some sample code on a face/eye detection classifier (taken from [opencv docs](https://docs.opencv.org/3.3.0/d7/d8b/tutorial_py_face_detection.html)).
2. In the `data` directory you can find some sample photos to begin experimenting with. 
3. The `gather_data.py` file can be used There's a directory `data/subset` which contains 100 photos of different sizes to start experimenting with. The directory `data/all` contains a much larger collection of photos which can be used when you want more examples or test your code on a bigger selection of photos. 

## Prerequisites

* python3
* virtualenv (highly recommended)

### Steps to install prerequisites

Installing prefrequisites
1. install brew: `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
`
2. install python3 and pip: `brew install python`
3. install virtualenv: `pip3 install virtualenv`

## Getting started

1. create a project directory (e.g. `mkdir FemaleInnovationDay`)
2. `cd FemaleInnovationDay`
3. clone the project `git clone https://github.com/IVermeulen/female_innovation_day_image_recognition.git`
3. create a virtual env: `virtualenv venv`
4. activate the virtual env: `source venv/bin/activate`
5. `cd female_innovation_day_image_recognition`
6. install the required packages in the virtual env: `pip install -r requirements.txt`
7. for using ipynb `python -m ipykernel install --user`
8. start coding! :)
