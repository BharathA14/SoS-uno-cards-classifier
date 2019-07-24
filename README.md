# SoS-uno-cards-classifier
this program takes the image of the card through webcam and then predicts the card
both the programmes are run via terminal-

for training the model
python3 train.py --dataset dataset --model uno.model --labelbin lb.pickle

for running the classifier:
python3 classify.py --model uno.model --labelbin lb.pickle
