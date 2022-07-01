#  2021 Better Working World Data Challenge
This repository shows our contribution to this data chnallenge organized by EY. We have finished 20th in the Global ranking and 2nd in the French ranking. 

## The challenge
The objective was identify the forest fire in a grayscale image. The challenge was to deal with only few annotated images. Here is an example of the dataset: 

## Our results
We decided to firstly do image augmentation on the dataset to have more trainning data. Then, we have used an U-net with an InceptionResNetv2 as encoder. Finally, we have developed some image post-processing on the model output to obatain a more accurate and smooth prediction. We have reached a F1-score of 0.76 on the challenge test set. Here an exemple of our outputs: 
