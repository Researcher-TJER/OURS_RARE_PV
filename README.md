We have uploaded the code to GitHub. In the test_images folder, you will find the images used in Figure 13, which have been annotated with ground truth. 
The test_results folder contains code for generating the confusion matrix, the model's performance results in pkl format, and the validation data processed in COCO format (json file). 
Additionally, this folder includes the trained model files. OURS_RARE PV.pth contains the model from the training process, while OURS_RARE PV_reduced.pth is used for testing, having removed the contrast head and additional FC branches, and applied structure reparameterization to the weights. 
The size of OURS_RARE PV_reduced.pth is consistent with the TFA model, as the contrast head and additional FC branches are only used during the training stage. We have also provided a requirements.txt file to specify the packages and versions that the project depends on.

The link for test_results on Baidu Netdisk is: https://pan.baidu.com/s/11JxiYZPpI9X1lT_I7xVTew?pwd=x5em
The link for data on Baidu Netdisk is: https://pan.baidu.com/s/1lDe_meTsJIEv5nxA30jDKw?pwd=8bkw
