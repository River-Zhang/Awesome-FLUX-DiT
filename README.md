# Awesome FLUX/DiT methods [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to DiT/FLUX. Content is automatically updated daily.

> Last Update: 2025-05-25 06:31:08

Thanks to [@longxiang-ai](https://github.com/longxiang-ai) for the template.

## Categories

- [Image Editing](#image-editing) (31 papers) - Papers about image editing with Diffusion Transformer or FLUX
- [Image Generation](#image-generation) (174 papers) - Papers focusing on image generation with Diffusion Transformer or FLUX
- [Video Related](#video-related) (113 papers) - Papers about video generation and editing with Diffusion Transformer or FLUX



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### Image Editing

- **[DanceGRPO: Unleashing GRPO on Visual Generation](https://arxiv.org/abs/2505.07818v1)** (Published: 2025-05-12)  
  Authors: Zeyue Xue, Jie Wu, Yu Gao, Fangyuan Kong, Lingting Zhu, Mengzhao Chen, Zhiheng Liu, Wei Liu, Qiushan Guo, Weilin Huang, Ping Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.07818v1.pdf)  
  Keywords: video generation, rectified flow, FLUX, text-to-image  
- **[Lay-Your-Scene: Natural Scene Layout Generation with Diffusion Transformers](https://arxiv.org/abs/2505.04718v1)** (Published: 2025-05-07)  
  Authors: Divyansh Srivastava, Xiang Zhang, He Wen, Chenru Wen, Zhuowen Tu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.04718v1.pdf)  
  Keywords: Controllable, diffusion transformer, image editing, image generation, Control  
- **[In-Context Edit: Enabling Instructional Image Editing with In-Context Generation in Large Scale Diffusion Transformer](https://arxiv.org/abs/2504.20690v1)** (Published: 2025-04-29)  
  Authors: Zechuan Zhang, Ji Xie, Yu Lu, Zongxin Yang, Yi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.20690v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://river-zhang.github.io/ICEdit-gh-pages/.)  
  Keywords: image editing, diffusion transformer  
- **[Disentangling Instruction Influence in Diffusion Transformers for Parallel Multi-Instruction-Guided Image Editing](https://arxiv.org/abs/2504.04784v1)** (Published: 2025-04-07)  
  Authors: Hui Liu, Bin Zou, Suiyun Zhang, Kecheng Chen, Rui Liu, Haoliang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04784v1.pdf)  
  Keywords: image editing, diffusion transformer, Control  
- **[Detection Limits and Statistical Separability of Tree Ring Watermarks in Rectified Flow-based Text-to-Image Generation Models](https://arxiv.org/abs/2504.03850v1)** (Published: 2025-04-04)  
  Authors: Ved Umrajkar, Aakash Kumar Singh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.03850v1.pdf) | [![GitHub](https://img.shields.io/github/stars/dsgiitr/flux-watermarking?style=social)](https://github.com/dsgiitr/flux-watermarking)  
  Keywords: inversion, image generation, text-to-image, rectified flow, FLUX  
- **[DiT4SR: Taming Diffusion Transformer for Real-World Image Super-Resolution](https://arxiv.org/abs/2503.23580v1)** (Published: 2025-03-30)  
  Authors: Zheng-Peng Duan, Jiawei Zhang, Xin Jin, Ziheng Zhang, Zheng Xiong, Dongqing Zou, Jimmy Ren, Chun-Le Guo, Chongyi Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.23580v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://adam-duan.github.io/projects/dit4sr/.)  
  Keywords: image super-resolution, diffusion transformer, image generation, Control  
- **[FreeFlux: Understanding and Exploiting Layer-Specific Roles in RoPE-Based MMDiT for Versatile Image Editing](https://arxiv.org/abs/2503.16153v1)** (Published: 2025-03-20)  
  Authors: Tianyi Wei, Yifan Zhou, Dongdong Chen, Xingang Pan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.16153v1.pdf)  
  Keywords: FLUX, diffusion transformer, image editing, image generation, text-to-image  
- **[Personalize Anything for Free with Diffusion Transformer](https://arxiv.org/abs/2503.12590v1)** (Published: 2025-03-16)  
  Authors: Haoran Feng, Zehuan Huang, Lin Li, Hairong Lv, Lu Sheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.12590v1.pdf)  
  Keywords: image editing, diffusion transformer, image generation, Control  
- **[NAMI: Efficient Image Generation via Progressive Rectified Flow Transformers](https://arxiv.org/abs/2503.09242v1)** (Published: 2025-03-12)  
  Authors: Yuhang Ma, Bo Cheng, Shanyuan Liu, Ao Ma, Xiaoyu Wu, Liebucha Wu, Dawei Leng, Yuhui Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.09242v1.pdf)  
  Keywords: diffusion transformer, rectified flow, image generation  
- **[Seedream 2.0: A Native Chinese-English Bilingual Image Generation Foundation Model](https://arxiv.org/abs/2503.07703v1)** (Published: 2025-03-10)  
  Authors: Lixue Gong, Xiaoxia Hou, Fanshi Li, Liang Li, Xiaochen Lian, Fei Liu, Liyang Liu, Wei Liu, Wei Lu, Yichun Shi, Shiqi Sun, Yu Tian, Zhi Tian, Peng Wang, Xun Wang, Ye Wang, Guofeng Wu, Jie Wu, Xin Xia, Xuefeng Xiao, Linjie Yang, Zhonghua Zhai, Xinyu Zhang, Qi Zhang, Yuwei Zhang, Shijia Zhao, Jianchao Yang, Weilin Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07703v1.pdf)  
  Keywords: image generation, image editing, FLUX  
- **[TIDE : Temporal-Aware Sparse Autoencoders for Interpretable Diffusion Transformers in Image Generation](https://arxiv.org/abs/2503.07050v1)** (Published: 2025-03-10)  
  Authors: Victor Shea-Jay Huang, Le Zhuo, Yi Xin, Zhaokai Wang, Peng Gao, Hongsheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07050v1.pdf)  
  Keywords: image editing, diffusion transformer, image generation, Control  
- **[X2I: Seamless Integration of Multimodal Understanding into Diffusion Transformer via Attention Distillation](https://arxiv.org/abs/2503.06134v2)** (Published: 2025-03-08)  
  Authors: Jian Ma, Qirong Peng, Xu Guo, Chen Chen, Haonan Lu, Zhenyu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.06134v2.pdf) | [![GitHub](https://img.shields.io/github/stars/OPPO-Mente-Lab/X2I?style=social)](https://github.com/OPPO-Mente-Lab/X2I)  
  Keywords: diffusion transformer, image to image, image editing, image generation, text-to-image, Control  
- **[AnyRefill: A Unified, Data-Efficient Framework for Left-Prompt-Guided Vision Tasks](https://arxiv.org/abs/2502.11158v2)** (Published: 2025-02-16)  
  Authors: Ming Xie, Chenjie Cao, Yunuo Cai, Xiangyang Xue, Yu-Gang Jiang, Yanwei Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.11158v2.pdf)  
  Keywords: image editing, diffusion transformer, text-to-image  
- **[EliGen: Entity-Level Controlled Image Generation with Regional Attention](https://arxiv.org/abs/2501.01097v3)** (Published: 2025-01-02)  
  Authors: Hong Zhang, Zhongjie Duan, Xingjun Wang, Yingda Chen, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.01097v3.pdf) | [![GitHub](https://img.shields.io/github/stars/modelscope/DiffSynth-Studio.git?style=social)](https://github.com/modelscope/DiffSynth-Studio.git)  
  Keywords: diffusion transformer, image inpainting, image generation, text-to-image, Control  
- **[Context Canvas: Enhancing Text-to-Image Diffusion Models with Knowledge Graph-Based RAG](https://arxiv.org/abs/2412.09614v1)** (Published: 2024-12-12)  
  Authors: Kavana Venkatesh, Yusuf Dalva, Ismini Lourentzou, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09614v1.pdf)  
  Keywords: image editing, text-to-image, FLUX, Control  
- **[FluxSpace: Disentangled Semantic Editing in Rectified Flow Transformers](https://arxiv.org/abs/2412.09611v1)** (Published: 2024-12-12)  
  Authors: Yusuf Dalva, Kavana Venkatesh, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09611v1.pdf)  
  Keywords: image editing, image generation, rectified flow, FLUX, Control  
- **[AMO Sampler: Enhancing Text Rendering with Overshooting](https://arxiv.org/abs/2411.19415v2)** (Published: 2024-11-28)  
  Authors: Xixi Hu, Keyang Xu, Bo Liu, Qiang Liu, Hongliang Fei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.19415v2.pdf) | [![GitHub](https://img.shields.io/github/stars/hxixixh/amo-release?style=social)](https://github.com/hxixixh/amo-release)  
  Keywords: image generation, text-to-image, rectified flow, FLUX, Control  
- **[Prediction with Action: Visual Policy Learning via Joint Denoising Process](https://arxiv.org/abs/2411.18179v1)** (Published: 2024-11-27)  
  Authors: Yanjiang Guo, Yucheng Hu, Jianke Zhang, Yen-Jen Wang, Xiaoyu Chen, Chaochao Lu, Jianyu Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.18179v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sites.google.com/view/pad-paper)  
  Keywords: image editing, diffusion transformer, image generation, Control  
- **[HeadRouter: A Training-free Image Editing Framework for MM-DiTs by Adaptively Routing Attention Heads](https://arxiv.org/abs/2411.15034v1)** (Published: 2024-11-22)  
  Authors: Yu Xu, Fan Tang, Juan Cao, Yuxin Zhang, Xiaoyu Kong, Jintao Li, Oliver Deussen, Tong-Yee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.15034v1.pdf)  
  Keywords: image editing, diffusion transformer, image generation  
- **[Stable Flow: Vital Layers for Training-Free Image Editing](https://arxiv.org/abs/2411.14430v2)** (Published: 2024-11-21)  
  Authors: Omri Avrahami, Or Patashnik, Ohad Fried, Egor Nemchinov, Kfir Aberman, Dani Lischinski, Daniel Cohen-Or  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.14430v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://omriavrahami.com/stable-flow)  
  Keywords: image editing, diffusion transformer, Control, inversion  
- **[Oscillation Inversion: Understand the structure of Large Flow Model through the Lens of Inversion Method](https://arxiv.org/abs/2411.11135v1)** (Published: 2024-11-17)  
  Authors: Yan Zheng, Zhenxiao Liang, Xiaoyan Cong, Lanqing guo, Yuehao Wang, Peihao Wang, Zhangyang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.11135v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yanyanzheng96.github.io/oscillation_inversion/}{this)  
  Keywords: inversion, image editing, text-to-image, rectified flow, FLUX  
- **[Latent Space Disentanglement in Diffusion Transformers Enables Precise Zero-shot Semantic Editing](https://arxiv.org/abs/2411.08196v1)** (Published: 2024-11-12)  
  Authors: Zitao Shuai, Chenwei Wu, Zhengxu Tang, Bowen Song, Liyue Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.08196v1.pdf)  
  Keywords: image editing, diffusion transformer, image generation, Control  
- **[Taming Rectified Flow for Inversion and Editing](https://arxiv.org/abs/2411.04746v2)** (Published: 2024-11-07)  
  Authors: Jiangshan Wang, Junfu Pu, Zhongang Qi, Jiayi Guo, Yue Ma, Nisha Huang, Yuxin Chen, Xiu Li, Ying Shan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.04746v2.pdf) | [![GitHub](https://img.shields.io/github/stars/wangjiangshan0725/RF-Solver-Edit?style=social)](https://github.com/wangjiangshan0725/RF-Solver-Edit)  
  Keywords: inversion, diffusion transformer, video editing, video generation, rectified flow, FLUX  
- **[DiT4Edit: Diffusion Transformer for Image Editing](https://arxiv.org/abs/2411.03286v2)** (Published: 2024-11-05)  
  Authors: Kunyu Feng, Yue Ma, Bingyuan Wang, Chenyang Qi, Haozhe Chen, Qifeng Chen, Zeyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.03286v2.pdf)  
  Keywords: inversion, diffusion transformer, image editing, image generation, Control  
- **[FiTv2: Scalable and Improved Flexible Vision Transformer for Diffusion Model](https://arxiv.org/abs/2410.13925v1)** (Published: 2024-10-17)  
  Authors: ZiDong Wang, Zeyu Lu, Di Huang, Cai Zhou, Wanli Ouyang, and Lei Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.13925v1.pdf) | [![GitHub](https://img.shields.io/github/stars/whlzy/FiT?style=social)](https://github.com/whlzy/FiT)  
  Keywords: diffusion transformer, rectified flow, image generation  
- **[Semantic Image Inversion and Editing using Rectified Stochastic Differential Equations](https://arxiv.org/abs/2410.10792v1)** (Published: 2024-10-14)  
  Authors: Litu Rout, Yujia Chen, Nataniel Ruiz, Constantine Caramanis, Sanjay Shakkottai, Wen-Sheng Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.10792v1.pdf)  
  Keywords: inversion, image editing, rectified flow, FLUX, Control  
- **[Effective Diffusion Transformer Architecture for Image Super-Resolution](https://arxiv.org/abs/2409.19589v1)** (Published: 2024-09-29)  
  Authors: Kun Cheng, Lei Yu, Zhijun Tu, Xiao He, Liyu Chen, Yong Guo, Mingrui Zhu, Nannan Wang, Xinbo Gao, Jie Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.19589v1.pdf)  
  Keywords: diffusion transformer, image generation, image super-resolution  
- **[PixWizard: Versatile Image-to-Image Visual Assistant with Open-Language Instructions](https://arxiv.org/abs/2409.15278v4)** (Published: 2024-09-23)  
  Authors: Weifeng Lin, Xinyu Wei, Renrui Zhang, Le Zhuo, Shitian Zhao, Siyuan Huang, Huan Teng, Junlin Xie, Yu Qiao, Peng Gao, Hongsheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.15278v4.pdf) | [![GitHub](https://img.shields.io/github/stars/AFeng-x/PixWizard?style=social)](https://github.com/AFeng-x/PixWizard)  
  Keywords: Controllable, diffusion transformer, image editing, image generation, text-to-image, Control  
- **[Latent Space Disentanglement in Diffusion Transformers Enables Zero-shot Fine-grained Semantic Editing](https://arxiv.org/abs/2408.13335v1)** (Published: 2024-08-23)  
  Authors: Zitao Shuai, Chenwei Wu, Zhengxu Tang, Bowen Song, Liyue Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.13335v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://anonymous.com/anonymous/EMS-Benchmark,)  
  Keywords: image editing, diffusion transformer, text-to-image, Control  
- **[Lazy Diffusion Transformer for Interactive Image Editing](https://arxiv.org/abs/2404.12382v1)** (Published: 2024-04-18)  
  Authors: Yotam Nitzan, Zongze Wu, Richard Zhang, Eli Shechtman, Daniel Cohen-Or, Taesung Park, Michaël Gharbi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2404.12382v1.pdf)  
  Keywords: image editing, diffusion transformer  
- **[Lightning-Fast Image Inversion and Editing for Text-to-Image Diffusion Models](https://arxiv.org/abs/2312.12540v5)** (Published: 2023-12-19)  
  Authors: Dvir Samuel, Barak Meiri, Haggai Maron, Yoad Tewel, Nir Darshan, Shai Avidan, Gal Chechik, Rami Ben-Ari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2312.12540v5.pdf)  
  Keywords: inversion, image editing, text-to-image, FLUX  

### Image Generation

*Showing the latest 50 out of 174 papers*

- **[Interspatial Attention for Efficient 4D Human Video Generation](https://arxiv.org/abs/2505.15800v1)** (Published: 2025-05-21)  
  Authors: Ruizhi Shao, Yinghao Xu, Yujun Shen, Ceyuan Yang, Yang Zheng, Changan Chen, Yebin Liu, Gordon Wetzstein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.15800v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dsaurus.github.io/isa4d/.)  
  Keywords: video generation, Controllable, diffusion transformer, Control  
- **[Scaling Diffusion Transformers Efficiently via $μ$P](https://arxiv.org/abs/2505.15270v1)** (Published: 2025-05-21)  
  Authors: Chenyu Zheng, Xinyu Zhang, Rongzhen Wang, Wei Huang, Zhi Tian, Weilin Huang, Jun Zhu, Chongxuan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.15270v1.pdf)  
  Keywords: diffusion transformer, text-to-image, image generation  
- **[LMP: Leveraging Motion Prior in Zero-Shot Video Generation with Diffusion Transformer](https://arxiv.org/abs/2505.14167v1)** (Published: 2025-05-20)  
  Authors: Changgu Chen, Xiaoyan Yang, Junwei Shu, Changbo Wang, Yang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.14167v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vpx-ecnu.github.io/LMP-Website/)  
  Keywords: video generation, diffusion transformer, Control  
- **[Swin DiT: Diffusion Transformer using Pseudo Shifted Windows](https://arxiv.org/abs/2505.13219v2)** (Published: 2025-05-19)  
  Authors: Jiafu Wu, Yabiao Wang, Jian Li, Jinlong Peng, Yun Cao, Chengjie Wang, Jiangning Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.13219v2.pdf) | [![GitHub](https://img.shields.io/github/stars/wujiafu007/Swin-DiT?style=social)](https://github.com/wujiafu007/Swin-DiT)  
  Keywords: diffusion transformer, image generation  
- **[SounDiT: Geo-Contextual Soundscape-to-Landscape Generation](https://arxiv.org/abs/2505.12734v1)** (Published: 2025-05-19)  
  Authors: Junbo Wang, Haofeng Tan, Bowen Liao, Albert Jiang, Teng Fei, Qixing Huang, Zhengzhong Tu, Shan Ye, Yuhao Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.12734v1.pdf)  
  Keywords: diffusion transformer, image generation  
- **[Exploring the Deep Fusion of Large Language Models and Diffusion Transformers for Text-to-Image Synthesis](https://arxiv.org/abs/2505.10046v1)** (Published: 2025-05-15)  
  Authors: Bingda Tang, Boyang Zheng, Xichen Pan, Sayak Paul, Saining Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.10046v1.pdf)  
  Keywords: diffusion transformer, text-to-image, image generation, Control  
- **[BLIP3-o: A Family of Fully Open Unified Multimodal Models-Architecture, Training and Dataset](https://arxiv.org/abs/2505.09568v1)** (Published: 2025-05-14)  
  Authors: Jiuhai Chen, Zhiyang Xu, Xichen Pan, Yushi Hu, Can Qin, Tom Goldstein, Lifu Huang, Tianyi Zhou, Saining Xie, Silvio Savarese, Le Xue, Caiming Xiong, Ran Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.09568v1.pdf)  
  Keywords: diffusion transformer, image generation  
- **[Train a Multi-Task Diffusion Policy on RLBench-18 in One Day with One GPU](https://arxiv.org/abs/2505.09430v1)** (Published: 2025-05-14)  
  Authors: Yutong Hu, Pinhao Song, Kehan Wen, Renaud Detry  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.09430v1.pdf) | [![GitHub](https://img.shields.io/github/stars/utomm/mini-diffuse-actor?style=social)](https://github.com/utomm/mini-diffuse-actor)  
  Keywords: diffusion transformer, image generation  
- **[DanceGRPO: Unleashing GRPO on Visual Generation](https://arxiv.org/abs/2505.07818v1)** (Published: 2025-05-12)  
  Authors: Zeyue Xue, Jie Wu, Yu Gao, Fangyuan Kong, Lingting Zhu, Mengzhao Chen, Zhiheng Liu, Wei Liu, Qiushan Guo, Weilin Huang, Ping Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.07818v1.pdf)  
  Keywords: video generation, rectified flow, FLUX, text-to-image  
- **[Accelerating Diffusion Transformer via Increment-Calibrated Caching with Channel-Aware Singular Value Decomposition](https://arxiv.org/abs/2505.05829v1)** (Published: 2025-05-09)  
  Authors: Zhiyuan Chen, Keyi Li, Yifan Jia, Le Ye, Yufei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.05829v1.pdf) | [![GitHub](https://img.shields.io/github/stars/ccccczzy/icc?style=social)](https://github.com/ccccczzy/icc)  
  Keywords: diffusion transformer, image generation  
- **[Lay-Your-Scene: Natural Scene Layout Generation with Diffusion Transformers](https://arxiv.org/abs/2505.04718v1)** (Published: 2025-05-07)  
  Authors: Divyansh Srivastava, Xiang Zhang, He Wen, Chenru Wen, Zhuowen Tu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.04718v1.pdf)  
  Keywords: Controllable, diffusion transformer, image editing, image generation, Control  
- **[Deepfakes on Demand: the rise of accessible non-consensual deepfake image generators](https://arxiv.org/abs/2505.03859v1)** (Published: 2025-05-06)  
  Authors: Will Hawkins, Chris Russell, Brent Mittelstadt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.03859v1.pdf)  
  Keywords: text-to-image, FLUX  
- **[DualReal: Adaptive Joint Training for Lossless Identity-Motion Fusion in Video Customization](https://arxiv.org/abs/2505.02192v1)** (Published: 2025-05-04)  
  Authors: Wenchuan Wang, Mengqi Huang, Yijing Tu, Zhendong Mao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.02192v1.pdf)  
  Keywords: video generation, diffusion transformer, Control  
- **[JointDiT: Enhancing RGB-Depth Joint Modeling with Diffusion Transformers](https://arxiv.org/abs/2505.00482v1)** (Published: 2025-05-01)  
  Authors: Kwon Byung-Ki, Qi Dai, Lee Hyoseok, Chong Luo, Tae-Hyun Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.00482v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://byungki-k.github.io/JointDiT/.)  
  Keywords: diffusion transformer, image generation, Control  
- **[Can We Achieve Efficient Diffusion without Self-Attention? Distilling Self-Attention into Convolutions](https://arxiv.org/abs/2504.21292v1)** (Published: 2025-04-30)  
  Authors: ZiYi Dong, Chengxing Zhou, Weijian Deng, Pengxu Wei, Xiangyang Ji, Liang Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.21292v1.pdf)  
  Keywords: diffusion transformer, image generation  
- **[DiVE: Efficient Multi-View Driving Scenes Generation Based on Video Diffusion Transformer](https://arxiv.org/abs/2504.19614v1)** (Published: 2025-04-28)  
  Authors: Junpeng Jiang, Gangyi Hong, Miao Zhang, Hengtong Hu, Kun Zhan, Rui Shao, Liqiang Nie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.19614v1.pdf)  
  Keywords: video generation, diffusion transformer, Control  
- **[Physics-based super-resolved simulation of 3D elastic wave propagation adopting scalable Diffusion Transformer](https://arxiv.org/abs/2504.17308v1)** (Published: 2025-04-24)  
  Authors: Hugo Gabrielidis, Filippo Gatti, Stéphane Vialle  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.17308v1.pdf)  
  Keywords: diffusion transformer, image generation  
- **[Boosting Generative Image Modeling via Joint Image-Feature Synthesis](https://arxiv.org/abs/2504.16064v1)** (Published: 2025-04-22)  
  Authors: Theodoros Kouzelis, Efstathios Karypidis, Ioannis Kakogeorgiou, Spyros Gidaris, Nikos Komodakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.16064v1.pdf)  
  Keywords: diffusion transformer, image generation  
- **[Acquire and then Adapt: Squeezing out Text-to-Image Model for Image Restoration](https://arxiv.org/abs/2504.15159v1)** (Published: 2025-04-21)  
  Authors: Junyuan Deng, Xinyi Wu, Yongxing Yang, Congchao Zhu, Song Wang, Zhenyao Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.15159v1.pdf)  
  Keywords: FLUX, diffusion transformer, image generation, text-to-image, Control  
- **[Text-Audio-Visual-conditioned Diffusion Model for Video Saliency Prediction](https://arxiv.org/abs/2504.14267v1)** (Published: 2025-04-19)  
  Authors: Li Yu, Xuanzhe Sun, Wei Zhou, Moncef Gabbouj  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.14267v1.pdf)  
  Keywords: diffusion transformer, image generation  
- **[Entropy Rectifying Guidance for Diffusion and Flow Models](https://arxiv.org/abs/2504.13987v1)** (Published: 2025-04-18)  
  Authors: Tariq Berrada Ifriqi, Adriana Romero-Soriano, Michal Drozdzal, Jakob Verbeek, Karteek Alahari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.13987v1.pdf)  
  Keywords: diffusion transformer, text-to-image, image generation  
- **[InstantCharacter: Personalize Any Characters with a Scalable Diffusion Transformer Framework](https://arxiv.org/abs/2504.12395v1)** (Published: 2025-04-16)  
  Authors: Jiale Tao, Yanbing Zhang, Qixun Wang, Yiji Cheng, Haofan Wang, Xu Bai, Zhengguang Zhou, Ruihuang Li, Linqing Wang, Chunyu Wang, Qin Lin, Qinglin Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.12395v1.pdf) | [![GitHub](https://img.shields.io/github/stars/Tencent/InstantCharacter?style=social)](https://github.com/Tencent/InstantCharacter)  
  Keywords: Controllable, diffusion transformer, image generation, Control  
- **[Using LLMs as prompt modifier to avoid biases in AI image generators](https://arxiv.org/abs/2504.11104v1)** (Published: 2025-04-15)  
  Authors: René Peinl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.11104v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://iisys-hof.github.io/llm-prompt-img-gen/)  
  Keywords: image generation, text-to-image, FLUX  
- **[D$^2$iT: Dynamic Diffusion Transformer for Accurate Image Generation](https://arxiv.org/abs/2504.09454v1)** (Published: 2025-04-13)  
  Authors: Weinan Jia, Mengqi Huang, Nan Chen, Lei Zhang, Zhendong Mao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.09454v1.pdf) | [![GitHub](https://img.shields.io/github/stars/jiawn-creator/Dynamic-DiT?style=social)](https://github.com/jiawn-creator/Dynamic-DiT)  
  Keywords: diffusion transformer, image generation  
- **[Flux Already Knows -- Activating Subject-Driven Image Generation without Training](https://arxiv.org/abs/2504.11478v2)** (Published: 2025-04-12)  
  Authors: Hao Kang, Stathi Fotiadis, Liming Jiang, Qing Yan, Yumin Jia, Zichuan Liu, Min Jin Chong, Xin Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.11478v2.pdf)  
  Keywords: image generation, text-to-image, FLUX  
- **[MixDiT: Accelerating Image Diffusion Transformer Inference with Mixed-Precision MX Quantization](https://arxiv.org/abs/2504.08398v1)** (Published: 2025-04-11)  
  Authors: Daeun Kim, Jinwoo Hwang, Changhun Oh, Jongse Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.08398v1.pdf)  
  Keywords: diffusion transformer, image generation  
- **[DyDiT++: Dynamic Diffusion Transformers for Efficient Visual Generation](https://arxiv.org/abs/2504.06803v2)** (Published: 2025-04-09)  
  Authors: Wangbo Zhao, Yizeng Han, Jiasheng Tang, Kai Wang, Hao Luo, Yibing Song, Gao Huang, Fan Wang, Yang You  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.06803v2.pdf)  
  Keywords: FLUX, diffusion transformer, image generation, video generation, text-to-image  
- **[Disentangling Instruction Influence in Diffusion Transformers for Parallel Multi-Instruction-Guided Image Editing](https://arxiv.org/abs/2504.04784v1)** (Published: 2025-04-07)  
  Authors: Hui Liu, Bin Zou, Suiyun Zhang, Kecheng Chen, Rui Liu, Haoliang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04784v1.pdf)  
  Keywords: image editing, diffusion transformer, Control  
- **[DiTaiListener: Controllable High Fidelity Listener Video Generation with Diffusion](https://arxiv.org/abs/2504.04010v1)** (Published: 2025-04-05)  
  Authors: Maksim Siniukov, Di Chang, Minh Tran, Hongkun Gong, Ashutosh Chaubey, Mohammad Soleymani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04010v1.pdf)  
  Keywords: video generation, Controllable, diffusion transformer, Control  
- **[Detection Limits and Statistical Separability of Tree Ring Watermarks in Rectified Flow-based Text-to-Image Generation Models](https://arxiv.org/abs/2504.03850v1)** (Published: 2025-04-04)  
  Authors: Ved Umrajkar, Aakash Kumar Singh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.03850v1.pdf) | [![GitHub](https://img.shields.io/github/stars/dsgiitr/flux-watermarking?style=social)](https://github.com/dsgiitr/flux-watermarking)  
  Keywords: inversion, image generation, text-to-image, rectified flow, FLUX  
- **[SkyReels-A2: Compose Anything in Video Diffusion Transformers](https://arxiv.org/abs/2504.02436v1)** (Published: 2025-04-03)  
  Authors: Zhengcong Fei, Debang Li, Di Qiu, Jiahua Wang, Yikun Dou, Rui Wang, Jingtao Xu, Mingyuan Fan, Guibin Chen, Yang Li, Yahui Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.02436v1.pdf)  
  Keywords: video generation, Controllable, diffusion transformer, Control  
- **[Less-to-More Generalization: Unlocking More Controllability by In-Context Generation](https://arxiv.org/abs/2504.02160v1)** (Published: 2025-04-02)  
  Authors: Shaojin Wu, Mengqi Huang, Wenxu Wu, Yufeng Cheng, Fei Ding, Qian He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.02160v1.pdf)  
  Keywords: diffusion transformer, text-to-image, image generation, Control  
- **[DiT4SR: Taming Diffusion Transformer for Real-World Image Super-Resolution](https://arxiv.org/abs/2503.23580v1)** (Published: 2025-03-30)  
  Authors: Zheng-Peng Duan, Jiawei Zhang, Xin Jin, Ziheng Zhang, Zheng Xiong, Dongqing Zou, Jimmy Ren, Chun-Le Guo, Chongyi Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.23580v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://adam-duan.github.io/projects/dit4sr/.)  
  Keywords: image super-resolution, diffusion transformer, image generation, Control  
- **[DiTFastAttnV2: Head-wise Attention Compression for Multi-Modality Diffusion Transformers](https://arxiv.org/abs/2503.22796v1)** (Published: 2025-03-28)  
  Authors: Hanling Zhang, Rundong Su, Zhihang Yuan, Pengtao Chen, Mingzhu Shen Yibo Fan, Shengen Yan, Guohao Dai, Yu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.22796v1.pdf)  
  Keywords: diffusion transformer, text-to-image, image generation  
- **[DynamiCtrl: Rethinking the Basic Structure and the Role of Text for High-quality Human Image Animation](https://arxiv.org/abs/2503.21246v2)** (Published: 2025-03-27)  
  Authors: Haoyu Zhao, Zhongang Qi, Cong Wang, Qingping Zheng, Guansong Lu, Fei Chen, Hang Xu, Zuxuan Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.21246v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gulucaptain.github.io/DynamiCtrl/.)  
  Keywords: video generation, diffusion transformer, Control  
- **[BizGen: Advancing Article-level Visual Text Rendering for Infographics Generation](https://arxiv.org/abs/2503.20672v1)** (Published: 2025-03-26)  
  Authors: Yuyang Peng, Shishi Xiao, Keming Wu, Qisheng Liao, Bohan Chen, Kevin Lin, Danqing Huang, Ji Li, Yuhui Yuan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.20672v1.pdf)  
  Keywords: image generation, text-to-image, FLUX  
- **[MMGen: Unified Multi-modal Image Generation and Understanding in One Go](https://arxiv.org/abs/2503.20644v1)** (Published: 2025-03-26)  
  Authors: Jiepeng Wang, Zhaoqing Wang, Hao Pan, Yuan Liu, Dongdong Yu, Changhu Wang, Wenping Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.20644v1.pdf)  
  Keywords: Controllable, diffusion transformer, image generation, Control  
- **[Scaling Down Text Encoders of Text-to-Image Diffusion Models](https://arxiv.org/abs/2503.19897v1)** (Published: 2025-03-25)  
  Authors: Lifu Wang, Daqing Liu, Xinchen Liu, Xiaodong He  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.19897v1.pdf)  
  Keywords: image generation, text-to-image, FLUX  
- **[Boosting Resolution Generalization of Diffusion Transformers with Randomized Positional Encodings](https://arxiv.org/abs/2503.18719v1)** (Published: 2025-03-24)  
  Authors: Cong Liu, Liang Hou, Mingwu Zheng, Xin Tao, Pengfei Wan, Di Zhang, Kun Gai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.18719v1.pdf)  
  Keywords: diffusion transformer, image generation  
- **[Diffusion-4K: Ultra-High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2503.18352v2)** (Published: 2025-03-24)  
  Authors: Jinjin Zhang, Qiuyu Huang, Junjie Liu, Xiefan Guo, Di Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.18352v2.pdf)  
  Keywords: image generation, text-to-image, FLUX  
- **[EDiT: Efficient Diffusion Transformers with Linear Compressed Attention](https://arxiv.org/abs/2503.16726v1)** (Published: 2025-03-20)  
  Authors: Philipp Becker, Abhinav Mehrotra, Ruchika Chavhan, Malcolm Chadwick, Luca Morreale, Mehdi Noroozi, Alberto Gil Ramos, Sourav Bhattacharya  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.16726v1.pdf)  
  Keywords: diffusion transformer, text-to-image, image generation  
- **[InfiniteYou: Flexible Photo Recrafting While Preserving Your Identity](https://arxiv.org/abs/2503.16418v1)** (Published: 2025-03-20)  
  Authors: Liming Jiang, Qing Yan, Yumin Jia, Zichuan Liu, Hao Kang, Xin Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.16418v1.pdf)  
  Keywords: image generation, diffusion transformer, FLUX  
- **[Ultra-Resolution Adaptation with Ease](https://arxiv.org/abs/2503.16322v1)** (Published: 2025-03-20)  
  Authors: Ruonan Yu, Songhua Liu, Zhenxiong Tan, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.16322v1.pdf) | [![GitHub](https://img.shields.io/github/stars/Huage001/URAE?style=social)](https://github.com/Huage001/URAE)  
  Keywords: image generation, text-to-image, FLUX  
- **[FreeFlux: Understanding and Exploiting Layer-Specific Roles in RoPE-Based MMDiT for Versatile Image Editing](https://arxiv.org/abs/2503.16153v1)** (Published: 2025-03-20)  
  Authors: Tianyi Wei, Yifan Zhou, Dongdong Chen, Xingang Pan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.16153v1.pdf)  
  Keywords: FLUX, diffusion transformer, image editing, image generation, text-to-image  
- **[Guardians of Generation: Dynamic Inference-Time Copyright Shielding with Adaptive Guidance for AI Image Generation](https://arxiv.org/abs/2503.16171v1)** (Published: 2025-03-19)  
  Authors: Soham Roy, Abhishek Mishra, Shirish Karande, Murari Mandal  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.16171v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://respailab.github.io/gog)  
  Keywords: image generation, text-to-image, FLUX  
- **[DiffMoE: Dynamic Token Selection for Scalable Diffusion Transformers](https://arxiv.org/abs/2503.14487v1)** (Published: 2025-03-18)  
  Authors: Minglei Shi, Ziyang Yuan, Haotian Yang, Xintao Wang, Mingwu Zheng, Xin Tao, Wenliang Zhao, Wenzhao Zheng, Jie Zhou, Jiwen Lu, Pengfei Wan, Di Zhang, Kun Gai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.14487v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shiml20.github.io/DiffMoE/)  
  Keywords: diffusion transformer, text-to-image, image generation  
- **[Personalize Anything for Free with Diffusion Transformer](https://arxiv.org/abs/2503.12590v1)** (Published: 2025-03-16)  
  Authors: Haoran Feng, Zehuan Huang, Lin Li, Hairong Lv, Lu Sheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.12590v1.pdf)  
  Keywords: image editing, diffusion transformer, image generation, Control  
- **[Reflect-DiT: Inference-Time Scaling for Text-to-Image Diffusion Transformers via In-Context Reflection](https://arxiv.org/abs/2503.12271v1)** (Published: 2025-03-15)  
  Authors: Shufan Li, Konstantinos Kallidromitis, Akash Gokul, Arsh Koneru, Yusuke Kato, Kazuki Kozuka, Aditya Grover  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.12271v1.pdf)  
  Keywords: diffusion transformer, text-to-image, image generation  
- **[DiT-Air: Revisiting the Efficiency of Diffusion Model Architecture Design in Text to Image Generation](https://arxiv.org/abs/2503.10618v2)** (Published: 2025-03-13)  
  Authors: Chen Chen, Rui Qian, Wenze Hu, Tsu-Jui Fu, Jialing Tong, Xinze Wang, Lezhi Li, Bowen Zhang, Alex Schwing, Wei Liu, Yinfei Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.10618v2.pdf)  
  Keywords: diffusion transformer, text-to-image, image generation  
- **[Do I look like a `cat.n.01` to you? A Taxonomy Image Generation Benchmark](https://arxiv.org/abs/2503.10357v1)** (Published: 2025-03-13)  
  Authors: Viktor Moskvoretskii, Alina Lobanova, Ekaterina Neminova, Chris Biemann, Alexander Panchenko, Irina Nikishina  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.10357v1.pdf)  
  Keywords: image generation, text-to-image, FLUX  

### Video Related

*Showing the latest 50 out of 113 papers*

- **[Training-Free Efficient Video Generation via Dynamic Token Carving](https://arxiv.org/abs/2505.16864v1)** (Published: 2025-05-22)  
  Authors: Yuechen Zhang, Jinbo Xing, Bin Xia, Shaoteng Liu, Bohao Peng, Xin Tao, Pengfei Wan, Eric Lo, Jiaya Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.16864v1.pdf) | [![GitHub](https://img.shields.io/github/stars/dvlab-research/Jenga?style=social)](https://github.com/dvlab-research/Jenga)  
  Keywords: video generation, diffusion transformer  
- **[Interspatial Attention for Efficient 4D Human Video Generation](https://arxiv.org/abs/2505.15800v1)** (Published: 2025-05-21)  
  Authors: Ruizhi Shao, Yinghao Xu, Yujun Shen, Ceyuan Yang, Yang Zheng, Changan Chen, Yebin Liu, Gordon Wetzstein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.15800v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dsaurus.github.io/isa4d/.)  
  Keywords: video generation, Controllable, diffusion transformer, Control  
- **[Grouping First, Attending Smartly: Training-Free Acceleration for Diffusion Transformers](https://arxiv.org/abs/2505.14687v1)** (Published: 2025-05-20)  
  Authors: Sucheng Ren, Qihang Yu, Ju He, Alan Yuille, Liang-Chieh Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.14687v1.pdf)  
  Keywords: video generation, diffusion transformer, FLUX  
- **[LMP: Leveraging Motion Prior in Zero-Shot Video Generation with Diffusion Transformer](https://arxiv.org/abs/2505.14167v1)** (Published: 2025-05-20)  
  Authors: Changgu Chen, Xiaoyan Yang, Junwei Shu, Changbo Wang, Yang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.14167v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vpx-ecnu.github.io/LMP-Website/)  
  Keywords: video generation, diffusion transformer, Control  
- **[DraftAttention: Fast Video Diffusion via Low-Resolution Attention Guidance](https://arxiv.org/abs/2505.14708v1)** (Published: 2025-05-17)  
  Authors: Xuan Shen, Chenxia Han, Yufa Zhou, Yanyue Xie, Yifan Gong, Quanyi Wang, Yiwei Wang, Yanzhi Wang, Pu Zhao, Jiuxiang Gu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.14708v1.pdf) | [![GitHub](https://img.shields.io/github/stars/shawnricecake/draft-attention?style=social)](https://github.com/shawnricecake/draft-attention)  
  Keywords: video generation, diffusion transformer  
- **[DanceGRPO: Unleashing GRPO on Visual Generation](https://arxiv.org/abs/2505.07818v1)** (Published: 2025-05-12)  
  Authors: Zeyue Xue, Jie Wu, Yu Gao, Fangyuan Kong, Lingting Zhu, Mengzhao Chen, Zhiheng Liu, Wei Liu, Qiushan Guo, Weilin Huang, Ping Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.07818v1.pdf)  
  Keywords: video generation, rectified flow, FLUX, text-to-image  
- **[Generative Pre-trained Autoregressive Diffusion Transformer](https://arxiv.org/abs/2505.07344v4)** (Published: 2025-05-12)  
  Authors: Yuan Zhang, Jiacheng Jiang, Guoqing Ma, Zhiying Lu, Haoyang Huang, Jianlong Yuan, Nan Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.07344v4.pdf)  
  Keywords: video generation, diffusion transformer  
- **[DualReal: Adaptive Joint Training for Lossless Identity-Motion Fusion in Video Customization](https://arxiv.org/abs/2505.02192v1)** (Published: 2025-05-04)  
  Authors: Wenchuan Wang, Mengqi Huang, Yijing Tu, Zhendong Mao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.02192v1.pdf)  
  Keywords: video generation, diffusion transformer, Control  
- **[DiVE: Efficient Multi-View Driving Scenes Generation Based on Video Diffusion Transformer](https://arxiv.org/abs/2504.19614v1)** (Published: 2025-04-28)  
  Authors: Junpeng Jiang, Gangyi Hong, Miao Zhang, Hengtong Hu, Kun Zhan, Rui Shao, Liqiang Nie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.19614v1.pdf)  
  Keywords: video generation, diffusion transformer, Control  
- **[DiTPainter: Efficient Video Inpainting with Diffusion Transformers](https://arxiv.org/abs/2504.15661v3)** (Published: 2025-04-22)  
  Authors: Xian Wu, Chang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.15661v3.pdf)  
  Keywords: video generation, video inpainting, diffusion transformer  
- **[Turbo2K: Towards Ultra-Efficient and High-Quality 2K Video Synthesis](https://arxiv.org/abs/2504.14470v1)** (Published: 2025-04-20)  
  Authors: Jingjing Ren, Wenbo Li, Zhongdao Wang, Haoze Sun, Bangzhen Liu, Haoyu Chen, Jiaqi Xu, Aoxue Li, Shifeng Zhang, Bin Shao, Yong Guo, Lei Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.14470v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[VGDFR: Diffusion-based Video Generation with Dynamic Latent Frame Rate](https://arxiv.org/abs/2504.12259v1)** (Published: 2025-04-16)  
  Authors: Zhihang Yuan, Rui Xie, Yuzhang Shang, Hanling Zhang, Siyuan Wang, Shengen Yan, Guohao Dai, Yu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.12259v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Analysis of Attention in Video Diffusion Transformers](https://arxiv.org/abs/2504.10317v1)** (Published: 2025-04-14)  
  Authors: Yuxin Wen, Jim Wu, Ajay Jain, Tom Goldstein, Ashwinee Panda  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.10317v1.pdf)  
  Keywords: diffusion transformer, video editing  
- **[Diffusion Transformers for Tabular Data Time Series Generation](https://arxiv.org/abs/2504.07566v2)** (Published: 2025-04-10)  
  Authors: Fabrizio Garuti, Enver Sangineto, Simone Luetto, Lorenzo Forni, Rita Cucchiara  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.07566v2.pdf)  
  Keywords: video generation, diffusion transformer  
- **[DyDiT++: Dynamic Diffusion Transformers for Efficient Visual Generation](https://arxiv.org/abs/2504.06803v2)** (Published: 2025-04-09)  
  Authors: Wangbo Zhao, Yizeng Han, Jiasheng Tang, Kai Wang, Hao Luo, Yibing Song, Gao Huang, Fan Wang, Yang You  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.06803v2.pdf)  
  Keywords: FLUX, diffusion transformer, image generation, video generation, text-to-image  
- **[DiTaiListener: Controllable High Fidelity Listener Video Generation with Diffusion](https://arxiv.org/abs/2504.04010v1)** (Published: 2025-04-05)  
  Authors: Maksim Siniukov, Di Chang, Minh Tran, Hongkun Gong, Ashutosh Chaubey, Mohammad Soleymani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04010v1.pdf)  
  Keywords: video generation, Controllable, diffusion transformer, Control  
- **[SkyReels-A2: Compose Anything in Video Diffusion Transformers](https://arxiv.org/abs/2504.02436v1)** (Published: 2025-04-03)  
  Authors: Zhengcong Fei, Debang Li, Di Qiu, Jiahua Wang, Yikun Dou, Rui Wang, Jingtao Xu, Mingyuan Fan, Guibin Chen, Yang Li, Yahui Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.02436v1.pdf)  
  Keywords: video generation, Controllable, diffusion transformer, Control  
- **[JavisDiT: Joint Audio-Video Diffusion Transformer with Hierarchical Spatio-Temporal Prior Synchronization](https://arxiv.org/abs/2503.23377v1)** (Published: 2025-03-30)  
  Authors: Kai Liu, Wei Li, Lai Chen, Shengqiong Wu, Yanhao Zheng, Jiayi Ji, Fan Zhou, Rongxin Jiang, Jiebo Luo, Hao Fei, Tat-Seng Chua  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.23377v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://javisdit.github.io/.)  
  Keywords: video generation, diffusion transformer  
- **[DynamiCtrl: Rethinking the Basic Structure and the Role of Text for High-quality Human Image Animation](https://arxiv.org/abs/2503.21246v2)** (Published: 2025-03-27)  
  Authors: Haoyu Zhao, Zhongang Qi, Cong Wang, Qingping Zheng, Guansong Lu, Fei Chen, Hang Xu, Zuxuan Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.21246v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gulucaptain.github.io/DynamiCtrl/.)  
  Keywords: video generation, diffusion transformer, Control  
- **[Wan: Open and Advanced Large-Scale Video Generative Models](https://arxiv.org/abs/2503.20314v2)** (Published: 2025-03-26)  
  Authors: Team Wan, Ang Wang, Baole Ai, Bin Wen, Chaojie Mao, Chen-Wei Xie, Di Chen, Feiwu Yu, Haiming Zhao, Jianxiao Yang, Jianyuan Zeng, Jiayu Wang, Jingfeng Zhang, Jingren Zhou, Jinkai Wang, Jixuan Chen, Kai Zhu, Kang Zhao, Keyu Yan, Lianghua Huang, Mengyang Feng, Ningyi Zhang, Pandeng Li, Pingyu Wu, Ruihang Chu, Ruili Feng, Shiwei Zhang, Siyang Sun, Tao Fang, Tianxing Wang, Tianyi Gui, Tingyu Weng, Tong Shen, Wei Lin, Wei Wang, Wei Wang, Wenmeng Zhou, Wente Wang, Wenting Shen, Wenyuan Yu, Xianzhong Shi, Xiaoming Huang, Xin Xu, Yan Kou, Yangyu Lv, Yifei Li, Yijing Liu, Yiming Wang, Yingya Zhang, Yitong Huang, Yong Li, You Wu, Yu Liu, Yulin Pan, Yun Zheng, Yuntao Hong, Yupeng Shi, Yutong Feng, Zeyinzi Jiang, Zhen Han, Zhi-Fan Wu, Ziyu Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.20314v2.pdf) | [![GitHub](https://img.shields.io/github/stars/Wan-Video/Wan2.1?style=social)](https://github.com/Wan-Video/Wan2.1)  
  Keywords: video generation, diffusion transformer, video editing  
- **[Mask$^2$DiT: Dual Mask-based Diffusion Transformer for Multi-Scene Long Video Generation](https://arxiv.org/abs/2503.19881v1)** (Published: 2025-03-25)  
  Authors: Tianhao Qi, Jianlong Yuan, Wanquan Feng, Shancheng Fang, Jiawei Liu, SiYu Zhou, Qian He, Hongtao Xie, Yongdong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.19881v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://tianhao-qi.github.io/Mask2DiTProject.)  
  Keywords: video generation, diffusion transformer  
- **[AudCast: Audio-Driven Human Video Generation by Cascaded Diffusion Transformers](https://arxiv.org/abs/2503.19824v1)** (Published: 2025-03-25)  
  Authors: Jiazhi Guan, Kaisiyuan Wang, Zhiliang Xu, Quanwei Yang, Yasheng Sun, Shengyi He, Borong Liang, Yukang Cao, Yingying Li, Haocheng Feng, Errui Ding, Jingdong Wang, Youjian Zhao, Hang Zhou, Ziwei Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.19824v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://guanjz20.github.io/projects/AudCast.)  
  Keywords: video generation, diffusion transformer  
- **[FuXi-RTM: A Physics-Guided Prediction Framework with Radiative Transfer Modeling](https://arxiv.org/abs/2503.19940v1)** (Published: 2025-03-25)  
  Authors: Qiusheng Huang, Xiaohui Zhong, Xu Fan, Lei Chen, Hao Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.19940v1.pdf)  
  Keywords: video generation, FLUX  
- **[Long-Context Autoregressive Video Modeling with Next-Frame Prediction](https://arxiv.org/abs/2503.19325v3)** (Published: 2025-03-25)  
  Authors: Yuchao Gu, Weijia Mao, Mike Zheng Shou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.19325v3.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Generating, Fast and Slow: Scalable Parallel Video Generation with Video Interface Networks](https://arxiv.org/abs/2503.17539v1)** (Published: 2025-03-21)  
  Authors: Bhishma Dedhia, David Bourgin, Krishna Kumar Singh, Yuheng Li, Yan Kang, Zhan Xu, Niraj K. Jha, Yuchen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.17539v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Long Context Tuning for Video Generation](https://arxiv.org/abs/2503.10589v1)** (Published: 2025-03-13)  
  Authors: Yuwei Guo, Ceyuan Yang, Ziyan Yang, Zhibei Ma, Zhijie Lin, Zhenheng Yang, Dahua Lin, Lu Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.10589v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://guoyww.github.io/projects/long-context-video/)  
  Keywords: video generation, diffusion transformer  
- **[Other Vehicle Trajectories Are Also Needed: A Driving World Model Unifies Ego-Other Vehicle Trajectories in Video Latent Space](https://arxiv.org/abs/2503.09215v2)** (Published: 2025-03-12)  
  Authors: Jian Zhu, Zhengyu Jia, Tian Gao, Jiaxin Deng, Shidi Li, Fu Liu, Peng Jia, Xianpeng Lang, Xiaolong Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.09215v2.pdf)  
  Keywords: video generation, Controllable, diffusion transformer, Control  
- **[Reangle-A-Video: 4D Video Generation as Video-to-Video Translation](https://arxiv.org/abs/2503.09151v2)** (Published: 2025-03-12)  
  Authors: Hyeonho Jeong, Suhyeon Lee, Jong Chul Ye  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.09151v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hyeonho99.github.io/reangle-a-video/)  
  Keywords: video generation, diffusion transformer, Control  
- **[REGEN: Learning Compact Video Embedding with (Re-)Generative Decoder](https://arxiv.org/abs/2503.08665v1)** (Published: 2025-03-11)  
  Authors: Yitian Zhang, Long Mai, Aniruddha Mahapatra, David Bourgin, Yicong Hong, Jonah Casebeer, Feng Liu, Yun Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.08665v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[VACE: All-in-One Video Creation and Editing](https://arxiv.org/abs/2503.07598v2)** (Published: 2025-03-10)  
  Authors: Zeyinzi Jiang, Zhen Han, Chaojie Mao, Jingfeng Zhang, Yulin Pan, Yu Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07598v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ali-vilab.github.io/VACE-Page/.)  
  Keywords: video generation, diffusion transformer, video editing  
- **[QuantCache: Adaptive Importance-Guided Quantization with Hierarchical Latent and Layer Caching for Video Generation](https://arxiv.org/abs/2503.06545v1)** (Published: 2025-03-09)  
  Authors: Junyi Wu, Zhiteng Li, Zheng Hui, Yulun Zhang, Linghe Kong, Xiaokang Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.06545v1.pdf) | [![GitHub](https://img.shields.io/github/stars/JunyiWuCode/QuantCache?style=social)](https://github.com/JunyiWuCode/QuantCache)  
  Keywords: video generation, diffusion transformer  
- **[Get In Video: Add Anything You Want to the Video](https://arxiv.org/abs/2503.06268v1)** (Published: 2025-03-08)  
  Authors: Shaobin Zhuang, Zhipeng Huang, Binxin Yang, Ying Zhang, Fangyikang Wang, Canmiao Fu, Chong Sun, Zheng-Jun Zha, Chen Li, Yali Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.06268v1.pdf)  
  Keywords: diffusion transformer, video editing  
- **[MagicInfinite: Generating Infinite Talking Videos with Your Words and Voice](https://arxiv.org/abs/2503.05978v1)** (Published: 2025-03-07)  
  Authors: Hongwei Yi, Tian Ye, Shitong Shao, Xuancheng Yang, Jiantong Zhao, Hanzhong Guo, Terrance Wang, Qingyu Yin, Zeke Xie, Lei Zhu, Wei Li, Michael Lingelbach, Daquan Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.05978v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://www.hedra.com/,)  
  Keywords: video generation, diffusion transformer, Control  
- **[Rethinking Video Super-Resolution: Towards Diffusion-Based Methods without Motion Alignment](https://arxiv.org/abs/2503.03355v4)** (Published: 2025-03-05)  
  Authors: Zhihao Zhan, Wang Pang, Xiang Zhu, Yechao Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.03355v4.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Training-free and Adaptive Sparse Attention for Efficient Long Video Generation](https://arxiv.org/abs/2502.21079v1)** (Published: 2025-02-28)  
  Authors: Yifei Xia, Suhan Ling, Fangcheng Fu, Yujie Wang, Huixia Li, Xuefeng Xiao, Bin Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.21079v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[FlexiDiT: Your Diffusion Transformer Can Easily Generate High-Quality Samples with Less Compute](https://arxiv.org/abs/2502.20126v1)** (Published: 2025-02-27)  
  Authors: Sotiris Anagnostidis, Gregor Bachmann, Yeongmin Kim, Jonas Kohler, Markos Georgopoulos, Artsiom Sanakoyeu, Yuming Du, Albert Pumarola, Ali Thabet, Edgar Schönfeld  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.20126v1.pdf)  
  Keywords: video generation, diffusion transformer, image generation  
- **[RIFLEx: A Free Lunch for Length Extrapolation in Video Diffusion Transformers](https://arxiv.org/abs/2502.15894v1)** (Published: 2025-02-21)  
  Authors: Min Zhao, Guande He, Yixiao Chen, Hongzhou Zhu, Chongxuan Li, Jun Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.15894v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://riflex-video.github.io/}{https://riflex-video.github.io/.})  
  Keywords: video generation, diffusion transformer  
- **[Hardware-Friendly Static Quantization Method for Video Diffusion Transformers](https://arxiv.org/abs/2502.15077v2)** (Published: 2025-02-20)  
  Authors: Sanghyun Yi, Qingfeng Liu, Mostafa El-Khamy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.15077v2.pdf)  
  Keywords: video generation, diffusion transformer  
- **[RelaCtrl: Relevance-Guided Efficient Control for Diffusion Transformers](https://arxiv.org/abs/2502.14377v4)** (Published: 2025-02-20)  
  Authors: Ke Cao, Jing Wang, Ao Ma, Jiasong Feng, Zhanjie Zhang, Xuanhua He, Shanyuan Liu, Bo Cheng, Dawei Leng, Yuhui Yin, Jie Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.14377v4.pdf)  
  Keywords: Controllable, diffusion transformer, video generation, text-to-image, Control  
- **[Designing Parameter and Compute Efficient Diffusion Transformers using Distillation](https://arxiv.org/abs/2502.14226v1)** (Published: 2025-02-20)  
  Authors: Vignesh Sundaresha  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.14226v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[FantasyID: Face Knowledge Enhanced ID-Preserving Video Generation](https://arxiv.org/abs/2502.13995v1)** (Published: 2025-02-19)  
  Authors: Yunpeng Zhang, Qiang Wang, Fan Jiang, Yaqi Fan, Mu Xu, Yonggang Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.13995v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Lumina-Video: Efficient and Flexible Video Generation with Multi-scale Next-DiT](https://arxiv.org/abs/2502.06782v2)** (Published: 2025-02-10)  
  Authors: Dongyang Liu, Shicheng Li, Yutong Liu, Zhen Li, Kai Wang, Xinyue Li, Qi Qin, Yufei Liu, Yi Xin, Zhongyu Li, Bin Fu, Chenyang Si, Yuewen Cao, Conghui He, Ziwei Liu, Yu Qiao, Qibin Hou, Hongsheng Li, Peng Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.06782v2.pdf) | [![GitHub](https://img.shields.io/github/stars/Alpha-VLLM/Lumina-Video?style=social)](https://github.com/Alpha-VLLM/Lumina-Video)  
  Keywords: video generation, diffusion transformer, Control  
- **[CustomVideoX: 3D Reference Attention Driven Dynamic Adaptation for Zero-Shot Customized Video Diffusion Transformers](https://arxiv.org/abs/2502.06527v2)** (Published: 2025-02-10)  
  Authors: D. She, Mushui Liu, Jingxuan Pang, Jin Wang, Zhen Yang, Wanggui He, Guanghao Zhang, Yi Wang, Qihan Huang, Haobin Tang, Yunlong Yu, Siming Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.06527v2.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Efficient-vDiT: Efficient Video Diffusion Transformers With Attention Tile](https://arxiv.org/abs/2502.06155v2)** (Published: 2025-02-10)  
  Authors: Hangliang Ding, Dacheng Li, Runlong Su, Peiyuan Zhang, Zhijie Deng, Ion Stoica, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.06155v2.pdf)  
  Keywords: video generation, diffusion transformer  
- **[HumanDiT: Pose-Guided Diffusion Transformer for Long-form Human Motion Video Generation](https://arxiv.org/abs/2502.04847v4)** (Published: 2025-02-07)  
  Authors: Qijun Gan, Yi Ren, Chen Zhang, Zhenhui Ye, Pan Xie, Xiang Yin, Zehuan Yuan, Bingyue Peng, Jianke Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.04847v4.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Fast Video Generation with Sliding Tile Attention](https://arxiv.org/abs/2502.04507v1)** (Published: 2025-02-06)  
  Authors: Peiyuan Zhang, Yongqi Chen, Runlong Su, Hangliang Ding, Ion Stoica, Zhenghong Liu, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.04507v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[UniForm: A Unified Multi-Task Diffusion Transformer for Audio-Video Generation](https://arxiv.org/abs/2502.03897v4)** (Published: 2025-02-06)  
  Authors: Lei Zhao, Linfeng Feng, Dongxu Ge, Rujin Chen, Fangqiu Yi, Chi Zhang, Xiao-Lei Zhang, Xuelong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.03897v4.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://uniform-t2av.github.io/.)  
  Keywords: video generation, diffusion transformer  
- **[UniCP: A Unified Caching and Pruning Framework for Efficient Video Generation](https://arxiv.org/abs/2502.04393v1)** (Published: 2025-02-06)  
  Authors: Wenzhang Sun, Qirui Hou, Donglin Di, Jiahui Yang, Yongjia Ma, Jianxun Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.04393v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Sparse VideoGen: Accelerating Video Diffusion Transformers with Spatial-Temporal Sparsity](https://arxiv.org/abs/2502.01776v2)** (Published: 2025-02-03)  
  Authors: Haocheng Xi, Shuo Yang, Yilong Zhao, Chenfeng Xu, Muyang Li, Xiuyu Li, Yujun Lin, Han Cai, Jintao Zhang, Dacheng Li, Jianfei Chen, Ion Stoica, Kurt Keutzer, Song Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.01776v2.pdf) | [![GitHub](https://img.shields.io/github/stars/svg-project/Sparse-VideoGen?style=social)](https://github.com/svg-project/Sparse-VideoGen)  
  Keywords: video generation, diffusion transformer  
- **[OmniHuman-1: Rethinking the Scaling-Up of One-Stage Conditioned Human Animation Models](https://arxiv.org/abs/2502.01061v2)** (Published: 2025-02-03)  
  Authors: Gaojie Lin, Jianwen Jiang, Jiaqi Yang, Zerong Zheng, Chao Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.01061v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://omnihuman-lab.github.io))  
  Keywords: video generation, diffusion transformer  



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
