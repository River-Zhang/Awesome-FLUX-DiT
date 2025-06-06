# Awesome FLUX/DiT methods [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to DiT/FLUX. Content is automatically updated daily.

> Last Update: 2025-06-06 06:35:38

Thanks to [@longxiang-ai](https://github.com/longxiang-ai) for the template.

## Categories

- [Image Editing](#image-editing) (36 papers) - Papers about image editing with Diffusion Transformer or FLUX
- [Image Generation](#image-generation) (194 papers) - Papers focusing on image generation with Diffusion Transformer or FLUX
- [Video Related](#video-related) (135 papers) - Papers about video generation and editing with Diffusion Transformer or FLUX



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### Image Editing

- **[Image Editing As Programs with Diffusion Models](https://arxiv.org/abs/2506.04158v1)** (Published: 2025-06-04)  
  Authors: Yujia Hu, Songhua Liu, Zhenxiong Tan, Xingyi Yang, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.04158v1.pdf) | [![GitHub](https://img.shields.io/github/stars/YujiaHu1109/IEAP?style=social)](https://github.com/YujiaHu1109/IEAP)  
  Keywords: image generation, image editing, diffusion transformer, text-to-image  
- **[ByteMorph: Benchmarking Instruction-Guided Image Editing with Non-Rigid Motions](https://arxiv.org/abs/2506.03107v1)** (Published: 2025-06-03)  
  Authors: Di Chang, Mingdeng Cao, Yichun Shi, Bo Liu, Shengqu Cai, Shijie Zhou, Weilin Huang, Gordon Wetzstein, Mohammad Soleymani, Peng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.03107v1.pdf)  
  Keywords: image editing, diffusion transformer  
- **[RelationAdapter: Learning and Transferring Visual Relation with Diffusion Transformers](https://arxiv.org/abs/2506.02528v1)** (Published: 2025-06-03)  
  Authors: Yan Gong, Yiren Song, Yicheng Li, Chenglin Li, Yin Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.02528v1.pdf)  
  Keywords: image editing, diffusion transformer  
- **[LoRAShop: Training-Free Multi-Concept Image Generation and Editing with Rectified Flow Transformers](https://arxiv.org/abs/2505.23758v1)** (Published: 2025-05-29)  
  Authors: Yusuf Dalva, Hidir Yesiltepe, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.23758v1.pdf)  
  Keywords: image generation, image editing, diffusion transformer, FLUX, rectified flow  
- **[HiDream-I1: A High-Efficient Image Generative Foundation Model with Sparse Diffusion Transformer](https://arxiv.org/abs/2505.22705v1)** (Published: 2025-05-28)  
  Authors: Qi Cai, Jingwen Chen, Yang Chen, Yehao Li, Fuchen Long, Yingwei Pan, Zhaofan Qiu, Yiheng Zhang, Fengbin Gao, Peihan Xu, Yimeng Wang, Kai Yu, Wenxuan Chen, Ziwei Feng, Zijian Gong, Jianzhuang Pan, Yi Peng, Rui Tian, Siyu Wang, Bo Zhao, Ting Yao, Tao Mei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.22705v1.pdf) | [![GitHub](https://img.shields.io/github/stars/HiDream-ai/HiDream-I1?style=social)](https://github.com/HiDream-ai/HiDream-I1) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vivago.ai/studio.)  
  Keywords: image generation, image editing, diffusion transformer, text-to-image  
- **[DanceGRPO: Unleashing GRPO on Visual Generation](https://arxiv.org/abs/2505.07818v1)** (Published: 2025-05-12)  
  Authors: Zeyue Xue, Jie Wu, Yu Gao, Fangyuan Kong, Lingting Zhu, Mengzhao Chen, Zhiheng Liu, Wei Liu, Qiushan Guo, Weilin Huang, Ping Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.07818v1.pdf)  
  Keywords: FLUX, rectified flow, text-to-image, video generation  
- **[Lay-Your-Scene: Natural Scene Layout Generation with Diffusion Transformers](https://arxiv.org/abs/2505.04718v1)** (Published: 2025-05-07)  
  Authors: Divyansh Srivastava, Xiang Zhang, He Wen, Chenru Wen, Zhuowen Tu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.04718v1.pdf)  
  Keywords: Controllable, image generation, image editing, diffusion transformer, Control  
- **[In-Context Edit: Enabling Instructional Image Editing with In-Context Generation in Large Scale Diffusion Transformer](https://arxiv.org/abs/2504.20690v1)** (Published: 2025-04-29)  
  Authors: Zechuan Zhang, Ji Xie, Yu Lu, Zongxin Yang, Yi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.20690v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://river-zhang.github.io/ICEdit-gh-pages/.)  
  Keywords: image editing, diffusion transformer  
- **[Disentangling Instruction Influence in Diffusion Transformers for Parallel Multi-Instruction-Guided Image Editing](https://arxiv.org/abs/2504.04784v1)** (Published: 2025-04-07)  
  Authors: Hui Liu, Bin Zou, Suiyun Zhang, Kecheng Chen, Rui Liu, Haoliang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04784v1.pdf)  
  Keywords: image editing, Control, diffusion transformer  
- **[Detection Limits and Statistical Separability of Tree Ring Watermarks in Rectified Flow-based Text-to-Image Generation Models](https://arxiv.org/abs/2504.03850v1)** (Published: 2025-04-04)  
  Authors: Ved Umrajkar, Aakash Kumar Singh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.03850v1.pdf) | [![GitHub](https://img.shields.io/github/stars/dsgiitr/flux-watermarking?style=social)](https://github.com/dsgiitr/flux-watermarking)  
  Keywords: text-to-image, image generation, FLUX, rectified flow, inversion  
- **[DiT4SR: Taming Diffusion Transformer for Real-World Image Super-Resolution](https://arxiv.org/abs/2503.23580v1)** (Published: 2025-03-30)  
  Authors: Zheng-Peng Duan, Jiawei Zhang, Xin Jin, Ziheng Zhang, Zheng Xiong, Dongqing Zou, Jimmy Ren, Chun-Le Guo, Chongyi Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.23580v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://adam-duan.github.io/projects/dit4sr/.)  
  Keywords: image super-resolution, image generation, Control, diffusion transformer  
- **[FreeFlux: Understanding and Exploiting Layer-Specific Roles in RoPE-Based MMDiT for Versatile Image Editing](https://arxiv.org/abs/2503.16153v1)** (Published: 2025-03-20)  
  Authors: Tianyi Wei, Yifan Zhou, Dongdong Chen, Xingang Pan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.16153v1.pdf)  
  Keywords: text-to-image, image generation, image editing, diffusion transformer, FLUX  
- **[Personalize Anything for Free with Diffusion Transformer](https://arxiv.org/abs/2503.12590v1)** (Published: 2025-03-16)  
  Authors: Haoran Feng, Zehuan Huang, Lin Li, Hairong Lv, Lu Sheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.12590v1.pdf)  
  Keywords: image editing, image generation, Control, diffusion transformer  
- **[NAMI: Efficient Image Generation via Progressive Rectified Flow Transformers](https://arxiv.org/abs/2503.09242v1)** (Published: 2025-03-12)  
  Authors: Yuhang Ma, Bo Cheng, Shanyuan Liu, Ao Ma, Xiaoyu Wu, Liebucha Wu, Dawei Leng, Yuhui Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.09242v1.pdf)  
  Keywords: image generation, rectified flow, diffusion transformer  
- **[Seedream 2.0: A Native Chinese-English Bilingual Image Generation Foundation Model](https://arxiv.org/abs/2503.07703v1)** (Published: 2025-03-10)  
  Authors: Lixue Gong, Xiaoxia Hou, Fanshi Li, Liang Li, Xiaochen Lian, Fei Liu, Liyang Liu, Wei Liu, Wei Lu, Yichun Shi, Shiqi Sun, Yu Tian, Zhi Tian, Peng Wang, Xun Wang, Ye Wang, Guofeng Wu, Jie Wu, Xin Xia, Xuefeng Xiao, Linjie Yang, Zhonghua Zhai, Xinyu Zhang, Qi Zhang, Yuwei Zhang, Shijia Zhao, Jianchao Yang, Weilin Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07703v1.pdf)  
  Keywords: FLUX, image editing, image generation  
- **[TIDE : Temporal-Aware Sparse Autoencoders for Interpretable Diffusion Transformers in Image Generation](https://arxiv.org/abs/2503.07050v1)** (Published: 2025-03-10)  
  Authors: Victor Shea-Jay Huang, Le Zhuo, Yi Xin, Zhaokai Wang, Peng Gao, Hongsheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07050v1.pdf)  
  Keywords: image editing, image generation, Control, diffusion transformer  
- **[X2I: Seamless Integration of Multimodal Understanding into Diffusion Transformer via Attention Distillation](https://arxiv.org/abs/2503.06134v2)** (Published: 2025-03-08)  
  Authors: Jian Ma, Qirong Peng, Xu Guo, Chen Chen, Haonan Lu, Zhenyu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.06134v2.pdf) | [![GitHub](https://img.shields.io/github/stars/OPPO-Mente-Lab/X2I?style=social)](https://github.com/OPPO-Mente-Lab/X2I)  
  Keywords: text-to-image, image generation, image editing, diffusion transformer, image to image, Control  
- **[AnyRefill: A Unified, Data-Efficient Framework for Left-Prompt-Guided Vision Tasks](https://arxiv.org/abs/2502.11158v2)** (Published: 2025-02-16)  
  Authors: Ming Xie, Chenjie Cao, Yunuo Cai, Xiangyang Xue, Yu-Gang Jiang, Yanwei Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.11158v2.pdf)  
  Keywords: image editing, diffusion transformer, text-to-image  
- **[EliGen: Entity-Level Controlled Image Generation with Regional Attention](https://arxiv.org/abs/2501.01097v3)** (Published: 2025-01-02)  
  Authors: Hong Zhang, Zhongjie Duan, Xingjun Wang, Yingda Chen, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.01097v3.pdf) | [![GitHub](https://img.shields.io/github/stars/modelscope/DiffSynth-Studio.git?style=social)](https://github.com/modelscope/DiffSynth-Studio.git)  
  Keywords: text-to-image, image generation, diffusion transformer, Control, image inpainting  
- **[Context Canvas: Enhancing Text-to-Image Diffusion Models with Knowledge Graph-Based RAG](https://arxiv.org/abs/2412.09614v1)** (Published: 2024-12-12)  
  Authors: Kavana Venkatesh, Yusuf Dalva, Ismini Lourentzou, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09614v1.pdf)  
  Keywords: image editing, FLUX, Control, text-to-image  
- **[FluxSpace: Disentangled Semantic Editing in Rectified Flow Transformers](https://arxiv.org/abs/2412.09611v1)** (Published: 2024-12-12)  
  Authors: Yusuf Dalva, Kavana Venkatesh, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09611v1.pdf)  
  Keywords: image generation, image editing, FLUX, rectified flow, Control  
- **[AMO Sampler: Enhancing Text Rendering with Overshooting](https://arxiv.org/abs/2411.19415v2)** (Published: 2024-11-28)  
  Authors: Xixi Hu, Keyang Xu, Bo Liu, Qiang Liu, Hongliang Fei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.19415v2.pdf) | [![GitHub](https://img.shields.io/github/stars/hxixixh/amo-release?style=social)](https://github.com/hxixixh/amo-release)  
  Keywords: text-to-image, image generation, FLUX, rectified flow, Control  
- **[Prediction with Action: Visual Policy Learning via Joint Denoising Process](https://arxiv.org/abs/2411.18179v1)** (Published: 2024-11-27)  
  Authors: Yanjiang Guo, Yucheng Hu, Jianke Zhang, Yen-Jen Wang, Xiaoyu Chen, Chaochao Lu, Jianyu Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.18179v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sites.google.com/view/pad-paper)  
  Keywords: image editing, image generation, Control, diffusion transformer  
- **[HeadRouter: A Training-free Image Editing Framework for MM-DiTs by Adaptively Routing Attention Heads](https://arxiv.org/abs/2411.15034v1)** (Published: 2024-11-22)  
  Authors: Yu Xu, Fan Tang, Juan Cao, Yuxin Zhang, Xiaoyu Kong, Jintao Li, Oliver Deussen, Tong-Yee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.15034v1.pdf)  
  Keywords: image generation, image editing, diffusion transformer  
- **[Stable Flow: Vital Layers for Training-Free Image Editing](https://arxiv.org/abs/2411.14430v2)** (Published: 2024-11-21)  
  Authors: Omri Avrahami, Or Patashnik, Ohad Fried, Egor Nemchinov, Kfir Aberman, Dani Lischinski, Daniel Cohen-Or  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.14430v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://omriavrahami.com/stable-flow)  
  Keywords: image editing, inversion, Control, diffusion transformer  
- **[Oscillation Inversion: Understand the structure of Large Flow Model through the Lens of Inversion Method](https://arxiv.org/abs/2411.11135v1)** (Published: 2024-11-17)  
  Authors: Yan Zheng, Zhenxiao Liang, Xiaoyan Cong, Lanqing guo, Yuehao Wang, Peihao Wang, Zhangyang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.11135v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yanyanzheng96.github.io/oscillation_inversion/}{this)  
  Keywords: text-to-image, image editing, FLUX, rectified flow, inversion  
- **[Latent Space Disentanglement in Diffusion Transformers Enables Precise Zero-shot Semantic Editing](https://arxiv.org/abs/2411.08196v1)** (Published: 2024-11-12)  
  Authors: Zitao Shuai, Chenwei Wu, Zhengxu Tang, Bowen Song, Liyue Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.08196v1.pdf)  
  Keywords: image editing, image generation, Control, diffusion transformer  
- **[Taming Rectified Flow for Inversion and Editing](https://arxiv.org/abs/2411.04746v2)** (Published: 2024-11-07)  
  Authors: Jiangshan Wang, Junfu Pu, Zhongang Qi, Jiayi Guo, Yue Ma, Nisha Huang, Yuxin Chen, Xiu Li, Ying Shan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.04746v2.pdf) | [![GitHub](https://img.shields.io/github/stars/wangjiangshan0725/RF-Solver-Edit?style=social)](https://github.com/wangjiangshan0725/RF-Solver-Edit)  
  Keywords: diffusion transformer, FLUX, rectified flow, inversion, video editing, video generation  
- **[DiT4Edit: Diffusion Transformer for Image Editing](https://arxiv.org/abs/2411.03286v2)** (Published: 2024-11-05)  
  Authors: Kunyu Feng, Yue Ma, Bingyuan Wang, Chenyang Qi, Haozhe Chen, Qifeng Chen, Zeyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.03286v2.pdf)  
  Keywords: image generation, image editing, diffusion transformer, Control, inversion  
- **[FiTv2: Scalable and Improved Flexible Vision Transformer for Diffusion Model](https://arxiv.org/abs/2410.13925v1)** (Published: 2024-10-17)  
  Authors: ZiDong Wang, Zeyu Lu, Di Huang, Cai Zhou, Wanli Ouyang, and Lei Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.13925v1.pdf) | [![GitHub](https://img.shields.io/github/stars/whlzy/FiT?style=social)](https://github.com/whlzy/FiT)  
  Keywords: image generation, rectified flow, diffusion transformer  
- **[Semantic Image Inversion and Editing using Rectified Stochastic Differential Equations](https://arxiv.org/abs/2410.10792v1)** (Published: 2024-10-14)  
  Authors: Litu Rout, Yujia Chen, Nataniel Ruiz, Constantine Caramanis, Sanjay Shakkottai, Wen-Sheng Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.10792v1.pdf)  
  Keywords: image editing, FLUX, rectified flow, Control, inversion  
- **[Effective Diffusion Transformer Architecture for Image Super-Resolution](https://arxiv.org/abs/2409.19589v1)** (Published: 2024-09-29)  
  Authors: Kun Cheng, Lei Yu, Zhijun Tu, Xiao He, Liyu Chen, Yong Guo, Mingrui Zhu, Nannan Wang, Xinbo Gao, Jie Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.19589v1.pdf)  
  Keywords: image super-resolution, image generation, diffusion transformer  
- **[PixWizard: Versatile Image-to-Image Visual Assistant with Open-Language Instructions](https://arxiv.org/abs/2409.15278v4)** (Published: 2024-09-23)  
  Authors: Weifeng Lin, Xinyu Wei, Renrui Zhang, Le Zhuo, Shitian Zhao, Siyuan Huang, Huan Teng, Junlin Xie, Yu Qiao, Peng Gao, Hongsheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.15278v4.pdf) | [![GitHub](https://img.shields.io/github/stars/AFeng-x/PixWizard?style=social)](https://github.com/AFeng-x/PixWizard)  
  Keywords: text-to-image, Controllable, image generation, image editing, diffusion transformer, Control  
- **[Latent Space Disentanglement in Diffusion Transformers Enables Zero-shot Fine-grained Semantic Editing](https://arxiv.org/abs/2408.13335v1)** (Published: 2024-08-23)  
  Authors: Zitao Shuai, Chenwei Wu, Zhengxu Tang, Bowen Song, Liyue Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.13335v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://anonymous.com/anonymous/EMS-Benchmark,)  
  Keywords: image editing, Control, diffusion transformer, text-to-image  
- **[Lazy Diffusion Transformer for Interactive Image Editing](https://arxiv.org/abs/2404.12382v1)** (Published: 2024-04-18)  
  Authors: Yotam Nitzan, Zongze Wu, Richard Zhang, Eli Shechtman, Daniel Cohen-Or, Taesung Park, Michaël Gharbi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2404.12382v1.pdf)  
  Keywords: image editing, diffusion transformer  
- **[Lightning-Fast Image Inversion and Editing for Text-to-Image Diffusion Models](https://arxiv.org/abs/2312.12540v5)** (Published: 2023-12-19)  
  Authors: Dvir Samuel, Barak Meiri, Haggai Maron, Yoad Tewel, Nir Darshan, Shai Avidan, Gal Chechik, Rami Ben-Ari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2312.12540v5.pdf)  
  Keywords: FLUX, inversion, image editing, text-to-image  

### Image Generation

*Showing the latest 50 out of 194 papers*

- **[FullDiT2: Efficient In-Context Conditioning for Video Diffusion Transformers](https://arxiv.org/abs/2506.04213v2)** (Published: 2025-06-04)  
  Authors: Xuanhua He, Quande Liu, Zixuan Ye, Weicai Ye, Qiulin Wang, Xintao Wang, Qifeng Chen, Pengfei Wan, Di Zhang, Kun Gai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.04213v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://fulldit2.github.io/}{https://fulldit2.github.io/}.)  
  Keywords: video editing, Control, diffusion transformer, video generation  
- **[Image Editing As Programs with Diffusion Models](https://arxiv.org/abs/2506.04158v1)** (Published: 2025-06-04)  
  Authors: Yujia Hu, Songhua Liu, Zhenxiong Tan, Xingyi Yang, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.04158v1.pdf) | [![GitHub](https://img.shields.io/github/stars/YujiaHu1109/IEAP?style=social)](https://github.com/YujiaHu1109/IEAP)  
  Keywords: image generation, image editing, diffusion transformer, text-to-image  
- **[EmoArt: A Multidimensional Dataset for Emotion-Aware Artistic Generation](https://arxiv.org/abs/2506.03652v1)** (Published: 2025-06-04)  
  Authors: Cheng Zhang, Hongxia xie, Bin Wen, Songhan Zuo, Ruoxuan Zhang, Wen-huang Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.03652v1.pdf)  
  Keywords: FLUX, text-to-image, image generation  
- **[OmniV2V: Versatile Video Generation and Editing via Dynamic Content Manipulation](https://arxiv.org/abs/2506.01801v1)** (Published: 2025-06-02)  
  Authors: Sen Liang, Zhentao Yu, Zhengguang Zhou, Teng Hu, Hongmei Wang, Yi Chen, Qin Lin, Yuan Zhou, Xin Li, Qinglin Lu, Zhibo Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.01801v1.pdf)  
  Keywords: Control, diffusion transformer, video generation, Controllable  
- **[Evaluating Robot Policies in a World Model](https://arxiv.org/abs/2506.00613v1)** (Published: 2025-05-31)  
  Authors: Julian Quevedo, Percy Liang, Sherry Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.00613v1.pdf)  
  Keywords: Control, diffusion transformer, video generation  
- **[Seg2Any: Open-set Segmentation-Mask-to-Image Generation with Precise Shape and Semantic Control](https://arxiv.org/abs/2506.00596v1)** (Published: 2025-05-31)  
  Authors: Danfeng li, Hui Zhang, Sheng Wang, Jiacheng Li, Zuxuan Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.00596v1.pdf)  
  Keywords: text-to-image, image generation, diffusion transformer, FLUX, Control  
- **[Foresight: Adaptive Layer Reuse for Accelerated and High-Quality Text-to-Video Generation](https://arxiv.org/abs/2506.00329v1)** (Published: 2025-05-31)  
  Authors: Muhammad Adnan, Nithesh Kurella, Akhil Arunkumar, Prashant J. Nair  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.00329v1.pdf) | [![GitHub](https://img.shields.io/github/stars/STAR-Laboratory/foresight?style=social)](https://github.com/STAR-Laboratory/foresight)  
  Keywords: diffusion transformer, video generation, text-to-image  
- **[Interpreting Large Text-to-Image Diffusion Models with Dictionary Learning](https://arxiv.org/abs/2505.24360v2)** (Published: 2025-05-30)  
  Authors: Stepan Shabalin, Ayush Panda, Dmitrii Kharlapenko, Abdur Raheem Ali, Yixiong Hao, Arthur Conmy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.24360v2.pdf)  
  Keywords: FLUX, Control, text-to-image, image generation  
- **[LoRAShop: Training-Free Multi-Concept Image Generation and Editing with Rectified Flow Transformers](https://arxiv.org/abs/2505.23758v1)** (Published: 2025-05-29)  
  Authors: Yusuf Dalva, Hidir Yesiltepe, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.23758v1.pdf)  
  Keywords: image generation, image editing, diffusion transformer, FLUX, rectified flow  
- **[Muddit: Liberating Generation Beyond Text-to-Image with a Unified Discrete Diffusion Model](https://arxiv.org/abs/2505.23606v1)** (Published: 2025-05-29)  
  Authors: Qingyu Shi, Jinbin Bai, Zhuoran Zhao, Wenhao Chai, Kaidong Yu, Jianzong Wu, Shuangyong Song, Yunhai Tong, Xiangtai Li, Xuelong Li, Shuicheng Yan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.23606v1.pdf)  
  Keywords: image generation, diffusion transformer, text-to-image  
- **[HiDream-I1: A High-Efficient Image Generative Foundation Model with Sparse Diffusion Transformer](https://arxiv.org/abs/2505.22705v1)** (Published: 2025-05-28)  
  Authors: Qi Cai, Jingwen Chen, Yang Chen, Yehao Li, Fuchen Long, Yingwei Pan, Zhaofan Qiu, Yiheng Zhang, Fengbin Gao, Peihan Xu, Yimeng Wang, Kai Yu, Wenxuan Chen, Ziwei Feng, Zijian Gong, Jianzhuang Pan, Yi Peng, Rui Tian, Siyu Wang, Bo Zhao, Ting Yao, Tao Mei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.22705v1.pdf) | [![GitHub](https://img.shields.io/github/stars/HiDream-ai/HiDream-I1?style=social)](https://github.com/HiDream-ai/HiDream-I1) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vivago.ai/studio.)  
  Keywords: image generation, image editing, diffusion transformer, text-to-image  
- **[Q-VDiT: Towards Accurate Quantization and Distillation of Video-Generation Diffusion Transformers](https://arxiv.org/abs/2505.22167v1)** (Published: 2025-05-28)  
  Authors: Weilun Feng, Chuanguang Yang, Haotong Qin, Xiangqi Li, Yu Wang, Zhulin An, Libo Huang, Boyu Diao, Zixiang Zhao, Yongjun Xu, Michele Magno  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.22167v1.pdf) | [![GitHub](https://img.shields.io/github/stars/cantbebetter2/Q-VDiT?style=social)](https://github.com/cantbebetter2/Q-VDiT)  
  Keywords: image generation, diffusion transformer, video generation  
- **[AlignGen: Boosting Personalized Image Generation with Cross-Modality Prior Alignment](https://arxiv.org/abs/2505.21911v1)** (Published: 2025-05-28)  
  Authors: Yiheng Lin, Shifang Zhao, Ting Liu, Xiaochao Qu, Luoqi Liu, Yao Zhao, Yunchao Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.21911v1.pdf)  
  Keywords: image generation, diffusion transformer, text-to-image  
- **[Frame In-N-Out: Unbounded Controllable Image-to-Video Generation](https://arxiv.org/abs/2505.21491v1)** (Published: 2025-05-27)  
  Authors: Boyang Wang, Xuweiyi Chen, Matheus Gadelha, Zezhou Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.21491v1.pdf)  
  Keywords: Control, diffusion transformer, video generation, Controllable  
- **[Hierarchical Masked Autoregressive Models with Low-Resolution Token Pivots](https://arxiv.org/abs/2505.20288v1)** (Published: 2025-05-26)  
  Authors: Guangting Zheng, Yehao Li, Yingwei Pan, Jiajun Deng, Ting Yao, Yanyong Zhang, Tao Mei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.20288v1.pdf) | [![GitHub](https://img.shields.io/github/stars/HiDream-ai/himar?style=social)](https://github.com/HiDream-ai/himar)  
  Keywords: image generation, diffusion transformer, text-to-image  
- **[Dynamic-I2V: Exploring Image-to-Video Generation Models via Multimodal LLM](https://arxiv.org/abs/2505.19901v3)** (Published: 2025-05-26)  
  Authors: Peng Liu, Xiaoming Ren, Fengkai Liu, Qingsong Xie, Quanlong Zheng, Yanhao Zhang, Haonan Lu, Yujiu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.19901v3.pdf)  
  Keywords: Control, diffusion transformer, video generation  
- **[MMIG-Bench: Towards Comprehensive and Explainable Evaluation of Multi-Modal Image Generation Models](https://arxiv.org/abs/2505.19415v2)** (Published: 2025-05-26)  
  Authors: Hang Hua, Ziyun Zeng, Yizhi Song, Yunlong Tang, Liu He, Daniel Aliaga, Wei Xiong, Jiebo Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.19415v2.pdf)  
  Keywords: FLUX, text-to-image, image generation  
- **[Sparse VideoGen2: Accelerate Video Generation with Sparse Attention via Semantic-Aware Permutation](https://arxiv.org/abs/2505.18875v1)** (Published: 2025-05-24)  
  Authors: Shuo Yang, Haocheng Xi, Yilong Zhao, Muyang Li, Jintao Zhang, Han Cai, Yujun Lin, Xiuyu Li, Chenfeng Xu, Kelly Peng, Jianfei Chen, Song Han, Kurt Keutzer, Ion Stoica  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.18875v1.pdf)  
  Keywords: Control, diffusion transformer, video generation  
- **[Mod-Adapter: Tuning-Free and Versatile Multi-concept Personalization via Modulation Adapter](https://arxiv.org/abs/2505.18612v1)** (Published: 2025-05-24)  
  Authors: Weizhi Zhong, Huan Yang, Zheng Liu, Huiguo He, Zijian He, Xuesong Niu, Di Zhang, Guanbin Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.18612v1.pdf)  
  Keywords: image generation, diffusion transformer, text-to-image  
- **[RestoreVAR: Visual Autoregressive Generation for All-in-One Image Restoration](https://arxiv.org/abs/2505.18047v1)** (Published: 2025-05-23)  
  Authors: Sudarshan Rajagopalan, Kartik Narayan, Vishal M. Patel  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.18047v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[Interspatial Attention for Efficient 4D Human Video Generation](https://arxiv.org/abs/2505.15800v2)** (Published: 2025-05-21)  
  Authors: Ruizhi Shao, Yinghao Xu, Yujun Shen, Ceyuan Yang, Yang Zheng, Changan Chen, Yebin Liu, Gordon Wetzstein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.15800v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dsaurus.github.io/isa4d/.)  
  Keywords: Control, diffusion transformer, video generation, Controllable  
- **[Scaling Diffusion Transformers Efficiently via $μ$P](https://arxiv.org/abs/2505.15270v1)** (Published: 2025-05-21)  
  Authors: Chenyu Zheng, Xinyu Zhang, Rongzhen Wang, Wei Huang, Zhi Tian, Weilin Huang, Jun Zhu, Chongxuan Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.15270v1.pdf)  
  Keywords: image generation, diffusion transformer, text-to-image  
- **[LMP: Leveraging Motion Prior in Zero-Shot Video Generation with Diffusion Transformer](https://arxiv.org/abs/2505.14167v1)** (Published: 2025-05-20)  
  Authors: Changgu Chen, Xiaoyan Yang, Junwei Shu, Changbo Wang, Yang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.14167v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vpx-ecnu.github.io/LMP-Website/)  
  Keywords: Control, diffusion transformer, video generation  
- **[Swin DiT: Diffusion Transformer using Pseudo Shifted Windows](https://arxiv.org/abs/2505.13219v2)** (Published: 2025-05-19)  
  Authors: Jiafu Wu, Yabiao Wang, Jian Li, Jinlong Peng, Yun Cao, Chengjie Wang, Jiangning Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.13219v2.pdf) | [![GitHub](https://img.shields.io/github/stars/wujiafu007/Swin-DiT?style=social)](https://github.com/wujiafu007/Swin-DiT)  
  Keywords: image generation, diffusion transformer  
- **[SounDiT: Geo-Contextual Soundscape-to-Landscape Generation](https://arxiv.org/abs/2505.12734v1)** (Published: 2025-05-19)  
  Authors: Junbo Wang, Haofeng Tan, Bowen Liao, Albert Jiang, Teng Fei, Qixing Huang, Zhengzhong Tu, Shan Ye, Yuhao Kang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.12734v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[Exploring the Deep Fusion of Large Language Models and Diffusion Transformers for Text-to-Image Synthesis](https://arxiv.org/abs/2505.10046v1)** (Published: 2025-05-15)  
  Authors: Bingda Tang, Boyang Zheng, Xichen Pan, Sayak Paul, Saining Xie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.10046v1.pdf)  
  Keywords: image generation, Control, diffusion transformer, text-to-image  
- **[BLIP3-o: A Family of Fully Open Unified Multimodal Models-Architecture, Training and Dataset](https://arxiv.org/abs/2505.09568v1)** (Published: 2025-05-14)  
  Authors: Jiuhai Chen, Zhiyang Xu, Xichen Pan, Yushi Hu, Can Qin, Tom Goldstein, Lifu Huang, Tianyi Zhou, Saining Xie, Silvio Savarese, Le Xue, Caiming Xiong, Ran Xu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.09568v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[Mini Diffuser: Fast Multi-task Diffusion Policy Training Using Two-level Mini-batches](https://arxiv.org/abs/2505.09430v2)** (Published: 2025-05-14)  
  Authors: Yutong Hu, Pinhao Song, Kehan Wen, Renaud Detry  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.09430v2.pdf)  
  Keywords: image generation, diffusion transformer  
- **[DanceGRPO: Unleashing GRPO on Visual Generation](https://arxiv.org/abs/2505.07818v1)** (Published: 2025-05-12)  
  Authors: Zeyue Xue, Jie Wu, Yu Gao, Fangyuan Kong, Lingting Zhu, Mengzhao Chen, Zhiheng Liu, Wei Liu, Qiushan Guo, Weilin Huang, Ping Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.07818v1.pdf)  
  Keywords: FLUX, rectified flow, text-to-image, video generation  
- **[Accelerating Diffusion Transformer via Increment-Calibrated Caching with Channel-Aware Singular Value Decomposition](https://arxiv.org/abs/2505.05829v1)** (Published: 2025-05-09)  
  Authors: Zhiyuan Chen, Keyi Li, Yifan Jia, Le Ye, Yufei Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.05829v1.pdf) | [![GitHub](https://img.shields.io/github/stars/ccccczzy/icc?style=social)](https://github.com/ccccczzy/icc)  
  Keywords: image generation, diffusion transformer  
- **[Lay-Your-Scene: Natural Scene Layout Generation with Diffusion Transformers](https://arxiv.org/abs/2505.04718v1)** (Published: 2025-05-07)  
  Authors: Divyansh Srivastava, Xiang Zhang, He Wen, Chenru Wen, Zhuowen Tu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.04718v1.pdf)  
  Keywords: Controllable, image generation, image editing, diffusion transformer, Control  
- **[Deepfakes on Demand: the rise of accessible non-consensual deepfake image generators](https://arxiv.org/abs/2505.03859v1)** (Published: 2025-05-06)  
  Authors: Will Hawkins, Chris Russell, Brent Mittelstadt  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.03859v1.pdf)  
  Keywords: FLUX, text-to-image  
- **[DualReal: Adaptive Joint Training for Lossless Identity-Motion Fusion in Video Customization](https://arxiv.org/abs/2505.02192v1)** (Published: 2025-05-04)  
  Authors: Wenchuan Wang, Mengqi Huang, Yijing Tu, Zhendong Mao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.02192v1.pdf)  
  Keywords: Control, diffusion transformer, video generation  
- **[JointDiT: Enhancing RGB-Depth Joint Modeling with Diffusion Transformers](https://arxiv.org/abs/2505.00482v1)** (Published: 2025-05-01)  
  Authors: Kwon Byung-Ki, Qi Dai, Lee Hyoseok, Chong Luo, Tae-Hyun Oh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.00482v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://byungki-k.github.io/JointDiT/.)  
  Keywords: image generation, Control, diffusion transformer  
- **[Can We Achieve Efficient Diffusion without Self-Attention? Distilling Self-Attention into Convolutions](https://arxiv.org/abs/2504.21292v1)** (Published: 2025-04-30)  
  Authors: ZiYi Dong, Chengxing Zhou, Weijian Deng, Pengxu Wei, Xiangyang Ji, Liang Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.21292v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[DiVE: Efficient Multi-View Driving Scenes Generation Based on Video Diffusion Transformer](https://arxiv.org/abs/2504.19614v1)** (Published: 2025-04-28)  
  Authors: Junpeng Jiang, Gangyi Hong, Miao Zhang, Hengtong Hu, Kun Zhan, Rui Shao, Liqiang Nie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.19614v1.pdf)  
  Keywords: Control, diffusion transformer, video generation  
- **[Physics-based super-resolved simulation of 3D elastic wave propagation adopting scalable Diffusion Transformer](https://arxiv.org/abs/2504.17308v1)** (Published: 2025-04-24)  
  Authors: Hugo Gabrielidis, Filippo Gatti, Stéphane Vialle  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.17308v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[Boosting Generative Image Modeling via Joint Image-Feature Synthesis](https://arxiv.org/abs/2504.16064v1)** (Published: 2025-04-22)  
  Authors: Theodoros Kouzelis, Efstathios Karypidis, Ioannis Kakogeorgiou, Spyros Gidaris, Nikos Komodakis  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.16064v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[Acquire and then Adapt: Squeezing out Text-to-Image Model for Image Restoration](https://arxiv.org/abs/2504.15159v1)** (Published: 2025-04-21)  
  Authors: Junyuan Deng, Xinyi Wu, Yongxing Yang, Congchao Zhu, Song Wang, Zhenyao Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.15159v1.pdf)  
  Keywords: text-to-image, image generation, diffusion transformer, FLUX, Control  
- **[Text-Audio-Visual-conditioned Diffusion Model for Video Saliency Prediction](https://arxiv.org/abs/2504.14267v1)** (Published: 2025-04-19)  
  Authors: Li Yu, Xuanzhe Sun, Wei Zhou, Moncef Gabbouj  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.14267v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[Entropy Rectifying Guidance for Diffusion and Flow Models](https://arxiv.org/abs/2504.13987v1)** (Published: 2025-04-18)  
  Authors: Tariq Berrada Ifriqi, Adriana Romero-Soriano, Michal Drozdzal, Jakob Verbeek, Karteek Alahari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.13987v1.pdf)  
  Keywords: image generation, diffusion transformer, text-to-image  
- **[InstantCharacter: Personalize Any Characters with a Scalable Diffusion Transformer Framework](https://arxiv.org/abs/2504.12395v1)** (Published: 2025-04-16)  
  Authors: Jiale Tao, Yanbing Zhang, Qixun Wang, Yiji Cheng, Haofan Wang, Xu Bai, Zhengguang Zhou, Ruihuang Li, Linqing Wang, Chunyu Wang, Qin Lin, Qinglin Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.12395v1.pdf) | [![GitHub](https://img.shields.io/github/stars/Tencent/InstantCharacter?style=social)](https://github.com/Tencent/InstantCharacter)  
  Keywords: image generation, Control, diffusion transformer, Controllable  
- **[Using LLMs as prompt modifier to avoid biases in AI image generators](https://arxiv.org/abs/2504.11104v1)** (Published: 2025-04-15)  
  Authors: René Peinl  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.11104v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://iisys-hof.github.io/llm-prompt-img-gen/)  
  Keywords: FLUX, text-to-image, image generation  
- **[D$^2$iT: Dynamic Diffusion Transformer for Accurate Image Generation](https://arxiv.org/abs/2504.09454v1)** (Published: 2025-04-13)  
  Authors: Weinan Jia, Mengqi Huang, Nan Chen, Lei Zhang, Zhendong Mao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.09454v1.pdf) | [![GitHub](https://img.shields.io/github/stars/jiawn-creator/Dynamic-DiT?style=social)](https://github.com/jiawn-creator/Dynamic-DiT)  
  Keywords: image generation, diffusion transformer  
- **[Flux Already Knows -- Activating Subject-Driven Image Generation without Training](https://arxiv.org/abs/2504.11478v2)** (Published: 2025-04-12)  
  Authors: Hao Kang, Stathi Fotiadis, Liming Jiang, Qing Yan, Yumin Jia, Zichuan Liu, Min Jin Chong, Xin Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.11478v2.pdf)  
  Keywords: FLUX, text-to-image, image generation  
- **[MixDiT: Accelerating Image Diffusion Transformer Inference with Mixed-Precision MX Quantization](https://arxiv.org/abs/2504.08398v1)** (Published: 2025-04-11)  
  Authors: Daeun Kim, Jinwoo Hwang, Changhun Oh, Jongse Park  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.08398v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[DyDiT++: Dynamic Diffusion Transformers for Efficient Visual Generation](https://arxiv.org/abs/2504.06803v2)** (Published: 2025-04-09)  
  Authors: Wangbo Zhao, Yizeng Han, Jiasheng Tang, Kai Wang, Hao Luo, Yibing Song, Gao Huang, Fan Wang, Yang You  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.06803v2.pdf)  
  Keywords: text-to-image, image generation, diffusion transformer, FLUX, video generation  
- **[Disentangling Instruction Influence in Diffusion Transformers for Parallel Multi-Instruction-Guided Image Editing](https://arxiv.org/abs/2504.04784v1)** (Published: 2025-04-07)  
  Authors: Hui Liu, Bin Zou, Suiyun Zhang, Kecheng Chen, Rui Liu, Haoliang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04784v1.pdf)  
  Keywords: image editing, Control, diffusion transformer  
- **[DiTaiListener: Controllable High Fidelity Listener Video Generation with Diffusion](https://arxiv.org/abs/2504.04010v1)** (Published: 2025-04-05)  
  Authors: Maksim Siniukov, Di Chang, Minh Tran, Hongkun Gong, Ashutosh Chaubey, Mohammad Soleymani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04010v1.pdf)  
  Keywords: Control, diffusion transformer, video generation, Controllable  
- **[Detection Limits and Statistical Separability of Tree Ring Watermarks in Rectified Flow-based Text-to-Image Generation Models](https://arxiv.org/abs/2504.03850v1)** (Published: 2025-04-04)  
  Authors: Ved Umrajkar, Aakash Kumar Singh  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.03850v1.pdf) | [![GitHub](https://img.shields.io/github/stars/dsgiitr/flux-watermarking?style=social)](https://github.com/dsgiitr/flux-watermarking)  
  Keywords: text-to-image, image generation, FLUX, rectified flow, inversion  

### Video Related

*Showing the latest 50 out of 135 papers*

- **[Astraea: A GPU-Oriented Token-wise Acceleration Framework for Video Diffusion Transformers](https://arxiv.org/abs/2506.05096v1)** (Published: 2025-06-05)  
  Authors: Haosong Liu, Yuge Cheng, Zihan Liu, Aiyue Chen, Yiwu Yao, Chen Chen, Jingwen Leng, Yu Feng, Minyi Guo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.05096v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[LayerFlow: A Unified Model for Layer-aware Video Generation](https://arxiv.org/abs/2506.04228v1)** (Published: 2025-06-04)  
  Authors: Sihui Ji, Hao Luo, Xi Chen, Yuanpeng Tu, Yiyang Wang, Hengshuang Zhao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.04228v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[FullDiT2: Efficient In-Context Conditioning for Video Diffusion Transformers](https://arxiv.org/abs/2506.04213v2)** (Published: 2025-06-04)  
  Authors: Xuanhua He, Quande Liu, Zixuan Ye, Weicai Ye, Qiulin Wang, Xintao Wang, Qifeng Chen, Pengfei Wan, Di Zhang, Kun Gai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.04213v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://fulldit2.github.io/}{https://fulldit2.github.io/}.)  
  Keywords: video editing, Control, diffusion transformer, video generation  
- **[Chipmunk: Training-Free Acceleration of Diffusion Transformers with Dynamic Column-Sparse Deltas](https://arxiv.org/abs/2506.03275v1)** (Published: 2025-06-03)  
  Authors: Austin Silveria, Soham V. Govande, Daniel Y. Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.03275v1.pdf)  
  Keywords: FLUX, diffusion transformer, video generation  
- **[Sparse-vDiT: Unleashing the Power of Sparse Attention to Accelerate Video Diffusion Transformers](https://arxiv.org/abs/2506.03065v1)** (Published: 2025-06-03)  
  Authors: Pengtao Chen, Xianfang Zeng, Maosen Zhao, Peng Ye, Mingzhu Shen, Wei Cheng, Gang Yu, Tao Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.03065v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[OmniV2V: Versatile Video Generation and Editing via Dynamic Content Manipulation](https://arxiv.org/abs/2506.01801v1)** (Published: 2025-06-02)  
  Authors: Sen Liang, Zhentao Yu, Zhengguang Zhou, Teng Hu, Hongmei Wang, Yi Chen, Qin Lin, Yuan Zhou, Xin Li, Qinglin Lu, Zhibo Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.01801v1.pdf)  
  Keywords: Control, diffusion transformer, video generation, Controllable  
- **[LongDWM: Cross-Granularity Distillation for Building a Long-Term Driving World Model](https://arxiv.org/abs/2506.01546v1)** (Published: 2025-06-02)  
  Authors: Xiaodong Wang, Zhirong Wu, Peixi Peng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.01546v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://Wang-Xiaodong1899.github.io/longdwm/.)  
  Keywords: diffusion transformer, video generation  
- **[Playing with Transformer at 30+ FPS via Next-Frame Diffusion](https://arxiv.org/abs/2506.01380v1)** (Published: 2025-06-02)  
  Authors: Xinle Cheng, Tianyu He, Jiayi Xu, Junliang Guo, Di He, Jiang Bian  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.01380v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[Evaluating Robot Policies in a World Model](https://arxiv.org/abs/2506.00613v1)** (Published: 2025-05-31)  
  Authors: Julian Quevedo, Percy Liang, Sherry Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.00613v1.pdf)  
  Keywords: Control, diffusion transformer, video generation  
- **[Foresight: Adaptive Layer Reuse for Accelerated and High-Quality Text-to-Video Generation](https://arxiv.org/abs/2506.00329v1)** (Published: 2025-05-31)  
  Authors: Muhammad Adnan, Nithesh Kurella, Akhil Arunkumar, Prashant J. Nair  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2506.00329v1.pdf) | [![GitHub](https://img.shields.io/github/stars/STAR-Laboratory/foresight?style=social)](https://github.com/STAR-Laboratory/foresight)  
  Keywords: diffusion transformer, video generation, text-to-image  
- **[STORK: Improving the Fidelity of Mid-NFE Sampling for Diffusion and Flow Matching Models](https://arxiv.org/abs/2505.24210v1)** (Published: 2025-05-30)  
  Authors: Zheng Tan, Weizhen Wang, Andrea L. Bertozzi, Ernest K. Ryu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.24210v1.pdf) | [![GitHub](https://img.shields.io/github/stars/ZT220501/STORK?style=social)](https://github.com/ZT220501/STORK)  
  Keywords: FLUX, video generation  
- **[Q-VDiT: Towards Accurate Quantization and Distillation of Video-Generation Diffusion Transformers](https://arxiv.org/abs/2505.22167v1)** (Published: 2025-05-28)  
  Authors: Weilun Feng, Chuanguang Yang, Haotong Qin, Xiangqi Li, Yu Wang, Zhulin An, Libo Huang, Boyu Diao, Zixiang Zhao, Yongjun Xu, Michele Magno  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.22167v1.pdf) | [![GitHub](https://img.shields.io/github/stars/cantbebetter2/Q-VDiT?style=social)](https://github.com/cantbebetter2/Q-VDiT)  
  Keywords: image generation, diffusion transformer, video generation  
- **[Frame In-N-Out: Unbounded Controllable Image-to-Video Generation](https://arxiv.org/abs/2505.21491v1)** (Published: 2025-05-27)  
  Authors: Boyang Wang, Xuweiyi Chen, Matheus Gadelha, Zezhou Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.21491v1.pdf)  
  Keywords: Control, diffusion transformer, video generation, Controllable  
- **[Minute-Long Videos with Dual Parallelisms](https://arxiv.org/abs/2505.21070v2)** (Published: 2025-05-27)  
  Authors: Zeqing Wang, Bowen Zheng, Xingyi Yang, Zhenxiong Tan, Yuecong Xu, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.21070v2.pdf)  
  Keywords: diffusion transformer, video generation  
- **[RainFusion: Adaptive Video Generation Acceleration via Multi-Dimensional Visual Redundancy](https://arxiv.org/abs/2505.21036v1)** (Published: 2025-05-27)  
  Authors: Aiyue Chen, Bin Dong, Jingru Li, Jing Lin, Yiwu Yao, Gongyi Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.21036v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[Dynamic-I2V: Exploring Image-to-Video Generation Models via Multimodal LLM](https://arxiv.org/abs/2505.19901v3)** (Published: 2025-05-26)  
  Authors: Peng Liu, Xiaoming Ren, Fengkai Liu, Qingsong Xie, Quanlong Zheng, Yanhao Zhang, Haonan Lu, Yujiu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.19901v3.pdf)  
  Keywords: Control, diffusion transformer, video generation  
- **[The Role of Video Generation in Enhancing Data-Limited Action Understanding](https://arxiv.org/abs/2505.19495v1)** (Published: 2025-05-26)  
  Authors: Wei Li, Dezhao Luo, Dongbao Yang, Zhenhang Li, Weiping Wang, Yu Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.19495v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[SRDiffusion: Accelerate Video Diffusion Inference via Sketching-Rendering Cooperation](https://arxiv.org/abs/2505.19151v1)** (Published: 2025-05-25)  
  Authors: Shenggan Cheng, Yuanxin Wei, Lansong Diao, Yong Liu, Bujiao Chen, Lianghua Huang, Yu Liu, Wenyuan Yu, Jiangsu Du, Wei Lin, Yang You  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.19151v1.pdf)  
  Keywords: video editing, diffusion transformer, video generation  
- **[Sparse VideoGen2: Accelerate Video Generation with Sparse Attention via Semantic-Aware Permutation](https://arxiv.org/abs/2505.18875v1)** (Published: 2025-05-24)  
  Authors: Shuo Yang, Haocheng Xi, Yilong Zhao, Muyang Li, Jintao Zhang, Han Cai, Yujun Lin, Xiuyu Li, Chenfeng Xu, Kelly Peng, Jianfei Chen, Song Han, Kurt Keutzer, Ion Stoica  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.18875v1.pdf)  
  Keywords: Control, diffusion transformer, video generation  
- **[VORTA: Efficient Video Diffusion via Routing Sparse Attention](https://arxiv.org/abs/2505.18809v1)** (Published: 2025-05-24)  
  Authors: Wenhao Sun, Rong-Cheng Tu, Yifu Ding, Zhao Jin, Jingyi Liao, Shunyu Liu, Dacheng Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.18809v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[DVD-Quant: Data-free Video Diffusion Transformers Quantization](https://arxiv.org/abs/2505.18663v1)** (Published: 2025-05-24)  
  Authors: Zhiteng Li, Hanxuan Li, Junyi Wu, Kai Liu, Linghe Kong, Guihai Chen, Yulun Zhang, Xiaokang Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.18663v1.pdf) | [![GitHub](https://img.shields.io/github/stars/lhxcs/DVD-Quant?style=social)](https://github.com/lhxcs/DVD-Quant)  
  Keywords: diffusion transformer, video generation  
- **[Training-Free Efficient Video Generation via Dynamic Token Carving](https://arxiv.org/abs/2505.16864v1)** (Published: 2025-05-22)  
  Authors: Yuechen Zhang, Jinbo Xing, Bin Xia, Shaoteng Liu, Bohao Peng, Xin Tao, Pengfei Wan, Eric Lo, Jiaya Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.16864v1.pdf) | [![GitHub](https://img.shields.io/github/stars/dvlab-research/Jenga?style=social)](https://github.com/dvlab-research/Jenga)  
  Keywords: diffusion transformer, video generation  
- **[Interspatial Attention for Efficient 4D Human Video Generation](https://arxiv.org/abs/2505.15800v2)** (Published: 2025-05-21)  
  Authors: Ruizhi Shao, Yinghao Xu, Yujun Shen, Ceyuan Yang, Yang Zheng, Changan Chen, Yebin Liu, Gordon Wetzstein  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.15800v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://dsaurus.github.io/isa4d/.)  
  Keywords: Control, diffusion transformer, video generation, Controllable  
- **[Grouping First, Attending Smartly: Training-Free Acceleration for Diffusion Transformers](https://arxiv.org/abs/2505.14687v1)** (Published: 2025-05-20)  
  Authors: Sucheng Ren, Qihang Yu, Ju He, Alan Yuille, Liang-Chieh Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.14687v1.pdf)  
  Keywords: FLUX, diffusion transformer, video generation  
- **[LMP: Leveraging Motion Prior in Zero-Shot Video Generation with Diffusion Transformer](https://arxiv.org/abs/2505.14167v1)** (Published: 2025-05-20)  
  Authors: Changgu Chen, Xiaoyan Yang, Junwei Shu, Changbo Wang, Yang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.14167v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://vpx-ecnu.github.io/LMP-Website/)  
  Keywords: Control, diffusion transformer, video generation  
- **[DraftAttention: Fast Video Diffusion via Low-Resolution Attention Guidance](https://arxiv.org/abs/2505.14708v1)** (Published: 2025-05-17)  
  Authors: Xuan Shen, Chenxia Han, Yufa Zhou, Yanyue Xie, Yifan Gong, Quanyi Wang, Yiwei Wang, Yanzhi Wang, Pu Zhao, Jiuxiang Gu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.14708v1.pdf) | [![GitHub](https://img.shields.io/github/stars/shawnricecake/draft-attention?style=social)](https://github.com/shawnricecake/draft-attention)  
  Keywords: diffusion transformer, video generation  
- **[DanceGRPO: Unleashing GRPO on Visual Generation](https://arxiv.org/abs/2505.07818v1)** (Published: 2025-05-12)  
  Authors: Zeyue Xue, Jie Wu, Yu Gao, Fangyuan Kong, Lingting Zhu, Mengzhao Chen, Zhiheng Liu, Wei Liu, Qiushan Guo, Weilin Huang, Ping Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.07818v1.pdf)  
  Keywords: FLUX, rectified flow, text-to-image, video generation  
- **[Generative Pre-trained Autoregressive Diffusion Transformer](https://arxiv.org/abs/2505.07344v4)** (Published: 2025-05-12)  
  Authors: Yuan Zhang, Jiacheng Jiang, Guoqing Ma, Zhiying Lu, Haoyang Huang, Jianlong Yuan, Nan Duan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.07344v4.pdf)  
  Keywords: diffusion transformer, video generation  
- **[DualReal: Adaptive Joint Training for Lossless Identity-Motion Fusion in Video Customization](https://arxiv.org/abs/2505.02192v1)** (Published: 2025-05-04)  
  Authors: Wenchuan Wang, Mengqi Huang, Yijing Tu, Zhendong Mao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2505.02192v1.pdf)  
  Keywords: Control, diffusion transformer, video generation  
- **[DiVE: Efficient Multi-View Driving Scenes Generation Based on Video Diffusion Transformer](https://arxiv.org/abs/2504.19614v1)** (Published: 2025-04-28)  
  Authors: Junpeng Jiang, Gangyi Hong, Miao Zhang, Hengtong Hu, Kun Zhan, Rui Shao, Liqiang Nie  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.19614v1.pdf)  
  Keywords: Control, diffusion transformer, video generation  
- **[DiTPainter: Efficient Video Inpainting with Diffusion Transformers](https://arxiv.org/abs/2504.15661v3)** (Published: 2025-04-22)  
  Authors: Xian Wu, Chang Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.15661v3.pdf)  
  Keywords: diffusion transformer, video generation, video inpainting  
- **[Turbo2K: Towards Ultra-Efficient and High-Quality 2K Video Synthesis](https://arxiv.org/abs/2504.14470v1)** (Published: 2025-04-20)  
  Authors: Jingjing Ren, Wenbo Li, Zhongdao Wang, Haoze Sun, Bangzhen Liu, Haoyu Chen, Jiaqi Xu, Aoxue Li, Shifeng Zhang, Bin Shao, Yong Guo, Lei Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.14470v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[VGDFR: Diffusion-based Video Generation with Dynamic Latent Frame Rate](https://arxiv.org/abs/2504.12259v1)** (Published: 2025-04-16)  
  Authors: Zhihang Yuan, Rui Xie, Yuzhang Shang, Hanling Zhang, Siyuan Wang, Shengen Yan, Guohao Dai, Yu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.12259v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[Analysis of Attention in Video Diffusion Transformers](https://arxiv.org/abs/2504.10317v1)** (Published: 2025-04-14)  
  Authors: Yuxin Wen, Jim Wu, Ajay Jain, Tom Goldstein, Ashwinee Panda  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.10317v1.pdf)  
  Keywords: video editing, diffusion transformer  
- **[Diffusion Transformers for Tabular Data Time Series Generation](https://arxiv.org/abs/2504.07566v2)** (Published: 2025-04-10)  
  Authors: Fabrizio Garuti, Enver Sangineto, Simone Luetto, Lorenzo Forni, Rita Cucchiara  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.07566v2.pdf)  
  Keywords: diffusion transformer, video generation  
- **[DyDiT++: Dynamic Diffusion Transformers for Efficient Visual Generation](https://arxiv.org/abs/2504.06803v2)** (Published: 2025-04-09)  
  Authors: Wangbo Zhao, Yizeng Han, Jiasheng Tang, Kai Wang, Hao Luo, Yibing Song, Gao Huang, Fan Wang, Yang You  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.06803v2.pdf)  
  Keywords: text-to-image, image generation, diffusion transformer, FLUX, video generation  
- **[DiTaiListener: Controllable High Fidelity Listener Video Generation with Diffusion](https://arxiv.org/abs/2504.04010v1)** (Published: 2025-04-05)  
  Authors: Maksim Siniukov, Di Chang, Minh Tran, Hongkun Gong, Ashutosh Chaubey, Mohammad Soleymani  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.04010v1.pdf)  
  Keywords: Control, diffusion transformer, video generation, Controllable  
- **[SkyReels-A2: Compose Anything in Video Diffusion Transformers](https://arxiv.org/abs/2504.02436v1)** (Published: 2025-04-03)  
  Authors: Zhengcong Fei, Debang Li, Di Qiu, Jiahua Wang, Yikun Dou, Rui Wang, Jingtao Xu, Mingyuan Fan, Guibin Chen, Yang Li, Yahui Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.02436v1.pdf)  
  Keywords: Control, diffusion transformer, video generation, Controllable  
- **[OmniTalker: One-shot Real-time Text-Driven Talking Audio-Video Generation With Multimodal Style Mimicking](https://arxiv.org/abs/2504.02433v2)** (Published: 2025-04-03)  
  Authors: Zhongjian Wang, Peng Zhang, Jinwei Qi, Guangyuan Wang, Chaonan Ji, Sheng Xu, Bang Zhang, Liefeng Bo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.02433v2.pdf)  
  Keywords: diffusion transformer, video generation  
- **[JavisDiT: Joint Audio-Video Diffusion Transformer with Hierarchical Spatio-Temporal Prior Synchronization](https://arxiv.org/abs/2503.23377v1)** (Published: 2025-03-30)  
  Authors: Kai Liu, Wei Li, Lai Chen, Shengqiong Wu, Yanhao Zheng, Jiayi Ji, Fan Zhou, Rongxin Jiang, Jiebo Luo, Hao Fei, Tat-Seng Chua  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.23377v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://javisdit.github.io/.)  
  Keywords: diffusion transformer, video generation  
- **[DynamiCtrl: Rethinking the Basic Structure and the Role of Text for High-quality Human Image Animation](https://arxiv.org/abs/2503.21246v2)** (Published: 2025-03-27)  
  Authors: Haoyu Zhao, Zhongang Qi, Cong Wang, Qingping Zheng, Guansong Lu, Fei Chen, Hang Xu, Zuxuan Wu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.21246v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://gulucaptain.github.io/DynamiCtrl/.)  
  Keywords: Control, diffusion transformer, video generation  
- **[Wan: Open and Advanced Large-Scale Video Generative Models](https://arxiv.org/abs/2503.20314v2)** (Published: 2025-03-26)  
  Authors: Team Wan, Ang Wang, Baole Ai, Bin Wen, Chaojie Mao, Chen-Wei Xie, Di Chen, Feiwu Yu, Haiming Zhao, Jianxiao Yang, Jianyuan Zeng, Jiayu Wang, Jingfeng Zhang, Jingren Zhou, Jinkai Wang, Jixuan Chen, Kai Zhu, Kang Zhao, Keyu Yan, Lianghua Huang, Mengyang Feng, Ningyi Zhang, Pandeng Li, Pingyu Wu, Ruihang Chu, Ruili Feng, Shiwei Zhang, Siyang Sun, Tao Fang, Tianxing Wang, Tianyi Gui, Tingyu Weng, Tong Shen, Wei Lin, Wei Wang, Wei Wang, Wenmeng Zhou, Wente Wang, Wenting Shen, Wenyuan Yu, Xianzhong Shi, Xiaoming Huang, Xin Xu, Yan Kou, Yangyu Lv, Yifei Li, Yijing Liu, Yiming Wang, Yingya Zhang, Yitong Huang, Yong Li, You Wu, Yu Liu, Yulin Pan, Yun Zheng, Yuntao Hong, Yupeng Shi, Yutong Feng, Zeyinzi Jiang, Zhen Han, Zhi-Fan Wu, Ziyu Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.20314v2.pdf) | [![GitHub](https://img.shields.io/github/stars/Wan-Video/Wan2.1?style=social)](https://github.com/Wan-Video/Wan2.1)  
  Keywords: video editing, diffusion transformer, video generation  
- **[Mask$^2$DiT: Dual Mask-based Diffusion Transformer for Multi-Scene Long Video Generation](https://arxiv.org/abs/2503.19881v1)** (Published: 2025-03-25)  
  Authors: Tianhao Qi, Jianlong Yuan, Wanquan Feng, Shancheng Fang, Jiawei Liu, SiYu Zhou, Qian He, Hongtao Xie, Yongdong Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.19881v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://tianhao-qi.github.io/Mask2DiTProject.)  
  Keywords: diffusion transformer, video generation  
- **[AudCast: Audio-Driven Human Video Generation by Cascaded Diffusion Transformers](https://arxiv.org/abs/2503.19824v1)** (Published: 2025-03-25)  
  Authors: Jiazhi Guan, Kaisiyuan Wang, Zhiliang Xu, Quanwei Yang, Yasheng Sun, Shengyi He, Borong Liang, Yukang Cao, Yingying Li, Haocheng Feng, Errui Ding, Jingdong Wang, Youjian Zhao, Hang Zhou, Ziwei Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.19824v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://guanjz20.github.io/projects/AudCast.)  
  Keywords: diffusion transformer, video generation  
- **[FuXi-RTM: A Physics-Guided Prediction Framework with Radiative Transfer Modeling](https://arxiv.org/abs/2503.19940v1)** (Published: 2025-03-25)  
  Authors: Qiusheng Huang, Xiaohui Zhong, Xu Fan, Lei Chen, Hao Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.19940v1.pdf)  
  Keywords: FLUX, video generation  
- **[Long-Context Autoregressive Video Modeling with Next-Frame Prediction](https://arxiv.org/abs/2503.19325v3)** (Published: 2025-03-25)  
  Authors: Yuchao Gu, Weijia Mao, Mike Zheng Shou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.19325v3.pdf)  
  Keywords: diffusion transformer, video generation  
- **[Generating, Fast and Slow: Scalable Parallel Video Generation with Video Interface Networks](https://arxiv.org/abs/2503.17539v1)** (Published: 2025-03-21)  
  Authors: Bhishma Dedhia, David Bourgin, Krishna Kumar Singh, Yuheng Li, Yan Kang, Zhan Xu, Niraj K. Jha, Yuchen Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.17539v1.pdf)  
  Keywords: diffusion transformer, video generation  
- **[Long Context Tuning for Video Generation](https://arxiv.org/abs/2503.10589v1)** (Published: 2025-03-13)  
  Authors: Yuwei Guo, Ceyuan Yang, Ziyan Yang, Zhibei Ma, Zhijie Lin, Zhenheng Yang, Dahua Lin, Lu Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.10589v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://guoyww.github.io/projects/long-context-video/)  
  Keywords: diffusion transformer, video generation  
- **[Other Vehicle Trajectories Are Also Needed: A Driving World Model Unifies Ego-Other Vehicle Trajectories in Video Latent Space](https://arxiv.org/abs/2503.09215v2)** (Published: 2025-03-12)  
  Authors: Jian Zhu, Zhengyu Jia, Tian Gao, Jiaxin Deng, Shidi Li, Fu Liu, Peng Jia, Xianpeng Lang, Xiaolong Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.09215v2.pdf)  
  Keywords: Control, diffusion transformer, video generation, Controllable  
- **[Reangle-A-Video: 4D Video Generation as Video-to-Video Translation](https://arxiv.org/abs/2503.09151v2)** (Published: 2025-03-12)  
  Authors: Hyeonho Jeong, Suhyeon Lee, Jong Chul Ye  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.09151v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hyeonho99.github.io/reangle-a-video/)  
  Keywords: Control, diffusion transformer, video generation  



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
