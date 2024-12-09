# Awesome FLUX/DiT methods [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to DiT/FLUX. Content is automatically updated daily.

> Last Update: 2024-12-09 10:26:51

## Categories

- [Image Editing](#image-editing) (15 papers) - Papers about image editing with Diffusion Transformer or FLUX
- [Image Generation](#image-generation) (76 papers) - Papers focusing on image generation with Diffusion Transformer or FLUX
- [Video Related](#video-related) (42 papers) - Papers about video generation and editing with Diffusion Transformer or FLUX



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### Image Editing

- **[AMO Sampler: Enhancing Text Rendering with Overshooting](https://arxiv.org/abs/2411.19415v1)** (Published: 2024-11-28)  
  Authors: Xixi Hu, Keyang Xu, Bo Liu, Qiang Liu, Hongliang Fei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.19415v1.pdf)  
  Keywords: Control, text-to-image, FLUX, rectified flow, image generation  
- **[Prediction with Action: Visual Policy Learning via Joint Denoising Process](https://arxiv.org/abs/2411.18179v1)** (Published: 2024-11-27)  
  Authors: Yanjiang Guo, Yucheng Hu, Jianke Zhang, Yen-Jen Wang, Xiaoyu Chen, Chaochao Lu, Jianyu Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.18179v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sites.google.com/view/pad-paper)  
  Keywords: image editing, diffusion transformer, Control, image generation  
- **[HeadRouter: A Training-free Image Editing Framework for MM-DiTs by Adaptively Routing Attention Heads](https://arxiv.org/abs/2411.15034v1)** (Published: 2024-11-22)  
  Authors: Yu Xu, Fan Tang, Juan Cao, Yuxin Zhang, Xiaoyu Kong, Jintao Li, Oliver Deussen, Tong-Yee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.15034v1.pdf)  
  Keywords: image editing, diffusion transformer, image generation  
- **[Stable Flow: Vital Layers for Training-Free Image Editing](https://arxiv.org/abs/2411.14430v1)** (Published: 2024-11-21)  
  Authors: Omri Avrahami, Or Patashnik, Ohad Fried, Egor Nemchinov, Kfir Aberman, Dani Lischinski, Daniel Cohen-Or  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.14430v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://omriavrahami.com/stable-flow)  
  Keywords: image editing, diffusion transformer, Control  
- **[Oscillation Inversion: Understand the structure of Large Flow Model through the Lens of Inversion Method](https://arxiv.org/abs/2411.11135v1)** (Published: 2024-11-17)  
  Authors: Yan Zheng, Zhenxiao Liang, Xiaoyan Cong, Lanqing guo, Yuehao Wang, Peihao Wang, Zhangyang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.11135v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yanyanzheng96.github.io/oscillation_inversion/}{this)  
  Keywords: image editing, FLUX, rectified flow, text-to-image  
- **[Latent Space Disentanglement in Diffusion Transformers Enables Precise Zero-shot Semantic Editing](https://arxiv.org/abs/2411.08196v1)** (Published: 2024-11-12)  
  Authors: Zitao Shuai, Chenwei Wu, Zhengxu Tang, Bowen Song, Liyue Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.08196v1.pdf)  
  Keywords: image editing, diffusion transformer, Control, image generation  
- **[Taming Rectified Flow for Inversion and Editing](https://arxiv.org/abs/2411.04746v2)** (Published: 2024-11-07)  
  Authors: Jiangshan Wang, Junfu Pu, Zhongang Qi, Jiayi Guo, Yue Ma, Nisha Huang, Yuxin Chen, Xiu Li, Ying Shan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.04746v2.pdf) | [![GitHub](https://img.shields.io/github/stars/wangjiangshan0725/RF-Solver-Edit?style=social)](https://github.com/wangjiangshan0725/RF-Solver-Edit)  
  Keywords: FLUX, rectified flow, video generation, video editing, diffusion transformer  
- **[DiT4Edit: Diffusion Transformer for Image Editing](https://arxiv.org/abs/2411.03286v2)** (Published: 2024-11-05)  
  Authors: Kunyu Feng, Yue Ma, Bingyuan Wang, Chenyang Qi, Haozhe Chen, Qifeng Chen, Zeyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.03286v2.pdf)  
  Keywords: image editing, diffusion transformer, Control, image generation  
- **[FiTv2: Scalable and Improved Flexible Vision Transformer for Diffusion Model](https://arxiv.org/abs/2410.13925v1)** (Published: 2024-10-17)  
  Authors: ZiDong Wang, Zeyu Lu, Di Huang, Cai Zhou, Wanli Ouyang, and Lei Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.13925v1.pdf) | [![GitHub](https://img.shields.io/github/stars/whlzy/FiT?style=social)](https://github.com/whlzy/FiT)  
  Keywords: diffusion transformer, rectified flow, image generation  
- **[Semantic Image Inversion and Editing using Rectified Stochastic Differential Equations](https://arxiv.org/abs/2410.10792v1)** (Published: 2024-10-14)  
  Authors: Litu Rout, Yujia Chen, Nataniel Ruiz, Constantine Caramanis, Sanjay Shakkottai, Wen-Sheng Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.10792v1.pdf)  
  Keywords: image editing, Control, FLUX, rectified flow  

### Image Generation

*Showing the latest 50 out of 76 papers*

- **[Mind the Time: Temporally-Controlled Multi-Event Video Generation](https://arxiv.org/abs/2412.05263v1)** (Published: 2024-12-06)  
  Authors: Ziyi Wu, Aliaksandr Siarohin, Willi Menapace, Ivan Skorokhodov, Yuwei Fang, Varnith Chordia, Igor Gilitschenski, Sergey Tulyakov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05263v1.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[CreatiLayout: Siamese Multimodal Diffusion Transformer for Creative Layout-to-Image Generation](https://arxiv.org/abs/2412.03859v1)** (Published: 2024-12-05)  
  Authors: Hui Zhang, Dexiang Hong, Tingwei Gao, Yitong Wang, Jie Shao, Xinglong Wu, Zuxuan Wu, Yu-Gang Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03859v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://creatilayout.github.io.)  
  Keywords: Controllable, diffusion transformer, Control, image generation  
- **[Navigation World Models](https://arxiv.org/abs/2412.03572v1)** (Published: 2024-12-04)  
  Authors: Amir Bar, Gaoyue Zhou, Danny Tran, Trevor Darrell, Yann LeCun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03572v1.pdf)  
  Keywords: Controllable, diffusion transformer, Control, video generation  
- **[Seeing Beyond Views: Multi-View Driving Scene Video Generation with Holistic Attention](https://arxiv.org/abs/2412.03520v1)** (Published: 2024-12-04)  
  Authors: Hannan Lu, Xiaohe Wu, Shudong Wang, Xiameng Qin, Xinyu Zhang, Junyu Han, Wangmeng Zuo, Ji Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03520v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://luhannan.github.io/CogDrivingPage/.)  
  Keywords: video generation, diffusion transformer, Control, ControlNet  
- **[Panoptic Diffusion Models: co-generation of images and segmentation maps](https://arxiv.org/abs/2412.02929v1)** (Published: 2024-12-04)  
  Authors: Yinghan Long, Kaushik Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02929v1.pdf)  
  Keywords: diffusion transformer, Control, image generation  
- **[Generative Photography: Scene-Consistent Camera Control for Realistic Text-to-Image Synthesis](https://arxiv.org/abs/2412.02168v2)** (Published: 2024-12-03)  
  Authors: Yu Yuan, Xijun Wang, Yichen Sheng, Prateek Chennuri, Xingguang Zhang, Stanley Chan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02168v2.pdf)  
  Keywords: Control, FLUX, image generation, text-to-image  
- **[World-consistent Video Diffusion with Explicit 3D Modeling](https://arxiv.org/abs/2412.01821v1)** (Published: 2024-12-02)  
  Authors: Qihang Zhang, Shuangfei Zhai, Miguel Angel Bautista, Kevin Miao, Alexander Toshev, Joshua Susskind, Jiatao Gu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01821v1.pdf)  
  Keywords: video generation, diffusion transformer, Control, image generation  
- **[CPA: Camera-pose-awareness Diffusion Transformer for Video Generation](https://arxiv.org/abs/2412.01429v1)** (Published: 2024-12-02)  
  Authors: Yuelei Wang, Jian Zhang, Pengtao Jiang, Hao Zhang, Jinwei Chen, Bo Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01429v1.pdf)  
  Keywords: Controllable, diffusion transformer, Control, video generation  
- **[TinyFusion: Diffusion Transformers Learned Shallow](https://arxiv.org/abs/2412.01199v1)** (Published: 2024-12-02)  
  Authors: Gongfan Fang, Kunjun Li, Xinyin Ma, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01199v1.pdf) | [![GitHub](https://img.shields.io/github/stars/VainF/TinyFusion?style=social)](https://github.com/VainF/TinyFusion)  
  Keywords: diffusion transformer, image generation  
- **[AMO Sampler: Enhancing Text Rendering with Overshooting](https://arxiv.org/abs/2411.19415v1)** (Published: 2024-11-28)  
  Authors: Xixi Hu, Keyang Xu, Bo Liu, Qiang Liu, Hongliang Fei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.19415v1.pdf)  
  Keywords: Control, text-to-image, FLUX, rectified flow, image generation  

### Video Related

- **[Mind the Time: Temporally-Controlled Multi-Event Video Generation](https://arxiv.org/abs/2412.05263v1)** (Published: 2024-12-06)  
  Authors: Ziyi Wu, Aliaksandr Siarohin, Willi Menapace, Ivan Skorokhodov, Yuwei Fang, Varnith Chordia, Igor Gilitschenski, Sergey Tulyakov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05263v1.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[Navigation World Models](https://arxiv.org/abs/2412.03572v1)** (Published: 2024-12-04)  
  Authors: Amir Bar, Gaoyue Zhou, Danny Tran, Trevor Darrell, Yann LeCun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03572v1.pdf)  
  Keywords: Controllable, diffusion transformer, Control, video generation  
- **[Seeing Beyond Views: Multi-View Driving Scene Video Generation with Holistic Attention](https://arxiv.org/abs/2412.03520v1)** (Published: 2024-12-04)  
  Authors: Hannan Lu, Xiaohe Wu, Shudong Wang, Xiameng Qin, Xinyu Zhang, Junyu Han, Wangmeng Zuo, Ji Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03520v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://luhannan.github.io/CogDrivingPage/.)  
  Keywords: video generation, diffusion transformer, Control, ControlNet  
- **[World-consistent Video Diffusion with Explicit 3D Modeling](https://arxiv.org/abs/2412.01821v1)** (Published: 2024-12-02)  
  Authors: Qihang Zhang, Shuangfei Zhai, Miguel Angel Bautista, Kevin Miao, Alexander Toshev, Joshua Susskind, Jiatao Gu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01821v1.pdf)  
  Keywords: video generation, diffusion transformer, Control, image generation  
- **[CPA: Camera-pose-awareness Diffusion Transformer for Video Generation](https://arxiv.org/abs/2412.01429v1)** (Published: 2024-12-02)  
  Authors: Yuelei Wang, Jian Zhang, Pengtao Jiang, Hao Zhang, Jinwei Chen, Bo Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01429v1.pdf)  
  Keywords: Controllable, diffusion transformer, Control, video generation  
- **[OpenHumanVid: A Large-Scale High-Quality Dataset for Enhancing Human-Centric Video Generation](https://arxiv.org/abs/2412.00115v2)** (Published: 2024-11-28)  
  Authors: Hui Li, Mingwang Xu, Yun Zhan, Shan Mu, Jiaye Li, Kaihui Cheng, Yuxuan Chen, Tan Chen, Mao Ye, Jingdong Wang, Siyu Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.00115v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://fudan-generative-vision.github.io/OpenHumanVid)  
  Keywords: diffusion transformer, video generation  
- **[AC3D: Analyzing and Improving 3D Camera Control in Video Diffusion Transformers](https://arxiv.org/abs/2411.18673v2)** (Published: 2024-11-27)  
  Authors: Sherwin Bahmani, Ivan Skorokhodov, Guocheng Qian, Aliaksandr Siarohin, Willi Menapace, Andrea Tagliasacchi, David B. Lindell, Sergey Tulyakov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.18673v2.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[Accelerating Vision Diffusion Transformers with Skip Branches](https://arxiv.org/abs/2411.17616v2)** (Published: 2024-11-26)  
  Authors: Guanjie Chen, Xinyu Zhao, Yucheng Zhou, Tianlong Chen, Yu Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.17616v2.pdf) | [![GitHub](https://img.shields.io/github/stars/OpenSparseLLMs/Skip-DiT.git?style=social)](https://github.com/OpenSparseLLMs/Skip-DiT.git)  
  Keywords: video generation, diffusion transformer, image generation  
- **[Identity-Preserving Text-to-Video Generation by Frequency Decomposition](https://arxiv.org/abs/2411.17440v2)** (Published: 2024-11-26)  
  Authors: Shenghai Yuan, Jinfa Huang, Xianyi He, Yunyuan Ge, Yujun Shi, Liuhan Chen, Jiebo Luo, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.17440v2.pdf)  
  Keywords: Controllable, diffusion transformer, Control, video generation  
- **[LetsTalk: Latent Diffusion Transformer for Talking Video Synthesis](https://arxiv.org/abs/2411.16748v1)** (Published: 2024-11-24)  
  Authors: Haojie Zhang, Zhihao Liang, Ruibo Fu, Zhengqi Wen, Xuefei Liu, Chenxing Li, Jianhua Tao, Yaling Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.16748v1.pdf)  
  Keywords: diffusion transformer, video generation  



## Classic Papers
- **[Scalable Diffusion Models with Transformers](https://arxiv.org/abs/2212.09748)** (ICCV 2023)
  Authors: William Peebles, Saining Xie  
  Code: 🔗 [GitHub](https://github.com/facebookresearch/DiT)  
  Keywords: diffusion model, transformer architecture

## Open Source Projects

## Applications


## Tutorials & Blogs


## Contribution Guidelines
Feel free to submit Pull Requests to improve this list! Please follow these formats:
- Paper entry format: `**[Paper Title](link)** - Brief description`
- Project entry format: `[Project Name](link) - Project description`

## License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/) 

## Acknowledgements
Thanks to [@longxiang-ai](https://github.com/longxiang-ai) for the template.
