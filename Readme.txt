After cloning the tensorflow models, compile the protos files in object_detection folder by opening terminal in models/research and type protoc object_detection/protos/*.proto --python_out=. Then, copy object detection in the folder of the same file and in scripts folder. Then collect images and label them using labelimg.
Install labelimg by opening terminal in this folder and write pip install labelImg.
Save them in test and train folder and now you are good to go!
