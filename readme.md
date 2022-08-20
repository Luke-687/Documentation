Backyard ANimal Detection

This project when run correctly whill be able to identify animals that you would commonly see in your backyard which could be either eating your plants, or even stuck within the fence


[Imgur](https://i.imgur.com/nEciGOT.jpg)

The Algorithm

Add an explanation of the algorithm and how it works. Make sure to include details about how the code works, what it depends on, and any other relevant info. Add images or other descriptions for your project here. 

Running this project

1. To run this project you must use the code lines of imagenet.py to register image as seen in module 6 (imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/<class>/<image>.jpeg <savingPlace>.jpg)
2. Once image is finished being saved, and processed use a scp command on a new terminal to find your image, and open it up to gage the success (scp <nanousername>@192.168.55.1:/home/<nanousername>/jetson-inference/python/training/classification/cat.jpg ./)

[View a video explanation here](video link)
