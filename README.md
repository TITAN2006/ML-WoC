# ML-WoC

Linear Regression:

At first i tried to run the code with the original data and realized that feature scaling(z-score in this case) needed to be performed to make the data more simpler
The next method tried was to remove the bias. As in i included the bial in w itself. so i did not have to write unnecessary lines
I had recieved the inspiration of having a decaying learining rate to improve the chances of achieving cost minima at lesser iterations which means more accurate predictions but i did not have time to implement it


Polynomial Regression:
At first i was under the assumption that i only had to raise the features to higher powers but the R2 score corresponding to that was very small( around 0.28). so i realised i needed to implement interaction terms. i got the inspiration from the multinomial explaintion format where we have terms like x1x2.


Logistic Regression:
At first everything was running smoothly but my f1 scores were very low. Upon inspection i realised that i needed to find the perfect threshold. So i implemented a code where multiple threshold values between 0.1 and 0.9 are stored and the value at which the best f1 score was acchieved was chosen


Multiclassification:
The challenge i faced was understandind how to implement one hot encode. Other than that it was almost similar to binary classification. I learnt a new function that i implemented here called enumerate


k Means classification:
The main challenge faced here was to understand the number of clusters to put. Using elbow method it came out ot be 4


Neural Network:



