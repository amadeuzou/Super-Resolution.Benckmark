# Super-Resolution.Benckmark
A curated list of super-resolution resources and a benchmark for single image super-resolution algorithms.

See my implementated super-resolution algorithms:

+ [SRGAN](https://github.com/huangzehao/torch-srgan)
+ [VDSR](https://github.com/huangzehao/caffe-vdsr)
+ [CSCN](https://github.com/huangzehao/SCN_Matlab)

## TODO
Build a benckmark like [SelfExSR_Code](https://sites.google.com/site/jbhuang0604/publications/struct_sr)

## State-of-the-art algorithms
#### Classical Sparse Coding Method
 * ScSR [[Web]](http://www.ifp.illinois.edu/~jyang29/ScSR.htm)
  * Image super-resolution as sparse representation of raw image patches (CVPR2008), Jianchao Yang et al.
  * Image super-resolution via sparse representation (TIP2010), Jianchao Yang et al.
  * Coupled dictionary training for image super-resolution (TIP2011), Jianchao Yang et al.
 
#### Anchored Neighborhood Regression Method
 * ANR [[Web]](http://www.vision.ee.ethz.ch/~timofter/ICCV2013_ID1774_SUPPLEMENTARY/index.html)
  * Anchored Neighborhood Regression for Fast Example-Based Super-Resolution (ICCV2013), Radu Timofte et al.
 * A+ [[Web]](http://www.vision.ee.ethz.ch/~timofter/ACCV2014_ID820_SUPPLEMENTARY/)
  * A+: Adjusted Anchored Neighborhood Regression for Fast Super-Resolution (ACCV2014), Radu Timofte et al.
 * IA [[Web]](http://www.vision.ee.ethz.ch/~timofter/CVPR2016_ID769_SUPPLEMENTARY/index.html)
  * Seven ways to improve example-based single image super resolution (CVPR2016), Radu Timofte et al.
 
#### Self-Exemplars
 * SelfExSR [[Web]](https://sites.google.com/site/jbhuang0604/publications/struct_sr)
  * Single Image Super-Resolution from Transformed Self-Exemplars (CVPR2015), Jia-Bin Huang et al.
 
#### Bayes
 * NBSRF [[Web]](http://jordisalvador-image.blogspot.com/2015/08/iccv-2015.html)
  * Naive Bayes Super-Resolution Forest (ICCV2015), Jordi Salvador et al.
 
#### Deep Learning Method
 * SRCNN [[Web]](http://mmlab.ie.cuhk.edu.hk/projects/SRCNN.html) [[waifu2x by nagadomi]](https://github.com/nagadomi/waifu2x)
  * Image Super-Resolution Using Deep Convolutional Networks (ECCV2014), Chao Dong et al.
  * Image Super-Resolution Using Deep Convolutional Networks (TPAMI2015), Chao Dong et al.
 * CSCN [[Web]](http://www.ifp.illinois.edu/~dingliu2/iccv15/)
  * Deep Networks for Image Super-Resolution with Sparse Prior (ICCV2015), Zhaowen Wang et al.
  * Robust Single Image Super-Resolution via Deep Networks with Sparse Prior (TIP2016), Ding Liu et al.
 * VDSR [[Web]](http://cv.snu.ac.kr/research/VDSR/) [[Unofficial Implementation in Caffe]](https://github.com/huangzehao/caffe-vdsr)
  * Accurate Image Super-Resolution Using Very Deep Convolutional Networks (CVPR2016), Jiwon Kim et al.
 * DRCN [[Web]](http://cv.snu.ac.kr/research/DRCN/)
  * Deeply-Recursive Convolutional Network for Image Super-Resolution (CVPR2016), Jiwon Kim et al. 
 * ESPCN [[PDF]](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Shi_Real-Time_Single_Image_CVPR_2016_paper.pdf)
  * Real-Time Single Image and Video Super-Resolution Using an Efficient Sub-Pixel Convolutional Neural Network (CVPR2016), Wenzhe Shi et al.
  * Is the deconvolution layer the same as a convolutional layer? [[PDF]](https://arxiv.org/ftp/arxiv/papers/1609/1609.07009.pdf)
 * FSRCNN [[Web]](http://mmlab.ie.cuhk.edu.hk/projects/FSRCNN.html)
  * Acclerating the Super-Resolution Convolutional Neural Network (ECCV2016), Dong Chao et al.

#### Perceptual Loss and GAN
 * Perceptual Loss [[PDF]](http://cs.stanford.edu/people/jcjohns/papers/eccv16/JohnsonECCV16.pdf)
  * Perceptual Losses for Real-Time Style Transfer and Super-Resolution (ECCV2016), Justin Johnson et al.
 * SRGAN [[PDF]](https://arxiv.org/abs/1609.04802)
  * Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network, Christian Ledig et al.
 * AffGAN [[PDF]](https://arxiv.org/pdf/1610.04490.pdf)
  * AMORTISED MAP INFERENCE FOR IMAGE SUPER-RESOLUTION, Casper Kaae Sønderby et al.
 * EnhanceNet [[PDF]](https://arxiv.org/abs/1612.07919)
  * EnhanceNet: Single Image Super-Resolution through Automated Texture Synthesis, Mehdi S. M. Sajjadi et al.
 * neural-enchance [[Github]](https://github.com/alexjc/neural-enhance)

#### Video SR
 * VESPCN [[PDF]](Real-Time Video Super-Resolution with Spatio-Temporal Networks and Motion Compensation)
 
## Dicussion
#### Deconvolution and Sub-Pixel Convolution
 * [Deconvolution and Checkerboard Artifacts](http://distill.pub/2016/deconv-checkerboard/)
 * [SubPixel](https://github.com/Tetrachrome/subpixel)
 

## Datasets

| Test Dataset | Image source |
|---- | ---|----|
| **Set 5** |  [Bevilacqua et al. BMVC 2012](http://people.rennes.inria.fr/Aline.Roumy/results/SR_BMVC12.html)  |
| **Set 14** |  [Zeyde et al. LNCS 2010](https://sites.google.com/site/romanzeyde/research-interests)  |
| **BSD 100** | [Martin et al. ICCV 2001](https://www.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/) |
| **Urban 100** | [Huang et al. CVPR 2015](https://sites.google.com/site/jbhuang0604/publications/struct_sr)  |

| Train Dataset | Image source |
|---- | ---|----|
| **Yang 91** |  [Yang et al. CVPR 2008](http://www.ifp.illinois.edu/~jyang29/ScSR.htm)  |
| **BSD 200** | [Martin et al. ICCV 2001](https://www.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/) |
| **General 100** | [Dong et al. ECCV 2016](http://mmlab.ie.cuhk.edu.hk/projects/FSRCNN.html) |
| **ImageNet** | [Olga Russakovsky et al. IJCV 2015](http://www.image-net.org/) |
| **COCO**| [Tsung-Yi Lin et al. ECCV 2014](http://mscoco.org/)
## Quantitative comparisons
Results from papers of VDSR, DRCN, CSCN and IA.

**Note:** IA use enchanced prediction trick to improve result.
##### Results on Set 5

|  Scale    | Bicubic | A+  | SRCNN | SelfExSR | CSCN | VDSR | DRCN | IA |
|:---------:|:-------:|:--------:|:------:|:----:|:----:|:----:|:----:|:----:|
| **2x** - PSNR/SSIM|   33.66/0.9929	|   36.54/0.9544	|   36.66/0.9542	|   36.49/0.9537	|  36.93/0.9552	|  37.53/0.9587	|  37.63/0.9588	|37.39/|    
| **3x** - PSNR/SSIM|   30.39/0.8682	|   32.59/0.9088	|   32.75/0.9090	|   32.58/0.9093	|  33.10/0.9144	|  33.66/0.9213	|  33.82/0.9226	|33.46/|  
| **4x** - PSNR/SSIM|   28.42/0.8104	|   30.28/0.8603	|   30.48/0.8628	|   30.31/0.8619	|  30.86/0.8732	|  31.35/0.8838	|  31.53/0.8854	|31.10/|  

##### Results on Set 14

|  Scale    | Bicubic | A+  | SRCNN | SelfExSR | CSCN | VDSR | DRCN | IA |
|:---------:|:-------:|:--------:|:------:|:----:|:----:|:----:|:----:|:----:|
| **2x** - PSNR/SSIM|   30.24/0.8688	|   32.28/0.9056	|   32.42/0.9063	|   32.22/0.9034	|  32.56/0.9074	|  33.03/0.9124	|  33.04/0.9118	|32.87/|    
| **3x** - PSNR/SSIM|   27.55/0.7742	|   29.13/0.8188	|   29.28/0.8209	|   29.16/0.8196	|  29.41/0.8238	|  29.77/0.8314	|  29.76/0.8311	|29.69/|  
| **4x** - PSNR/SSIM|   26.00/0.7027	|   27.32/0.7491	|   27.49/0.7503	|   27.40/0.7518	|  27.64/0.7587	|  28.01/0.7674	|  28.02/0.7670	|27.88/|  

##### Results on BSD 100

|  Scale    | Bicubic | A+  | SRCNN | SelfExSR | CSCN | VDSR | DRCN | IA |
|:---------:|:-------:|:--------:|:------:|:----:|:----:|:----:|:----:|:----:|
| **2x** - PSNR/SSIM|   29.56/0.8431	|   31.21/0.8863	|   31.36/0.8879	|   31.18/0.8855	|  31.40/0.8884	|  31.90/0.8960	|  31.85/0.8942	|31.79/|
| **3x** - PSNR/SSIM|   27.21/0.7385	|   28.29/0.7835	|   28.41/0.7863	|   28.29/0.7840	|  28.50/0.7885	|  28.82/0.7976	|  28.80/0.7963	|28.76/|  
| **4x** - PSNR/SSIM|   25.96/0.6675	|   26.82/0.7087	|   26.90/0.7101	|   26.84/0.7106	|  27.03/0.7161	|  27.29/0.7251	|  27.23/0.7233	|27.25/|  

##### -- Results on Set 5 (PSNR/SSIM/Time)

|  Scale    | Bicubic | A+  | SRCNN | SelfExSR | SCN | VDSR | DRCN  | PSyCo (32)|PSyCo (1024) | FSRCNN-S | FSRCNN | RAISR |   
|:---------:|:-------:|:--------:|:------:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
| **2x** |   33.66/0.002 	|   36.54/0.684 	|   36.66/4.722 	|   36.49/42.521  	|  36.93 	|  37.53/0.9587/0.13 | 37.63/0.9588/1.54 	| 36.57/0.038  | 36.88/0.185 | 36.58/0.024 | 37.00/0.068 |36.061/0.951/0.018 |   
| **3x** |   30.39/0.002	|   32.59/0.401	|   32.75/5.226 	|   32.58/31.008	|  33.10	|  33.66/0.9213/0.13 	|  33.82/0.9226/1.55 	| 32.63/0.049 | 32.93/0.456 | 32.61/0.010 | 33.16/0.027 |32.172/0.900/0.015  |
| **4x** |   28.42/0.002 	|   30.28/0.226 	|   30.48/9.962  	|   30.31/26.728 	|  30.86 	|  31.35/0.8838/0.12 |  31.53/0.8854/1.54 	| 30.32/0.055 | 30.62/0.210 | 30.11/0.0052 | 30.71/0.015 |29.834/0.848/0.017 |

##### ---
[ **RAISR** ] [RAISR: Rapid and Accurate Image Super Resolution](https://drive.google.com/file/d/0BzCe024Ewz8ab2RKUFVFZGJ4OWc/view)

[ **PSyCo** ] [PSyCo: Manifold Span Reduction for Super Resolution](https://bitbucket.org/EduPerez/psycosuperres/wiki/Home)

[ **FSRCNN** ] [Accelerating the Super-Resolution Convolutional Neural Network](http://mmlab.ie.cuhk.edu.hk/projects/FSRCNN.html)

[ **DRCN** ] [Deeply-Recursive Convolutional Network for Image Super-Resolution](http://cv.snu.ac.kr/research/DRCN/)

[ **AI** ] [Seven ways to improve example-based single image super resolution](http://www.vision.ee.ethz.ch/~timofter/CVPR2016_ID769_SUPPLEMENTARY/index.html)

[ **VDSR** ] [Accurate Image Super-Resolution Using Very Deep Convolutional Networks](http://cv.snu.ac.kr/research/VDSR/)

[ **SCN** ] [Deep Networks for Image Super-Resolution with Sparse Prior](http://www.ifp.illinois.edu/~dingliu2/iccv15/)

[ **SRCNN** ] [Image Super-Resolution Using Deep Convolutional Networks](http://mmlab.ie.cuhk.edu.hk/projects/SRCNN.html)

[ **ANR** ] [Anchored Neighborhood Regression for Fast Example-Based Super-Resolution](http://www.vision.ee.ethz.ch/~timofter/ICCV2013_ID1774_SUPPLEMENTARY/index.html)

[ **A+** ] [A+: Adjusted Anchored Neighborhood Regression for Fast Super-Resolution](http://www.vision.ee.ethz.ch/~timofter/ACCV2014_ID820_SUPPLEMENTARY/)
