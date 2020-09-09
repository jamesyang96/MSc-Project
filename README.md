# MSc-Project
It's for MSc Project on robotic simulation and neural networks.


Jupyter notebook 'MScProject_KukaGrasping.ipynb' is the main part of the project. It contains pybullet environment setting, image generation, VAE training, and regression model training.

Jupyter notebook 'MScProject_KukaGrasping.ipynb' is the data processing pipeline using the trained VAE and regression model. In this notebook, the arm can automatically grasp object.

Folder 'VAE_Loss_Fixed' contains the training loss arrays for VAE using fixed camera target position RGB images, using latent space 128, 256, 512 and 1024.

Folder 'VAE_Loss_Change_128' contains the training loss array for VAE using changeable camera target position RGB images. This folder and folder 'VAE_Loss_Fixed' are used to select image generation method and latent space dimension.

Folder 'VAE_result_RGB_v3_BasedOn7OriImg', 'VAE_result_DepthImg_v1', and 'VAE_result_RGBD_v1' contain the RGB, Depth and RGBD version VAE result respectively. Models use changeable camera target image to train and latent space dimension is 128.

Folder 'regressionResult' contains the trained regression model result for RGB, depth and RGBD version and the training loss.

