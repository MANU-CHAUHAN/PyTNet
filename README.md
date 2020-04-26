# PyTNet
A deep neural net Libraby Built on top of Pytorch

## **File Structure**

1. **Modles** - Contains the dnn models
   * NewResnetModel.py - Dawnbench mark 2019 winners model
   * QuizModel.py - Dense Net 
   * ResNetModel.py - Resnet 
   * S7Model.py - custom model
   
2. **Albumentation transforms** - Used for Image Agumentations. It is from Albumentations library.

3. **GradCam** - Implements gradCam of the given images and specified layer of the model.

4. **LrFinder** - It finds the Lr of given range.

5. **LR_Range_test** - It finds the best Lr for One Cyce Policy

6. **evaluate** - It evaluates the final test accuracy, classwise accuracy, plots the given curves, gives misclassified inages and plots misclassified images, 

7. **show_images** - Plots the given images of tensor for. Mainly used to visualise the train data.

8. **tinyimagenet** - It downloads the tiny imagenet data, mix train-test, split into the given ratio and returns train and test set of type dataset.

9. **train_test** - Used to train the model.

10. **train_test_loader** - takes the train test data of type dataset, converts into data loader form, set the seed, check for the cuda availability.
