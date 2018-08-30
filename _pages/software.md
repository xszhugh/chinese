---
layout: archive
permalink: /software/
author_profile: true
---
<!--## [<font color='blue'>Robust image watermarking</font>](https://github.com/academicpages/academicpages.github.io "Image watermarking")--> 
<!--## [<font color='blue'>Robust video watermarking</font>](https://github.com/academicpages/academicpages.github.io "Video watermarking") -->  
<!--## [<font color='blue'>Fast patch matching</font>](https://github.com/academicpages/academicpages.github.io "Patch matching") -->  
<!--## [<font color='blue'>Compressed sensing</font>](https://github.com/academicpages/academicpages.github.io "compressed sensing") -->  
<!--## [<font color='blue'>Inpainting forensics</font>](https://xszhugh.github.io/_pages/inpainting-forensics.md "Forensics")  --> 
<!--## [<font color='blue'>DNA data processing</font>](https://github.com/academicpages/academicpages.github.io "DNA")  -->
## <font color='blue'>鲁棒图像水印</font>
### 国家数字图书馆多媒体内容版权保护系统
#### 软件信息
软件界面  
<img src="https://xszhugh.github.io/images/national-digital-library.png" width="60%"  />   
<font color='blue'>图1 多媒体内容版权保护系统软件界面   </font>
软件大小： 3788KB  
运行平台： Windows  
开发语言： c and c++  
#### 功能描述
核心的数字水印算法被做成动态链接库供主程序使用。该系统能实现在图像、音频和视频中嵌入和检测水印信息，支持多种文件格式，主要有bmp、jpg、tif、avi、MPEG1、MPEG2和wav等。该系统从三个层次上管理多媒体内容：ⅰ）通过可视水印和不可视水印嵌入版权拥有者的标识，实现版权保护；ⅱ）通过嵌入脆弱水印防止内容被非法篡改；ⅲ）通过传统的加密技术，防止关键信息被非法获取。 

### 面向安卓系统的鲁棒水印软件  
#### 软件信息  
软件界面  
<img src="https://xszhugh.github.io/images/mobile-watermarking.png" width="30%"  />   
<font color='blue'>图2 安卓系统鲁棒水印软件界面   </font>
软件大小： 87KB  
运行平台： Win CE  
开发语言： c and c++  
####  功能描述
嵌入水印时，在操作界面内输入目标图像的完整路径、水印信息和密钥，由水印嵌入模块将水印信息嵌入到目标图像中。检测水印时，在操作界面内输入目标图像的完整路径和水印密钥，通过水印检测模块提取水印信息并显示出来。
本系统可直接运行在终端设备上，保护数字图像的版权，并可扩展用于保密通信、数字指纹、拷贝控制以及广播监视等。

###  基于数字水印的国家图书馆文物、文艺图片版权保护系统  
#### 软件信息  
软件界面   
<img src="https://xszhugh.github.io/images/cultural-watermarking.png" width="60%"  />   
<font color='blue'>图3 文物图像水印软件界面   </font>
运行平台： Windows  
开发语言： c and c++  
#### 功能描述
主要解决大尺度文物图像（见图4）的水印嵌入和检测问题，其操作界面如图3所示，数字水印核心算法被做成动态链接库供主程序调用。该算法具有三个典型特征：ⅰ）在信号的变换域中嵌入水印，但整个水印嵌入过程只需对载体信号进行一次逆变换，大大降低了水印复杂度；ⅱ）在图像空间域中自适应的调整水印嵌入强度，特别适合有残损或形状不规则文物的图像，例如，出土的古人服饰、壁画，以及古代碑文图片；ⅲ）利用基于图像矩的图像快速归一化技术，提升水印对几何攻击的鲁棒性。该方案已成功应用于“国家图书馆文物、文艺图片版权保护系统”。  
<img src="https://xszhugh.github.io/images/cultural-images.png" width="80%"  />   
<font color='blue'>图4 原始的和加水印后的文物图像示例  </font>

### <font color='blue'>鲁棒视频水印技术</font>
### 面向全国电视剧备案管理系统的多位鲁棒视频水印技术
#### 软件信息  
软件界面  
<img src="https://xszhugh.github.io/images/video-watermarking.png" width="60%"  />   
<font color='blue'>图5 鲁棒视频水印软件界面   </font>
运行平台： Windows  
开发语言： c and c++  
#### 功能描述
用于“全国电视剧备案管理系统”，实现对电视剧版权或来源的检测。该方案结合了Trellis code、三维小波变换、基于affine modular transformation的置乱算法，以及基于随机归一化相关系数的量化调制等技术，其主要特点是在严格的理论分析和Monte Carlo仿真实验的基础上设定水印嵌入率和鲁棒性的相关参数，水印检测是盲检测，而且无须输入水印嵌入强度信息，可以实现在视频信号中隐藏多位水印信息，并满足人眼不可感知性，对视频编码、转码、Gamma校正、噪声、滤波等操作具有良好的鲁棒性。  
<img src="https://xszhugh.github.io/images/video-watermarking-process.png" width="80%"  />   
<font color='blue'>图5 多位视频水印嵌入过程  </font>
<!--title: "软件系统"-->
