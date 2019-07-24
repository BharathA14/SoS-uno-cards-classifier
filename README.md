# SoS-uno-cards-classifier
this program takes the image of the card through webcam and then predicts the card.
To try using the file, run the classifier and when the webcam opens, put an UNO card in front of it and hit the space-bar. 
UNO.model stores the trianefd neural network. Training it takes a lot of time, my databset which i sued was somewhere around 5Gb, hence i couldnt include it in here. Bes reu to place all files in the same folder.
The trained model can be downloaded via the google drive link also present in the doc.
both the programmes are run via terminal-

for training the model
python3 train.py --dataset dataset --model uno.model --labelbin lb.pickle

for running the classifier:
python3 classify.py --model uno.model --labelbin lb.pickle
