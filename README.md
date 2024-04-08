# Vehicle-Detection
**Objective:**
This project performs object detection on three vehicle types by employing transfer learning with FasterRCNN, achieving an 88.17% mAP score on the test dataset. 

**Dataset:**
This project aims to detect three types of vehicles, labeled 1-3:
1. Cars (including SUVs, vans, pick-up trucks and other small trucks)
2. Medium-sized trucks (e.g., Amazon or FedEx delivery trucks)
3. Large trucks (18-wheelers, buses, cargo trucks)

The dataset followed the below file format:

![image](https://github.com/Vsamyuktha/Vehicle-Detection/assets/20947664/607a77c6-0d9f-4ccb-a1ea-87eb7cdca385)


The label text file format: **<image_id> <class> <cx> <cy> <w> <h>**. The predictions followed a similar format but were relative. The image_id was simply the file name minus the extension.

**Experimental Results**
![image](https://github.com/Vsamyuktha/Vehicle-Detection/assets/20947664/38a36dfc-2084-42f4-ac99-4539c5707d57)



**Sample output**

Test Image using FasterRCNN (ResNet50) 

![image](https://github.com/Vsamyuktha/Vehicle-Detection/assets/20947664/2ed8b2d9-3de3-4da8-b693-25c0077da74e)




Test Image after applying NMS

![image](https://github.com/Vsamyuktha/Vehicle-Detection/assets/20947664/13f6ed6f-f076-4381-b00c-db9d4414746d)




Test Image after filtering based on confidence score

![image](https://github.com/Vsamyuktha/Vehicle-Detection/assets/20947664/e06014b0-1acf-4318-a9f3-d25c88fdeb63)



