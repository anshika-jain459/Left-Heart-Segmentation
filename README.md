# Left-Heart-Segmentation
Left Heart Segmentation in Echocardiographic  Images Using DNN Model

- Developed and benchmarked U-Net, NN-UNet, and ACNN models to segment left ventricle (endocardium/epicardium) and left atrium from 2D echocardiograms.

- Preprocessed data (noise reduction, augmentation, normalization) and implemented 10-fold cross-validation.

- NN-UNet achieved 96.7% accuracy, 0.954 Dice score, and 4.5 Hausdorff distance, outperforming other architectures.

- Evaluated using clinical metrics: MAE (5.9), Jaccard Index (0.915), and Correlation Coefficient (0.978).
