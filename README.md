# Awesome Gaussian Splatting [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to Gaussian Splatting. Content is automatically updated daily.

> Last Update: 2024-12-09 12:49:10

## Categories

- [Applications](#applications) (238 papers) - Papers about specific applications
- [Image Editing](#image-editing) (13 papers) - Papers about image editing with Flux/DiT
- [Image Generation](#image-generation) (160 papers) - Papers focusing on image generation (text-to-image, controllable image generation) with Flux/DiT
- [Surveys](#surveys) (19 papers) - Survey papers and benchmarks about Diffusion Transformer
- [Video Related](#video-related) (19 papers) - Papers about video generation and editing with Flux/DiT



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### Applications

*Showing the latest 50 out of 238 papers*

- **[Turbo3D: Ultra-fast Text-to-3D Generation](https://arxiv.org/abs/2412.04470v1)**  
  Authors: Hanzhe Hu, Tianwei Yin, Fujun Luan, Yiwei Hu, Hao Tan, Zexiang Xu, Sai Bi, Shubham Tulsiani, Kai Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.04470v1.pdf)  
  Keywords: 3D generation  
- **[DGNS: Deformable Gaussian Splatting and Dynamic Neural Surface for Monocular Dynamic 3D Reconstruction](https://arxiv.org/abs/2412.03910v1)**  
  Authors: Xuesong Li, Jinguang Tong, Jie Hong, Vivien Rolland, Lars Petersson  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03910v1.pdf)  
  Keywords: 3D reconstruction  
- **[Splats in Splats: Embedding Invisible 3D Watermark within Gaussian Splatting](https://arxiv.org/abs/2412.03121v1)**  
  Authors: Yijia Guo, Wenkai Huang, Yang Li, Gaolei Li, Hang Zhang, Liwen Hu, Jianhua Li, Tiejun Huang, Lei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03121v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://water-gs.github.io.)  
  Keywords: 3D reconstruction  
- **[AniGS: Animatable Gaussian Avatar from a Single Image with Inconsistent Gaussian Reconstruction](https://arxiv.org/abs/2412.02684v1)**  
  Authors: Lingteng Qiu, Shenhao Zhu, Qi Zuo, Xiaodong Gu, Yuan Dong, Junfei Zhang, Chao Xu, Zhe Li, Weihao Yuan, Liefeng Bo, Guanying Chen, Zilong Dong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02684v1.pdf)  
  Keywords: 3D reconstruction, Controllable, Control, video generation  
- **[Towards Rich Emotions in 3D Avatars: A Text-to-3D Avatar Generation Benchmark](https://arxiv.org/abs/2412.02508v1)**  
  Authors: Haidong Xu, Meishan Zhang, Hao Ju, Zhedong Zheng, Hongyuan Zhu, Erik Cambria, Min Zhang, Hao Fei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02508v1.pdf)  
  Keywords: DiT, 3D generation  
- **[Multi-robot autonomous 3D reconstruction using Gaussian splatting with Semantic guidance](https://arxiv.org/abs/2412.02249v1)**  
  Authors: Jing Zeng, Qi Ye, Tianle Liu, Yang Xu, Jin Li, Jinming Xu, Liang Li, Jiming Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02249v1.pdf)  
  Keywords: DiT, 3D reconstruction  
- **[How to Use Diffusion Priors under Sparse Views?](https://arxiv.org/abs/2412.02225v1)**  
  Authors: Qisen Wang, Yifan Zhao, Jiawei Ma, Jia Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02225v1.pdf) | [![GitHub](https://img.shields.io/github/stars/iCVTEAM/IPSM?style=social)](https://github.com/iCVTEAM/IPSM)  
  Keywords: 3D reconstruction  
- **[Gaussian Object Carver: Object-Compositional Gaussian Splatting with surfaces completion](https://arxiv.org/abs/2412.02075v1)**  
  Authors: Liu Liu, Xinjie Wang, Jiaxiong Qiu, Tianwei Lin, Xiaolin Zhou, Zhizhong Su  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02075v1.pdf)  
  Keywords: DiT, vr  
- **[Occam's LGS: A Simple Approach for Language Gaussian Splatting](https://arxiv.org/abs/2412.01807v1)**  
  Authors: Jiahuan Cheng, Jan-Nico Zaech, Luc Van Gool, Danda Pani Paudel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01807v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://insait-institute.github.io/OccamLGS/)  
  Keywords: 3D reconstruction  
- **[Structured 3D Latents for Scalable and Versatile 3D Generation](https://arxiv.org/abs/2412.01506v1)**  
  Authors: Jianfeng Xiang, Zelong Lv, Sicheng Xu, Yu Deng, Ruicheng Wang, Bowen Zhang, Dong Chen, Xin Tong, Jiaolong Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01506v1.pdf)  
  Keywords: DiT, 3D generation  

### Image Editing

- **[CTRL-D: Controllable Dynamic 3D Scene Editing with Personalized 2D Diffusion](https://arxiv.org/abs/2412.01792v1)**  
  Authors: Kai He, Chin-Hsuan Wu, Igor Gilitschenski  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01792v1.pdf)  
  Keywords: Controllable, image editing, DiT, Control  
- **[Diffusion Models with Anisotropic Gaussian Splatting for Image Inpainting](https://arxiv.org/abs/2412.01682v2)**  
  Authors: Jacob Fein-Ashley, Benjamin Fein-Ashley  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01682v2.pdf)  
  Keywords: image inpainting  
- **[Instant3dit: Multiview Inpainting for Fast Editing of 3D Objects](https://arxiv.org/abs/2412.00518v1)**  
  Authors: Amir Barda, Matheus Gadelha, Vladimir G. Kim, Noam Aigerman, Amit H. Bermano, Thibault Groueix  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.00518v1.pdf)  
  Keywords: DiT, image inpainting  
- **[AI-Driven Stylization of 3D Environments](https://arxiv.org/abs/2411.06067v1)**  
  Authors: Yuanbo Chen, Yixiao Kang, Yukun Song, Cyrus Vachha, Sining Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.06067v1.pdf)  
  Keywords: image stylization  
- **[ArCSEM: Artistic Colorization of SEM Images via Gaussian Splatting](https://arxiv.org/abs/2410.21310v1)**  
  Authors: Takuma Nishimura, Andreea Dogaru, Martin Oeggerli, Bernhard Egger  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.21310v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ronly2460.github.io/ArCSEM)  
  Keywords: image editing, DiT  
- **[GS-VTON: Controllable 3D Virtual Try-on with Gaussian Splatting](https://arxiv.org/abs/2410.05259v1)**  
  Authors: Yukang Cao, Masoud Hadi, Liang Pan, Ziwei Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.05259v1.pdf)  
  Keywords: Controllable, image editing, DiT, Control  
- **[MiraGe: Editable 2D Images using Gaussian Splatting](https://arxiv.org/abs/2410.01521v1)**  
  Authors: Joanna Waczyńska, Tomasz Szczepanik, Piotr Borycki, Sławomir Tadeja, Thomas Bohné, Przemysław Spurek  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.01521v1.pdf)  
  Keywords: image editing, DiT, Control  
- **[WaSt-3D: Wasserstein-2 Distance for Scene-to-Scene Stylization on 3D Gaussians](https://arxiv.org/abs/2409.17917v1)**  
  Authors: Dmytro Kotovenko, Olga Grebenkova, Nikolaos Sarafianos, Avinash Paliwal, Pingchuan Ma, Omid Poursaeed, Sreyas Mohan, Yuchen Fan, Yilei Li, Rakesh Ranjan, Björn Ommer  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.17917v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://compvis.github.io/wast3d/}{https://compvis.github.io/wast3d/}$.)  
  Keywords: DiT, image stylization  
- **[GaussianSR: High Fidelity 2D Gaussian Splatting for Arbitrary-Scale Image Super-Resolution](https://arxiv.org/abs/2407.18046v1)**  
  Authors: Jintong Hu, Bin Xia, Bin Chen, Wenming Yang, Lei Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.18046v1.pdf)  
  Keywords: DiT, image super-resolution  
- **[3DitScene: Editing Any Scene via Language-guided Disentangled Gaussian Splatting](https://arxiv.org/abs/2405.18424v1)**  
  Authors: Qihang Zhang, Yinghao Xu, Chaoyang Wang, Hsin-Ying Lee, Gordon Wetzstein, Bolei Zhou, Ceyuan Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2405.18424v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://zqh0253.github.io/3DitScene/.)  
  Keywords: image editing, DiT, Control  

### Image Generation

*Showing the latest 50 out of 160 papers*

- **[InfiniCube: Unbounded and Controllable Dynamic 3D Driving Scene Generation with World-Guided Video Models](https://arxiv.org/abs/2412.03934v1)**  
  Authors: Yifan Lu, Xuanchi Ren, Jiawei Yang, Tianchang Shen, Zhangjie Wu, Jun Gao, Yue Wang, Siheng Chen, Mike Chen, Sanja Fidler, Jiahui Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03934v1.pdf)  
  Keywords: Controllable, DiT, Control  
- **[2DGS-Room: Seed-Guided 2D Gaussian Splatting with Geometric Constrains for High-Fidelity Indoor Scene Reconstruction](https://arxiv.org/abs/2412.03428v1)**  
  Authors: Wanting Zhang, Haodong Xiang, Zhichao Liao, Xiansong Lai, Xinghui Li, Long Zeng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03428v1.pdf)  
  Keywords: DiT, Control  
- **[NeRF and Gaussian Splatting SLAM in the Wild](https://arxiv.org/abs/2412.03263v1)**  
  Authors: Fabian Schmidt, Markus Enzweiler, Abhinav Valada  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03263v1.pdf) | [![GitHub](https://img.shields.io/github/stars/iis-esslingen/nerf-3dgs-benchmark?style=social)](https://github.com/iis-esslingen/nerf-3dgs-benchmark)  
  Keywords: DiT, Control  
- **[AniGS: Animatable Gaussian Avatar from a Single Image with Inconsistent Gaussian Reconstruction](https://arxiv.org/abs/2412.02684v1)**  
  Authors: Lingteng Qiu, Shenhao Zhu, Qi Zuo, Xiaodong Gu, Yuan Dong, Junfei Zhang, Chao Xu, Zhe Li, Weihao Yuan, Liefeng Bo, Guanying Chen, Zilong Dong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02684v1.pdf)  
  Keywords: 3D reconstruction, Controllable, Control, video generation  
- **[TimeWalker: Personalized Neural Space for Lifelong Head Avatars](https://arxiv.org/abs/2412.02421v1)**  
  Authors: Dongwei Pan, Yang Li, Hongsheng Li, Kwan-Yee Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02421v1.pdf)  
  Keywords: Controllable, DiT, Control  
- **[CTRL-D: Controllable Dynamic 3D Scene Editing with Personalized 2D Diffusion](https://arxiv.org/abs/2412.01792v1)**  
  Authors: Kai He, Chin-Hsuan Wu, Igor Gilitschenski  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01792v1.pdf)  
  Keywords: Controllable, image editing, DiT, Control  
- **[HUGSIM: A Real-Time, Photo-Realistic and Closed-Loop Simulator for Autonomous Driving](https://arxiv.org/abs/2412.01718v1)**  
  Authors: Hongyu Zhou, Longzhong Lin, Jiabao Wang, Yichong Lu, Dongfeng Bai, Bingbing Liu, Yue Wang, Andreas Geiger, Yiyi Liao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01718v1.pdf)  
  Keywords: Control  
- **[3DSceneEditor: Controllable 3D Scene Editing with Gaussian Splatting](https://arxiv.org/abs/2412.01583v1)**  
  Authors: Ziyang Yan, Lei Li, Yihua Shao, Siyu Chen, Wuzong Kai, Jenq-Neng Hwang, Hao Zhao, Fabio Remondino  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01583v1.pdf)  
  Keywords: Controllable, DiT, Control  
- **[6DOPE-GS: Online 6D Object Pose Estimation using Gaussian Splatting](https://arxiv.org/abs/2412.01543v1)**  
  Authors: Yufeng Jin, Vignesh Prasad, Snehal Jauhri, Mathias Franzius, Georgia Chalvatzaki  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01543v1.pdf)  
  Keywords: Control  
- **[One Shot, One Talk: Whole-body Talking Avatar from a Single Image](https://arxiv.org/abs/2412.01106v1)**  
  Authors: Jun Xiang, Yudong Guo, Leipeng Hu, Boyang Guo, Yancheng Yuan, Juyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01106v1.pdf)  
  Keywords: Control  

### Surveys

- **[Adversarial Attacks Using Differentiable Rendering: A Survey](https://arxiv.org/abs/2411.09749v1)**  
  Authors: Matthew Hull, Chao Zhang, Zsolt Kira, Duen Horng Chau  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.09749v1.pdf)  
  Keywords: survey  
- **[Neural Fields in Robotics: A Survey](https://arxiv.org/abs/2410.20220v1)**  
  Authors: Muhammad Zubair Irshad, Mauro Comi, Yen-Chen Lin, Nick Heppert, Abhinav Valada, Rares Ambrus, Zsolt Kira, Jonathan Tremblay  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.20220v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://robonerf.github.io)  
  Keywords: survey, Control, 3D reconstruction  
- **[3D Gaussian Splatting in Robotics: A Survey](https://arxiv.org/abs/2410.12262v1)**  
  Authors: Siting Zhu, Guangming Wang, Dezhi Kong, Hesheng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.12262v1.pdf)  
  Keywords: survey  
- **[3D Representation Methods: A Survey](https://arxiv.org/abs/2410.06475v1)**  
  Authors: Zhengren Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.06475v1.pdf)  
  Keywords: survey  
- **[Learning-based Multi-View Stereo: A Survey](https://arxiv.org/abs/2408.15235v1)**  
  Authors: Fangjinhua Wang, Qingtian Zhu, Di Chang, Quankai Gao, Junlin Han, Tong Zhang, Richard Hartley, Marc Pollefeys  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.15235v1.pdf)  
  Keywords: survey, DiT, vr, 3D reconstruction  
- **[DESI Peculiar Velocity Survey -- Fundamental Plane](https://arxiv.org/abs/2408.13842v1)**  
  Authors: Khaled Said, Cullan Howlett, Tamara Davis, John Lucey, Christoph Saulder, Kelly Douglass, Alex G. Kim, Anthony Kremin, Caitlin Ross, Greg Aldering, Jessica Nicole Aguilar, Steven Ahlen, Segev BenZvi, Davide Bianchi, David Brooks, Todd Claybaugh, Kyle Dawson, Axel de la Macorra, Biprateep Dey, Peter Doel, Kevin Fanning, Simone Ferraro, Andreu Font-Ribera, Jaime E. Forero-Romero, Enrique Gaztañaga, Satya Gontcho A Gontcho, Julien Guy, Klaus Honscheid, Robert Kehoe, Theodore Kisner, Andrew Lambert, Martin Landriau, Laurent Le Guillou, Marc Manera, Aaron Meisner, Ramon Miquel, John Moustakas, Andrea Muñoz-Gutiérrez, Adam Myers, Jundan Nie, Nathalie Palanque-Delabrouille, Will Percival, Francisco Prada, Graziano Rossi, Eusebio Sanchez, David Schlegel, Michael Schubnell, Joseph Harry Silber, David Sprayberry, Gregory Tarlé, Mariana Vargas Magana, Benjamin Alan Weaver, Risa Wechsler, Zhimin Zhou, Hu Zou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.13842v1.pdf)  
  Keywords: survey, DiT  
- **[3D Gaussian Splatting: Survey, Technologies, Challenges, and Opportunities](https://arxiv.org/abs/2407.17418v1)**  
  Authors: Yanqi Bao, Tianyu Ding, Jing Huo, Yaoli Liu, Yuxin Li, Wenbin Li, Yang Gao, Jiebo Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.17418v1.pdf)  
  Keywords: survey, DiT  
- **[Survey on Fundamental Deep Learning 3D Reconstruction Techniques](https://arxiv.org/abs/2407.08137v1)**  
  Authors: Yonge Bai, LikHang Wong, TszYin Twan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.08137v1.pdf)  
  Keywords: survey, 3D reconstruction  
- **[Panopticon: a telescope for our times](https://arxiv.org/abs/2407.05103v2)**  
  Authors: Will Saunders, Timothy Chin, Michael Goodwin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.05103v2.pdf)  
  Keywords: survey  
- **[3DGS.zip: A survey on 3D Gaussian Splatting Compression Methods](https://arxiv.org/abs/2407.09510v4)**  
  Authors: Milena T. Bagdasarian, Paul Knoll, Yi-Hsin Li, Florian Barthel, Anna Hilsmann, Peter Eisert, Wieland Morgenstern  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.09510v4.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://w-m.github.io/3dgs-compression-survey/)  
  Keywords: survey, DiT  

### Video Related

- **[AniGS: Animatable Gaussian Avatar from a Single Image with Inconsistent Gaussian Reconstruction](https://arxiv.org/abs/2412.02684v1)**  
  Authors: Lingteng Qiu, Shenhao Zhu, Qi Zuo, Xiaodong Gu, Yuan Dong, Junfei Zhang, Chao Xu, Zhe Li, Weihao Yuan, Liefeng Bo, Guanying Chen, Zilong Dong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02684v1.pdf)  
  Keywords: 3D reconstruction, Controllable, Control, video generation  
- **[PhysMotion: Physics-Grounded Dynamics From a Single Image](https://arxiv.org/abs/2411.17189v2)**  
  Authors: Xiyang Tan, Ying Jiang, Xuan Li, Zeshun Zong, Tianyi Xie, Yin Yang, Chenfanfu Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.17189v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://supertan0204.github.io/physmotion_website/.)  
  Keywords: DiT, text-to-image, video generation  
- **[Automated 3D Physical Simulation of Open-world Scene with Gaussian Splatting](https://arxiv.org/abs/2411.12789v1)**  
  Authors: Haoyu Zhao, Hao Wang, Xingyue Zhao, Hongqiu Wang, Zhiyu Wu, Chengjiang Long, Hua Zou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.12789v1.pdf)  
  Keywords: 3D generation, video generation  
- **[MVSplat360: Feed-Forward 360 Scene Synthesis from Sparse Views](https://arxiv.org/abs/2411.04924v1)**  
  Authors: Yuedong Chen, Chuanxia Zheng, Haofei Xu, Bohan Zhuang, Andrea Vedaldi, Tat-Jen Cham, Jianfei Cai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.04924v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://donydchen.github.io/mvsplat360.)  
  Keywords: 3D reconstruction, video generation  
- **[3DGS-Enhancer: Enhancing Unbounded 3D Gaussian Splatting with View-consistent 2D Diffusion Priors](https://arxiv.org/abs/2410.16266v1)**  
  Authors: Xi Liu, Chaoyi Zhou, Siyu Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.16266v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://xiliu8006.github.io/3DGS-Enhancer-project)  
  Keywords: video generation  
- **[DriveDreamer4D: World Models Are Effective Data Machines for 4D Driving Scene Representation](https://arxiv.org/abs/2410.13571v3)**  
  Authors: Guosheng Zhao, Chaojun Ni, Xiaofeng Wang, Zheng Zhu, Xueyang Zhang, Yida Wang, Guan Huang, Xinze Chen, Boyuan Wang, Youyi Zhang, Wenjun Mei, Xingang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.13571v3.pdf)  
  Keywords: DiT, Control, video generation  
- **[Portrait Video Editing Empowered by Multimodal Generative Priors](https://arxiv.org/abs/2409.13591v1)**  
  Authors: Xuan Gao, Haiyao Xiao, Chenglai Zhong, Shimin Hu, Yudong Guo, Juyong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.13591v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ustc3dv.github.io/PortraitGen/)  
  Keywords: DiT, video editing  
- **[Hi3D: Pursuing High-Resolution Image-to-3D Generation with Video Diffusion Models](https://arxiv.org/abs/2409.07452v1)**  
  Authors: Haibo Yang, Yang Chen, Yingwei Pan, Ting Yao, Zhineng Chen, Chong-Wah Ngo, Tao Mei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.07452v1.pdf) | [![GitHub](https://img.shields.io/github/stars/yanghb22-fdu/Hi3D-Official?style=social)](https://github.com/yanghb22-fdu/Hi3D-Official)  
  Keywords: DiT, video generation, image generation, 3D reconstruction, 3D generation  
- **[Splatter a Video: Video Gaussian Representation for Versatile Processing](https://arxiv.org/abs/2406.13870v2)**  
  Authors: Yang-Tian Sun, Yi-Hua Huang, Lin Ma, Xiaoyang Lyu, Yan-Pei Cao, Xiaojuan Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.13870v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sunyangtian.github.io/spatter_a_video_web/)  
  Keywords: DiT, video generation  
- **[Enhancing Temporal Consistency in Video Editing by Reconstructing Videos with 3D Gaussian Splatting](https://arxiv.org/abs/2406.02541v3)**  
  Authors: Inkyu Shin, Qihang Yu, Xiaohui Shen, In So Kweon, Kuk-Jin Yoon, Liang-Chieh Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.02541v3.pdf)  
  Keywords: DiT, video editing  



## Classic Papers
- **[3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/)** (SIGGRAPH 2023)  
  Authors: Bernhard Kerbl, Georgios Kopanas, Thomas Leimkühler, George Drettakis  
  Code: 🔗 [GitHub](https://github.com/graphdeco-inria/gaussian-splatting)  
  Keywords: Real-time Rendering, Neural Rendering, Point-based Graphics

## Open Source Projects
- [gaussian-splatting](https://github.com/graphdeco-inria/gaussian-splatting) - Original implementation of 3D Gaussian Splatting
- [taichi-3d-gaussian-splatting](https://github.com/wanmeihuali/taichi-3d-gaussian-splatting) - 3D Gaussian Splatting implemented in Taichi

## Applications
- [3D Gaussian Splatting for Real-Time Radiance Field Rendering Demo](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) - Online Demo

## Tutorials & Blogs
- [Introduction to 3D Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting) - Official Tutorial

## Contribution Guidelines
Feel free to submit Pull Requests to improve this list! Please follow these formats:
- Paper entry format: `**[Paper Title](link)** - Brief description`
- Project entry format: `[Project Name](link) - Project description`

## License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/) 

## Acknowledgements
Thanks to [@longxiang-ai](https://github.com/longxiang-ai) for the template.
