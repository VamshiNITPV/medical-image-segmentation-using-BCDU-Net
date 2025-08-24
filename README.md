# medical-image-segmentation-using-BCDU-Net
Implemented BCDU-Net, an enhanced U-Net architecture combining Bi-directional ConvLSTM and dense convolutions for accurate lung CT image segmentation. Achieved perfect sensitivity and high AUC-ROC. The model effectively extracts contextual features, improving recall and enabling robust detection of lung regions in medical imaging.

# Lung segmentation
1- Mount Google Drive and load the 3D lung images dataset [Kaggle](https://www.kaggle.com/datasets/kmader/finding-lungs-in-ct-data/data)
 from the specified directory.
2- Run the preprocessing section for data preparation, train/test separation and generating new masks around the lung tissues.
3- Run the training section for training the BCDU-Net model using training and validation sets (20 percent of the training set). The model will be trained for 10 epochs and it will save the best weights for the validation set. You can train either BCDU-Net model with 1 or 3 densely connected convolutions.
4- For performance calculation and producing segmentation results, run the evaluation section. It will represent performance measures and will save related figures and results.
