This is an introductory implementation of diffusion models with the following characteristics:
1. Trained on Stanford Cars Dataset available here: https://www.kaggle.com/datasets/jessicali9530/stanford-cars-dataset
2. Utilizes a UNET architecture with downsample and upsample layers with attention layers, without resnet layers
3. Uses Mean Absolute Error as an evaluation metric, achieiving an MAE of 0.07 in 200 epochs
4. Trained on T4 GPU
