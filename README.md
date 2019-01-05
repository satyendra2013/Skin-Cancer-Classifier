# Skin-Cancer-Classifier
This is initial work Satyendra Pandit. This project is created as side project for Facebook's PyTorch Challenge Scholarship 2018/19.

How to run this note book.
1. Download the restructured HAM10000 skin cancer dataset from below Google Drive link.
https://drive.google.com/open?id=1hO42zUHH6AJeWfvFacbCieiChZ72VGUv
 & Upload the Cancer folder into drive which comprises of train_dir, val_dir, test_dir, can_to_name.json & cancer_classifier_checkpointV1.pth.

2. Mount the drive correctly then you can able to access dataset.
3. Mention the path of data_dir as data_dir = 'drive/My Drive/Cancer' in "Data Augmentation Step",
4. After successful training, save the checkpoint. Here, I have saved the checkpoint as "cancer_classifier_checkpointV1.pth".
5. Load the checkpoint and rebuild the model again. 
6. Now, in Sanity Check, you can change the path of image to see the prediction.
#Give image path
image_path = 'drive/My Drive/Cancer/test_dir/6/ISIC_0024309.jpg' #Change path of image to get different image.

Here is a small prototype of final skin cancer classifier app. !(https://share.proto.io/LPE8ES/)
