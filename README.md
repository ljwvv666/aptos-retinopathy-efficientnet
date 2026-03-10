# APTOS 2019 Diabetic Retinopathy Detection
EfficientNet-B0 transfer learning for fundus image grading (0-4 severity).
## Dataset
- APTOS 2019 Kaggle Competition
- 3,662 training fundus images
- 5-class ordinal regression (treated as MSE regression)
## Model
- EfficientNet-B0 (pretrained on ImageNet)
- MSELoss + Adam optimizer + StepLR scheduler
- Best val_loss: 0.2563 (epoch 8/10)
- License: MIT | Dataset: CC BY-SA 4.0
