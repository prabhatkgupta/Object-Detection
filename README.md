# Object-Detection
This Repository contains all the files related to Object Detection model using YOLO algorithm.

## Important points related to model: 
- This a Deep CNN model that uses YOLO(You Only Look Once) algorithm for identifying objects.
- It includes a single scan of the image to detect the objects.
- There are various anchor boxes that are used to bound the objects and prediction is done for each anchor box.
- The model uses transfer learning to get the pre-trained parameters and was then fine-tuned with cross validation set to improve the test-set accuracy.
- Model uses Non-Max Suppression and Intersection-over-Union(IoU) as a parameter to filter multiple anchor boxes.
- It was developed on Keras Framework.
