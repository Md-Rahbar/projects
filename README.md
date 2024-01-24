This project determines the unfiltering of any photo or image.
It is a project which shows how a completely high quality which actually looks without high brightness and filters.
This project aims to automatically add color to grayscale images using deep learning techniques.
The model implemented here is designed to understand the context of an image and predict appropriate colors for different regions.
important libraries
(import cv2
import skimage
import glob
import numpy as np
import pandas as pd
from matplotlib import pyplot as plt
from sklearn.neighbors import KNeighborsClassifier
from skimage.segmentation import slic
from skimage.util import img_as_float
from scipy import ndimage as nd
import warnings
warnings.filterwarnings("ignore")
import matplotlib.pyplot as plt
import matplotlib.image as mpimg
%matplotlib inline
import os)
