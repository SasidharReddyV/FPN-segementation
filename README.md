# FPN-segementation

1.Clone segmentatin_models_pytorch git repo from https://github.com/qubvel/segmentation_models.pytorch

2.Install all the necessary modules

3.create a child class of torch.utils.data.Dataset to get process the image and split the train/val data sets

4.change the image format from HWC -> CHW and load the train,valid and test data loaders

5. expand the dimension of the mask/label to 1HW

# create a model class and fit the data using trainer 




