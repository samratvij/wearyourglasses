# wearyourglasses

### Plan:
A. Loading/Preprocessing <br>
1. Collect dataset: <br>
a. Glasses or Not from Kaggle (https://www.kaggle.com/jorgebuenoperez/datacleaningglassesnoglasses) - DONE <br>
b. SOF (Specs on Faces https://sites.google.com/view/sof-dataset) - DONE <br>
c. Own pictures: Develop python bot to take pictures from webcam every 5-10 mins - DONE (Capture images for 5-10 days - DONE)  <br>
2. Scale images to same dimensions - DONE <br> <br>

B. Training <br>
1. Split in train test validation <br>
a. All from SOF and Kaggle in training and validation. <br>
b. 50% Own pictures in training, 20% in validation, 30% in test. <br>
2. Data Augmentation <br>
a. Only for training data <br>
b. Not on SOF - already augmented <br>
3. Transfer learning (Direct + Fine tuning) <br> <br>

C. Test script <br>
1. Script to take input from webcam and predict <br>
2. Show error message if no specs <br>
3. Convert to installable software package <br> <br>
