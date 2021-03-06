# Eye2Brain
[![forthebadge deployed-on-Heroku](https://heroku-badge.herokuapp.com/?app=eye2brain)](https://eye2brain.herokuapp.com/)
[![Slack](https://img.shields.io/static/v1?label=chat&message=slack&color=<COLOR>)](https://app.slack.com/client/TQAB3S6BD/CQDT4KJJD)
![Status](https://travis-ci.org/AmulyaReddy99/Eye2Brain.svg?branch=master)
[![Open Source Love png2](https://badges.frapsoft.com/os/v2/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)
![forks](https://img.shields.io/github/forks/AmulyaReddy99/Eye2Brain)
![stars](https://img.shields.io/github/stars/AmulyaReddy99/Eye2Brain)
![version](https://img.shields.io/badge/version-1.0-blue)

Join slack [here](https://join.slack.com/t/eye2brain/shared_invite/enQtODI5OTIyNjcyNDMzLWE1ZTUwNTgyZDcwYzZlZmE5ODdkZjJjYmQzMzBhMTY3MGU3OGVjZGE2MDIzYWQ5ZWI3ZWY4MGFmZjFmMTFlZmU)

Find datasets [here](https://drive.google.com/open?id=1iAlhNdK2QRfdpruK7ibMtgjGzND52mie)

Find saved_models [here](https://drive.google.com/open?id=1qsB1vqGZyuL6cyF2Mg1oxfy7AyUv_OiX)
Replace saved_models uploaded to github by this folder.

## Django - app
Our aim is to build a web interface for the models.

## Setup
- Clone this repo
- `cd DNN-master`
- Start jupyter noterbook to view the ipynb files
- To run the app goto `cd Django app`
- Create virtual environment (Delete env folder used here since it may not work in your environment)
- Install dependencies by `pip3 install -r requirements.txt`
- Replace saved_models uploaded to github with the drive folder provided in the link [here](https://drive.google.com/open?id=1qsB1vqGZyuL6cyF2Mg1oxfy7AyUv_OiX)
- Run the app by `python3 manage.py runserver`
- Click on `Choose file`
- Take input from `Django app/test images` or from any other source you wish

**Check code snippets for `# @Todo`. Change the code there as per requirements mentioned in the comments below. Refer to respective Readme in outputs directory.**

Files where @ Todo can be found are:
- load_saved_model.py
- views.py

----------------------------------

## The UI
![cover photo](https://github.com/AmulyaReddy99/Eye2Brain/blob/master/img/cover%20page.png)

 Now            |  Expected 
------------- | ---------
![cover photo](https://github.com/AmulyaReddy99/Eye2Brain/blob/master/img/output.png)| ![cover photo](https://github.com/AmulyaReddy99/Eye2Brain/blob/master/img/expected.png)

*PLEASE DOWNLOAD THE DATASETS. INSTRUCTIONS PROVIDED IN THE TABLE BELOW*

## Explaination of DNN files

| Name  | Dataset & Downloads | File |
| ------------- | ------------- | ----------- |
| Brain Tumor  | Pretrained model `vgg16_weights_tf_dim_ordering_tf_kernels_notop.h5` | `Tumor.ipynb` | 
| Image Captions  | `Kaggle Flikr image dataset` & Pretrained model `vgg16_weights_tf_dim_ordering_tf_kernels_notop.h5` | `Image Captions.ipynb` |
| Voice Recognition | `https://www.openslr.org/12` | `Voice Recognition.ipynb` | 
| Banana Ripeness Detection | [here](github.com/giovannipcarvalho/banana-ripeness-classificationtree/master/data) | `Banana.ipynb` |
| Stock Price Prediction | Alphavantage API | `Stocks.ipynb` |
| Sarcasm Detection |  | `Sarcasm Detection.ipynb` |
| Leaf Identification | Leaf snap dataset | `Leaf.ipynb` |
| Handwritten Text recognition | IAM handwriting dataset Top 50 (kaggle) | `Handwritten.ipynb` |
| Object Detection | Yolopretrained model | `object_detection.py` |

