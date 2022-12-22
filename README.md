# Adversarial Patch Attacks Tensorflow

### Please open Patch_Attack_Tensorflow.ipynb where all the trainnings, reports and definitions of useful functions and classes are inside.

## Step:
1. Install the necessary packages and import libraries;
2. Please change the variable DATA_DIR to your repository where your wish to save the trainned patchs and other important data;
3. Download the image files toaster.png, peace_sign.png, tie_dye.png under your DATA_DIR
4. Execute the code of all the definition of fonctions and two classes ModelContainer and MetaModel until the part of Patch Generation
5. Execute the white box, black box trainning process, every patch and data will be saved under DATA_DIR that you define at the beginning
6. After all the trainning, execute the evaluation to see the plot of performance of the patches generated


## Attention:
1. Image and Patch size are generally (299,299,3)
2. The attack target label here is 'toaster' and you can modify it to anything you want, but make sure it's in the category of objets that the classifiers are able to recognize
3. The trainning resulte with a wider difference between SCALE_MIN and SCALE_MAX works better

## Resulte
![resulte](https://user-images.githubusercontent.com/118989703/209239620-f66d4a6d-37c2-4394-9d75-10c768a59367.png)

