# Mask detection using tensorflow keras

Predicting whether a person is wearing a mask or not using the intelligent tensorflow library.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install tensorflow, numpy, matplotlib, sklearn etc.

```bash
pip install tensorflow
pip install numpy
pip install matplotlib
pip install sklearn
```

## Requirements
Large dataset with two folders, one with images of face with mask and other without mask.
NB: you can get it from kaggle

## Usage

Train the model first by running the file
```bash
training_detector.py
```
Then test it by running the file
```bash
detect_mask_video.py
```
## Result
### Without Mask
![nomask](https://github.com/shezin888/Mask-detector/blob/master/without_mask.png?raw=true)
### With Mask
![mask](https://github.com/shezin888/Mask-detector/blob/master/with_mask.png?raw=true)

