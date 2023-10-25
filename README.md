# 2D-UNet-Brats2021
In our proposed model, we have enhanced the U-Net architecture by increasing its depth and resizing input images to 128x128. This added depth involves incorporating more layers within the encoder and decoder sections, which allows for more complex feature extraction and refined segmentation. The image resizing to 128x128 not only reduces computational demands but also enhances model performance by preserving critical details while still effectively capturing context. These modifications collectively empower the model to better handle intricate segmentation tasks, making it more robust and accurate in applications such as medical image analysis, particularly for tasks like brain tumor detection and localization.
# Reading the Brats2021 Images
Unzip the BraTS2021_Training_Data.tar file using tarfile library and since file BraTS20_Training_355 has ill formatted name for seg.nii file do this "train_and_val_directories.remove(TRAIN_DATASET_PATH+'BraTS20_Training_355')" to completely remove that file since we have ample image data

Dataset Link: https://www.kaggle.com/datasets/dschettler8845/brats-2021-task1
