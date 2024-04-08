# Vehicle-Detection
**Objective:**
This project performs object detection on three vehicle types by employing transfer learning with FasterRCNN, achieving an 88.17% mAP score on the test dataset. 

**Dataset:**
This project aims to detect three types of vehicles, labeled 1-3:
1. Cars (including SUVs, vans, pick-up trucks and other small trucks)
2. Medium-sized trucks (e.g., Amazon or FedEx delivery trucks)
3. Large trucks (18-wheelers, buses, cargo trucks)

The dataset followed the below folder structure:

![image](https://github.com/Vsamyuktha/Vehicle-Detection/assets/20947664/348de4fc-7ca3-45a9-9bd2-5f1e3f295548)


The label text file follow the below format:<br>
  **image_id class cx cy w h**<br>
The predictions followed a similar format but the values were relative. The image_id was the file name minus the extension.

**Experimental Results:**

![image](https://github.com/Vsamyuktha/Vehicle-Detection/assets/20947664/e5c383a0-24ee-492d-bcaa-1f8223c058e6)




**Sample output:**

Test Image using FasterRCNN (ResNet50):

![image](https://github.com/Vsamyuktha/Vehicle-Detection/assets/20947664/2ed8b2d9-3de3-4da8-b693-25c0077da74e)




Test Image after filtering based on confidence score:

![image](https://github.com/Vsamyuktha/Vehicle-Detection/assets/20947664/e06014b0-1acf-4318-a9f3-d25c88fdeb63)





Test Image after applying NMS (Non-Maximum Suppression) and confidence score filtering:

![image](https://github.com/Vsamyuktha/Vehicle-Detection/assets/20947664/13f6ed6f-f076-4381-b00c-db9d4414746d)



