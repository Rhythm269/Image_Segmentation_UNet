# Image_Segmentation_UNet
Image Segmentation task is performed using UNet Architecture on a large number of  nuclei images.

Link of dataset used: https://www.kaggle.com/c/data-science-bowl-2018/data

Dataset Description: 
This dataset contains a large number of segmented nuclei images. The images were acquired under a variety of conditions and vary in the cell type, magnification, and imaging modality (brightfield vs. fluorescence). The dataset is designed to challenge an algorithm's ability to generalize across these variations.

An associated ImageId represents each image. Files belonging to an image are contained in a folder with this ImageId. Within this folder are two subfolders:


Images contain the image file.
Masks contain the segmented masks of each nucleus. This folder is only included in the training set. Each mask contains one nucleus. Masks are not allowed to overlap (no pixel belongs to two masks).

![img](https://github.com/Rhythm269/Image_Segmentation_UNet/assets/92662885/2c269b04-c8b8-4398-a3fd-5b539236a336)

![mask](https://github.com/Rhythm269/Image_Segmentation_UNet/assets/92662885/61ad12b8-d66b-421c-8dab-818383f8b79b)

![seg_res](https://github.com/Rhythm269/Image_Segmentation_UNet/assets/92662885/e3972084-5cd9-4e27-bd70-6417ba2983b1)
