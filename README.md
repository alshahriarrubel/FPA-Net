# FPA-Net-Frequency-guided-Position-based-Attention-Network-for-Land-Cover-Image-Segmentation
Official Code for [FPA-Net: Frequency-Guided Position-Based Attention Network for Land Cover Image Segmentation](https://www.worldscientific.com/doi/10.1142/S0218001423540150)
<br>
<br>
<img width="1037" alt="framework" src="https://github.com/alshahriarrubel/FPA-Net-Frequency-guided-Position-based-Attention-Network-for-Land-Cover-Image-Segmentation/assets/24860187/4d1d77f5-c729-4cb8-b882-3eb0ff321490">


# Dependencies
* pytorch-lightning
* segmentation-models-pytorch
* albumentations
* torchinfo
* pandas
* matplotlib
* torch-dct
* sklearn

# Dataset 
We have used 3 datasets. Sample image and corresponding mask and RGB color code for each dataset are given below. <br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **[Deep Globe](https://arxiv.org/abs/1805.06561)** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **[GID-15](https://www.sciencedirect.com/science/article/pii/S0034425719303414?casa_token=UhnnRM5Ty0gAAAAA:LHEtKcxKMcDBKJUtU3r2LZqNpko8El23c6xQTU05c4sM_MMhV54k6O1b09Oj_qidGrLBzRtlAsE)** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**[Land Cover AI](https://openaccess.thecvf.com/content/CVPR2021W/EarthVision/papers/Boguszewski_LandCover.ai_Dataset_for_Automatic_Mapping_of_Buildings_Woodlands_Water_and_CVPRW_2021_paper.pdf)** <br>
<img width="30%" alt="deepglobe_sample" src="https://github.com/alshahriarrubel/FPA-Net-Frequency-guided-Position-based-Attention-Network-for-Land-Cover-Image-Segmentation/assets/24860187/4a0378da-6fc9-4f56-abd5-2036810c29ce"> &nbsp;&nbsp;<img width="30%" alt="gid-15_sample" src="https://github.com/alshahriarrubel/FPA-Net-Frequency-guided-Position-based-Attention-Network-for-Land-Cover-Image-Segmentation/assets/24860187/1e7c3c07-e4e1-47f6-98d4-ea301725a70f">
 &nbsp;&nbsp;<img width="30%" alt="landcoverai_sample" src="https://github.com/alshahriarrubel/FPA-Net-Frequency-guided-Position-based-Attention-Network-for-Land-Cover-Image-Segmentation/assets/24860187/07831825-82b0-4bc1-a50f-229471e758e1">


 <br>
<img width="30%" alt="Screenshot 2023-10-14 at 3 53 15 PM" src="https://github.com/alshahriarrubel/FPA-Net-Frequency-guided-Position-based-Attention-Network-for-Land-Cover-Image-Segmentation/assets/24860187/0f2a141a-6271-4fae-8814-efa2d041db6e">&nbsp;&nbsp; <img height="205" width="30%" alt="Screenshot 2023-10-14 at 4 19 31 PM" src="https://github.com/alshahriarrubel/FPA-Net-Frequency-guided-Position-based-Attention-Network-for-Land-Cover-Image-Segmentation/assets/24860187/c91fc422-22c2-48f1-910b-e5206cb0c3ba">&nbsp;&nbsp; <img width="30%" alt="Screenshot 2023-10-14 at 4 19 14 PM" src="https://github.com/alshahriarrubel/FPA-Net-Frequency-guided-Position-based-Attention-Network-for-Land-Cover-Image-Segmentation/assets/24860187/6a5fb7f1-70b6-4742-8c84-ed28aa614cbd">

# Notebook Sections
* Dataset Preparation
* Model Preparation (Before Training)
* Start Training (DeepGlobe Dataset)
* Start Testing
* Evaluate the model with single image from test dataset
* Evaluate the model with a random image
* Save Figures

# How to run
* Download this repository and upload to Google Drive
* Open the FPANet_DeepGlobe.ipynb file in Google Colab
* Change the directory for data based on where your data are stored
* Run the .ipynb file

# Visualization
<img width="92%" alt="visualization" src="https://github.com/alshahriarrubel/FPA-Net-Frequency-guided-Position-based-Attention-Network-for-Land-Cover-Image-Segmentation/assets/24860187/83c5edb8-84de-4305-bd6e-181c21a34b8b">


# Citation (Please cite the following research paper)
Rubel, Al Shahriar, and Frank Y. Shih. "FPA-Net: Frequency-guided Position-based Attention Network for Land Cover Image Segmentation." International Journal of Pattern Recognition and Artificial Intelligence (2023).

