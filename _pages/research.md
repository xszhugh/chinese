---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
The complete project list is [<font color='blue'>here</font>](https://xszhugh.github.io/files/projects.pdf "Projects").  

<!--## [<font color='blue'>Robust image watermarking</font>](https://github.com/academicpages/academicpages.github.io "Image watermarking")--> 
<!--## [<font color='blue'>Robust video watermarking</font>](https://github.com/academicpages/academicpages.github.io "Video watermarking") -->  
<!--## [<font color='blue'>Fast patch matching</font>](https://github.com/academicpages/academicpages.github.io "Patch matching") -->  
<!--## [<font color='blue'>Compressed sensing</font>](https://github.com/academicpages/academicpages.github.io "compressed sensing") -->  
<!--## [<font color='blue'>Inpainting forensics</font>](https://xszhugh.github.io/_pages/inpainting-forensics.md "Forensics")  --> 
<!--## [<font color='blue'>DNA data processing</font>](https://github.com/academicpages/academicpages.github.io "DNA")  -->
## <font color='blue'>Robust image watermarking</font>
## <font color='blue'>Robust video watermarking</font>
## <font color='blue'>Fast patch matching</font>
## <font color='blue'>Compressed sensing</font>
## <font color='blue'>Inpainting forensics</font>
### A deep learning approach to patch-based image inpainting forensics
[[paper](https://www.sciencedirect.com/science/article/pii/S0923596518305344)] [source code] [dataset] 
<!--[Experimental results]-->
#### Background   
Although image inpainting is now an effective image editing technique, limited work has been done for inpainting forensics. The main drawbacks of the conventional inpainting forensics methods lie in the difficulties on inpainting feature extraction and the very high computational cost.   
![inpainting-application](https://xszhugh.github.io/images/inpainting-application.png)
<font color='blue'>Fiugre 1 Inpainting applications: scratch or text removal, recovery of missing blocks, object removal </font>
#### Main contribution   
The main contribution of this paper is as follows. First, CNNs tend to learn features to represent the image content rather than the manipulation information. To solve this problem, we construct a class label matrix for an image instead of a single label to provide more supervisory information for the training process. Second, the inpainted pixels are usually much less than the uninpainted ones, causing the imbalance between the positive and negative sample data. For this problem, we design the weighted cross-entropy as the loss function for the training. Last, the CNN is built following the encoder–decoder network, which allows to predict the inpainting probability for each pixel in an image. 
![cnn-forensics](https://xszhugh.github.io/images/cnn-forensics.png)
<font color='blue'>Fiugre 2 The layout, architecture and parameter settings of the CNN for inpainting forensics </font>
### Experimental results
By the established CNN, inpainting forensics does not need to consider feature extraction and classifier design, and use any postprocessing as in conventional forensics methods. They are combined into the unique framework and optimized simultaneously. Experimental results show that the proposed method achieves superior performance in terms of true positive rate, false positive rate and the running time, as compared with state-of-the-art methods for inpainting forensics, and is very robust against JPEG compression and scaling manipulations.  
![figure3](https://xszhugh.github.io/images/cnn-forensics-results.png)  
<font color='blue'>Fiugre 3 The uninpainted images with the missing regions (marked in green) and different removing ratioes, the inpainted images (2st row) and the corresponding tampered region detection results obtained by the methods proposed in [13] (3rd row) and [14] (4th row), and our CNN (5th row). </font>  
<font color='blue'>Table 1 Comparing TPR (%), FPR (%) and AP (%) of Refs. [13,14] and the proposed method. </font>
![table](https://xszhugh.github.io/images/cnn-forensics-table1.png)  
<font color='blue'>Table 2 Comparing TPR (%), FPR (%) and AP (%) of the CNN with the loss function being WCEL and ACEL respectively. </font>
![table](https://xszhugh.github.io/images/cnn-forensics-table2.png)  

## <font color='blue'>DNA data processing</font>
