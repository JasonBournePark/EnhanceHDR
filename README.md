

# EnhanceHDR
Generation of High Dynamic Range Illumination from a Single Image  for the Enhancement of Undesirably Illuminated Images


## Abstract

This paper presents an image enhancement method for undesirably illuminated images,
which is basically a single image high dynamic range (HDR) imaging method.
The input image is first decomposed into illumination and reflectance components by 
using an edge-preserving smoothing filter. Then, the reflectance component is scaled up 
to improve the image details in bright areas. Simultaneously, the illumination 
component is scaled up and down to generate several illumination images
that correspond to certain camera exposure values different from the
original. These illuminations are combined with the enhanced reflectance,
which generates pseudo multi-exposure images. Finally, a detail-enhanced and 
illumination-equalized image is constructed by employing a tone fusion 
method that blends the multi-exposure images, where we also
propose a method to generate appropriate weight maps for our
pseudo multi-exposure images.


<p align="center">
<img src="/Paper_Images/Figure1_block_diagram.png" width="700"> 
</p>


## Experimental Results

#### Test images of backlighting conditions
<p align="center">
<img src="/Paper_Images/Figure_Exp_Rst_BL1.png" width="700"> 
<img src="/Paper_Images/Figure_Exp_Rst_BL2.png" width="700"> 
</p>

##### Results for the image.From top left to bottom right: input image, result of CLAHE, CVC, MSR, FbEM,	LIME, NPEA and proposed method.

#### Test images of low light conditions
<p align="center">
<img src="/Paper_Images/Figure_Exp_Rst_Low1.png" width="700"> 
<img src="/Paper_Images/Figure_Exp_Rst_Low2.png" width="700"> 
</p>
##### Results for the image. From top left to bottom right: input image, result of CLAHE, CVC, MSR, FbEM,	LIME, NPEA and proposed method.

#### Test images of low light conditions
<p align="center">
<img src="/Paper_Images/Figure_Exp_Rst_NonUni.png" width="700"> 
</p>
##### Results for the image. From top left to bottom right: input image, result of CLAHE, CVC, MSR, FbEM,	LIME, NPEA and proposed method.

