# Awesome FLUX/DiT methods [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to DiT/FLUX. Content is automatically updated daily.

> Last Update: 2025-03-12 06:30:47

Thanks to [@longxiang-ai](https://github.com/longxiang-ai) for the template.

## Categories

- [Image Editing](#image-editing) (22 papers) - Papers about image editing with Diffusion Transformer or FLUX
- [Image Generation](#image-generation) (119 papers) - Papers focusing on image generation with Diffusion Transformer or FLUX
- [Video Related](#video-related) (85 papers) - Papers about video generation and editing with Diffusion Transformer or FLUX



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### Image Editing

- **[Seedream 2.0: A Native Chinese-English Bilingual Image Generation Foundation Model](https://arxiv.org/abs/2503.07703v1)** (Published: 2025-03-10)  
  Authors: Lixue Gong, Xiaoxia Hou, Fanshi Li, Liang Li, Xiaochen Lian, Fei Liu, Liyang Liu, Wei Liu, Wei Lu, Yichun Shi, Shiqi Sun, Yu Tian, Zhi Tian, Peng Wang, Xun Wang, Ye Wang, Guofeng Wu, Jie Wu, Xin Xia, Xuefeng Xiao, Linjie Yang, Zhonghua Zhai, Xinyu Zhang, Qi Zhang, Yuwei Zhang, Shijia Zhao, Jianchao Yang, Weilin Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07703v1.pdf)  
  Keywords: image generation, image editing, FLUX  
- **[TIDE : Temporal-Aware Sparse Autoencoders for Interpretable Diffusion Transformers in Image Generation](https://arxiv.org/abs/2503.07050v1)** (Published: 2025-03-10)  
  Authors: Victor Shea-Jay Huang, Le Zhuo, Yi Xin, Zhaokai Wang, Peng Gao, Hongsheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07050v1.pdf)  
  Keywords: image editing, image generation, diffusion transformer, Control  
- **[X2I: Seamless Integration of Multimodal Understanding into Diffusion Transformer via Attention Distillation](https://arxiv.org/abs/2503.06134v1)** (Published: 2025-03-08)  
  Authors: Jian Ma, Qirong Peng, Xu Guo, Chen Chen, Haonan Lu, Zhenyu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.06134v1.pdf) | [![GitHub](https://img.shields.io/github/stars/OPPO-Mente-Lab/X2I?style=social)](https://github.com/OPPO-Mente-Lab/X2I)  
  Keywords: diffusion transformer, Control, image to image, image editing, image generation, text-to-image  
- **[AnyRefill: A Unified, Data-Efficient Framework for Left-Prompt-Guided Vision Tasks](https://arxiv.org/abs/2502.11158v2)** (Published: 2025-02-16)  
  Authors: Ming Xie, Chenjie Cao, Yunuo Cai, Xiangyang Xue, Yu-Gang Jiang, Yanwei Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.11158v2.pdf)  
  Keywords: image editing, diffusion transformer, text-to-image  
- **[EliGen: Entity-Level Controlled Image Generation with Regional Attention](https://arxiv.org/abs/2501.01097v3)** (Published: 2025-01-02)  
  Authors: Hong Zhang, Zhongjie Duan, Xingjun Wang, Yingda Chen, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.01097v3.pdf) | [![GitHub](https://img.shields.io/github/stars/modelscope/DiffSynth-Studio.git?style=social)](https://github.com/modelscope/DiffSynth-Studio.git)  
  Keywords: diffusion transformer, Control, image generation, text-to-image, image inpainting  
- **[Context Canvas: Enhancing Text-to-Image Diffusion Models with Knowledge Graph-Based RAG](https://arxiv.org/abs/2412.09614v1)** (Published: 2024-12-12)  
  Authors: Kavana Venkatesh, Yusuf Dalva, Ismini Lourentzou, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09614v1.pdf)  
  Keywords: image editing, Control, text-to-image, FLUX  
- **[FluxSpace: Disentangled Semantic Editing in Rectified Flow Transformers](https://arxiv.org/abs/2412.09611v1)** (Published: 2024-12-12)  
  Authors: Yusuf Dalva, Kavana Venkatesh, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09611v1.pdf)  
  Keywords: Control, image editing, image generation, rectified flow, FLUX  
- **[AMO Sampler: Enhancing Text Rendering with Overshooting](https://arxiv.org/abs/2411.19415v1)** (Published: 2024-11-28)  
  Authors: Xixi Hu, Keyang Xu, Bo Liu, Qiang Liu, Hongliang Fei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.19415v1.pdf)  
  Keywords: Control, image generation, text-to-image, rectified flow, FLUX  
- **[Prediction with Action: Visual Policy Learning via Joint Denoising Process](https://arxiv.org/abs/2411.18179v1)** (Published: 2024-11-27)  
  Authors: Yanjiang Guo, Yucheng Hu, Jianke Zhang, Yen-Jen Wang, Xiaoyu Chen, Chaochao Lu, Jianyu Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.18179v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://sites.google.com/view/pad-paper)  
  Keywords: image editing, image generation, diffusion transformer, Control  
- **[HeadRouter: A Training-free Image Editing Framework for MM-DiTs by Adaptively Routing Attention Heads](https://arxiv.org/abs/2411.15034v1)** (Published: 2024-11-22)  
  Authors: Yu Xu, Fan Tang, Juan Cao, Yuxin Zhang, Xiaoyu Kong, Jintao Li, Oliver Deussen, Tong-Yee Lee  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.15034v1.pdf)  
  Keywords: image generation, diffusion transformer, image editing  
- **[Stable Flow: Vital Layers for Training-Free Image Editing](https://arxiv.org/abs/2411.14430v1)** (Published: 2024-11-21)  
  Authors: Omri Avrahami, Or Patashnik, Ohad Fried, Egor Nemchinov, Kfir Aberman, Dani Lischinski, Daniel Cohen-Or  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.14430v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://omriavrahami.com/stable-flow)  
  Keywords: image editing, inversion, diffusion transformer, Control  
- **[Oscillation Inversion: Understand the structure of Large Flow Model through the Lens of Inversion Method](https://arxiv.org/abs/2411.11135v1)** (Published: 2024-11-17)  
  Authors: Yan Zheng, Zhenxiao Liang, Xiaoyan Cong, Lanqing guo, Yuehao Wang, Peihao Wang, Zhangyang Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.11135v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://yanyanzheng96.github.io/oscillation_inversion/}{this)  
  Keywords: image editing, text-to-image, rectified flow, inversion, FLUX  
- **[Latent Space Disentanglement in Diffusion Transformers Enables Precise Zero-shot Semantic Editing](https://arxiv.org/abs/2411.08196v1)** (Published: 2024-11-12)  
  Authors: Zitao Shuai, Chenwei Wu, Zhengxu Tang, Bowen Song, Liyue Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.08196v1.pdf)  
  Keywords: image editing, image generation, diffusion transformer, Control  
- **[Taming Rectified Flow for Inversion and Editing](https://arxiv.org/abs/2411.04746v2)** (Published: 2024-11-07)  
  Authors: Jiangshan Wang, Junfu Pu, Zhongang Qi, Jiayi Guo, Yue Ma, Nisha Huang, Yuxin Chen, Xiu Li, Ying Shan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.04746v2.pdf) | [![GitHub](https://img.shields.io/github/stars/wangjiangshan0725/RF-Solver-Edit?style=social)](https://github.com/wangjiangshan0725/RF-Solver-Edit)  
  Keywords: diffusion transformer, rectified flow, video editing, video generation, inversion, FLUX  
- **[DiT4Edit: Diffusion Transformer for Image Editing](https://arxiv.org/abs/2411.03286v2)** (Published: 2024-11-05)  
  Authors: Kunyu Feng, Yue Ma, Bingyuan Wang, Chenyang Qi, Haozhe Chen, Qifeng Chen, Zeyu Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.03286v2.pdf)  
  Keywords: diffusion transformer, Control, image editing, image generation, inversion  
- **[FiTv2: Scalable and Improved Flexible Vision Transformer for Diffusion Model](https://arxiv.org/abs/2410.13925v1)** (Published: 2024-10-17)  
  Authors: ZiDong Wang, Zeyu Lu, Di Huang, Cai Zhou, Wanli Ouyang, and Lei Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.13925v1.pdf) | [![GitHub](https://img.shields.io/github/stars/whlzy/FiT?style=social)](https://github.com/whlzy/FiT)  
  Keywords: image generation, diffusion transformer, rectified flow  
- **[Semantic Image Inversion and Editing using Rectified Stochastic Differential Equations](https://arxiv.org/abs/2410.10792v1)** (Published: 2024-10-14)  
  Authors: Litu Rout, Yujia Chen, Nataniel Ruiz, Constantine Caramanis, Sanjay Shakkottai, Wen-Sheng Chu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.10792v1.pdf)  
  Keywords: Control, image editing, rectified flow, inversion, FLUX  
- **[Effective Diffusion Transformer Architecture for Image Super-Resolution](https://arxiv.org/abs/2409.19589v1)** (Published: 2024-09-29)  
  Authors: Kun Cheng, Lei Yu, Zhijun Tu, Xiao He, Liyu Chen, Yong Guo, Mingrui Zhu, Nannan Wang, Xinbo Gao, Jie Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.19589v1.pdf)  
  Keywords: image generation, diffusion transformer, image super-resolution  
- **[PixWizard: Versatile Image-to-Image Visual Assistant with Open-Language Instructions](https://arxiv.org/abs/2409.15278v4)** (Published: 2024-09-23)  
  Authors: Weifeng Lin, Xinyu Wei, Renrui Zhang, Le Zhuo, Shitian Zhao, Siyuan Huang, Huan Teng, Junlin Xie, Yu Qiao, Peng Gao, Hongsheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2409.15278v4.pdf) | [![GitHub](https://img.shields.io/github/stars/AFeng-x/PixWizard?style=social)](https://github.com/AFeng-x/PixWizard)  
  Keywords: diffusion transformer, Control, image editing, image generation, text-to-image, Controllable  
- **[Latent Space Disentanglement in Diffusion Transformers Enables Zero-shot Fine-grained Semantic Editing](https://arxiv.org/abs/2408.13335v1)** (Published: 2024-08-23)  
  Authors: Zitao Shuai, Chenwei Wu, Zhengxu Tang, Bowen Song, Liyue Shen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.13335v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://anonymous.com/anonymous/EMS-Benchmark,)  
  Keywords: image editing, Control, diffusion transformer, text-to-image  
- **[Lazy Diffusion Transformer for Interactive Image Editing](https://arxiv.org/abs/2404.12382v1)** (Published: 2024-04-18)  
  Authors: Yotam Nitzan, Zongze Wu, Richard Zhang, Eli Shechtman, Daniel Cohen-Or, Taesung Park, Michaël Gharbi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2404.12382v1.pdf)  
  Keywords: diffusion transformer, image editing  
- **[Lightning-Fast Image Inversion and Editing for Text-to-Image Diffusion Models](https://arxiv.org/abs/2312.12540v5)** (Published: 2023-12-19)  
  Authors: Dvir Samuel, Barak Meiri, Haggai Maron, Yoad Tewel, Nir Darshan, Shai Avidan, Gal Chechik, Rami Ben-Ari  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2312.12540v5.pdf)  
  Keywords: image editing, inversion, text-to-image, FLUX  

### Image Generation

*Showing the latest 50 out of 119 papers*

- **[OminiControl2: Efficient Conditioning for Diffusion Transformers](https://arxiv.org/abs/2503.08280v1)** (Published: 2025-03-11)  
  Authors: Zhenxiong Tan, Qiaochu Xue, Xingyi Yang, Songhua Liu, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.08280v1.pdf)  
  Keywords: diffusion transformer, Control, image generation, text-to-image, Controllable  
- **[Seedream 2.0: A Native Chinese-English Bilingual Image Generation Foundation Model](https://arxiv.org/abs/2503.07703v1)** (Published: 2025-03-10)  
  Authors: Lixue Gong, Xiaoxia Hou, Fanshi Li, Liang Li, Xiaochen Lian, Fei Liu, Liyang Liu, Wei Liu, Wei Lu, Yichun Shi, Shiqi Sun, Yu Tian, Zhi Tian, Peng Wang, Xun Wang, Ye Wang, Guofeng Wu, Jie Wu, Xin Xia, Xuefeng Xiao, Linjie Yang, Zhonghua Zhai, Xinyu Zhang, Qi Zhang, Yuwei Zhang, Shijia Zhao, Jianchao Yang, Weilin Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07703v1.pdf)  
  Keywords: image generation, image editing, FLUX  
- **[TIDE : Temporal-Aware Sparse Autoencoders for Interpretable Diffusion Transformers in Image Generation](https://arxiv.org/abs/2503.07050v1)** (Published: 2025-03-10)  
  Authors: Victor Shea-Jay Huang, Le Zhuo, Yi Xin, Zhaokai Wang, Peng Gao, Hongsheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07050v1.pdf)  
  Keywords: image editing, image generation, diffusion transformer, Control  
- **[Post-Training Quantization for Diffusion Transformer via Hierarchical Timestep Grouping](https://arxiv.org/abs/2503.06930v1)** (Published: 2025-03-10)  
  Authors: Ning Ding, Jing Han, Yuchuan Tian, Chao Xu, Kai Han, Yehui Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.06930v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[X2I: Seamless Integration of Multimodal Understanding into Diffusion Transformer via Attention Distillation](https://arxiv.org/abs/2503.06134v1)** (Published: 2025-03-08)  
  Authors: Jian Ma, Qirong Peng, Xu Guo, Chen Chen, Haonan Lu, Zhenyu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.06134v1.pdf) | [![GitHub](https://img.shields.io/github/stars/OPPO-Mente-Lab/X2I?style=social)](https://github.com/OPPO-Mente-Lab/X2I)  
  Keywords: diffusion transformer, Control, image to image, image editing, image generation, text-to-image  
- **[MagicInfinite: Generating Infinite Talking Videos with Your Words and Voice](https://arxiv.org/abs/2503.05978v1)** (Published: 2025-03-07)  
  Authors: Hongwei Yi, Tian Ye, Shitong Shao, Xuancheng Yang, Jiantong Zhao, Hanzhong Guo, Terrance Wang, Qingyu Yin, Zeke Xie, Lei Zhu, Wei Li, Michael Lingelbach, Daquan Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.05978v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://www.hedra.com/,)  
  Keywords: video generation, diffusion transformer, Control  
- **[Q&C: When Quantization Meets Cache in Efficient Image Generation](https://arxiv.org/abs/2503.02508v1)** (Published: 2025-03-04)  
  Authors: Xin Ding, Xin Li, Haotong Qin, Zhibo Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.02508v1.pdf) | [![GitHub](https://img.shields.io/github/stars/xinding-sys/Quant-Cache?style=social)](https://github.com/xinding-sys/Quant-Cache)  
  Keywords: image generation, diffusion transformer  
- **[Multimodal Representation Alignment for Image Generation: Text-Image Interleaved Control Is Easier Than You Think](https://arxiv.org/abs/2502.20172v1)** (Published: 2025-02-27)  
  Authors: Liang Chen, Shuai Bai, Wenhao Chai, Weichu Xie, Haozhe Zhao, Leon Vinci, Junyang Lin, Baobao Chang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.20172v1.pdf)  
  Keywords: diffusion transformer, Control, image generation, text-to-image, FLUX  
- **[FlexiDiT: Your Diffusion Transformer Can Easily Generate High-Quality Samples with Less Compute](https://arxiv.org/abs/2502.20126v1)** (Published: 2025-02-27)  
  Authors: Sotiris Anagnostidis, Gregor Bachmann, Yeongmin Kim, Jonas Kohler, Markos Georgopoulos, Artsiom Sanakoyeu, Yuming Du, Albert Pumarola, Ali Thabet, Edgar Schönfeld  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.20126v1.pdf)  
  Keywords: video generation, image generation, diffusion transformer  
- **[RelaCtrl: Relevance-Guided Efficient Control for Diffusion Transformers](https://arxiv.org/abs/2502.14377v3)** (Published: 2025-02-20)  
  Authors: Ke Cao, Jing Wang, Ao Ma, Jiasong Feng, Zhanjie Zhang, Xuanhua He, Shanyuan Liu, Bo Cheng, Dawei Leng, Yuhui Yin, Jie Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.14377v3.pdf)  
  Keywords: diffusion transformer, Control, text-to-image, video generation, Controllable  
- **[AnyRefill: A Unified, Data-Efficient Framework for Left-Prompt-Guided Vision Tasks](https://arxiv.org/abs/2502.11158v2)** (Published: 2025-02-16)  
  Authors: Ming Xie, Chenjie Cao, Yunuo Cai, Xiangyang Xue, Yu-Gang Jiang, Yanwei Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.11158v2.pdf)  
  Keywords: image editing, diffusion transformer, text-to-image  
- **[BCDDM: Branch-Corrected Denoising Diffusion Model for Black Hole Image Generation](https://arxiv.org/abs/2502.08528v1)** (Published: 2025-02-12)  
  Authors: Ao liu, Zelin Zhang, Songbai Chen, Cuihong Wen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.08528v1.pdf)  
  Keywords: image generation, FLUX  
- **[Lumina-Video: Efficient and Flexible Video Generation with Multi-scale Next-DiT](https://arxiv.org/abs/2502.06782v2)** (Published: 2025-02-10)  
  Authors: Dongyang Liu, Shicheng Li, Yutong Liu, Zhen Li, Kai Wang, Xinyue Li, Qi Qin, Yufei Liu, Yi Xin, Zhongyu Li, Bin Fu, Chenyang Si, Yuewen Cao, Conghui He, Ziwei Liu, Yu Qiao, Qibin Hou, Hongsheng Li, Peng Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.06782v2.pdf) | [![GitHub](https://img.shields.io/github/stars/Alpha-VLLM/Lumina-Video?style=social)](https://github.com/Alpha-VLLM/Lumina-Video)  
  Keywords: video generation, diffusion transformer, Control  
- **[Universal Approximation of Visual Autoregressive Transformers](https://arxiv.org/abs/2502.06167v1)** (Published: 2025-02-10)  
  Authors: Yifang Chen, Xiaoyu Li, Yingyu Liang, Zhenmei Shi, Zhao Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.06167v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[MakeAnything: Harnessing Diffusion Transformers for Multi-Domain Procedural Sequence Generation](https://arxiv.org/abs/2502.01572v2)** (Published: 2025-02-03)  
  Authors: Yiren Song, Cheng Liu, Mike Zheng Shou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.01572v2.pdf)  
  Keywords: image generation, diffusion transformer  
- **[RealRAG: Retrieval-augmented Realistic Image Generation via Self-reflective Contrastive Learning](https://arxiv.org/abs/2502.00848v1)** (Published: 2025-02-02)  
  Authors: Yuanhuiyi Lyu, Xu Zheng, Lutao Jiang, Yibo Yan, Xin Zou, Huiyu Zhou, Linfeng Zhang, Xuming Hu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.00848v1.pdf)  
  Keywords: image generation, text-to-image, FLUX  
- **[SANA 1.5: Efficient Scaling of Training-Time and Inference-Time Compute in Linear Diffusion Transformer](https://arxiv.org/abs/2501.18427v2)** (Published: 2025-01-30)  
  Authors: Enze Xie, Junsong Chen, Yuyang Zhao, Jincheng Yu, Ligeng Zhu, Yujun Lin, Zhekai Zhang, Muyang Li, Junyu Chen, Han Cai, Bingchen Liu, Daquan Zhou, Song Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.18427v2.pdf)  
  Keywords: image generation, diffusion transformer, text-to-image  
- **[Accelerate High-Quality Diffusion Models with Inner Loop Feedback](https://arxiv.org/abs/2501.13107v2)** (Published: 2025-01-22)  
  Authors: Matthew Gwilliam, Han Cai, Di Wu, Abhinav Shrivastava, Zhiyu Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.13107v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mgwillia.github.io/ilf.)  
  Keywords: image generation, diffusion transformer, text-to-image  
- **[LiT: Delving into a Simplified Linear Diffusion Transformer for Image Generation](https://arxiv.org/abs/2501.12976v1)** (Published: 2025-01-22)  
  Authors: Jiahao Wang, Ning Kang, Lewei Yao, Mengzhao Chen, Chengyue Wu, Songyang Zhang, Shuchen Xue, Yong Liu, Taiqiang Wu, Xihui Liu, Kaipeng Zhang, Shifeng Zhang, Wenqi Shao, Zhenguo Li, Ping Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.12976v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://techmonsterwang.github.io/LiT/.)  
  Keywords: image generation, diffusion transformer, text-to-image  
- **[Learnings from Scaling Visual Tokenizers for Reconstruction and Generation](https://arxiv.org/abs/2501.09755v1)** (Published: 2025-01-16)  
  Authors: Philippe Hansen-Estruch, David Yan, Ching-Yao Chung, Orr Zohar, Jialiang Wang, Tingbo Hou, Tao Xu, Sriram Vishwanath, Peter Vajda, Xinlei Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.09755v1.pdf)  
  Keywords: video generation, image generation, diffusion transformer  
- **[Enhancing Image Generation Fidelity via Progressive Prompts](https://arxiv.org/abs/2501.07070v1)** (Published: 2025-01-13)  
  Authors: Zhen Xiong, Yuqi Li, Chuanguang Yang, Tiao Tan, Zhihong Zhu, Siyuan Li, Yue Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.07070v1.pdf)  
  Keywords: image generation, diffusion transformer, Control  
- **[3DIS-FLUX: simple and efficient multi-instance generation with DiT rendering](https://arxiv.org/abs/2501.05131v1)** (Published: 2025-01-09)  
  Authors: Dewei Zhou, Ji Xie, Zongxin Yang, Yi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.05131v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://limuloo.github.io/3DIS/.)  
  Keywords: Control, image generation, text-to-image, FLUX, Controllable  
- **[Circuit Complexity Bounds for Visual Autoregressive Model](https://arxiv.org/abs/2501.04299v1)** (Published: 2025-01-08)  
  Authors: Yekun Ke, Xiaoyu Li, Yingyu Liang, Zhenmei Shi, Zhao Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.04299v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[GS-DiT: Advancing Video Generation with Pseudo 4D Gaussian Fields through Efficient Dense 3D Point Tracking](https://arxiv.org/abs/2501.02690v1)** (Published: 2025-01-05)  
  Authors: Weikang Bian, Zhaoyang Huang, Xiaoyu Shi, Yijin Li, Fu-Yun Wang, Hongsheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.02690v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wkbian.github.io/Projects/GS-DiT/.)  
  Keywords: video generation, diffusion transformer, Control  
- **[EliGen: Entity-Level Controlled Image Generation with Regional Attention](https://arxiv.org/abs/2501.01097v3)** (Published: 2025-01-02)  
  Authors: Hong Zhang, Zhongjie Duan, Xingjun Wang, Yingda Chen, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.01097v3.pdf) | [![GitHub](https://img.shields.io/github/stars/modelscope/DiffSynth-Studio.git?style=social)](https://github.com/modelscope/DiffSynth-Studio.git)  
  Keywords: diffusion transformer, Control, image generation, text-to-image, image inpainting  
- **[Dual Diffusion for Unified Image Generation and Understanding](https://arxiv.org/abs/2501.00289v1)** (Published: 2024-12-31)  
  Authors: Zijie Li, Henry Li, Yichun Shi, Amir Barati Farimani, Yuval Kluger, Linjie Yang, Peng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.00289v1.pdf)  
  Keywords: image generation, diffusion transformer, text-to-image  
- **[Open-Sora: Democratizing Efficient Video Production for All](https://arxiv.org/abs/2412.20404v1)** (Published: 2024-12-29)  
  Authors: Zangwei Zheng, Xiangyu Peng, Tianji Yang, Chenhui Shen, Shenggui Li, Hongxin Liu, Yukun Zhou, Tianyi Li, Yang You  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.20404v1.pdf) | [![GitHub](https://img.shields.io/github/stars/hpcaitech/Open-Sora?style=social)](https://github.com/hpcaitech/Open-Sora)  
  Keywords: video generation, image generation, diffusion transformer, text-to-image  
- **[UNIC-Adapter: Unified Image-instruction Adapter with Multi-modal Transformer for Image Generation](https://arxiv.org/abs/2412.18928v1)** (Published: 2024-12-25)  
  Authors: Lunhao Duan, Shanshan Zhao, Wenjun Yan, Yinglun Li, Qing-Guo Chen, Zhao Xu, Weihua Luo, Kaifu Zhang, Mingming Gong, Gui-Song Xia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18928v1.pdf)  
  Keywords: diffusion transformer, Control, image generation, text-to-image, Controllable  
- **[1.58-bit FLUX](https://arxiv.org/abs/2412.18653v1)** (Published: 2024-12-24)  
  Authors: Chenglin Yang, Celong Liu, Xueqing Deng, Dongwon Kim, Xing Mei, Xiaohui Shen, Liang-Chieh Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18653v1.pdf)  
  Keywords: image generation, text-to-image, FLUX  
- **[DiTCtrl: Exploring Attention Control in Multi-Modal Diffusion Transformer for Tuning-Free Multi-Prompt Longer Video Generation](https://arxiv.org/abs/2412.18597v1)** (Published: 2024-12-24)  
  Authors: Minghong Cai, Xiaodong Cun, Xiaoyu Li, Wenze Liu, Zhaoyang Zhang, Yong Zhang, Ying Shan, Xiangyu Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18597v1.pdf)  
  Keywords: video generation, diffusion transformer, Control, video editing  
- **[Layer- and Timestep-Adaptive Differentiable Token Compression Ratios for Efficient Diffusion Transformers](https://arxiv.org/abs/2412.16822v1)** (Published: 2024-12-22)  
  Authors: Haoran You, Connelly Barnes, Yuqian Zhou, Yan Kang, Zhenbang Du, Wei Zhou, Lingzhi Zhang, Yotam Nitzan, Xiaoyang Liu, Zhe Lin, Eli Shechtman, Sohrab Amirghodsi, Yingyan Celine Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.16822v1.pdf)  
  Keywords: image generation, diffusion transformer, text-to-image  
- **[CLEAR: Conv-Like Linearization Revs Pre-Trained Diffusion Transformers Up](https://arxiv.org/abs/2412.16112v1)** (Published: 2024-12-20)  
  Authors: Songhua Liu, Zhenxiong Tan, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.16112v1.pdf) | [![GitHub](https://img.shields.io/github/stars/Huage001/CLEAR?style=social)](https://github.com/Huage001/CLEAR)  
  Keywords: image generation, diffusion transformer  
- **[Efficient Scaling of Diffusion Transformers for Text-to-Image Generation](https://arxiv.org/abs/2412.12391v1)** (Published: 2024-12-16)  
  Authors: Hao Li, Shamit Lal, Zhiheng Li, Yusheng Xie, Ying Wang, Yang Zou, Orchid Majumder, R. Manmatha, Zhuowen Tu, Stefano Ermon, Stefano Soatto, Ashwin Swaminathan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.12391v1.pdf)  
  Keywords: image generation, diffusion transformer, text-to-image, Control  
- **[Causal Diffusion Transformers for Generative Modeling](https://arxiv.org/abs/2412.12095v2)** (Published: 2024-12-16)  
  Authors: Chaorui Deng, Deyao Zhu, Kunchang Li, Shi Guang, Haoqi Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.12095v2.pdf)  
  Keywords: image generation, diffusion transformer  
- **[Video Diffusion Transformers are In-Context Learners](https://arxiv.org/abs/2412.10783v2)** (Published: 2024-12-14)  
  Authors: Zhengcong Fei, Di Qiu, Changqian Yu, Debang Li, Mingyuan Fan, Xiang Wen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.10783v2.pdf) | [![GitHub](https://img.shields.io/github/stars/feizc/Video-In-Context?style=social)](https://github.com/feizc/Video-In-Context)  
  Keywords: video generation, diffusion transformer, Control, Controllable  
- **[MSC: Multi-Scale Spatio-Temporal Causal Attention for Autoregressive Video Diffusion](https://arxiv.org/abs/2412.09828v1)** (Published: 2024-12-13)  
  Authors: Xunnong Xu, Mengying Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09828v1.pdf)  
  Keywords: video generation, diffusion transformer, Control  
- **[Context Canvas: Enhancing Text-to-Image Diffusion Models with Knowledge Graph-Based RAG](https://arxiv.org/abs/2412.09614v1)** (Published: 2024-12-12)  
  Authors: Kavana Venkatesh, Yusuf Dalva, Ismini Lourentzou, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09614v1.pdf)  
  Keywords: image editing, Control, text-to-image, FLUX  
- **[FluxSpace: Disentangled Semantic Editing in Rectified Flow Transformers](https://arxiv.org/abs/2412.09611v1)** (Published: 2024-12-12)  
  Authors: Yusuf Dalva, Kavana Venkatesh, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09611v1.pdf)  
  Keywords: Control, image editing, image generation, rectified flow, FLUX  
- **[Multimodal Latent Language Modeling with Next-Token Diffusion](https://arxiv.org/abs/2412.08635v1)** (Published: 2024-12-11)  
  Authors: Yutao Sun, Hangbo Bao, Wenhui Wang, Zhiliang Peng, Li Dong, Shaohan Huang, Jianyong Wang, Furu Wei  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.08635v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[FlexDiT: Dynamic Token Density Control for Diffusion Transformer](https://arxiv.org/abs/2412.06028v1)** (Published: 2024-12-08)  
  Authors: Shuning Chang, Pichao Wang, Jiasheng Tang, Yi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.06028v1.pdf)  
  Keywords: diffusion transformer, Control, image generation, text-to-image, video generation  
- **[MotionStone: Decoupled Motion Intensity Modulation with Diffusion Transformer for Image-to-Video Generation](https://arxiv.org/abs/2412.05848v1)** (Published: 2024-12-08)  
  Authors: Shuwei Shi, Biao Gong, Xi Chen, Dandan Zheng, Shuai Tan, Zizheng Yang, Yuyuan Li, Jingwen He, Kecheng Zheng, Jingdong Chen, Ming Yang, Yinqiang Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05848v1.pdf)  
  Keywords: video generation, diffusion transformer, Control  
- **[Self-Guidance: Boosting Flow and Diffusion Generation on Their Own](https://arxiv.org/abs/2412.05827v2)** (Published: 2024-12-08)  
  Authors: Tiancheng Li, Weijian Luo, Zhiyang Chen, Liyuan Ma, Guo-Jun Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05827v2.pdf)  
  Keywords: video generation, text-to-image, FLUX  
- **[Language-Guided Image Tokenization for Generation](https://arxiv.org/abs/2412.05796v1)** (Published: 2024-12-08)  
  Authors: Kaiwen Zha, Lijun Yu, Alireza Fathi, David A. Ross, Cordelia Schmid, Dina Katabi, Xiuye Gu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05796v1.pdf)  
  Keywords: image generation, diffusion transformer, text-to-image  
- **[Mind the Time: Temporally-Controlled Multi-Event Video Generation](https://arxiv.org/abs/2412.05263v2)** (Published: 2024-12-06)  
  Authors: Ziyi Wu, Aliaksandr Siarohin, Willi Menapace, Ivan Skorokhodov, Yuwei Fang, Varnith Chordia, Igor Gilitschenski, Sergey Tulyakov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05263v2.pdf)  
  Keywords: video generation, diffusion transformer, Control  
- **[CreatiLayout: Siamese Multimodal Diffusion Transformer for Creative Layout-to-Image Generation](https://arxiv.org/abs/2412.03859v1)** (Published: 2024-12-05)  
  Authors: Hui Zhang, Dexiang Hong, Tingwei Gao, Yitong Wang, Jie Shao, Xinglong Wu, Zuxuan Wu, Yu-Gang Jiang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03859v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://creatilayout.github.io.)  
  Keywords: image generation, diffusion transformer, Control, Controllable  
- **[Navigation World Models](https://arxiv.org/abs/2412.03572v1)** (Published: 2024-12-04)  
  Authors: Amir Bar, Gaoyue Zhou, Danny Tran, Trevor Darrell, Yann LeCun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03572v1.pdf)  
  Keywords: video generation, diffusion transformer, Control, Controllable  
- **[Seeing Beyond Views: Multi-View Driving Scene Video Generation with Holistic Attention](https://arxiv.org/abs/2412.03520v2)** (Published: 2024-12-04)  
  Authors: Hannan Lu, Xiaohe Wu, Shudong Wang, Xiameng Qin, Xinyu Zhang, Junyu Han, Wangmeng Zuo, Ji Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03520v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://luhannan.github.io/CogDrivingPage/.)  
  Keywords: video generation, diffusion transformer, Control  
- **[Panoptic Diffusion Models: co-generation of images and segmentation maps](https://arxiv.org/abs/2412.02929v2)** (Published: 2024-12-04)  
  Authors: Yinghan Long, Kaushik Roy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02929v2.pdf)  
  Keywords: image generation, diffusion transformer, Control  
- **[Generative Photography: Scene-Consistent Camera Control for Realistic Text-to-Image Synthesis](https://arxiv.org/abs/2412.02168v2)** (Published: 2024-12-03)  
  Authors: Yu Yuan, Xijun Wang, Yichen Sheng, Prateek Chennuri, Xingguang Zhang, Stanley Chan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.02168v2.pdf)  
  Keywords: image generation, text-to-image, FLUX, Control  
- **[World-consistent Video Diffusion with Explicit 3D Modeling](https://arxiv.org/abs/2412.01821v1)** (Published: 2024-12-02)  
  Authors: Qihang Zhang, Shuangfei Zhai, Miguel Angel Bautista, Kevin Miao, Alexander Toshev, Joshua Susskind, Jiatao Gu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01821v1.pdf)  
  Keywords: video generation, image generation, diffusion transformer, Control  

### Video Related

*Showing the latest 50 out of 85 papers*

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
- **[Video Super-Resolution: All You Need is a Video Diffusion Model](https://arxiv.org/abs/2503.03355v1)** (Published: 2025-03-05)  
  Authors: Zhihao Zhan, Wang Pang, Xiang Zhu, Yechao Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.03355v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Training-free and Adaptive Sparse Attention for Efficient Long Video Generation](https://arxiv.org/abs/2502.21079v1)** (Published: 2025-02-28)  
  Authors: Yifei Xia, Suhan Ling, Fangcheng Fu, Yujie Wang, Huixia Li, Xuefeng Xiao, Bin Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.21079v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[FlexiDiT: Your Diffusion Transformer Can Easily Generate High-Quality Samples with Less Compute](https://arxiv.org/abs/2502.20126v1)** (Published: 2025-02-27)  
  Authors: Sotiris Anagnostidis, Gregor Bachmann, Yeongmin Kim, Jonas Kohler, Markos Georgopoulos, Artsiom Sanakoyeu, Yuming Du, Albert Pumarola, Ali Thabet, Edgar Schönfeld  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.20126v1.pdf)  
  Keywords: video generation, image generation, diffusion transformer  
- **[RIFLEx: A Free Lunch for Length Extrapolation in Video Diffusion Transformers](https://arxiv.org/abs/2502.15894v1)** (Published: 2025-02-21)  
  Authors: Min Zhao, Guande He, Yixiao Chen, Hongzhou Zhu, Chongxuan Li, Jun Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.15894v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://riflex-video.github.io/}{https://riflex-video.github.io/.})  
  Keywords: video generation, diffusion transformer  
- **[Hardware-Friendly Static Quantization Method for Video Diffusion Transformers](https://arxiv.org/abs/2502.15077v1)** (Published: 2025-02-20)  
  Authors: Sanghyun Yi, Qingfeng Liu, Mostafa El-Khamy  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.15077v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[RelaCtrl: Relevance-Guided Efficient Control for Diffusion Transformers](https://arxiv.org/abs/2502.14377v3)** (Published: 2025-02-20)  
  Authors: Ke Cao, Jing Wang, Ao Ma, Jiasong Feng, Zhanjie Zhang, Xuanhua He, Shanyuan Liu, Bo Cheng, Dawei Leng, Yuhui Yin, Jie Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.14377v3.pdf)  
  Keywords: diffusion transformer, Control, text-to-image, video generation, Controllable  
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
- **[HumanDiT: Pose-Guided Diffusion Transformer for Long-form Human Motion Video Generation](https://arxiv.org/abs/2502.04847v2)** (Published: 2025-02-07)  
  Authors: Qijun Gan, Yi Ren, Chen Zhang, Zhenhui Ye, Pan Xie, Xiang Yin, Zehuan Yuan, Bingyue Peng, Jianke Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.04847v2.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Fast Video Generation with Sliding Tile Attention](https://arxiv.org/abs/2502.04507v1)** (Published: 2025-02-06)  
  Authors: Peiyuan Zhang, Yongqi Chen, Runlong Su, Hangliang Ding, Ion Stoica, Zhenghong Liu, Hao Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.04507v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[UniForm: A Unified Diffusion Transformer for Audio-Video Generation](https://arxiv.org/abs/2502.03897v2)** (Published: 2025-02-06)  
  Authors: Lei Zhao, Linfeng Feng, Dongxu Ge, Fangqiu Yi, Chi Zhang, Xiao-Lei Zhang, Xuelong Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.03897v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://uniform-t2av.github.io/.)  
  Keywords: video generation, diffusion transformer  
- **[UniCP: A Unified Caching and Pruning Framework for Efficient Video Generation](https://arxiv.org/abs/2502.04393v1)** (Published: 2025-02-06)  
  Authors: Wenzhang Sun, Qirui Hou, Donglin Di, Jiahui Yang, Yongjia Ma, Jianxun Cui  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.04393v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Sparse VideoGen: Accelerating Video Diffusion Transformers with Spatial-Temporal Sparsity](https://arxiv.org/abs/2502.01776v1)** (Published: 2025-02-03)  
  Authors: Haocheng Xi, Shuo Yang, Yilong Zhao, Chenfeng Xu, Muyang Li, Xiuyu Li, Yujun Lin, Han Cai, Jintao Zhang, Dacheng Li, Jianfei Chen, Ion Stoica, Kurt Keutzer, Song Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.01776v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[OmniHuman-1: Rethinking the Scaling-Up of One-Stage Conditioned Human Animation Models](https://arxiv.org/abs/2502.01061v2)** (Published: 2025-02-03)  
  Authors: Gaojie Lin, Jianwen Jiang, Jiaqi Yang, Zerong Zheng, Chao Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.01061v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://omnihuman-lab.github.io))  
  Keywords: video generation, diffusion transformer  
- **[CatV2TON: Taming Diffusion Transformers for Vision-Based Virtual Try-On with Temporal Concatenation](https://arxiv.org/abs/2501.11325v1)** (Published: 2025-01-20)  
  Authors: Zheng Chong, Wenqing Zhang, Shiyue Zhang, Jun Zheng, Xiao Dong, Haoxiang Li, Yiling Wu, Dongmei Jiang, Xiaodan Liang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.11325v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Learnings from Scaling Visual Tokenizers for Reconstruction and Generation](https://arxiv.org/abs/2501.09755v1)** (Published: 2025-01-16)  
  Authors: Philippe Hansen-Estruch, David Yan, Ching-Yao Chung, Orr Zohar, Jialiang Wang, Tingbo Hou, Tao Xu, Sriram Vishwanath, Peter Vajda, Xinlei Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.09755v1.pdf)  
  Keywords: video generation, image generation, diffusion transformer  
- **[Multi-subject Open-set Personalization in Video Generation](https://arxiv.org/abs/2501.06187v1)** (Published: 2025-01-10)  
  Authors: Tsai-Shien Chen, Aliaksandr Siarohin, Willi Menapace, Yuwei Fang, Kwot Sin Lee, Ivan Skorokhodov, Kfir Aberman, Jun-Yan Zhu, Ming-Hsuan Yang, Sergey Tulyakov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.06187v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[ConceptMaster: Multi-Concept Video Customization on Diffusion Transformer Models Without Test-Time Tuning](https://arxiv.org/abs/2501.04698v1)** (Published: 2025-01-08)  
  Authors: Yuzhou Huang, Ziyang Yuan, Quande Liu, Qiulin Wang, Xintao Wang, Ruimao Zhang, Pengfei Wan, Di Zhang, Kun Gai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.04698v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Magic Mirror: ID-Preserved Video Generation in Video Diffusion Transformers](https://arxiv.org/abs/2501.03931v1)** (Published: 2025-01-07)  
  Authors: Yuechen Zhang, Yaoyang Liu, Bin Xia, Bohao Peng, Zexin Yan, Eric Lo, Jiaya Jia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.03931v1.pdf) | [![GitHub](https://img.shields.io/github/stars/dvlab-research/MagicMirror?style=social)](https://github.com/dvlab-research/MagicMirror)  
  Keywords: video generation, diffusion transformer  
- **[TransPixeler: Advancing Text-to-Video Generation with Transparency](https://arxiv.org/abs/2501.03006v2)** (Published: 2025-01-06)  
  Authors: Luozhou Wang, Yijun Li, Zhifei Chen, Jui-Hsien Wang, Zhifei Zhang, He Zhang, Zhe Lin, Yingcong Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.03006v2.pdf)  
  Keywords: video generation, diffusion transformer  
- **[GS-DiT: Advancing Video Generation with Pseudo 4D Gaussian Fields through Efficient Dense 3D Point Tracking](https://arxiv.org/abs/2501.02690v1)** (Published: 2025-01-05)  
  Authors: Weikang Bian, Zhaoyang Huang, Xiaoyu Shi, Yijin Li, Fu-Yun Wang, Hongsheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.02690v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wkbian.github.io/Projects/GS-DiT/.)  
  Keywords: video generation, diffusion transformer, Control  
- **[Open-Sora: Democratizing Efficient Video Production for All](https://arxiv.org/abs/2412.20404v1)** (Published: 2024-12-29)  
  Authors: Zangwei Zheng, Xiangyu Peng, Tianji Yang, Chenhui Shen, Shenggui Li, Hongxin Liu, Yukun Zhou, Tianyi Li, Yang You  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.20404v1.pdf) | [![GitHub](https://img.shields.io/github/stars/hpcaitech/Open-Sora?style=social)](https://github.com/hpcaitech/Open-Sora)  
  Keywords: video generation, image generation, diffusion transformer, text-to-image  
- **[Accelerating Diffusion Transformers with Dual Feature Caching](https://arxiv.org/abs/2412.18911v1)** (Published: 2024-12-25)  
  Authors: Chang Zou, Evelyn Zhang, Runlin Guo, Haohang Xu, Conghui He, Xuming Hu, Linfeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18911v1.pdf) | [![GitHub](https://img.shields.io/github/stars/Shenyi-Z/DuCa?style=social)](https://github.com/Shenyi-Z/DuCa)  
  Keywords: video generation, diffusion transformer  
- **[DiTCtrl: Exploring Attention Control in Multi-Modal Diffusion Transformer for Tuning-Free Multi-Prompt Longer Video Generation](https://arxiv.org/abs/2412.18597v1)** (Published: 2024-12-24)  
  Authors: Minghong Cai, Xiaodong Cun, Xiaoyu Li, Wenze Liu, Zhaoyang Zhang, Yong Zhang, Ying Shan, Xiangyu Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18597v1.pdf)  
  Keywords: video generation, diffusion transformer, Control, video editing  
- **[FFA Sora, video generation as fundus fluorescein angiography simulator](https://arxiv.org/abs/2412.17346v1)** (Published: 2024-12-23)  
  Authors: Xinyuan Wu, Lili Wang, Ruoyu Chen, Bowen Liu, Weiyi Zhang, Xi Yang, Yifan Feng, Mingguang He, Danli Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.17346v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Video Diffusion Transformers are In-Context Learners](https://arxiv.org/abs/2412.10783v2)** (Published: 2024-12-14)  
  Authors: Zhengcong Fei, Di Qiu, Changqian Yu, Debang Li, Mingyuan Fan, Xiang Wen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.10783v2.pdf) | [![GitHub](https://img.shields.io/github/stars/feizc/Video-In-Context?style=social)](https://github.com/feizc/Video-In-Context)  
  Keywords: video generation, diffusion transformer, Control, Controllable  
- **[LinGen: Towards High-Resolution Minute-Length Text-to-Video Generation with Linear Computational Complexity](https://arxiv.org/abs/2412.09856v1)** (Published: 2024-12-13)  
  Authors: Hongjie Wang, Chih-Yao Ma, Yen-Cheng Liu, Ji Hou, Tao Xu, Jialiang Wang, Felix Juefei-Xu, Yaqiao Luo, Peizhao Zhang, Tingbo Hou, Peter Vajda, Niraj K. Jha, Xiaoliang Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09856v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lineargen.github.io/.)  
  Keywords: video generation, diffusion transformer  
- **[MSC: Multi-Scale Spatio-Temporal Causal Attention for Autoregressive Video Diffusion](https://arxiv.org/abs/2412.09828v1)** (Published: 2024-12-13)  
  Authors: Xunnong Xu, Mengying Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09828v1.pdf)  
  Keywords: video generation, diffusion transformer, Control  
- **[From Slow Bidirectional to Fast Autoregressive Video Diffusion Models](https://arxiv.org/abs/2412.07772v2)** (Published: 2024-12-10)  
  Authors: Tianwei Yin, Qiang Zhang, Richard Zhang, William T. Freeman, Fredo Durand, Eli Shechtman, Xun Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07772v2.pdf)  
  Keywords: video generation, diffusion transformer  
- **[STIV: Scalable Text and Image Conditioned Video Generation](https://arxiv.org/abs/2412.07730v1)** (Published: 2024-12-10)  
  Authors: Zongyu Lin, Wei Liu, Chen Chen, Jiasen Lu, Wenze Hu, Tsu-Jui Fu, Jesse Allardice, Zhengfeng Lai, Liangchen Song, Bowen Zhang, Cha Chen, Yiran Fei, Yifan Jiang, Lezhi Li, Yizhou Sun, Kai-Wei Chang, Yinfei Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07730v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[ACDiT: Interpolating Autoregressive Conditional Modeling and Diffusion Transformer](https://arxiv.org/abs/2412.07720v1)** (Published: 2024-12-10)  
  Authors: Jinyi Hu, Shengding Hu, Yuxuan Song, Yufei Huang, Mingxuan Wang, Hao Zhou, Zhiyuan Liu, Wei-Ying Ma, Maosong Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07720v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[FlexDiT: Dynamic Token Density Control for Diffusion Transformer](https://arxiv.org/abs/2412.06028v1)** (Published: 2024-12-08)  
  Authors: Shuning Chang, Pichao Wang, Jiasheng Tang, Yi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.06028v1.pdf)  
  Keywords: diffusion transformer, Control, image generation, text-to-image, video generation  
- **[MotionStone: Decoupled Motion Intensity Modulation with Diffusion Transformer for Image-to-Video Generation](https://arxiv.org/abs/2412.05848v1)** (Published: 2024-12-08)  
  Authors: Shuwei Shi, Biao Gong, Xi Chen, Dandan Zheng, Shuai Tan, Zizheng Yang, Yuyuan Li, Jingwen He, Kecheng Zheng, Jingdong Chen, Ming Yang, Yinqiang Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05848v1.pdf)  
  Keywords: video generation, diffusion transformer, Control  
- **[Self-Guidance: Boosting Flow and Diffusion Generation on Their Own](https://arxiv.org/abs/2412.05827v2)** (Published: 2024-12-08)  
  Authors: Tiancheng Li, Weijian Luo, Zhiyang Chen, Liyuan Ma, Guo-Jun Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05827v2.pdf)  
  Keywords: video generation, text-to-image, FLUX  
- **[Mind the Time: Temporally-Controlled Multi-Event Video Generation](https://arxiv.org/abs/2412.05263v2)** (Published: 2024-12-06)  
  Authors: Ziyi Wu, Aliaksandr Siarohin, Willi Menapace, Ivan Skorokhodov, Yuwei Fang, Varnith Chordia, Igor Gilitschenski, Sergey Tulyakov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05263v2.pdf)  
  Keywords: video generation, diffusion transformer, Control  
- **[Navigation World Models](https://arxiv.org/abs/2412.03572v1)** (Published: 2024-12-04)  
  Authors: Amir Bar, Gaoyue Zhou, Danny Tran, Trevor Darrell, Yann LeCun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03572v1.pdf)  
  Keywords: video generation, diffusion transformer, Control, Controllable  
- **[Seeing Beyond Views: Multi-View Driving Scene Video Generation with Holistic Attention](https://arxiv.org/abs/2412.03520v2)** (Published: 2024-12-04)  
  Authors: Hannan Lu, Xiaohe Wu, Shudong Wang, Xiameng Qin, Xinyu Zhang, Junyu Han, Wangmeng Zuo, Ji Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03520v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://luhannan.github.io/CogDrivingPage/.)  
  Keywords: video generation, diffusion transformer, Control  
- **[SyncFlow: Toward Temporally Aligned Joint Audio-Video Generation from Text](https://arxiv.org/abs/2412.15220v1)** (Published: 2024-12-03)  
  Authors: Haohe Liu, Gael Le Lan, Xinhao Mei, Zhaoheng Ni, Anurag Kumar, Varun Nagaraja, Wenwu Wang, Mark D. Plumbley, Yangyang Shi, Vikas Chandra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.15220v1.pdf)  
  Keywords: video generation  
- **[World-consistent Video Diffusion with Explicit 3D Modeling](https://arxiv.org/abs/2412.01821v1)** (Published: 2024-12-02)  
  Authors: Qihang Zhang, Shuangfei Zhai, Miguel Angel Bautista, Kevin Miao, Alexander Toshev, Joshua Susskind, Jiatao Gu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01821v1.pdf)  
  Keywords: video generation, image generation, diffusion transformer, Control  
- **[CPA: Camera-pose-awareness Diffusion Transformer for Video Generation](https://arxiv.org/abs/2412.01429v1)** (Published: 2024-12-02)  
  Authors: Yuelei Wang, Jian Zhang, Pengtao Jiang, Hao Zhang, Jinwei Chen, Bo Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01429v1.pdf)  
  Keywords: video generation, diffusion transformer, Control, Controllable  
- **[OpenHumanVid: A Large-Scale High-Quality Dataset for Enhancing Human-Centric Video Generation](https://arxiv.org/abs/2412.00115v3)** (Published: 2024-11-28)  
  Authors: Hui Li, Mingwang Xu, Yun Zhan, Shan Mu, Jiaye Li, Kaihui Cheng, Yuxuan Chen, Tan Chen, Mao Ye, Jingdong Wang, Siyu Zhu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.00115v3.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://fudan-generative-vision.github.io/OpenHumanVid)  
  Keywords: video generation, diffusion transformer  
- **[AC3D: Analyzing and Improving 3D Camera Control in Video Diffusion Transformers](https://arxiv.org/abs/2411.18673v2)** (Published: 2024-11-27)  
  Authors: Sherwin Bahmani, Ivan Skorokhodov, Guocheng Qian, Aliaksandr Siarohin, Willi Menapace, Andrea Tagliasacchi, David B. Lindell, Sergey Tulyakov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.18673v2.pdf)  
  Keywords: video generation, diffusion transformer, Control  



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
