# Awesome FLUX/DiT methods [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to DiT/FLUX. Content is automatically updated daily.

> Last Update: 2024-12-30 06:30:11

Thanks to [@longxiang-ai](https://github.com/longxiang-ai) for the template.

## Categories

- [Image Editing](#image-editing) (17 papers) - Papers about image editing with Diffusion Transformer or FLUX
- [Image Generation](#image-generation) (92 papers) - Papers focusing on image generation with Diffusion Transformer or FLUX
- [Video Related](#video-related) (54 papers) - Papers about video generation and editing with Diffusion Transformer or FLUX



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### Image Editing

- **[Context Canvas: Enhancing Text-to-Image Diffusion Models with Knowledge Graph-Based RAG](https://arxiv.org/abs/2412.09614v1)** (Published: 2024-12-12)  
  Authors: Kavana Venkatesh, Yusuf Dalva, Ismini Lourentzou, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09614v1.pdf)  
  Keywords: image editing, text-to-image, FLUX, Control  
- **[FluxSpace: Disentangled Semantic Editing in Rectified Flow Transformers](https://arxiv.org/abs/2412.09611v1)** (Published: 2024-12-12)  
  Authors: Yusuf Dalva, Kavana Venkatesh, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09611v1.pdf)  
  Keywords: rectified flow, FLUX, image generation, image editing, Control  
- **[AMO Sampler: Enhancing Text Rendering with Overshooting](https://arxiv.org/abs/2411.19415v1)** (Published: 2024-11-28)  
  Authors: Xixi Hu, Keyang Xu, Bo Liu, Qiang Liu, Hongliang Fei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.19415v1.pdf)  
  Keywords: rectified flow, FLUX, text-to-image, image generation, Control  
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
  Keywords: image editing, inversion, diffusion transformer, Control  
- **[Oscillation Inversion: Understand the structure of Large Flow Model through the Lens of Inversion Method](https://arxiv.org/abs/2411.11135v1)** (Published: 2024-11-17)  
  Authors: Yan Zheng, Zhenxiao Liang, Xiaoyan Cong, Lanqing guo, Yuehao Wang, Peihao Wang, Zhangyang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.11135v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yanyanzheng96.github.io/oscillation_inversion/}{this)  
  Keywords: rectified flow, FLUX, text-to-image, inversion, image editing  
- **[Latent Space Disentanglement in Diffusion Transformers Enables Precise Zero-shot Semantic Editing](https://arxiv.org/abs/2411.08196v1)** (Published: 2024-11-12)  
  Authors: Zitao Shuai, Chenwei Wu, Zhengxu Tang, Bowen Song, Liyue Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.08196v1.pdf)  
  Keywords: image editing, diffusion transformer, Control, image generation  
- **[Taming Rectified Flow for Inversion and Editing](https://arxiv.org/abs/2411.04746v2)** (Published: 2024-11-07)  
  Authors: Jiangshan Wang, Junfu Pu, Zhongang Qi, Jiayi Guo, Yue Ma, Nisha Huang, Yuxin Chen, Xiu Li, Ying Shan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.04746v2.pdf) | [![GitHub](https://img.shields.io/github/stars/wangjiangshan0725/RF-Solver-Edit?style=social)](https://github.com/wangjiangshan0725/RF-Solver-Edit)  
  Keywords: rectified flow, FLUX, video editing, video generation, diffusion transformer, inversion  
- **[DiT4Edit: Diffusion Transformer for Image Editing](https://arxiv.org/abs/2411.03286v2)** (Published: 2024-11-05)  
  Authors: Kunyu Feng, Yue Ma, Bingyuan Wang, Chenyang Qi, Haozhe Chen, Qifeng Chen, Zeyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.03286v2.pdf)  
  Keywords: diffusion transformer, inversion, image generation, image editing, Control  
- **[FiTv2: Scalable and Improved Flexible Vision Transformer for Diffusion Model](https://arxiv.org/abs/2410.13925v1)** (Published: 2024-10-17)  
  Authors: ZiDong Wang, Zeyu Lu, Di Huang, Cai Zhou, Wanli Ouyang, and Lei Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.13925v1.pdf) | [![GitHub](https://img.shields.io/github/stars/whlzy/FiT?style=social)](https://github.com/whlzy/FiT)  
  Keywords: rectified flow, diffusion transformer, image generation  
- **[Semantic Image Inversion and Editing using Rectified Stochastic Differential Equations](https://arxiv.org/abs/2410.10792v1)** (Published: 2024-10-14)  
  Authors: Litu Rout, Yujia Chen, Nataniel Ruiz, Constantine Caramanis, Sanjay Shakkottai, Wen-Sheng Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.10792v1.pdf)  
  Keywords: rectified flow, FLUX, inversion, image editing, Control  
- **[Effective Diffusion Transformer Architecture for Image Super-Resolution](https://arxiv.org/abs/2409.19589v1)** (Published: 2024-09-29)  
  Authors: Kun Cheng, Lei Yu, Zhijun Tu, Xiao He, Liyu Chen, Yong Guo, Mingrui Zhu, Nannan Wang, Xinbo Gao, Jie Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.19589v1.pdf)  
  Keywords: image super-resolution, diffusion transformer, image generation  
- **[PixWizard: Versatile Image-to-Image Visual Assistant with Open-Language Instructions](https://arxiv.org/abs/2409.15278v2)** (Published: 2024-09-23)  
  Authors: Weifeng Lin, Xinyu Wei, Renrui Zhang, Le Zhuo, Shitian Zhao, Siyuan Huang, Junlin Xie, Yu Qiao, Peng Gao, Hongsheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.15278v2.pdf) | [![GitHub](https://img.shields.io/github/stars/AFeng-x/PixWizard?style=social)](https://github.com/AFeng-x/PixWizard)  
  Keywords: text-to-image, diffusion transformer, Controllable, image generation, image editing, Control  
- **[Latent Space Disentanglement in Diffusion Transformers Enables Zero-shot Fine-grained Semantic Editing](https://arxiv.org/abs/2408.13335v1)** (Published: 2024-08-23)  
  Authors: Zitao Shuai, Chenwei Wu, Zhengxu Tang, Bowen Song, Liyue Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.13335v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://anonymous.com/anonymous/EMS-Benchmark,)  
  Keywords: image editing, text-to-image, diffusion transformer, Control  
- **[Lazy Diffusion Transformer for Interactive Image Editing](https://arxiv.org/abs/2404.12382v1)** (Published: 2024-04-18)  
  Authors: Yotam Nitzan, Zongze Wu, Richard Zhang, Eli Shechtman, Daniel Cohen-Or, Taesung Park, Michaël Gharbi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2404.12382v1.pdf)  
  Keywords: image editing, diffusion transformer  
- **[Lightning-Fast Image Inversion and Editing for Text-to-Image Diffusion Models](https://arxiv.org/abs/2312.12540v4)** (Published: 2023-12-19)  
  Authors: Dvir Samuel, Barak Meiri, Haggai Maron, Yoad Tewel, Nir Darshan, Shai Avidan, Gal Chechik, Rami Ben-Ari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2312.12540v4.pdf)  
  Keywords: image editing, text-to-image, FLUX, inversion  

### Image Generation

*Showing the latest 50 out of 92 papers*

- **[UNIC-Adapter: Unified Image-instruction Adapter with Multi-modal Transformer for Image Generation](https://arxiv.org/abs/2412.18928v1)** (Published: 2024-12-25)  
  Authors: Lunhao Duan, Shanshan Zhao, Wenjun Yan, Yinglun Li, Qing-Guo Chen, Zhao Xu, Weihua Luo, Kaifu Zhang, Mingming Gong, Gui-Song Xia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18928v1.pdf)  
  Keywords: text-to-image, diffusion transformer, Controllable, image generation, Control  
- **[1.58-bit FLUX](https://arxiv.org/abs/2412.18653v1)** (Published: 2024-12-24)  
  Authors: Chenglin Yang, Celong Liu, Xueqing Deng, Dongwon Kim, Xing Mei, Xiaohui Shen, Liang-Chieh Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18653v1.pdf)  
  Keywords: text-to-image, FLUX, image generation  
- **[DiTCtrl: Exploring Attention Control in Multi-Modal Diffusion Transformer for Tuning-Free Multi-Prompt Longer Video Generation](https://arxiv.org/abs/2412.18597v1)** (Published: 2024-12-24)  
  Authors: Minghong Cai, Xiaodong Cun, Xiaoyu Li, Wenze Liu, Zhaoyang Zhang, Yong Zhang, Ying Shan, Xiangyu Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18597v1.pdf)  
  Keywords: video editing, diffusion transformer, Control, video generation  
- **[Layer- and Timestep-Adaptive Differentiable Token Compression Ratios for Efficient Diffusion Transformers](https://arxiv.org/abs/2412.16822v1)** (Published: 2024-12-22)  
  Authors: Haoran You, Connelly Barnes, Yuqian Zhou, Yan Kang, Zhenbang Du, Wei Zhou, Lingzhi Zhang, Yotam Nitzan, Xiaoyang Liu, Zhe Lin, Eli Shechtman, Sohrab Amirghodsi, Yingyan Celine Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.16822v1.pdf)  
  Keywords: text-to-image, diffusion transformer, image generation  
- **[CLEAR: Conv-Like Linearization Revs Pre-Trained Diffusion Transformers Up](https://arxiv.org/abs/2412.16112v1)** (Published: 2024-12-20)  
  Authors: Songhua Liu, Zhenxiong Tan, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.16112v1.pdf) | [![GitHub](https://img.shields.io/github/stars/Huage001/CLEAR?style=social)](https://github.com/Huage001/CLEAR)  
  Keywords: diffusion transformer, image generation  
- **[Efficient Scaling of Diffusion Transformers for Text-to-Image Generation](https://arxiv.org/abs/2412.12391v1)** (Published: 2024-12-16)  
  Authors: Hao Li, Shamit Lal, Zhiheng Li, Yusheng Xie, Ying Wang, Yang Zou, Orchid Majumder, R. Manmatha, Zhuowen Tu, Stefano Ermon, Stefano Soatto, Ashwin Swaminathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.12391v1.pdf)  
  Keywords: text-to-image, diffusion transformer, Control, image generation  
- **[Causal Diffusion Transformers for Generative Modeling](https://arxiv.org/abs/2412.12095v2)** (Published: 2024-12-16)  
  Authors: Chaorui Deng, Deyao Zhu, Kunchang Li, Shi Guang, Haoqi Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.12095v2.pdf)  
  Keywords: diffusion transformer, image generation  
- **[Video Diffusion Transformers are In-Context Learners](https://arxiv.org/abs/2412.10783v2)** (Published: 2024-12-14)  
  Authors: Zhengcong Fei, Di Qiu, Changqian Yu, Debang Li, Mingyuan Fan, Xiang Wen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.10783v2.pdf) | [![GitHub](https://img.shields.io/github/stars/feizc/Video-In-Context?style=social)](https://github.com/feizc/Video-In-Context)  
  Keywords: Controllable, diffusion transformer, Control, video generation  
- **[MSC: Multi-Scale Spatio-Temporal Causal Attention for Autoregressive Video Diffusion](https://arxiv.org/abs/2412.09828v1)** (Published: 2024-12-13)  
  Authors: Xunnong Xu, Mengying Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09828v1.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[Context Canvas: Enhancing Text-to-Image Diffusion Models with Knowledge Graph-Based RAG](https://arxiv.org/abs/2412.09614v1)** (Published: 2024-12-12)  
  Authors: Kavana Venkatesh, Yusuf Dalva, Ismini Lourentzou, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09614v1.pdf)  
  Keywords: image editing, text-to-image, FLUX, Control  
- **[FluxSpace: Disentangled Semantic Editing in Rectified Flow Transformers](https://arxiv.org/abs/2412.09611v1)** (Published: 2024-12-12)  
  Authors: Yusuf Dalva, Kavana Venkatesh, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09611v1.pdf)  
  Keywords: rectified flow, FLUX, image generation, image editing, Control  
- **[Multimodal Latent Language Modeling with Next-Token Diffusion](https://arxiv.org/abs/2412.08635v1)** (Published: 2024-12-11)  
  Authors: Yutao Sun, Hangbo Bao, Wenhui Wang, Zhiliang Peng, Li Dong, Shaohan Huang, Jianyong Wang, Furu Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.08635v1.pdf)  
  Keywords: diffusion transformer, image generation  
- **[FlexDiT: Dynamic Token Density Control for Diffusion Transformer](https://arxiv.org/abs/2412.06028v1)** (Published: 2024-12-08)  
  Authors: Shuning Chang, Pichao Wang, Jiasheng Tang, Yi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.06028v1.pdf)  
  Keywords: video generation, text-to-image, diffusion transformer, image generation, Control  
- **[MotionStone: Decoupled Motion Intensity Modulation with Diffusion Transformer for Image-to-Video Generation](https://arxiv.org/abs/2412.05848v1)** (Published: 2024-12-08)  
  Authors: Shuwei Shi, Biao Gong, Xi Chen, Dandan Zheng, Shuai Tan, Zizheng Yang, Yuyuan Li, Jingwen He, Kecheng Zheng, Jingdong Chen, Ming Yang, Yinqiang Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05848v1.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[Self-Guidance: Boosting Flow and Diffusion Generation on Their Own](https://arxiv.org/abs/2412.05827v1)** (Published: 2024-12-08)  
  Authors: Tiancheng Li, Weijian Luo, Zhiyang Chen, Liyuan Ma, Guo-Jun Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05827v1.pdf)  
  Keywords: FLUX, video generation, text-to-image, diffusion transformer, image generation  
- **[Language-Guided Image Tokenization for Generation](https://arxiv.org/abs/2412.05796v1)** (Published: 2024-12-08)  
  Authors: Kaiwen Zha, Lijun Yu, Alireza Fathi, David A. Ross, Cordelia Schmid, Dina Katabi, Xiuye Gu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05796v1.pdf)  
  Keywords: text-to-image, diffusion transformer, image generation  
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
- **[Seeing Beyond Views: Multi-View Driving Scene Video Generation with Holistic Attention](https://arxiv.org/abs/2412.03520v2)** (Published: 2024-12-04)  
  Authors: Hannan Lu, Xiaohe Wu, Shudong Wang, Xiameng Qin, Xinyu Zhang, Junyu Han, Wangmeng Zuo, Ji Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03520v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://luhannan.github.io/CogDrivingPage/.)  
  Keywords: diffusion transformer, Control, video generation  
- **[Panoptic Diffusion Models: co-generation of images and segmentation maps](https://arxiv.org/abs/2412.02929v1)** (Published: 2024-12-04)  
  Authors: Yinghan Long, Kaushik Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02929v1.pdf)  
  Keywords: diffusion transformer, Control, image generation  
- **[Generative Photography: Scene-Consistent Camera Control for Realistic Text-to-Image Synthesis](https://arxiv.org/abs/2412.02168v2)** (Published: 2024-12-03)  
  Authors: Yu Yuan, Xijun Wang, Yichen Sheng, Prateek Chennuri, Xingguang Zhang, Stanley Chan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02168v2.pdf)  
  Keywords: text-to-image, FLUX, Control, image generation  
- **[World-consistent Video Diffusion with Explicit 3D Modeling](https://arxiv.org/abs/2412.01821v1)** (Published: 2024-12-02)  
  Authors: Qihang Zhang, Shuangfei Zhai, Miguel Angel Bautista, Kevin Miao, Alexander Toshev, Joshua Susskind, Jiatao Gu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01821v1.pdf)  
  Keywords: diffusion transformer, Control, video generation, image generation  
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
  Keywords: rectified flow, FLUX, text-to-image, image generation, Control  
- **[AC3D: Analyzing and Improving 3D Camera Control in Video Diffusion Transformers](https://arxiv.org/abs/2411.18673v2)** (Published: 2024-11-27)  
  Authors: Sherwin Bahmani, Ivan Skorokhodov, Guocheng Qian, Aliaksandr Siarohin, Willi Menapace, Andrea Tagliasacchi, David B. Lindell, Sergey Tulyakov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.18673v2.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[Prediction with Action: Visual Policy Learning via Joint Denoising Process](https://arxiv.org/abs/2411.18179v1)** (Published: 2024-11-27)  
  Authors: Yanjiang Guo, Yucheng Hu, Jianke Zhang, Yen-Jen Wang, Xiaoyu Chen, Chaochao Lu, Jianyu Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.18179v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sites.google.com/view/pad-paper)  
  Keywords: image editing, diffusion transformer, Control, image generation  
- **[Type-R: Automatically Retouching Typos for Text-to-Image Generation](https://arxiv.org/abs/2411.18159v1)** (Published: 2024-11-27)  
  Authors: Wataru Shimoda, Naoto Inoue, Daichi Haraguchi, Hayato Mitani, Seichi Uchida, Kota Yamaguchi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.18159v1.pdf)  
  Keywords: text-to-image, FLUX, image generation  
- **[Accelerating Vision Diffusion Transformers with Skip Branches](https://arxiv.org/abs/2411.17616v2)** (Published: 2024-11-26)  
  Authors: Guanjie Chen, Xinyu Zhao, Yucheng Zhou, Tianlong Chen, Yu Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.17616v2.pdf) | [![GitHub](https://img.shields.io/github/stars/OpenSparseLLMs/Skip-DiT.git?style=social)](https://github.com/OpenSparseLLMs/Skip-DiT.git)  
  Keywords: diffusion transformer, video generation, image generation  
- **[Identity-Preserving Text-to-Video Generation by Frequency Decomposition](https://arxiv.org/abs/2411.17440v2)** (Published: 2024-11-26)  
  Authors: Shenghai Yuan, Jinfa Huang, Xianyi He, Yunyuan Ge, Yujun Shi, Liuhan Chen, Jiebo Luo, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.17440v2.pdf)  
  Keywords: Controllable, diffusion transformer, Control, video generation  
- **[OminiControl: Minimal and Universal Control for Diffusion Transformer](https://arxiv.org/abs/2411.15098v3)** (Published: 2024-11-22)  
  Authors: Zhenxiong Tan, Songhua Liu, Xingyi Yang, Qiaochu Xue, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.15098v3.pdf)  
  Keywords: diffusion transformer, Control  
- **[HeadRouter: A Training-free Image Editing Framework for MM-DiTs by Adaptively Routing Attention Heads](https://arxiv.org/abs/2411.15034v1)** (Published: 2024-11-22)  
  Authors: Yu Xu, Fan Tang, Juan Cao, Yuxin Zhang, Xiaoyu Kong, Jintao Li, Oliver Deussen, Tong-Yee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.15034v1.pdf)  
  Keywords: image editing, diffusion transformer, image generation  
- **[Stable Flow: Vital Layers for Training-Free Image Editing](https://arxiv.org/abs/2411.14430v1)** (Published: 2024-11-21)  
  Authors: Omri Avrahami, Or Patashnik, Ohad Fried, Egor Nemchinov, Kfir Aberman, Dani Lischinski, Daniel Cohen-Or  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.14430v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://omriavrahami.com/stable-flow)  
  Keywords: image editing, inversion, diffusion transformer, Control  
- **[Oscillation Inversion: Understand the structure of Large Flow Model through the Lens of Inversion Method](https://arxiv.org/abs/2411.11135v1)** (Published: 2024-11-17)  
  Authors: Yan Zheng, Zhenxiao Liang, Xiaoyan Cong, Lanqing guo, Yuehao Wang, Peihao Wang, Zhangyang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.11135v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yanyanzheng96.github.io/oscillation_inversion/}{this)  
  Keywords: rectified flow, FLUX, text-to-image, inversion, image editing  
- **[SmoothCache: A Universal Inference Acceleration Technique for Diffusion Transformers](https://arxiv.org/abs/2411.10510v1)** (Published: 2024-11-15)  
  Authors: Joseph Liu, Joshua Geddes, Ziyu Guo, Haomiao Jiang, Mahesh Kumar Nandwana  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.10510v1.pdf)  
  Keywords: diffusion transformer, image generation  
- **[Latent Space Disentanglement in Diffusion Transformers Enables Precise Zero-shot Semantic Editing](https://arxiv.org/abs/2411.08196v1)** (Published: 2024-11-12)  
  Authors: Zitao Shuai, Chenwei Wu, Zhengxu Tang, Bowen Song, Liyue Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.08196v1.pdf)  
  Keywords: image editing, diffusion transformer, Control, image generation  
- **[DiT4Edit: Diffusion Transformer for Image Editing](https://arxiv.org/abs/2411.03286v2)** (Published: 2024-11-05)  
  Authors: Kunyu Feng, Yue Ma, Bingyuan Wang, Chenyang Qi, Haozhe Chen, Qifeng Chen, Zeyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.03286v2.pdf)  
  Keywords: diffusion transformer, inversion, image generation, image editing, Control  
- **[Adaptive Caching for Faster Video Generation with Diffusion Transformers](https://arxiv.org/abs/2411.02397v2)** (Published: 2024-11-04)  
  Authors: Kumara Kahatapitiya, Haozhe Liu, Sen He, Ding Liu, Menglin Jia, Chenyang Zhang, Michael S. Ryoo, Tian Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.02397v2.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[Training-free Regional Prompting for Diffusion Transformers](https://arxiv.org/abs/2411.02395v1)** (Published: 2024-11-04)  
  Authors: Anthony Chen, Jianjin Xu, Wenzhao Zheng, Gaole Dai, Yida Wang, Renrui Zhang, Haofan Wang, Shanghang Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.02395v1.pdf) | [![GitHub](https://img.shields.io/github/stars/antonioo-c/Regional-Prompting-FLUX?style=social)](https://github.com/antonioo-c/Regional-Prompting-FLUX)  
  Keywords: text-to-image, FLUX, diffusion transformer, image generation  
- **[GameGen-X: Interactive Open-world Game Video Generation](https://arxiv.org/abs/2411.00769v3)** (Published: 2024-11-01)  
  Authors: Haoxuan Che, Xuanhua He, Quande Liu, Cheng Jin, Hao Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.00769v3.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[In-Context LoRA for Diffusion Transformers](https://arxiv.org/abs/2410.23775v3)** (Published: 2024-10-31)  
  Authors: Lianghua Huang, Wei Wang, Zhi-Fan Wu, Yupeng Shi, Huanzhang Dou, Chen Liang, Yutong Feng, Yu Liu, Jingren Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.23775v3.pdf) | [![GitHub](https://img.shields.io/github/stars/ali-vilab/In-Context-LoRA?style=social)](https://github.com/ali-vilab/In-Context-LoRA)  
  Keywords: text-to-image, diffusion transformer, image generation  
- **[Diffusion Beats Autoregressive: An Evaluation of Compositional Generation in Text-to-Image Models](https://arxiv.org/abs/2410.22775v1)** (Published: 2024-10-30)  
  Authors: Arash Marioriyad, Parham Rezaei, Mahdieh Soleymani Baghshah, Mohammad Hossein Rohban  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.22775v1.pdf)  
  Keywords: text-to-image, FLUX, image generation  
- **[Diff-Instruct*: Towards Human-Preferred One-step Text-to-image Generative Models](https://arxiv.org/abs/2410.20898v2)** (Published: 2024-10-28)  
  Authors: Weijian Luo, Colin Zhang, Debing Zhang, Zhengyang Geng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.20898v2.pdf) | [![GitHub](https://img.shields.io/github/stars/pkulwj1994/diff_instruct_star?style=social)](https://github.com/pkulwj1994/diff_instruct_star)  
  Keywords: text-to-image, FLUX  
- **[GrounDiT: Grounding Diffusion Transformers via Noisy Patch Transplantation](https://arxiv.org/abs/2410.20474v2)** (Published: 2024-10-27)  
  Authors: Phillip Y. Lee, Taehoon Yoon, Minhyuk Sung  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.20474v2.pdf)  
  Keywords: text-to-image, diffusion transformer, Control, image generation  
- **[FiTv2: Scalable and Improved Flexible Vision Transformer for Diffusion Model](https://arxiv.org/abs/2410.13925v1)** (Published: 2024-10-17)  
  Authors: ZiDong Wang, Zeyu Lu, Di Huang, Cai Zhou, Wanli Ouyang, and Lei Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.13925v1.pdf) | [![GitHub](https://img.shields.io/github/stars/whlzy/FiT?style=social)](https://github.com/whlzy/FiT)  
  Keywords: rectified flow, diffusion transformer, image generation  
- **[Boosting Camera Motion Control for Video Diffusion Transformers](https://arxiv.org/abs/2410.10802v1)** (Published: 2024-10-14)  
  Authors: Soon Yau Cheong, Duygu Ceylan, Armin Mustafa, Andrew Gilbert, Chun-Hao Paul Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.10802v1.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[Semantic Image Inversion and Editing using Rectified Stochastic Differential Equations](https://arxiv.org/abs/2410.10792v1)** (Published: 2024-10-14)  
  Authors: Litu Rout, Yujia Chen, Nataniel Ruiz, Constantine Caramanis, Sanjay Shakkottai, Wen-Sheng Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.10792v1.pdf)  
  Keywords: rectified flow, FLUX, inversion, image editing, Control  
- **[Scaling Laws For Diffusion Transformers](https://arxiv.org/abs/2410.08184v1)** (Published: 2024-10-10)  
  Authors: Zhengyang Liang, Hao He, Ceyuan Yang, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.08184v1.pdf)  
  Keywords: text-to-image, diffusion transformer, video generation, image generation  
- **[IterComp: Iterative Composition-Aware Feedback Learning from Model Gallery for Text-to-Image Generation](https://arxiv.org/abs/2410.07171v1)** (Published: 2024-10-09)  
  Authors: Xinchen Zhang, Ling Yang, Guohao Li, Yaqi Cai, Jiake Xie, Yong Tang, Yujiu Yang, Mengdi Wang, Bin Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.07171v1.pdf) | [![GitHub](https://img.shields.io/github/stars/YangLing0818/IterComp?style=social)](https://github.com/YangLing0818/IterComp)  
  Keywords: text-to-image, FLUX, image generation  

### Video Related

*Showing the latest 50 out of 54 papers*

- **[Accelerating Diffusion Transformers with Dual Feature Caching](https://arxiv.org/abs/2412.18911v1)** (Published: 2024-12-25)  
  Authors: Chang Zou, Evelyn Zhang, Runlin Guo, Haohang Xu, Conghui He, Xuming Hu, Linfeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18911v1.pdf) | [![GitHub](https://img.shields.io/github/stars/Shenyi-Z/DuCa?style=social)](https://github.com/Shenyi-Z/DuCa)  
  Keywords: diffusion transformer, video generation  
- **[DiTCtrl: Exploring Attention Control in Multi-Modal Diffusion Transformer for Tuning-Free Multi-Prompt Longer Video Generation](https://arxiv.org/abs/2412.18597v1)** (Published: 2024-12-24)  
  Authors: Minghong Cai, Xiaodong Cun, Xiaoyu Li, Wenze Liu, Zhaoyang Zhang, Yong Zhang, Ying Shan, Xiangyu Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18597v1.pdf)  
  Keywords: video editing, diffusion transformer, Control, video generation  
- **[FFA Sora, video generation as fundus fluorescein angiography simulator](https://arxiv.org/abs/2412.17346v1)** (Published: 2024-12-23)  
  Authors: Xinyuan Wu, Lili Wang, Ruoyu Chen, Bowen Liu, Weiyi Zhang, Xi Yang, Yifan Feng, Mingguang He, Danli Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.17346v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[Video Diffusion Transformers are In-Context Learners](https://arxiv.org/abs/2412.10783v2)** (Published: 2024-12-14)  
  Authors: Zhengcong Fei, Di Qiu, Changqian Yu, Debang Li, Mingyuan Fan, Xiang Wen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.10783v2.pdf) | [![GitHub](https://img.shields.io/github/stars/feizc/Video-In-Context?style=social)](https://github.com/feizc/Video-In-Context)  
  Keywords: Controllable, diffusion transformer, Control, video generation  
- **[LinGen: Towards High-Resolution Minute-Length Text-to-Video Generation with Linear Computational Complexity](https://arxiv.org/abs/2412.09856v1)** (Published: 2024-12-13)  
  Authors: Hongjie Wang, Chih-Yao Ma, Yen-Cheng Liu, Ji Hou, Tao Xu, Jialiang Wang, Felix Juefei-Xu, Yaqiao Luo, Peizhao Zhang, Tingbo Hou, Peter Vajda, Niraj K. Jha, Xiaoliang Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09856v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lineargen.github.io/.)  
  Keywords: diffusion transformer, video generation  
- **[MSC: Multi-Scale Spatio-Temporal Causal Attention for Autoregressive Video Diffusion](https://arxiv.org/abs/2412.09828v1)** (Published: 2024-12-13)  
  Authors: Xunnong Xu, Mengying Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09828v1.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[STIV: Scalable Text and Image Conditioned Video Generation](https://arxiv.org/abs/2412.07730v1)** (Published: 2024-12-10)  
  Authors: Zongyu Lin, Wei Liu, Chen Chen, Jiasen Lu, Wenze Hu, Tsu-Jui Fu, Jesse Allardice, Zhengfeng Lai, Liangchen Song, Bowen Zhang, Cha Chen, Yiran Fei, Yifan Jiang, Lezhi Li, Yizhou Sun, Kai-Wei Chang, Yinfei Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07730v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[ACDiT: Interpolating Autoregressive Conditional Modeling and Diffusion Transformer](https://arxiv.org/abs/2412.07720v1)** (Published: 2024-12-10)  
  Authors: Jinyi Hu, Shengding Hu, Yuxuan Song, Yufei Huang, Mingxuan Wang, Hao Zhou, Zhiyuan Liu, Wei-Ying Ma, Maosong Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07720v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[FlexDiT: Dynamic Token Density Control for Diffusion Transformer](https://arxiv.org/abs/2412.06028v1)** (Published: 2024-12-08)  
  Authors: Shuning Chang, Pichao Wang, Jiasheng Tang, Yi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.06028v1.pdf)  
  Keywords: video generation, text-to-image, diffusion transformer, image generation, Control  
- **[MotionStone: Decoupled Motion Intensity Modulation with Diffusion Transformer for Image-to-Video Generation](https://arxiv.org/abs/2412.05848v1)** (Published: 2024-12-08)  
  Authors: Shuwei Shi, Biao Gong, Xi Chen, Dandan Zheng, Shuai Tan, Zizheng Yang, Yuyuan Li, Jingwen He, Kecheng Zheng, Jingdong Chen, Ming Yang, Yinqiang Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05848v1.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[Self-Guidance: Boosting Flow and Diffusion Generation on Their Own](https://arxiv.org/abs/2412.05827v1)** (Published: 2024-12-08)  
  Authors: Tiancheng Li, Weijian Luo, Zhiyang Chen, Liyuan Ma, Guo-Jun Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05827v1.pdf)  
  Keywords: FLUX, video generation, text-to-image, diffusion transformer, image generation  
- **[Mind the Time: Temporally-Controlled Multi-Event Video Generation](https://arxiv.org/abs/2412.05263v1)** (Published: 2024-12-06)  
  Authors: Ziyi Wu, Aliaksandr Siarohin, Willi Menapace, Ivan Skorokhodov, Yuwei Fang, Varnith Chordia, Igor Gilitschenski, Sergey Tulyakov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05263v1.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[Navigation World Models](https://arxiv.org/abs/2412.03572v1)** (Published: 2024-12-04)  
  Authors: Amir Bar, Gaoyue Zhou, Danny Tran, Trevor Darrell, Yann LeCun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03572v1.pdf)  
  Keywords: Controllable, diffusion transformer, Control, video generation  
- **[Seeing Beyond Views: Multi-View Driving Scene Video Generation with Holistic Attention](https://arxiv.org/abs/2412.03520v2)** (Published: 2024-12-04)  
  Authors: Hannan Lu, Xiaohe Wu, Shudong Wang, Xiameng Qin, Xinyu Zhang, Junyu Han, Wangmeng Zuo, Ji Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03520v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://luhannan.github.io/CogDrivingPage/.)  
  Keywords: diffusion transformer, Control, video generation  
- **[SyncFlow: Toward Temporally Aligned Joint Audio-Video Generation from Text](https://arxiv.org/abs/2412.15220v1)** (Published: 2024-12-03)  
  Authors: Haohe Liu, Gael Le Lan, Xinhao Mei, Zhaoheng Ni, Anurag Kumar, Varun Nagaraja, Wenwu Wang, Mark D. Plumbley, Yangyang Shi, Vikas Chandra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.15220v1.pdf)  
  Keywords: video generation  
- **[World-consistent Video Diffusion with Explicit 3D Modeling](https://arxiv.org/abs/2412.01821v1)** (Published: 2024-12-02)  
  Authors: Qihang Zhang, Shuangfei Zhai, Miguel Angel Bautista, Kevin Miao, Alexander Toshev, Joshua Susskind, Jiatao Gu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01821v1.pdf)  
  Keywords: diffusion transformer, Control, video generation, image generation  
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
  Keywords: diffusion transformer, video generation, image generation  
- **[Identity-Preserving Text-to-Video Generation by Frequency Decomposition](https://arxiv.org/abs/2411.17440v2)** (Published: 2024-11-26)  
  Authors: Shenghai Yuan, Jinfa Huang, Xianyi He, Yunyuan Ge, Yujun Shi, Liuhan Chen, Jiebo Luo, Li Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.17440v2.pdf)  
  Keywords: Controllable, diffusion transformer, Control, video generation  
- **[LetsTalk: Latent Diffusion Transformer for Talking Video Synthesis](https://arxiv.org/abs/2411.16748v1)** (Published: 2024-11-24)  
  Authors: Haojie Zhang, Zhihao Liang, Ruibo Fu, Zhengqi Wen, Xuefei Liu, Chenxing Li, Jianhua Tao, Yaling Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.16748v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[TaQ-DiT: Time-aware Quantization for Diffusion Transformers](https://arxiv.org/abs/2411.14172v1)** (Published: 2024-11-21)  
  Authors: Xinyan Liu, Huihong Shi, Yang Xu, Zhongfeng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.14172v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[PoM: Efficient Image and Video Generation with the Polynomial Mixer](https://arxiv.org/abs/2411.12663v1)** (Published: 2024-11-19)  
  Authors: David Picard, Nicolas Dufour  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.12663v1.pdf) | [![GitHub](https://img.shields.io/github/stars/davidpicard/HoMM?style=social)](https://github.com/davidpicard/HoMM)  
  Keywords: diffusion transformer, video generation  
- **[Taming Rectified Flow for Inversion and Editing](https://arxiv.org/abs/2411.04746v2)** (Published: 2024-11-07)  
  Authors: Jiangshan Wang, Junfu Pu, Zhongang Qi, Jiayi Guo, Yue Ma, Nisha Huang, Yuxin Chen, Xiu Li, Ying Shan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.04746v2.pdf) | [![GitHub](https://img.shields.io/github/stars/wangjiangshan0725/RF-Solver-Edit?style=social)](https://github.com/wangjiangshan0725/RF-Solver-Edit)  
  Keywords: rectified flow, FLUX, video editing, video generation, diffusion transformer, inversion  
- **[Adaptive Caching for Faster Video Generation with Diffusion Transformers](https://arxiv.org/abs/2411.02397v2)** (Published: 2024-11-04)  
  Authors: Kumara Kahatapitiya, Haozhe Liu, Sen He, Ding Liu, Menglin Jia, Chenyang Zhang, Michael S. Ryoo, Tian Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.02397v2.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[GameGen-X: Interactive Open-world Game Video Generation](https://arxiv.org/abs/2411.00769v3)** (Published: 2024-11-01)  
  Authors: Haoxuan Che, Xuanhua He, Quande Liu, Cheng Jin, Hao Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.00769v3.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[ARLON: Boosting Diffusion Transformers with Autoregressive Models for Long Video Generation](https://arxiv.org/abs/2410.20502v1)** (Published: 2024-10-27)  
  Authors: Zongyi Li, Shujie Hu, Shujie Liu, Long Zhou, Jeongsoo Choi, Lingwei Meng, Xun Guo, Jinyu Li, Hefei Ling, Furu Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.20502v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](http://aka.ms/arlon}.)  
  Keywords: diffusion transformer, video generation  
- **[Boosting Camera Motion Control for Video Diffusion Transformers](https://arxiv.org/abs/2410.10802v1)** (Published: 2024-10-14)  
  Authors: Soon Yau Cheong, Duygu Ceylan, Armin Mustafa, Andrew Gilbert, Chun-Hao Paul Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.10802v1.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[Scaling Laws For Diffusion Transformers](https://arxiv.org/abs/2410.08184v1)** (Published: 2024-10-10)  
  Authors: Zhengyang Liang, Hao He, Ceyuan Yang, Bo Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.08184v1.pdf)  
  Keywords: text-to-image, diffusion transformer, video generation, image generation  
- **[Pyramidal Flow Matching for Efficient Video Generative Modeling](https://arxiv.org/abs/2410.05954v1)** (Published: 2024-10-08)  
  Authors: Yang Jin, Zhicheng Sun, Ningyuan Li, Kun Xu, Kun Xu, Hao Jiang, Nan Zhuang, Quzhe Huang, Yang Song, Yadong Mu, Zhouchen Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.05954v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://pyramid-flow.github.io.)  
  Keywords: diffusion transformer, video generation  
- **[Accelerating Diffusion Transformers with Token-wise Feature Caching](https://arxiv.org/abs/2410.05317v3)** (Published: 2024-10-05)  
  Authors: Chang Zou, Xuyang Liu, Ting Liu, Siteng Huang, Linfeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.05317v3.pdf)  
  Keywords: diffusion transformer, video generation  
- **[LoVA: Long-form Video-to-Audio Generation](https://arxiv.org/abs/2409.15157v1)** (Published: 2024-09-23)  
  Authors: Xin Cheng, Xihua Wang, Yihan Wu, Yuyue Wang, Ruihua Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.15157v1.pdf)  
  Keywords: diffusion transformer, video editing  
- **[Qihoo-T2X: An Efficient Proxy-Tokenized Diffusion Transformer for Text-to-Any-Task](https://arxiv.org/abs/2409.04005v2)** (Published: 2024-09-06)  
  Authors: Jing Wang, Ao Ma, Jiasong Feng, Dawei Leng, Yuhui Yin, Xiaodan Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.04005v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://360cvgroup.github.io/Qihoo-T2X/.)  
  Keywords: diffusion transformer, video generation  
- **[DiVE: DiT-based Video Generation with Enhanced Control](https://arxiv.org/abs/2409.01595v1)** (Published: 2024-09-03)  
  Authors: Junpeng Jiang, Gangyi Hong, Lijun Zhou, Enhui Ma, Hengtong Hu, Xia Zhou, Jie Xiang, Fan Liu, Kaicheng Yu, Haiyang Sun, Kun Zhan, Peng Jia, Miao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.01595v1.pdf)  
  Keywords: Controllable, diffusion transformer, Control, video generation  
- **[VQ4DiT: Efficient Post-Training Vector Quantization for Diffusion Transformers](https://arxiv.org/abs/2408.17131v1)** (Published: 2024-08-30)  
  Authors: Juncan Deng, Shuaiting Li, Zeyu Wang, Hong Gu, Kedong Xu, Kejie Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.17131v1.pdf)  
  Keywords: diffusion transformer, video generation, image generation  
- **[xGen-VideoSyn-1: High-fidelity Text-to-Video Synthesis with Compressed Representations](https://arxiv.org/abs/2408.12590v2)** (Published: 2024-08-22)  
  Authors: Can Qin, Congying Xia, Krithika Ramakrishnan, Michael Ryoo, Lifu Tu, Yihao Feng, Manli Shu, Honglu Zhou, Anas Awadalla, Jun Wang, Senthil Purushwalkam, Le Xue, Yingbo Zhou, Huan Wang, Silvio Savarese, Juan Carlos Niebles, Zeyuan Chen, Ran Xu, Caiming Xiong  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.12590v2.pdf)  
  Keywords: diffusion transformer, video generation  
- **[CogVideoX: Text-to-Video Diffusion Models with An Expert Transformer](https://arxiv.org/abs/2408.06072v2)** (Published: 2024-08-12)  
  Authors: Zhuoyi Yang, Jiayan Teng, Wendi Zheng, Ming Ding, Shiyu Huang, Jiazheng Xu, Yuanming Yang, Wenyi Hong, Xiaohan Zhang, Guanyu Feng, Da Yin, Xiaotao Gu, Yuxuan Zhang, Weihan Wang, Yean Cheng, Ting Liu, Bin Xu, Yuxiao Dong, Jie Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.06072v2.pdf) | [![GitHub](https://img.shields.io/github/stars/THUDM/CogVideo?style=social)](https://github.com/THUDM/CogVideo)  
  Keywords: diffusion transformer, video generation  
- **[Tora: Trajectory-oriented Diffusion Transformer for Video Generation](https://arxiv.org/abs/2407.21705v3)** (Published: 2024-07-31)  
  Authors: Zhenghao Zhang, Junchao Liao, Menghao Li, Zuozhuo Dai, Bingxue Qiu, Siyu Zhu, Long Qin, Weizhi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.21705v3.pdf) | [![GitHub](https://img.shields.io/github/stars/alibaba/Tora?style=social)](https://github.com/alibaba/Tora)  
  Keywords: Controllable, diffusion transformer, Control, video generation  
- **[MotionCraft: Crafting Whole-Body Motion with Plug-and-Play Multimodal Controls](https://arxiv.org/abs/2407.21136v3)** (Published: 2024-07-30)  
  Authors: Yuxuan Bian, Ailing Zeng, Xuan Ju, Xian Liu, Zhaoyang Zhang, Wei Liu, Qiang Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.21136v3.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[Diffusion Transformer Captures Spatial-Temporal Dependencies: A Theory for Gaussian Process Data](https://arxiv.org/abs/2407.16134v1)** (Published: 2024-07-23)  
  Authors: Hengyu Fu, Zehao Dou, Jiawei Guo, Mengdi Wang, Minshuo Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.16134v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[Anchored Diffusion for Video Face Reenactment](https://arxiv.org/abs/2407.15153v1)** (Published: 2024-07-21)  
  Authors: Idan Kligvasser, Regev Cohen, George Leifman, Ehud Rivlin, Michael Elad  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.15153v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[VD3D: Taming Large Video Diffusion Transformers for 3D Camera Control](https://arxiv.org/abs/2407.12781v2)** (Published: 2024-07-17)  
  Authors: Sherwin Bahmani, Ivan Skorokhodov, Aliaksandr Siarohin, Willi Menapace, Guocheng Qian, Michael Vasilkovsky, Hsin-Ying Lee, Chaoyang Wang, Jiaxu Zou, Andrea Tagliasacchi, David B. Lindell, Sergey Tulyakov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.12781v2.pdf)  
  Keywords: Controllable, diffusion transformer, Control, video generation  
- **[OpenVid-1M: A Large-Scale High-Quality Dataset for Text-to-video Generation](https://arxiv.org/abs/2407.02371v2)** (Published: 2024-07-02)  
  Authors: Kepan Nan, Rui Xie, Penghao Zhou, Tiehan Fan, Zhenheng Yang, Zhijie Chen, Xiang Li, Jian Yang, Ying Tai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.02371v2.pdf)  
  Keywords: diffusion transformer, video generation  
- **[Q-DiT: Accurate Post-Training Quantization for Diffusion Transformers](https://arxiv.org/abs/2406.17343v2)** (Published: 2024-06-25)  
  Authors: Lei Chen, Yuan Meng, Chen Tang, Xinzhu Ma, Jingyan Jiang, Xin Wang, Zhi Wang, Wenwu Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.17343v2.pdf) | [![GitHub](https://img.shields.io/github/stars/Juanerx/Q-DiT?style=social)](https://github.com/Juanerx/Q-DiT)  
  Keywords: diffusion transformer, video generation  
- **[DiTFastAttn: Attention Compression for Diffusion Transformer Models](https://arxiv.org/abs/2406.08552v2)** (Published: 2024-06-12)  
  Authors: Zhihang Yuan, Hanling Zhang, Pu Lu, Xuefei Ning, Linfeng Zhang, Tianchen Zhao, Shengen Yan, Guohao Dai, Yu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.08552v2.pdf)  
  Keywords: diffusion transformer, video generation, image generation  
- **[AV-DiT: Efficient Audio-Visual Diffusion Transformer for Joint Audio and Video Generation](https://arxiv.org/abs/2406.07686v1)** (Published: 2024-06-11)  
  Authors: Kai Wang, Shijian Deng, Jing Shi, Dimitrios Hatzinakos, Yapeng Tian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.07686v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[ViDiT-Q: Efficient and Accurate Quantization of Diffusion Transformers for Image and Video Generation](https://arxiv.org/abs/2406.02540v2)** (Published: 2024-06-04)  
  Authors: Tianchen Zhao, Tongcheng Fang, Enshu Liu, Rui Wan, Widyadewi Soedarmadji, Shiyao Li, Zinan Lin, Guohao Dai, Shengen Yan, Huazhong Yang, Xuefei Ning, Yu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.02540v2.pdf)  
  Keywords: text-to-image, diffusion transformer, video generation  
- **[VITON-DiT: Learning In-the-Wild Video Try-On from Human Dance Videos via Diffusion Transformers](https://arxiv.org/abs/2405.18326v2)** (Published: 2024-05-28)  
  Authors: Jun Zheng, Fuwei Zhao, Youjiang Xu, Xin Dong, Xiaodan Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2405.18326v2.pdf)  
  Keywords: diffusion transformer, Control, video generation  
- **[Human4DiT: 360-degree Human Video Generation with 4D Diffusion Transformer](https://arxiv.org/abs/2405.17405v2)** (Published: 2024-05-27)  
  Authors: Ruizhi Shao, Youxin Pang, Zerong Zheng, Jingxiang Sun, Yebin Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2405.17405v2.pdf)  
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
