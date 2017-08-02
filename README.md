

# EnhanceHDR
Generation of High Dynamic Range Illumination from a Single Image for the Enhancement of Undesirably Illuminated Images
<br><br>

# Progress and status of this paper to be publish as an Journal
- 2017.07.31 - Submitted.
- 2017.08.02 - The full version of this paper will be disclosed at arXiv.org (Processing...)

<br><br>

## Abstract

This paper presents an algorithm that enhances undesirably illuminated images by generating and fusing multi-level illuminations from a single image. The input image is first decomposed into illumination and reflectance components by using an edge-preserving smoothing filter. Then the reflectance component is scaled up to improve the image details in bright areas. The illumination component is scaled up and down to generate several illumination images that correspond to certain camera exposure values different from the original. The virtual multi-exposure illuminations are blended into an enhanced illumination, where we also propose a method to generate appropriate
weight maps for the tone fusion. Finally, an enhanced image is obtained by multiplying the equalized illumination and enhanced reflectance. Experiments show that the proposed algorithm produces visually pleasing output and also yields comparable objective results to the conventional enhancement methods, while requiring modest computational loads.

<br><br>
<br><br>

## Related Works
##### [NPEA] Naturalness Preserved Enhancement Algorithm for Non-Uniform Illumination Images <paper-button> <a href="http://ieeexplore.ieee.org/document/6512558/">Link</a> </paper-button>
##### [FbEM] A fusion-based enhancing method for weakly illuminated images <paper-button> <a href="http://www.sciencedirect.com/science/article/pii/S0165168416300949">Link</a> </paper-button>
##### [LIME] LIME: Low-Light Image Enhancement via Illumination Map Estimation <paper-button> <a href="http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7782813">Link</a> </paper-button>
<br><br>
<br><br>

## Experimental Results

#### Result #1 for test images of backlighting conditions
<p align="center">
<img src="/Paper_Images/Figure_Exp_Rst_BL1.png" width="700"> 
<img src="/Paper_Images/Figure_Exp_Rst_BL2.png" width="700"> 
</p>

##### [Results for the image.From top left to bottom right: input image, result of CLAHE, CVC, MSR, FbEM,	LIME, NPEA and proposed method.]

#### Result #2 for test images of low light conditions
<p align="center">
<img src="/Paper_Images/Figure_Exp_Rst_Low1.png" width="700"> 
<img src="/Paper_Images/Figure_Exp_Rst_Low2.png" width="700"> 
</p>

##### [Results for the image. From top left to bottom right: input image, result of CLAHE, CVC, MSR, FbEM,	LIME, NPEA and proposed method.]

#### Result #3 for a test image of low light conditions
<p align="center">
<img src="/Paper_Images/Figure_Exp_Rst_NonUni.png" width="700"> 
</p>

##### [Results for the image. From top left to bottom right: input image, result of CLAHE, CVC, MSR, FbEM,	LIME, NPEA and proposed method.]

