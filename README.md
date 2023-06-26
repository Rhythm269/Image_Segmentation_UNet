# Image_Segmentation_UNet
Image Segmentation task is performed using UNet Architecture on a large number of  nuclei images.

Link of dataset used: https://www.kaggle.com/c/data-science-bowl-2018/data

Dataset Description: 
This dataset contains a large number of segmented nuclei images. The images were acquired under a variety of conditions and vary in the cell type, magnification, and imaging modality (brightfield vs. fluorescence). The dataset is designed to challenge an algorithm's ability to generalize across these variations.

An associated ImageId represents each image. Files belonging to an image are contained in a folder with this ImageId. Within this folder are two subfolders:

Images contain the image file.
Masks contain the segmented masks of each nucleus. This folder is only included in the training set. Each mask contains one nucleus. Masks are not allowed to overlap (no pixel belongs to two masks).

