# Reproducible-image-restoration-state-of-the-art
State-of-the-arts of deep-learning-based image restoration work. Some of the codes may not be official, please doulbe check them. The lists under each subsections may have overlaps. This list is maintained by [Yuqian Zhou](http://yuqianzhou.com/) at [IFP UIUC](https://ifp-uiuc.github.io/).
## Information Sources
This collection is inspired and re-organized from the following sources,
 * Denoising
   * [summary by Bihan Wen](https://github.com/wenbihan/reproducible-image-denoising-state-of-the-art)
   * [summary by flyywh](https://github.com/flyywh/Image-Denoising-State-of-the-art)
 * Super-resolution
   * [summary by yapengtian](https://github.com/YapengTian/Single-Image-Super-Resolution)
   * [survey of SISR](https://arxiv.org/pdf/1902.06068.pdf)

## Image Super-resolution
### Supervised Methods
#### Residual Learning
 * VDSR [[Web]](https://arxiv.org/abs/1511.04587) [[Code]](https://github.com/twtygqyy/pytorch-vdsr) [[PDF]](https://arxiv.org/pdf/1511.04587.pdf)
   * Accurate image superresolution using very deep convolutional networks (CVPR16), Kim et al.
 * Memnet [[Web]](https://arxiv.org/abs/1708.02209) [[Code]](https://github.com/tyshiwo/MemNet) [[PDF]](http://cvlab.cse.msu.edu/pdfs/Image_Restoration%20using_Persistent_Memory_Network.pdf)
   * Memnet: A persistent memory network for image restoration(ICCV17), Tai et al.
 * RED [[Web]](https://bitbucket.org/chhshen/image-denoising/) [[Code]](https://bitbucket.org/chhshen/image-denoising/) [[PDF]](https://arxiv.org/pdf/1603.09056.pdf)
   * Image Restoration Using Very Deep Convolutional Encoder-Decoder Networks with Symmetric Skip Connections (NIPS2016), Mao et al.
 * DRRN [[Web]](http://cvlab.cse.msu.edu/project-super-resolution.html) [[Code]](https://github.com/tyshiwo/DRRN_CVPR17) [[PDF]](http://cvlab.cse.msu.edu/pdfs/Tai_Yang_Liu_CVPR2017.pdf)
   * Image Super-Resolution via Deep Recursive Residual Network(CVPR17), Tai et al.
 * IDN [[Web]](https://github.com/Zheng222/IDN-Caffe) [[Code]](https://github.com/Zheng222/IDN-Caffe) [[PDF]](https://arxiv.org/pdf/1803.09454.pdf)
   * Fast and Accurate Single Image Super-Resolution via Information Distillation Network (CVPR18), Hui et al.
 * EDSR  [[Web]](https://github.com/limbee/NTIRE2017) [[Code]](https://github.com/thstkdgus35/EDSR-PyTorch) [[PDF]](https://arxiv.org/pdf/1707.02921.pdf)
   * Enhanced Deep Residual Networks for Single Image Super-Resolution(NTIRE2017), Lim et al.
 * RCAN [[Web]](https://github.com/yulunzhang/RCAN) [[Code]](https://github.com/yulunzhang/RCAN) [[PDF]](https://arxiv.org/pdf/1807.02758.pdf)
   * Image Super-Resolution Using Very Deep Residual Channel Attention Networks(ECCV18), Zhang et al.
 * MSRN [[Web]](https://github.com/ehumss/MSRN_PyTorch) [[Code]](https://github.com/ehumss/MSRN_PyTorch) [[PDF]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Juncheng_Li_Multi-scale_Residual_Network_ECCV_2018_paper.pdf)
   * Multi-scale Residual Network for Image Super-Resolution(ECCV18),  Li et al.
 * DSRN [[Web]](https://github.com/WeiHan3/dsrn) [[Code]](https://github.com/WeiHan3/dsrn) [[PDF]](https://arxiv.org/pdf/1805.02704.pdf)
   * Image Super-resolution via Dual-state Recurrent Neural Networks (CVPR18), Han et al.

#### Recursive Learning
Recurvise learning introduced in super-resolution is for larger receptive field and reduced parameters.
 * DRCN [[Web]](https://github.com/jiny2001/deeply-recursive-cnn-tf) [[Code]](https://github.com/jiny2001/deeply-recursive-cnn-tf) [[PDF]](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Kim_Deeply-Recursive_Convolutional_Network_CVPR_2016_paper.pdf)
   * Deeply-recursive convolutional network for image super-resolution(CVPR16), Kim et al.
 * DRRN [[Web]](http://cvlab.cse.msu.edu/project-super-resolution.html) [[Code]](https://github.com/tyshiwo/DRRN_CVPR17) [[PDF]](http://cvlab.cse.msu.edu/pdfs/Tai_Yang_Liu_CVPR2017.pdf)
   * Image Super-Resolution via Deep Recursive Residual Network(CVPR17), Tai et al.
 * Memnet [[Web]](https://arxiv.org/abs/1708.02209) [[Code]](https://github.com/tyshiwo/MemNet) [[PDF]](http://cvlab.cse.msu.edu/pdfs/Image_Restoration%20using_Persistent_Memory_Network.pdf)
   * Memnet: A persistent memory network for image restoration(ICCV17), Tai et al.
 * CARN [[Web]](https://arxiv.org/abs/1803.08664) [[Code]](https://github.com/nmhkahn/CARN-pytorch) [[PDF]](https://arxiv.org/pdf/1803.08664.pdf)
   * Fast, Accurate, and Lightweight Super-Resolution with Cascading Residual Network(ECCV18), Ahn et al.
 * NLRN[[Web]](https://github.com/Ding-Liu/NLRN) [[Code]](https://github.com/Ding-Liu/NLRN) [[PDF]](http://papers.nips.cc/paper/7439-non-local-recurrent-network-for-image-restoration.pdf)
   * Non-Local Recurrent Network for Image Restoration (NeurIPS 2018), Liu et al.
   
 Recurvise learning can resolve large scaling factor problem by solving multiple smaller factor problems.
 * DSRN [[Web]](https://github.com/WeiHan3/dsrn) [[Code]](https://github.com/WeiHan3/dsrn) [[PDF]](https://arxiv.org/pdf/1805.02704.pdf)
   * Image Super-resolution via Dual-state Recurrent Neural Networks (CVPR18), Han et al.
   * Explore HR-LR relationship
 * LapSRN [[Web]](http://vllab.ucmerced.edu/wlai24/LapSRN/) [[Code]](https://github.com/phoenix104104/LapSRN) [[PDF]](https://arxiv.org/pdf/1704.03915.pdf)
   * Deep Laplacian Pyramid Networks for Fast and Accurate Super-Resolution(CVPR17), Lai et al.
 * MS-LapSRN [[Web]](https://arxiv.org/abs/1710.01992) [[Code]](https://github.com/phoenix104104/LapSRN) [[PDF]](https://arxiv.org/pdf/1710.01992.pdf)
   * Fast and accurate image super-resolution with deep laplacian pyramid networks(TPAM18), Lai et al.

   
#### Multi-path Learning
Better separate modeling performance, but increasing the parameter size greatly.
 * LapSRN [[Web]](http://vllab.ucmerced.edu/wlai24/LapSRN/) [[Code]](https://github.com/phoenix104104/LapSRN) [[PDF]](https://arxiv.org/pdf/1704.03915.pdf)
   * Deep Laplacian Pyramid Networks for Fast and Accurate Super-Resolution(CVPR17), Lai et al.
 * DSRN [[Web]](https://github.com/WeiHan3/dsrn) [[Code]](https://github.com/WeiHan3/dsrn) [[PDF]](https://arxiv.org/pdf/1805.02704.pdf)
   * Image Super-resolution via Dual-state Recurrent Neural Networks (CVPR18), Han et al.
   * Explore HR-LR relationship
 * PixelSR [[Web]](https://arxiv.org/abs/1702.00783) [[Code]](https://github.com/nilboy/pixel-recursive-super-resolution) [[PDF]](https://arxiv.org/pdf/1702.00783.pdf)
   * Pixel Recursive Super Resolution(ICCV17), Dahl et al.
 *  [[Web]]() [[Code]]() [[PDF]]()
   * (),  et al.
 *  [[Web]]() [[Code]]() [[PDF]]()
   * (),  et al.
 *  [[Web]]() [[Code]]() [[PDF]]()
   * (),  et al.
 *  [[Web]]() [[Code]]() [[PDF]]()
   * (),  et al.
   
#### Dense Connections
#### Attention-based
#### Advanced Convolution
#### Pixel-recursive
#### Pyramid Pooling
#### Wavelet Transform

### Unsupervised Methods
#### Zero-shot
#### Weekly-supervised
#### Deep Image Prior
## Image Denoising
#### Single-model
 * SF [[Web]](http://www.visinf.tu-darmstadt.de/vi_research/code/index.en.jsp#shrinkage_fields) [[Code]](https://github.com/uschmidt83/shrinkage-fields) [[PDF]](http://research.uweschmidt.org/pubs/cvpr14schmidt.pdf)
   * Shrinkage Fields for Effective Image Restoration (CVPR 2014), Schmidt et al.
 * TNRD [[Web]](http://www.icg.tugraz.at/Members/Chenyunjin/about-yunjin-chen) [[Code]](https://www.dropbox.com/s/8j6b880m6ddxtee/TNRD-Codes.zip?dl=0) [[PDF]](https://arxiv.org/pdf/1508.02848.pdf)
   * Trainable nonlinear reaction diffusion: A flexible framework for fast and effective image restoration (TPAMI 2016), Chen et al.
 * RED [[Web]](https://bitbucket.org/chhshen/image-denoising/) [[Code]](https://bitbucket.org/chhshen/image-denoising/) [[PDF]](https://arxiv.org/pdf/1603.09056.pdf)
   * Image Restoration Using Very Deep Convolutional Encoder-Decoder Networks with Symmetric Skip Connections (NIPS2016), Mao et al.
 * DnCNN [[Web]](https://github.com/cszn/DnCNN) [[Code]](https://github.com/cszn/DnCNN) [[PDF]](https://arxiv.org/pdf/1608.03981v1.pdf)
   * Beyond a Gaussian Denoiser: Residual Learning of Deep CNN for Image Denoising (TIP2017), Zhang et al.
 * MemNet [[Web]](https://github.com/tyshiwo/MemNet) [[Code]](https://github.com/tyshiwo/MemNet) [[PDF]](http://cvlab.cse.msu.edu/pdfs/Image_Restoration%20using_Persistent_Memory_Network.pdf)
   * MemNet: A Persistent Memory Network for Image Restoration (ICCV2017), Tai et al.  
 * WIN [[Web]](https://github.com/cswin/WIN) [[Code]](https://github.com/cswin/WIN) [[PDF]](https://arxiv.org/pdf/1707.09135.pdf)
   * Learning Pixel-Distribution Prior with Wider Convolution for Image Denoising (Arxiv), Liu et al.    
 * F-W Net [[Web]](https://github.com/sunke123/FW-Net) [[Code]](https://github.com/sunke123/FW-Net) [[PDF]](https://arxiv.org/abs/1802.10252)
   * L_p-Norm Constrained Coding With Frank-Wolfe Network (Arxiv), Sun et al.
 * NLCNN [[Web]](https://cig.skoltech.ru/publications) [[Code]](https://github.com/cig-skoltech/NLNet) [[PDF]](http://www.skoltech.ru/app/data/uploads/sites/19/2017/06/1320.pdf)
   * Non-Local Color Image Denoising with Convolutional Neural Networks (CVPR 2017), Lefkimmiatis.
 * Deep image prior [[Web]](https://dmitryulyanov.github.io/deep_image_prior) [[Code]](https://github.com/DmitryUlyanov/deep-image-prior) [[PDF]](https://sites.skoltech.ru/app/data/uploads/sites/25/2018/04/deep_image_prior.pdf)
 * xUnit [[Web]](https://github.com/kligvasser/xUnit) [[Code]](https://github.com/kligvasser/xUnit) [[PDF]](https://arxiv.org/pdf/1711.06445.pdf)
   * xUnit: Learning a Spatial Activation Function for Efficient Image Restoration (Arxiv), Kligvasser et al.  
 * UDNet [[Web]](https://github.com/cig-skoltech/UDNet) [[Code]](https://github.com/cig-skoltech/UDNet) [[PDF]](https://arxiv.org/pdf/1711.07807.pdf)
   * Universal Denoising Networks : A Novel CNN Architecture for Image Denoising (CVPR 2018), Stamatios  Lefkimmiatis.   
 * Wavelet-CNN [[Web]](https://github.com/lpj0/MWCNN) [[Code]](https://github.com/lpj0/MWCNN) [[PDF]](https://arxiv.org/abs/1805.07071)
   * Multi-level Wavelet-CNN for Image Restoration (Arxiv), Liu et al.  
 * FFDNet [[Web]](https://github.com/cszn/FFDNet/) [[Code]](https://github.com/cszn/FFDNet/) [[PDF]](https://arxiv.org/abs/1710.04026)
   * FFDNet: Toward a Fast and Flexible Solution for CNN-Based Image Denoising (TIP), Zhang et al.
 * FC-AIDE [[Web]](https://github.com/csm9493/FC-AIDE) [[Code]](https://github.com/GuoShi28/CBDNet) [[PDF]](https://arxiv.org/pdf/1807.07569.pdf)
   * Fully Convolutional Pixel Adaptive Image Denoiser (Arxiv), Cha et al.  
 * Noise2Noise [[Web]](https://github.com/yu4u/noise2noise) [[TF Code]](https://github.com/NVlabs/noise2noise) [[Keras Unofficial Code]](https://github.com/yu4u/noise2noise) [[PDF]](https://arxiv.org/pdf/1803.04189.pdf)
   * Noise2Noise: Learning Image Restoration without Clean Data (ICML 2018), Lehtinen et al.      
 * UDN [[Web]](https://cig.skoltech.ru/publications) [[Code]](https://github.com/cig-skoltech/UDNet) [[PDF]](http://www.skoltech.ru/app/data/uploads/sites/19/2018/03/UDNet_CVPR2018.pdf)
   * Universal Denoising Networks- A Novel CNN Architecture for Image Denoising (CVPR 2018), Lefkimmiatis.     
 * N3 [[Web]](https://github.com/visinf/n3net) [[Code]](https://github.com/visinf/n3net) [[PDF]](https://arxiv.org/abs/1810.12575)
   * Neural Nearest Neighbors Networks (NIPS 2018), Plotz et al.  
 * NLRN [[Web]](https://github.com/Ding-Liu/NLRN) [[Code]](https://github.com/Ding-Liu/NLRN) [[PDF]](https://arxiv.org/pdf/1806.02919.pdf)
   * Non-Local Recurrent Network for Image Restoration (NIPS 2018), Liu et al.
 * RDN+ [[Web]](https://github.com/yulunzhang/RDN) [[Code]](https://github.com/yulunzhang/RDN) [[PDF]](https://arxiv.org/abs/1812.10477)
   * Residual Dense Network for Image Restoration (CVPR 2018), Zhang et al.
   
#### Real Noise
 * CBDNet [[Web]](https://github.com/GuoShi28/CBDNet) [[Code]](https://github.com/GuoShi28/CBDNet) [[PDF]](https://arxiv.org/pdf/1807.04686.pdf)
   * Toward Convolutional Blind Denoising of Real Photographs (ECCV18), Guo et al.  
 * Pixel-shuffle (PD) [[Web]](https://github.com/yzhouas/PD-Denoising-pytorch) [[Code]](https://github.com/yzhouas/PD-Denoising-pytorch) [[PDF]](https://arxiv.org/abs/1904.03485)
   * When AWGN-based Denoiser Meets Real Noises(Arxiv2019), Zhou et al.
   
#### Sparsity and Low-rankness Combined
 * STROLLR-2D [[PDF]](http://transformlearning.csl.illinois.edu/assets/Bihan/ConferencePapers/BihanICASSP2017strollr.pdf) [[Code]](https://github.com/wenbihan/strollr2d_icassp2017) 
   * When Sparsity Meets Low-Rankness: Transform Learning With Non-Local Low-Rank Constraint for Image Restoration (ICASSP 2017), Wen et al.
   
#### Combined with High-Level Tasks
 * Meets High-level Tasks [[PDF]](https://arxiv.org/pdf/1706.04284.pdf) [[Code]](https://github.com/wenbihan/DeepDenoising) 
   * When Image Denoising Meets High-Level Vision Tasks: A Deep Learning Approach (IJCAI 2018), Liu et al.

#### Image Noise Level Estimation
 * SINLE [[PDF]](http://www.ok.sc.e.titech.ac.jp/res/NLE/TIP2013-noise-level-estimation06607209.pdf) [[Code]](https://www.mathworks.com/matlabcentral/fileexchange/36921-noise-level-estimation-from-a-single-image) [[Slides]](https://wwwpub.zih.tu-dresden.de/~hh3/Hauptsem/SS16/noise.pdf)
   * Single-image Noise Level Estimation for Blind Denoising (TIP 2014), Liu et al.

## Image Inpainting




## Image Restoration Tasks in a Single Model






## Novel Benchmark
 * ReNOIR [[Web]](http://ani.stat.fsu.edu/~abarbu/Renoir.html) [[Data]](http://ani.stat.fsu.edu/~abarbu/Renoir.html) [[PDF]](https://arxiv.org/pdf/1409.8230.pdf)
   * RENOIR - A Dataset for Real Low-Light Image Noise Reduction (Arxiv 2014), Anaya, Barbu.   
 * Darmstadt [[Web]](https://noise.visinf.tu-darmstadt.de/) [[Data]](https://noise.visinf.tu-darmstadt.de/downloads/) [[PDF]](https://download.visinf.tu-darmstadt.de/papers/2017-cvpr-ploetz-benchmarking_denoising_algorithms-preprint.pdf)
   * Benchmarking Denoising Algorithms with Real Photographs (CVPR 2017), Tobias Plotz, Stefan Roth.
 * PolyU [[Web]](https://github.com/csjunxu/PolyU-Real-World-Noisy-Images-Dataset) [[Data]](https://github.com/csjunxu/PolyU-Real-World-Noisy-Images-Dataset) [[PDF]](https://arxiv.org/pdf/1804.02603.pdf)
   * Real-world Noisy Image Denoising: A New Benchmark (Arxiv), Xu et al.
   
## Commonly Used Restoration Dataset
 * Kodak [[Web]](http://r0k.us/graphics/kodak/)
 * USC SIPI-Misc [[Web]](http://sipi.usc.edu/database/database.php?volume=misc) 
 * BSD [[Web]](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/)  

## Commonly Used Image Quality Metric Code
 * PSNR (Peak Signal-to-Noise Ratio) [[Wiki]](https://en.wikipedia.org/wiki/Peak_signal-to-noise_ratio) [[Matlab Code]](https://www.mathworks.com/help/images/ref/psnr.html) [[Python Code]](https://github.com/aizvorski/video-quality)
 * SSIM (Structural similarity) [[Wiki]](https://en.wikipedia.org/wiki/Structural_similarity) [[Matlab Code]](http://www.cns.nyu.edu/~lcv/ssim/ssim_index.m) [[Python Code]](https://github.com/aizvorski/video-quality/blob/master/ssim.py)
 * NIQE (Naturalness Image Quality Evaluator) [[Web]](http://live.ece.utexas.edu/research/Quality/nrqa.htm) [[Matlab Code]](http://live.ece.utexas.edu/research/Quality/nrqa.htm) [[Python Code]](https://github.com/aizvorski/video-quality/blob/master/niqe.py)


   
