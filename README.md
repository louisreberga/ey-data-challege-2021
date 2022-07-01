#  2021 Better Working World Data Challenge
This repository shows our contribution to this data challenge organized by EY. We have finished 2nd in the French ranking and 20th in the Global one. 

## The challenge
The objective was to precisely identify forest fires on grayscale images. The real challenge was to deal with only few annotated images. Here is an example of the dataset: 

<p float="left">
  <img src="https://raw.githubusercontent.com/louisreberga/ey-data-challenge-2021/main/images/dataset_1.png" width="400" />
  <img src="https://raw.githubusercontent.com/louisreberga/ey-data-challenge-2021/main/images/dataset_2.png" width="400" />
</p>

## Our results
We decided first to do image augmentation on the dataset to get more training data. Then, we have used an U-net with an InceptionResNetv2 encoder. Finally, we have developed some image post-processing on the model outputs to obatain more accurate and smoother predictions. We have reached a F1-score of 0.76 on the challenge test set. Here an exemple of our outputs: 
