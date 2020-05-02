# potholes-detection
This is a deep learning model for detecting the potholes on roads. The model is using YOLO-v2. 

Download the weights and place it in the root folder. 

Then
`python predict.py -c config.json -w /path/to/best_weights.h5 -i /path/to/image/or/video`

The model has been trained with 150 images having 568 potholes labels. The accuracy of the model will increase by traing the model with larger size dataset. 

## Image

![Road with potholes](images/1.jpg?raw=true "Road with Potholes")

## Detected potholes
![Road with potholes detected](images/1_detected.jpg?raw=true "Road with Potholes Detected")
