# Computer Vision - Object Tracking
# Sources
Algorithm for Object Tracking

- [Simple Online Realtime Tracking (SORT) Paper](https://arxiv.org/abs/1703.07402)
- [People Tracking Article](https://towardsdatascience.com/people-tracking-using-deep-learning-5c90d43774be#:~:text=Deep%20Sort%20Algorithm,-I%20love%20the&text=We%20track%20based%20on%20not,factor%20into%20the%20tracking%20logic)
- [Deep SORT Github Repo](https://github.com/nwojke/deep_sort)
- [YOlOv3 Article](https://machinelearningmastery.com/how-to-perform-object-detection-with-yolov3-in-keras/)
- [Road Segmentation](https://www.kaggle.com/datasets/sakshaymahna/kittiroadsegmentation?resource=download)


# Deep SORT Implementation Overview
## YOLOv3 Network
Generating the bounding boxes for detected objects

<img src="https://viso.ai/wp-content/uploads/2021/02/YOLOv3-how-it-works.jpg" alt="yolo3image">

## Detections
Encode given cropped image


## Kalman Filter
Used to generate predictions of objects' future locations

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Basic_concept_of_Kalman_filtering.svg/2000px-Basic_concept_of_Kalman_filtering.svg.png" alt="kal">

<img src="https://www.lancaster.ac.uk/stor-i-student-sites/jack-trainer/wp-content/uploads/sites/24/2021/03/KFplotnew-1024x597.png" alt="probability">

## IoU Matching
Solve linear assignment problem as well as cascade matching

<img src="https://929687.smushcdn.com/2633864/wp-content/uploads/2016/09/iou_examples.png?lossy=1&strip=1&webp=1" alt="">
<img src="https://929687.smushcdn.com/2633864/wp-content/uploads/2016/09/iou_car_bbs.jpg?lossy=1&strip=1&webp=1" alt="">

## Nearest Neighbor Matching
Solves cosine distance and Eucladian distance for Deep Appearance Descriptor as well as Kalman filter



## Tracking
Combines modules to create final object



## Object Tracking
Complete and run algorithm in a loop for each video. 



