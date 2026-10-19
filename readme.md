# Summary of the UNet-based Drone Panoramic Cropland Extraction Project

## Body

Summary of the UNet-based Drone Panoramic Cropland Extraction Project

I. Project Plan and Selection

Unet semantic segmentation network is adopted, relying on the RGB panoramic images of drone aerial photography in Guangdong Mingao District. Unet's advantage of preserving shallow layer features is utilized to automatically extract and segment cultivated land areas under complex scenes, achieving intelligent agricultural field surveying and statistical scenarios.

II. Data Preprocessing Process

1. The original panorama is stored in the panorama folder, first crop the original image and filter greenery to generate agricultural sample images.

2. Data Set Specification Division: The original images are placed in JPEGImages, and the segmentation labels are placed in SegmentationClass.

3. Generate training index txt file using the annotation.py script

III. Model Training & Prediction Configuration

1. This project only involves one slicing category, set the train.py classification parameters to 1.

2. Run train.py to complete the model training.

3. Modify the weight path and number of categories in unet.py during prediction phase, and run predict.py to output the results of crop segmentation.

4. Project-related training weight files, which can be concatenated and stored in the model directory.

IV. Output results

Three types of comparative images can be outputted: original image, manually labeled label image, and model prediction segmentation image. This enables precise extraction of land plot outlines, applicable to the verification of farmland rights and the calculation of arable land area.

## Images

![img_00.jpg](img_00.jpg)
![img_01.jpg](img_01.jpg)
![img_02.jpg](img_02.jpg)


## Payment

Here is a pay link on Stripe ( https://buy.stripe.com/3cs8yP7sY87d0vu9AB ). Please contact me lonlonago@foxmail.com after funding $89, and I will send you a complete data files , thank you!

![111.png](111.png)
