# Image-Segmentation-on-Indian-Driving-Dataset-using-pytorch-

- Predicted image segmentation masks Using [Pretrained DeepLabV3Plus-Pytorch](https://github.com/VainF/DeepLabV3Plus-Pytorch/tree/master) for [Indian Driving Dataset](https://idd.insaan.iiit.ac.in/)
- Compared predicted masks and true masks using various segmentation metrics such as IoU, Pixelwise Accuracy, Dice Score and finally calculating Recall and precision

The following show a few examples of given input images and their respective true maks (which have been color coded according to provided maps in their documentation)
![alt text](https://github.com/AbhayChowdhry/Image-Segmentation-on-Indian-Driving-Dataset-using-pytorch-/blob/main/media/img_label.png)


A color mapping transformation is required since the color map used for IDD is different from Cityscape (on which Deeplabv3plus is trained), the transformation makes the output colors from the cityscape prediction, match those in IDD.
![alt text](https://github.com/AbhayChowdhry/Image-Segmentation-on-Indian-Driving-Dataset-using-pytorch-/blob/main/media/pred.png)

