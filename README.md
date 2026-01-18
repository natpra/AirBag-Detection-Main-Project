
# Airbag Detection using Mask R-CNN (UNet) and FPN R-CNN (Detectron2) for video analysis system and processing.

In this project, I used UNet to segment the AirBag's presence in each frame of the video clip to drive insights.

### Actual Footage downloaded from Youtube (slowed down for better analysis):
https://github.com/natpra/AirBag-Detection-Main-Project/assets/113239581/39a832bc-8c01-4b64-97ad-23f03ac26b74
The above video clip was taken from YouTube and slowed down for further analysis.

### Yolov8 Results :
https://github.com/natpra/AirBag-Detection-Main-Project/assets/113239581/0aae59ee-caca-487b-bc98-79c05a3b3d33
The above video clip is what Yolov8 returned post training. This gives us the Region of Interest(ROI) for each frame.


### UNet Mask Results :
https://github.com/natpra/AirBag-Detection-Main-Project/assets/113239581/fcd09b16-c981-4d78-855f-200689b647db
The above video clip shows what UNet returns (masked images) post training. This gives us the binary result pixel-by-pixel.


### Mask visualized onto the video:
https://github.com/natpra/AirBag-Detection-Main-Project/assets/113239581/d7bce807-4a82-4ecd-8d3c-421b35eb43b7
Yolov8 performs object detection
UNet performs image segmentation
Yolov8 + UNet gives us the above video a fully bounded-region video of the airbag being deployed.

## Insights:
https://github.com/natpra/AirBag-Detection-Main-Project/assets/113239581/60533549-6f34-440c-9b6c-de3ecb538927

## Performance Comparsion:

### Detectron2 Results:
https://github.com/natpra/AirBag-Detection-Main-Project/assets/113239581/60533549-6f34-440c-9b6c-de3ecb538927
The above video is the result after Detectron2 was used on the raw footage. This is used for comparing our performances.

### DeepLabV3+ Results:
https://github.com/natpra/AirBag-Detection-Main-Project/assets/113239581/60533549-6f34-440c-9b6c-de3ecb538927
The above video is the result after Detectron2 was used on the raw footage. This is used for comparing our performances.
