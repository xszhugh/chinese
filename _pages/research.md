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
Although image inpainting is now an effective image editing technique, limited work has been done for inpainting
forensics. The main drawbacks of the conventional inpainting forensics methods lie in the difficulties on
inpainting feature extraction and the very high computational cost. In this paper, we propose a novel approach
based on a convolutional neural network (CNN) to detect patch-based inpainting operation. Specifically, the CNN
is built following the encoder–decoder network structure, which allows us to predict the inpainting probability
for each pixel in an image. To guide the CNN to automatically learn the inpainting features, a label matrix
is generated for the CNN training by assigning a class label for each pixel of an image, and the designed
weighted cross-entropy serves as the loss function. They further help to strongly supervise the CNN to capture the
manipulation information rather than the image content features. By the established CNN, inpainting forensics
does not need to consider feature extraction and classifier design, and use any postprocessing as in conventional
forensics methods. They are combined into the unique framework and optimized simultaneously. Experimental
results show that the proposed method achieves superior performance in terms of true positive rate, false positive
rate and the running time, as compared with state-of-the-art methods for inpainting forensics, and is very robust
against JPEG compression and scaling manipulations.  
## <font color='blue'>DNA data processing</font>
