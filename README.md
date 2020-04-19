# Weed-Detection
Precision agriculture is gaining increasing attention because of the possible reduction of agricultural inputs (e.g., fertilizers and pesticides) that can be obtained by using high-tech equipment, including robots. Information on weed distribution within the field is necessary to implement herbicide application. This research aims to provide a weed detection tool for future agricultural robots. The weed detection tool incorporates the use of machine-learning procedure explicitly implementing U-Net and morphological operations on RGB images to classify crop and weed. 

We have proposed a pipeline to detect and mask the presence of in an image. The image data is pre-processed in order to apply some morphological operation to detect weeds and fed them into UNET model which performs semantic segmentation and generates masks over weeds.
The main contributions of this work are:
•	A background removal method that uses a deep pixel-wise segmentation to distinguish between soil and plants.
•	Morphological erosion and dilation methods are used to disconnect objects within the image. 
•	An accurate crop/weed classifier based on U-Net. 
The limited amount of data with pixel-wise annotations is in fact the bottleneck for most crop/weed classification methods. Our method relies on generating more data by flipping the images
