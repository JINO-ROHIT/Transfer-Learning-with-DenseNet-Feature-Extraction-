# Transfer Learning Using TorchVision

In this notebook, we use the pretrained DenseNet which was trained on the 1000 class ImageNet and try and do some feature extraction.

## Difference between Fine Tuning and Feature Extraction
There is a big difference between Fine Tuning and Feature Extraction .
* In fine tuning, we start with a pretrained model and update all of the model’s parameters for our new task, which ultimately is retraining the whole model.
* In the case of feature extraction , we start with a pretrained model and only update the final layer weights from which we derive predictions.

 The performance of finetuning vs. feature extracting depends largely on the dataset but in general both transfer learning methods produce favorable results in terms of training time and overall accuracy versus a model trained from scratch.
