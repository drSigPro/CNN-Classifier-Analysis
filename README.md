# Lab for exploring existing CNN architectures in [torchvision models](https://pytorch.org/vision/stable/models.html), Fine tuning and transfer learning ImageNet models to classify birds in [CUB-200-2011 dataset](https://www.vision.caltech.edu/datasets/cub_200_2011/) and Explain models through feature visualization and understanding

The lab has three parts with homeworks for each part. All the parts are to be done in Google Colab and the reference notebooks are appended in the parts below.

# Part 1: Compare the various ImageNET models for accuracy (1% and 5%), memory requirements, inference time and floating point operations (FLOPS)
Please follow the below steps
1. Download the ImageNet sample dataset available in the [link](https://www.google.com/url?q=https%3A%2F%2Fdrive.google.com%2Ffile%2Fd%2F1ws6fnkXjbEINK-id-IuU4vZlTKiUDYDg%2Fview%3Fusp%3Dsharing) and upload to your google drive (Remember the path and update the same in the colab file).
2. Download the ImageNet class list available in the [link](https://www.google.com/url?q=https%3A%2F%2Fdrive.google.com%2Ffile%2Fd%2F1TfR3LfjbDYC8TN-KO1Tg34TtiFSUT4EL%2Fview%3Fusp%3Dsharing) and upload to your google drive (Remember the path and update the same in the colab file).
3. Now open the [colab file](compare_ImageNetModels.ipynb) and click on "Open in Colab" option.
4. Follow the instructions in the file and complete the home work listed at the end.

# Part 2: Tranfer learning, where you will try retrain a ResNet-50 model pretrained with ImageNet dataset (part of the torchvision models) with the [CUB-200-2011 dataset](https://www.vision.caltech.edu/datasets/cub_200_2011/)
Please follow the below steps
1. Download the customized CUB-200-2011 dataset (already made the train-test split) available in the [link](https://www.google.com/url?q=https%3A%2F%2Fdrive.google.com%2Ffile%2Fd%2F1pt1BcNDcJsEp7QLJgPqGLkuVXy5GeUPw%2Fview%3Fusp%3Dsharing) and upload to your google drive (Remember the path and update the same in the colab file).
2. Now open the [colab file](transfer_learning.ipynb) and click on "Open in Colab" option.
4. Follow the instructions in the file and complete the home work listed at the end.

# Part 3: Explain the trained models through feature visualization (Introducing forward backward hooks in Pytorch, visualize the filters, outputs, activation and understand Grad-CAM, Saliency Map etc)
Please follow the below steps
1. Follow step 1 in part 2 in case you haven't done so (Not ideal though!)
2. Now open the [colab file](model_explainability.ipynb) and click on "Open in Colab" option.
3. Follow the instructions in the file and complete the home work listed at the end.

# References:
- [CUB-200-2011 dataset](https://www.vision.caltech.edu/datasets/cub_200_2011/)
- [ImageNetSamples](https://github.com/EliSchwartz/imagenet-sample-images)
- [Jacob Gil's pytorch-gradcam](https://jacobgil.github.io/pytorch-gradcam-book/introduction.html)
- [Ben Trevett's Pytroch Image Classification](https://github.com/bentrevett/pytorch-image-classification/tree/master)
- [Getting hooked with PyTorch and Grad-CAM](https://www.kaggle.com/code/noobiedatascientist/getting-hooked-with-pytorch-and-grad-cam)
