<img src="images/memelord.jpg">

# THIS README IS STILL 🚧 UNDER CONSTRUCTION 🚧 DUE TO SEMESTER EXAMS
This is my submission to this <a href="https://www.kaggle.com/c/detect-pneumonia-fall-2020">Kaggle competition</a>. After **85 heroic submissions** full of trial and error, this solution achieved the highest score (86.1%) 

## The Goal
The goal was to categorize 1168 chest x-ray images into 3 categories:

- no disease
- bacterial pneumonia
- viral pneumonia 

## The Dataset 
The training dataset consisted of 4672 images out of which:

- 1227 images belong to class 0
- 2238 images belong to class 1
- 1207 images belong to class 2 

## Submission
Fine-tuned 5 pretrained models, 1 Xception and 4 EfficientNets. Each model had its own topping.
All of the models did their part in the ensemble, on which the final submission was based on.

Both the training and testing dataset had been pre-processed using Histogram Equalization.

You can try the code out on <a href="https://colab.research.google.com/drive/14xSD5mXPMSCAknmjm-bRVU-ohxbtDcXM?usp=sharing">Colab</a>

###### Many thanks to Google for lenting me those juicy NVidia Tesla T4 even if I was getting daily time outs.
