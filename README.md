# Improving-Accuracy-of-Liquid-Based-Pap-Test-Diagnosis-using-Pre-trained-CNN-Models-and-Fine-Tuning-T

This project is based on the classification of cancer cell images into 4 different types using transfer learning, as:
* Negative intraepithelial lesion (NIL).
* Low-grade squamous intraepithelial lesion (LSIL). 
* High-grade squamous intraepithelial lesion (HSIL).
* Squamous cell carcinoma (SCC).
The trainings were performed in Google Colab in its free version. 
The steps that were followed are:
1. Obtain the  [dataset](https://drive.google.com/drive/folders/1tzuhemvmCR94rbQK4_CZd_HoEq_mJQLU?usp=share_link).
2. Use transfer learning with different pre-trained architectures, such as EfficientNetB3, ResNet152, DenseNet201, and VGG19, on a large dataset such as ImageNet. Then adapt the top head to obtain the 4 outputs of the required classes, in addition to using the dataset from step 1.
3. Rename the different architectures on the .............. line of the .................. document to get the architecture that has the best performance.
4. Once the best performing architecture has been identified, the next step is to perform the fine-tuning with the different parameters specified in .......................
