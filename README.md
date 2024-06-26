## Load the data
The downlaoded from previous step should be moved to location in a specific format.
data >> images >> train
data >> labels >> train

## Update config.yaml file with these locations

## Train the model using python
python train.py

## Using cmd line
yolo detect train data=config.yaml model="yolov8n.yaml" epochs=1

## Use colab to run for 100 epochs and save model weights

## Run predict_video file
python predict_video.py