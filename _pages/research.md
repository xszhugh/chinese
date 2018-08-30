---
layout: archive
title: "学术研究"
permalink: /research/
author_profile: true
---
完整的项目列表[<font color='blue'>下载</font>](https://xszhugh.github.io/files/projects.pdf "Projects").  

### Robust Double Domain Watermarking for Binary Document Image 
[[paper](http://cjc.ict.ac.cn/online/onlinepaper/zxs-2014615143525.pdf)] [source code] [dataset] 
#### Background   
With the rapid development of electronic publishing industry, more and more documents are stored and transmitted in binary image format. Since digital document is easy to copy and edit, the copyright protection becomes an urgent issue. As such a promising technique, binary document image watermarking is always one of the active research topics in multimedia security area, and attracts more and more attention.   
#### Watermark embedding and decoding  
The watermark patterns are generated as signals in the discrete cosine transform (DCT) domain, and modulated with the embedded message. The modulated signal is then transformed into the spatial domain and adapted to the characteristics of human visual system by adjusting the localized embedding strengths before embedding. Watermark extractions can be performed by applying a correlation based detector in either of the two domains. The effects of perceptually shaping and the number of the flipped pixels on watermark decoding are also analyzed carefully. The DDW method is combined with an image normalization procedure, which is developed particularly for document image through skew detection and character segmentation, in order to resist synchronization distortions.  
<img src="https://xszhugh.github.io/images/ddw-geo.png" width="80%"  />   
<font color='blue'>Figures 1 The process for image normalization: Hough transform, projection in row and column (left, middle and right in 1st row), original image, word segment and normalized image (left, middle, right in 2nd row).   </font> 
<img src="https://xszhugh.github.io/images/ddwemb.png" width="60%"  />   
<font color='blue'>Figures 2 The process for watermark generation and embedding.   </font> 
<img src="https://xszhugh.github.io/images/ddwdec.png" width="60%"  />   
<font color='blue'>Figures 3 Watermark extration process.   </font> 
### Experimental results  
The experimental results show that the presented scheme manifests the good robustness against common image manipulations, geometrical attacks as well as print-scan process.  
<img src="https://xszhugh.github.io/images/ddw-ber.png" width="80%"  />   
<font color='blue'>Figures 4 Robustness comparisons for different types of attacks: Gaussian noise, pepper-salt noise, low-pass filtering, image rotation, and image scaling (from left to right).   </font> 
<img src="https://xszhugh.github.io/images/ddw-sign.png" width="80%"  />   
<font color='blue'>Figures 5 Robustness evaluation with a watermark sign: origian watermark sign and the attacked document images (from left to right in 1st row), the extracted watermark by Wu [8] (2nd row), by Qi [9] (3rd row), and by DDW (last row).   </font> 


### Normalized Correlation-Based Quantization Modulation for Robust Watermarking
[[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6860239)] [source code] [dataset] 
#### Background   
The security of digital information becomes an important concern in the digital multimedia era. As such a promising technique, digital watermarking is always one of the active research topics in the multimedia area. Watermarking has many other applications, including copyright protection, access control, authentication, broadcast monitoring, traitor tracing, covert communication, etc.  
<!--<img src="https://xszhugh.github.io/images/ncqm-framework.png" width="300" height="120" alt="CSDN图标" />-->
<!--![image](https://xszhugh.github.io/images/ncqm-principle.png=200*200)-->
<!--![image](https://xszhugh.github.io/images/ncqm-principle.png?imageView/1/w/225/q/45)  -->
<!--<center>-->
<!--<img src="https://xszhugh.github.io/images/ncqm-principle.png" width="25%" height="25%" />-->
<!--$ $-->
<!--Figure 1. Lena-->
<!--</center>-->
#### NC-based quantization modulation (NCQM)  
A feature signal is obtained by computing the normalized correlation (NC) between the host signal $\vec{x}$ and a random signal $\vec{u}$. Information modulation is carried out on the generated NC by selecting a codeword from the codebook associated with the embedded information. The watermarked signal is produced to provide the modulated NC in the sense of minimizing the embedding distortion.  
<!--<div style="float:left;border:solid 1px 000;margin:2px;"><img src="https://xszhugh.github.io/images/ncqm-framework.png" width="20%" /></div>-->
<!--<div style="float:left;border:solid 1px 000;margin:2px;"><img src="https://xszhugh.github.io/images/ncqm-principle.png" width="20%" /></div>  -->
<!--<div style="clear:both;"></div>-->

<figure class="half">
<a href="https://xszhugh.github.io/images/ncqm-framework.png"><img src="https://xszhugh.github.io/images/ncqm-framework.png" width="60%" ></a>&emsp;&emsp;&emsp;&emsp;<a href="https://xszhugh.github.io/images/ncqm-principle.png" ><img src="https://xszhugh.github.io/images/ncqm-principle.png" width="20%"  ></a>  
</figure>    
<!--![image](https://xszhugh.github.io/images/ncqm-principle.png)-->  

<font color='blue'>Figures 1 and 2 The basic watermarking model (left) and a geometric interpretation of watermark embedding and removal (right).   </font>   

### Experimental results  
Numerical simulations on artificial signals confirm the validity of our analyses and exhibit that NCQM achieves the performance closer to the lower bound by decreasing DWR. Simulations on real images show that the proposed NCQM not only achieves the improved watermark imperceptibility and a higher embedding capacity in high-noise regimes, but also is more robust to a wide range of attacks, e.g., valumetric scaling, Gaussian filtering, additive noise, Gamma correction, and Gray-level transformations, as compared with the state-of-the-art watermarking methods.  
<!--![image](https://xszhugh.github.io/images/ncqm-pevswnr.png)-->
<!--![image](https://xszhugh.github.io/images/ncqm-real-images.png)-->
<!--![image](https://xszhugh.github.io/images/ncqm-robust1.png)-->
<!--![image](https://xszhugh.github.io/images/ncqm-robust2.png)-->
<!--![image](https://xszhugh.github.io/images/ncqm-robust3.png)![image](https://xszhugh.github.io/images/ncqm-robust4.png)-->
<!--![image](https://xszhugh.github.io/images/ncqm-robust6.png)![image](https://xszhugh.github.io/images/ncqm-robust5.png)-->
<img src="https://xszhugh.github.io/images/ncqm-pevswnr.png" width="80%"  />  
<font color='blue'>Figure 3 Theoretical bit-error probability versus WNR for LBM, STDM, QP as 
well as NCQM and the performance lower bound proposed in [28].   </font>   
<img src="https://xszhugh.github.io/images/ncqm-real-images.png" width="80%" />   
<font color='blue'>Figure 4 The original images (first and third columns) and corresponding watermarked
copies using the NCQM method with a 128-bit message embedded and dB (second and fourth columns).   </font>     

<font color='blue'>Table 1 COMPARING BER (%) OF NCQM, RDM [14], STDM [6], AND ZAREIAN’S METHOD [20] UNDER DIFFERENT TYPES OF ATTACKS (MESSAGE LENGTH = 192 BITS, MSSIM=0.9939).   </font>  
<img src="https://xszhugh.github.io/images/ncqm-robust1.png" width="80%"  />    
<font color='blue'>Table 2 COMPARING BER (%) OF NCQM, RDM [14], STDM [6], AND ZAREIAN’S METHOD [20] UNDER NOISING AND FILTERING ATTACKS (MESSAGE LENGTH = 192 BITS, MSSIM=0.9939).   </font>  
<img src="https://xszhugh.github.io/images/ncqm-robust2.png" width="80%"  />   

<font color='blue'>Table 3 COMPARING BER (%) OF OUR METHOD AND THE METHODS IN [10], [12], [16] AND [18] UNDER DIFFERENT TYPES OF ATTACKS (MESSAGE LENGTH = 192 BITS, MSSIM=0.9939).   </font>   
<figure class="half">
<a href="https://xszhugh.github.io/images/ncqm-robust3.png"><img src="https://xszhugh.github.io/images/ncqm-robust3.png" width="33%" ></a>&emsp;&emsp;&emsp;&emsp;<a href="https://xszhugh.github.io/images/ncqm-robust4.png" ><img src="https://xszhugh.github.io/images/ncqm-robust4.png" width="33%"  ></a>  
</figure>    

<font color='blue'>Table 4 COMPARING BER (%) OF OUR METHOD AND THE METHODS IN [17] AND [36] UNDER DIFFERENT TYPES OF ATTACKS (MESSAGE LENGTH = 192 BITS, MSSIM=0.9939).   </font>   
<figure class="half">
<a href="https://xszhugh.github.io/images/ncqm-robust6.png"><img src="https://xszhugh.github.io/images/ncqm-robust6.png" width="33%" ></a>&emsp;&emsp;&emsp;&emsp;<a href="https://xszhugh.github.io/images/ncqm-robust5.png" ><img src="https://xszhugh.github.io/images/ncqm-robust5.png" width="33%"  ></a>  
</figure>  

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
<font color='blue'>Figure 1 Inpainting applications: scratch or text removal, recovery of missing blocks, object removal </font>
#### Main contribution   
The main contribution of this paper is as follows. First, CNNs tend to learn features to represent the image content rather than the manipulation information. To solve this problem, we construct a class label matrix for an image instead of a single label to provide more supervisory information for the training process. Second, the inpainted pixels are usually much less than the uninpainted ones, causing the imbalance between the positive and negative sample data. For this problem, we design the weighted cross-entropy as the loss function for the training. Last, the CNN is built following the encoder–decoder network, which allows to predict the inpainting probability for each pixel in an image. 
![cnn-forensics](https://xszhugh.github.io/images/cnn-forensics.png)
<font color='blue'>Figure 2 The layout, architecture and parameter settings of the CNN for inpainting forensics </font>
### Experimental results
By the established CNN, inpainting forensics does not need to consider feature extraction and classifier design, and use any postprocessing as in conventional forensics methods. They are combined into the unique framework and optimized simultaneously. Experimental results show that the proposed method achieves superior performance in terms of true positive rate, false positive rate and the running time, as compared with state-of-the-art methods for inpainting forensics, and is very robust against JPEG compression and scaling manipulations.  
![figure3](https://xszhugh.github.io/images/cnn-forensics-results.png)  
<font color='blue'>Figure 3 The uninpainted images with the missing regions (marked in green) and different removing ratioes, the inpainted images (2st row) and the corresponding tampered region detection results obtained by the methods proposed in [13] (3rd row) and [14] (4th row), and our CNN (5th row). </font>  
<font color='blue'>Table 1 Comparing TPR (%), FPR (%) and AP (%) of Refs. [13,14] and the proposed method. </font>
![table](https://xszhugh.github.io/images/cnn-forensics-table1.png)  
<font color='blue'>Table 2 Comparing TPR (%), FPR (%) and AP (%) of the CNN with the loss function being WCEL and ACEL respectively. </font>
![table](https://xszhugh.github.io/images/cnn-forensics-table2.png)  

## <font color='blue'>DNA data processing</font>
