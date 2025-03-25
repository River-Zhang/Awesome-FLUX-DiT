# Awesome FLUX/DiT methods [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of latest research papers, projects and resources related to DiT/FLUX. Content is automatically updated daily.

> Last Update: 2025-03-25 06:32:07

Thanks to [@longxiang-ai](https://github.com/longxiang-ai) for the template.

## Categories

- [Image Editing](#image-editing) (10 papers) - Papers about image editing with Diffusion Transformer or FLUX
- [Image Generation](#image-generation) (68 papers) - Papers focusing on image generation with Diffusion Transformer or FLUX
- [Video Related](#video-related) (51 papers) - Papers about video generation and editing with Diffusion Transformer or FLUX



## Table of Contents

- [Categorized Papers](#categorized-papers)
- [Classic Papers](#classic-papers)
- [Open Source Projects](#open-source-projects)
- [Applications](#applications)
- [Tutorials & Blogs](#tutorials--blogs)





## Categorized Papers

### Image Editing

- **[FreeFlux: Understanding and Exploiting Layer-Specific Roles in RoPE-Based MMDiT for Versatile Image Editing](https://arxiv.org/abs/2503.16153v1)** (Published: 2025-03-20)  
  Authors: Tianyi Wei, Yifan Zhou, Dongdong Chen, Xingang Pan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.16153v1.pdf)  
  Keywords: image generation, image editing, FLUX, text-to-image, diffusion transformer  
- **[Personalize Anything for Free with Diffusion Transformer](https://arxiv.org/abs/2503.12590v1)** (Published: 2025-03-16)  
  Authors: Haoran Feng, Zehuan Huang, Lin Li, Hairong Lv, Lu Sheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.12590v1.pdf)  
  Keywords: image editing, Control, image generation, diffusion transformer  
- **[NAMI: Efficient Image Generation via Progressive Rectified Flow Transformers](https://arxiv.org/abs/2503.09242v1)** (Published: 2025-03-12)  
  Authors: Yuhang Ma, Bo Cheng, Shanyuan Liu, Ao Ma, Xiaoyu Wu, Liebucha Wu, Dawei Leng, Yuhui Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.09242v1.pdf)  
  Keywords: rectified flow, image generation, diffusion transformer  
- **[Seedream 2.0: A Native Chinese-English Bilingual Image Generation Foundation Model](https://arxiv.org/abs/2503.07703v1)** (Published: 2025-03-10)  
  Authors: Lixue Gong, Xiaoxia Hou, Fanshi Li, Liang Li, Xiaochen Lian, Fei Liu, Liyang Liu, Wei Liu, Wei Lu, Yichun Shi, Shiqi Sun, Yu Tian, Zhi Tian, Peng Wang, Xun Wang, Ye Wang, Guofeng Wu, Jie Wu, Xin Xia, Xuefeng Xiao, Linjie Yang, Zhonghua Zhai, Xinyu Zhang, Qi Zhang, Yuwei Zhang, Shijia Zhao, Jianchao Yang, Weilin Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07703v1.pdf)  
  Keywords: image editing, FLUX, image generation  
- **[TIDE : Temporal-Aware Sparse Autoencoders for Interpretable Diffusion Transformers in Image Generation](https://arxiv.org/abs/2503.07050v1)** (Published: 2025-03-10)  
  Authors: Victor Shea-Jay Huang, Le Zhuo, Yi Xin, Zhaokai Wang, Peng Gao, Hongsheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07050v1.pdf)  
  Keywords: image editing, Control, image generation, diffusion transformer  
- **[X2I: Seamless Integration of Multimodal Understanding into Diffusion Transformer via Attention Distillation](https://arxiv.org/abs/2503.06134v2)** (Published: 2025-03-08)  
  Authors: Jian Ma, Qirong Peng, Xu Guo, Chen Chen, Haonan Lu, Zhenyu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.06134v2.pdf) | [![GitHub](https://img.shields.io/github/stars/OPPO-Mente-Lab/X2I?style=social)](https://github.com/OPPO-Mente-Lab/X2I)  
  Keywords: image generation, image editing, image to image, Control, text-to-image, diffusion transformer  
- **[AnyRefill: A Unified, Data-Efficient Framework for Left-Prompt-Guided Vision Tasks](https://arxiv.org/abs/2502.11158v2)** (Published: 2025-02-16)  
  Authors: Ming Xie, Chenjie Cao, Yunuo Cai, Xiangyang Xue, Yu-Gang Jiang, Yanwei Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.11158v2.pdf)  
  Keywords: image editing, text-to-image, diffusion transformer  
- **[EliGen: Entity-Level Controlled Image Generation with Regional Attention](https://arxiv.org/abs/2501.01097v3)** (Published: 2025-01-02)  
  Authors: Hong Zhang, Zhongjie Duan, Xingjun Wang, Yingda Chen, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.01097v3.pdf) | [![GitHub](https://img.shields.io/github/stars/modelscope/DiffSynth-Studio.git?style=social)](https://github.com/modelscope/DiffSynth-Studio.git)  
  Keywords: image inpainting, image generation, Control, text-to-image, diffusion transformer  
- **[Context Canvas: Enhancing Text-to-Image Diffusion Models with Knowledge Graph-Based RAG](https://arxiv.org/abs/2412.09614v1)** (Published: 2024-12-12)  
  Authors: Kavana Venkatesh, Yusuf Dalva, Ismini Lourentzou, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09614v1.pdf)  
  Keywords: image editing, Control, FLUX, text-to-image  
- **[FluxSpace: Disentangled Semantic Editing in Rectified Flow Transformers](https://arxiv.org/abs/2412.09611v1)** (Published: 2024-12-12)  
  Authors: Yusuf Dalva, Kavana Venkatesh, Pinar Yanardag  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09611v1.pdf)  
  Keywords: image generation, image editing, Control, rectified flow, FLUX  

### Image Generation

*Showing the latest 50 out of 68 papers*

- **[Boosting Resolution Generalization of Diffusion Transformers with Randomized Positional Encodings](https://arxiv.org/abs/2503.18719v1)** (Published: 2025-03-24)  
  Authors: Cong Liu, Liang Hou, Mingwu Zheng, Xin Tao, Pengfei Wan, Di Zhang, Kun Gai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.18719v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[Diffusion-4K: Ultra-High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2503.18352v1)** (Published: 2025-03-24)  
  Authors: Jinjin Zhang, Qiuyu Huang, Junjie Liu, Xiefan Guo, Di Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.18352v1.pdf)  
  Keywords: FLUX, text-to-image, image generation  
- **[EDiT: Efficient Diffusion Transformers with Linear Compressed Attention](https://arxiv.org/abs/2503.16726v1)** (Published: 2025-03-20)  
  Authors: Philipp Becker, Abhinav Mehrotra, Ruchika Chavhan, Malcolm Chadwick, Luca Morreale, Mehdi Noroozi, Alberto Gil Ramos, Sourav Bhattacharya  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.16726v1.pdf)  
  Keywords: image generation, text-to-image, diffusion transformer  
- **[InfiniteYou: Flexible Photo Recrafting While Preserving Your Identity](https://arxiv.org/abs/2503.16418v1)** (Published: 2025-03-20)  
  Authors: Liming Jiang, Qing Yan, Yumin Jia, Zichuan Liu, Hao Kang, Xin Lu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.16418v1.pdf)  
  Keywords: FLUX, image generation, diffusion transformer  
- **[Ultra-Resolution Adaptation with Ease](https://arxiv.org/abs/2503.16322v1)** (Published: 2025-03-20)  
  Authors: Ruonan Yu, Songhua Liu, Zhenxiong Tan, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.16322v1.pdf) | [![GitHub](https://img.shields.io/github/stars/Huage001/URAE?style=social)](https://github.com/Huage001/URAE)  
  Keywords: FLUX, text-to-image, image generation  
- **[FreeFlux: Understanding and Exploiting Layer-Specific Roles in RoPE-Based MMDiT for Versatile Image Editing](https://arxiv.org/abs/2503.16153v1)** (Published: 2025-03-20)  
  Authors: Tianyi Wei, Yifan Zhou, Dongdong Chen, Xingang Pan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.16153v1.pdf)  
  Keywords: image generation, image editing, FLUX, text-to-image, diffusion transformer  
- **[Guardians of Generation: Dynamic Inference-Time Copyright Shielding with Adaptive Guidance for AI Image Generation](https://arxiv.org/abs/2503.16171v1)** (Published: 2025-03-19)  
  Authors: Soham Roy, Abhishek Mishra, Shirish Karande, Murari Mandal  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.16171v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://respailab.github.io/gog)  
  Keywords: FLUX, text-to-image, image generation  
- **[DiffMoE: Dynamic Token Selection for Scalable Diffusion Transformers](https://arxiv.org/abs/2503.14487v1)** (Published: 2025-03-18)  
  Authors: Minglei Shi, Ziyang Yuan, Haotian Yang, Xintao Wang, Mingwu Zheng, Xin Tao, Wenliang Zhao, Wenzhao Zheng, Jie Zhou, Jiwen Lu, Pengfei Wan, Di Zhang, Kun Gai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.14487v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://shiml20.github.io/DiffMoE/)  
  Keywords: image generation, text-to-image, diffusion transformer  
- **[Personalize Anything for Free with Diffusion Transformer](https://arxiv.org/abs/2503.12590v1)** (Published: 2025-03-16)  
  Authors: Haoran Feng, Zehuan Huang, Lin Li, Hairong Lv, Lu Sheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.12590v1.pdf)  
  Keywords: image editing, Control, image generation, diffusion transformer  
- **[Reflect-DiT: Inference-Time Scaling for Text-to-Image Diffusion Transformers via In-Context Reflection](https://arxiv.org/abs/2503.12271v1)** (Published: 2025-03-15)  
  Authors: Shufan Li, Konstantinos Kallidromitis, Akash Gokul, Arsh Koneru, Yusuke Kato, Kazuki Kozuka, Aditya Grover  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.12271v1.pdf)  
  Keywords: image generation, text-to-image, diffusion transformer  
- **[DiT-Air: Revisiting the Efficiency of Diffusion Model Architecture Design in Text to Image Generation](https://arxiv.org/abs/2503.10618v2)** (Published: 2025-03-13)  
  Authors: Chen Chen, Rui Qian, Wenze Hu, Tsu-Jui Fu, Jialing Tong, Xinze Wang, Lezhi Li, Bowen Zhang, Alex Schwing, Wei Liu, Yinfei Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.10618v2.pdf)  
  Keywords: image generation, text-to-image, diffusion transformer  
- **[Do I look like a `cat.n.01` to you? A Taxonomy Image Generation Benchmark](https://arxiv.org/abs/2503.10357v1)** (Published: 2025-03-13)  
  Authors: Viktor Moskvoretskii, Alina Lobanova, Ekaterina Neminova, Chris Biemann, Alexander Panchenko, Irina Nikishina  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.10357v1.pdf)  
  Keywords: FLUX, text-to-image, image generation  
- **[UniCombine: Unified Multi-Conditional Combination with Diffusion Transformer](https://arxiv.org/abs/2503.09277v1)** (Published: 2025-03-12)  
  Authors: Haoxuan Wang, Jinlong Peng, Qingdong He, Hao Yang, Ying Jin, Jiafu Wu, Xiaobin Hu, Yanjie Pan, Zhenye Gan, Mingmin Chi, Bo Peng, Yabiao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.09277v1.pdf)  
  Keywords: Controllable, Control, image generation, diffusion transformer  
- **[NAMI: Efficient Image Generation via Progressive Rectified Flow Transformers](https://arxiv.org/abs/2503.09242v1)** (Published: 2025-03-12)  
  Authors: Yuhang Ma, Bo Cheng, Shanyuan Liu, Ao Ma, Xiaoyu Wu, Liebucha Wu, Dawei Leng, Yuhui Yin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.09242v1.pdf)  
  Keywords: rectified flow, image generation, diffusion transformer  
- **[Other Vehicle Trajectories Are Also Needed: A Driving World Model Unifies Ego-Other Vehicle Trajectories in Video Latent Space](https://arxiv.org/abs/2503.09215v2)** (Published: 2025-03-12)  
  Authors: Jian Zhu, Zhengyu Jia, Tian Gao, Jiaxin Deng, Shidi Li, Fu Liu, Peng Jia, Xianpeng Lang, Xiaolong Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.09215v2.pdf)  
  Keywords: Controllable, Control, video generation, diffusion transformer  
- **[Reangle-A-Video: 4D Video Generation as Video-to-Video Translation](https://arxiv.org/abs/2503.09151v2)** (Published: 2025-03-12)  
  Authors: Hyeonho Jeong, Suhyeon Lee, Jong Chul Ye  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.09151v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hyeonho99.github.io/reangle-a-video/)  
  Keywords: Control, video generation, diffusion transformer  
- **[Zero-Shot Subject-Centric Generation for Creative Application Using Entropy Fusion](https://arxiv.org/abs/2503.10697v1)** (Published: 2025-03-12)  
  Authors: Kaifeng Zou, Xiaoyi Feng, Peng Wang, Tao Huang, Zizhou Huang, Zhang Haihang, Yuntao Zou, Dagang Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.10697v1.pdf)  
  Keywords: FLUX, text-to-image, image generation  
- **[SANA-Sprint: One-Step Diffusion with Continuous-Time Consistency Distillation](https://arxiv.org/abs/2503.09641v2)** (Published: 2025-03-12)  
  Authors: Junsong Chen, Shuchen Xue, Yuyang Zhao, Jincheng Yu, Sayak Paul, Junyu Chen, Han Cai, Enze Xie, Song Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.09641v2.pdf)  
  Keywords: Control, FLUX, text-to-image, image generation  
- **[OminiControl2: Efficient Conditioning for Diffusion Transformers](https://arxiv.org/abs/2503.08280v1)** (Published: 2025-03-11)  
  Authors: Zhenxiong Tan, Qiaochu Xue, Xingyi Yang, Songhua Liu, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.08280v1.pdf)  
  Keywords: image generation, Control, Controllable, text-to-image, diffusion transformer  
- **[Seedream 2.0: A Native Chinese-English Bilingual Image Generation Foundation Model](https://arxiv.org/abs/2503.07703v1)** (Published: 2025-03-10)  
  Authors: Lixue Gong, Xiaoxia Hou, Fanshi Li, Liang Li, Xiaochen Lian, Fei Liu, Liyang Liu, Wei Liu, Wei Lu, Yichun Shi, Shiqi Sun, Yu Tian, Zhi Tian, Peng Wang, Xun Wang, Ye Wang, Guofeng Wu, Jie Wu, Xin Xia, Xuefeng Xiao, Linjie Yang, Zhonghua Zhai, Xinyu Zhang, Qi Zhang, Yuwei Zhang, Shijia Zhao, Jianchao Yang, Weilin Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07703v1.pdf)  
  Keywords: image editing, FLUX, image generation  
- **[TIDE : Temporal-Aware Sparse Autoencoders for Interpretable Diffusion Transformers in Image Generation](https://arxiv.org/abs/2503.07050v1)** (Published: 2025-03-10)  
  Authors: Victor Shea-Jay Huang, Le Zhuo, Yi Xin, Zhaokai Wang, Peng Gao, Hongsheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07050v1.pdf)  
  Keywords: image editing, Control, image generation, diffusion transformer  
- **[Post-Training Quantization for Diffusion Transformer via Hierarchical Timestep Grouping](https://arxiv.org/abs/2503.06930v1)** (Published: 2025-03-10)  
  Authors: Ning Ding, Jing Han, Yuchuan Tian, Chao Xu, Kai Han, Yehui Tang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.06930v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[X2I: Seamless Integration of Multimodal Understanding into Diffusion Transformer via Attention Distillation](https://arxiv.org/abs/2503.06134v2)** (Published: 2025-03-08)  
  Authors: Jian Ma, Qirong Peng, Xu Guo, Chen Chen, Haonan Lu, Zhenyu Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.06134v2.pdf) | [![GitHub](https://img.shields.io/github/stars/OPPO-Mente-Lab/X2I?style=social)](https://github.com/OPPO-Mente-Lab/X2I)  
  Keywords: image generation, image editing, image to image, Control, text-to-image, diffusion transformer  
- **[MagicInfinite: Generating Infinite Talking Videos with Your Words and Voice](https://arxiv.org/abs/2503.05978v1)** (Published: 2025-03-07)  
  Authors: Hongwei Yi, Tian Ye, Shitong Shao, Xuancheng Yang, Jiantong Zhao, Hanzhong Guo, Terrance Wang, Qingyu Yin, Zeke Xie, Lei Zhu, Wei Li, Michael Lingelbach, Daquan Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.05978v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://www.hedra.com/,)  
  Keywords: Control, video generation, diffusion transformer  
- **[Q&C: When Quantization Meets Cache in Efficient Image Generation](https://arxiv.org/abs/2503.02508v1)** (Published: 2025-03-04)  
  Authors: Xin Ding, Xin Li, Haotong Qin, Zhibo Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.02508v1.pdf) | [![GitHub](https://img.shields.io/github/stars/xinding-sys/Quant-Cache?style=social)](https://github.com/xinding-sys/Quant-Cache)  
  Keywords: image generation, diffusion transformer  
- **[Multimodal Representation Alignment for Image Generation: Text-Image Interleaved Control Is Easier Than You Think](https://arxiv.org/abs/2502.20172v1)** (Published: 2025-02-27)  
  Authors: Liang Chen, Shuai Bai, Wenhao Chai, Weichu Xie, Haozhe Zhao, Leon Vinci, Junyang Lin, Baobao Chang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.20172v1.pdf)  
  Keywords: image generation, Control, FLUX, text-to-image, diffusion transformer  
- **[FlexiDiT: Your Diffusion Transformer Can Easily Generate High-Quality Samples with Less Compute](https://arxiv.org/abs/2502.20126v1)** (Published: 2025-02-27)  
  Authors: Sotiris Anagnostidis, Gregor Bachmann, Yeongmin Kim, Jonas Kohler, Markos Georgopoulos, Artsiom Sanakoyeu, Yuming Du, Albert Pumarola, Ali Thabet, Edgar Schönfeld  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.20126v1.pdf)  
  Keywords: video generation, image generation, diffusion transformer  
- **[RelaCtrl: Relevance-Guided Efficient Control for Diffusion Transformers](https://arxiv.org/abs/2502.14377v4)** (Published: 2025-02-20)  
  Authors: Ke Cao, Jing Wang, Ao Ma, Jiasong Feng, Zhanjie Zhang, Xuanhua He, Shanyuan Liu, Bo Cheng, Dawei Leng, Yuhui Yin, Jie Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.14377v4.pdf)  
  Keywords: video generation, Control, Controllable, text-to-image, diffusion transformer  
- **[AnyRefill: A Unified, Data-Efficient Framework for Left-Prompt-Guided Vision Tasks](https://arxiv.org/abs/2502.11158v2)** (Published: 2025-02-16)  
  Authors: Ming Xie, Chenjie Cao, Yunuo Cai, Xiangyang Xue, Yu-Gang Jiang, Yanwei Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.11158v2.pdf)  
  Keywords: image editing, text-to-image, diffusion transformer  
- **[BCDDM: Branch-Corrected Denoising Diffusion Model for Black Hole Image Generation](https://arxiv.org/abs/2502.08528v1)** (Published: 2025-02-12)  
  Authors: Ao liu, Zelin Zhang, Songbai Chen, Cuihong Wen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.08528v1.pdf)  
  Keywords: FLUX, image generation  
- **[Lumina-Video: Efficient and Flexible Video Generation with Multi-scale Next-DiT](https://arxiv.org/abs/2502.06782v2)** (Published: 2025-02-10)  
  Authors: Dongyang Liu, Shicheng Li, Yutong Liu, Zhen Li, Kai Wang, Xinyue Li, Qi Qin, Yufei Liu, Yi Xin, Zhongyu Li, Bin Fu, Chenyang Si, Yuewen Cao, Conghui He, Ziwei Liu, Yu Qiao, Qibin Hou, Hongsheng Li, Peng Gao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.06782v2.pdf) | [![GitHub](https://img.shields.io/github/stars/Alpha-VLLM/Lumina-Video?style=social)](https://github.com/Alpha-VLLM/Lumina-Video)  
  Keywords: Control, video generation, diffusion transformer  
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
  Keywords: FLUX, text-to-image, image generation  
- **[SANA 1.5: Efficient Scaling of Training-Time and Inference-Time Compute in Linear Diffusion Transformer](https://arxiv.org/abs/2501.18427v3)** (Published: 2025-01-30)  
  Authors: Enze Xie, Junsong Chen, Yuyang Zhao, Jincheng Yu, Ligeng Zhu, Chengyue Wu, Yujun Lin, Zhekai Zhang, Muyang Li, Junyu Chen, Han Cai, Bingchen Liu, Daquan Zhou, Song Han  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.18427v3.pdf)  
  Keywords: image generation, text-to-image, diffusion transformer  
- **[Accelerate High-Quality Diffusion Models with Inner Loop Feedback](https://arxiv.org/abs/2501.13107v2)** (Published: 2025-01-22)  
  Authors: Matthew Gwilliam, Han Cai, Di Wu, Abhinav Shrivastava, Zhiyu Cheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.13107v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://mgwillia.github.io/ilf.)  
  Keywords: image generation, text-to-image, diffusion transformer  
- **[LiT: Delving into a Simplified Linear Diffusion Transformer for Image Generation](https://arxiv.org/abs/2501.12976v1)** (Published: 2025-01-22)  
  Authors: Jiahao Wang, Ning Kang, Lewei Yao, Mengzhao Chen, Chengyue Wu, Songyang Zhang, Shuchen Xue, Yong Liu, Taiqiang Wu, Xihui Liu, Kaipeng Zhang, Shifeng Zhang, Wenqi Shao, Zhenguo Li, Ping Luo  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.12976v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://techmonsterwang.github.io/LiT/.)  
  Keywords: image generation, text-to-image, diffusion transformer  
- **[Learnings from Scaling Visual Tokenizers for Reconstruction and Generation](https://arxiv.org/abs/2501.09755v1)** (Published: 2025-01-16)  
  Authors: Philippe Hansen-Estruch, David Yan, Ching-Yao Chung, Orr Zohar, Jialiang Wang, Tingbo Hou, Tao Xu, Sriram Vishwanath, Peter Vajda, Xinlei Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.09755v1.pdf)  
  Keywords: video generation, image generation, diffusion transformer  
- **[Enhancing Image Generation Fidelity via Progressive Prompts](https://arxiv.org/abs/2501.07070v1)** (Published: 2025-01-13)  
  Authors: Zhen Xiong, Yuqi Li, Chuanguang Yang, Tiao Tan, Zhihong Zhu, Siyuan Li, Yue Ma  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.07070v1.pdf)  
  Keywords: Control, image generation, diffusion transformer  
- **[3DIS-FLUX: simple and efficient multi-instance generation with DiT rendering](https://arxiv.org/abs/2501.05131v1)** (Published: 2025-01-09)  
  Authors: Dewei Zhou, Ji Xie, Zongxin Yang, Yi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.05131v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://limuloo.github.io/3DIS/.)  
  Keywords: image generation, Control, FLUX, Controllable, text-to-image  
- **[Circuit Complexity Bounds for Visual Autoregressive Model](https://arxiv.org/abs/2501.04299v1)** (Published: 2025-01-08)  
  Authors: Yekun Ke, Xiaoyu Li, Yingyu Liang, Zhenmei Shi, Zhao Song  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.04299v1.pdf)  
  Keywords: image generation, diffusion transformer  
- **[GS-DiT: Advancing Video Generation with Pseudo 4D Gaussian Fields through Efficient Dense 3D Point Tracking](https://arxiv.org/abs/2501.02690v1)** (Published: 2025-01-05)  
  Authors: Weikang Bian, Zhaoyang Huang, Xiaoyu Shi, Yijin Li, Fu-Yun Wang, Hongsheng Li  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.02690v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://wkbian.github.io/Projects/GS-DiT/.)  
  Keywords: Control, video generation, diffusion transformer  
- **[EliGen: Entity-Level Controlled Image Generation with Regional Attention](https://arxiv.org/abs/2501.01097v3)** (Published: 2025-01-02)  
  Authors: Hong Zhang, Zhongjie Duan, Xingjun Wang, Yingda Chen, Yu Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.01097v3.pdf) | [![GitHub](https://img.shields.io/github/stars/modelscope/DiffSynth-Studio.git?style=social)](https://github.com/modelscope/DiffSynth-Studio.git)  
  Keywords: image inpainting, image generation, Control, text-to-image, diffusion transformer  
- **[Dual Diffusion for Unified Image Generation and Understanding](https://arxiv.org/abs/2501.00289v1)** (Published: 2024-12-31)  
  Authors: Zijie Li, Henry Li, Yichun Shi, Amir Barati Farimani, Yuval Kluger, Linjie Yang, Peng Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.00289v1.pdf)  
  Keywords: image generation, text-to-image, diffusion transformer  
- **[Open-Sora: Democratizing Efficient Video Production for All](https://arxiv.org/abs/2412.20404v1)** (Published: 2024-12-29)  
  Authors: Zangwei Zheng, Xiangyu Peng, Tianji Yang, Chenhui Shen, Shenggui Li, Hongxin Liu, Yukun Zhou, Tianyi Li, Yang You  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.20404v1.pdf) | [![GitHub](https://img.shields.io/github/stars/hpcaitech/Open-Sora?style=social)](https://github.com/hpcaitech/Open-Sora)  
  Keywords: video generation, image generation, text-to-image, diffusion transformer  
- **[UNIC-Adapter: Unified Image-instruction Adapter with Multi-modal Transformer for Image Generation](https://arxiv.org/abs/2412.18928v1)** (Published: 2024-12-25)  
  Authors: Lunhao Duan, Shanshan Zhao, Wenjun Yan, Yinglun Li, Qing-Guo Chen, Zhao Xu, Weihua Luo, Kaifu Zhang, Mingming Gong, Gui-Song Xia  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18928v1.pdf)  
  Keywords: image generation, Control, Controllable, text-to-image, diffusion transformer  
- **[1.58-bit FLUX](https://arxiv.org/abs/2412.18653v1)** (Published: 2024-12-24)  
  Authors: Chenglin Yang, Celong Liu, Xueqing Deng, Dongwon Kim, Xing Mei, Xiaohui Shen, Liang-Chieh Chen  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18653v1.pdf)  
  Keywords: FLUX, text-to-image, image generation  
- **[DiTCtrl: Exploring Attention Control in Multi-Modal Diffusion Transformer for Tuning-Free Multi-Prompt Longer Video Generation](https://arxiv.org/abs/2412.18597v1)** (Published: 2024-12-24)  
  Authors: Minghong Cai, Xiaodong Cun, Xiaoyu Li, Wenze Liu, Zhaoyang Zhang, Yong Zhang, Ying Shan, Xiangyu Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18597v1.pdf)  
  Keywords: video editing, Control, video generation, diffusion transformer  
- **[Layer- and Timestep-Adaptive Differentiable Token Compression Ratios for Efficient Diffusion Transformers](https://arxiv.org/abs/2412.16822v1)** (Published: 2024-12-22)  
  Authors: Haoran You, Connelly Barnes, Yuqian Zhou, Yan Kang, Zhenbang Du, Wei Zhou, Lingzhi Zhang, Yotam Nitzan, Xiaoyang Liu, Zhe Lin, Eli Shechtman, Sohrab Amirghodsi, Yingyan Celine Lin  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.16822v1.pdf)  
  Keywords: image generation, text-to-image, diffusion transformer  
- **[CLEAR: Conv-Like Linearization Revs Pre-Trained Diffusion Transformers Up](https://arxiv.org/abs/2412.16112v1)** (Published: 2024-12-20)  
  Authors: Songhua Liu, Zhenxiong Tan, Xinchao Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.16112v1.pdf) | [![GitHub](https://img.shields.io/github/stars/Huage001/CLEAR?style=social)](https://github.com/Huage001/CLEAR)  
  Keywords: image generation, diffusion transformer  

### Video Related

*Showing the latest 50 out of 51 papers*

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
  Keywords: Controllable, Control, video generation, diffusion transformer  
- **[Reangle-A-Video: 4D Video Generation as Video-to-Video Translation](https://arxiv.org/abs/2503.09151v2)** (Published: 2025-03-12)  
  Authors: Hyeonho Jeong, Suhyeon Lee, Jong Chul Ye  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.09151v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://hyeonho99.github.io/reangle-a-video/)  
  Keywords: Control, video generation, diffusion transformer  
- **[REGEN: Learning Compact Video Embedding with (Re-)Generative Decoder](https://arxiv.org/abs/2503.08665v1)** (Published: 2025-03-11)  
  Authors: Yitian Zhang, Long Mai, Aniruddha Mahapatra, David Bourgin, Yicong Hong, Jonah Casebeer, Feng Liu, Yun Fu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.08665v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[VACE: All-in-One Video Creation and Editing](https://arxiv.org/abs/2503.07598v2)** (Published: 2025-03-10)  
  Authors: Zeyinzi Jiang, Zhen Han, Chaojie Mao, Jingfeng Zhang, Yulin Pan, Yu Liu  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07598v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://ali-vilab.github.io/VACE-Page/.)  
  Keywords: video editing, video generation, diffusion transformer  
- **[QuantCache: Adaptive Importance-Guided Quantization with Hierarchical Latent and Layer Caching for Video Generation](https://arxiv.org/abs/2503.06545v1)** (Published: 2025-03-09)  
  Authors: Junyi Wu, Zhiteng Li, Zheng Hui, Yulun Zhang, Linghe Kong, Xiaokang Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.06545v1.pdf) | [![GitHub](https://img.shields.io/github/stars/JunyiWuCode/QuantCache?style=social)](https://github.com/JunyiWuCode/QuantCache)  
  Keywords: video generation, diffusion transformer  
- **[Get In Video: Add Anything You Want to the Video](https://arxiv.org/abs/2503.06268v1)** (Published: 2025-03-08)  
  Authors: Shaobin Zhuang, Zhipeng Huang, Binxin Yang, Ying Zhang, Fangyikang Wang, Canmiao Fu, Chong Sun, Zheng-Jun Zha, Chen Li, Yali Wang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.06268v1.pdf)  
  Keywords: video editing, diffusion transformer  
- **[MagicInfinite: Generating Infinite Talking Videos with Your Words and Voice](https://arxiv.org/abs/2503.05978v1)** (Published: 2025-03-07)  
  Authors: Hongwei Yi, Tian Ye, Shitong Shao, Xuancheng Yang, Jiantong Zhao, Hanzhong Guo, Terrance Wang, Qingyu Yin, Zeke Xie, Lei Zhu, Wei Li, Michael Lingelbach, Daquan Zhou  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.05978v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://www.hedra.com/,)  
  Keywords: Control, video generation, diffusion transformer  
- **[Video Super-Resolution: All You Need is a Video Diffusion Model](https://arxiv.org/abs/2503.03355v3)** (Published: 2025-03-05)  
  Authors: Zhihao Zhan, Wang Pang, Xiang Zhu, Yechao Bai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.03355v3.pdf)  
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
- **[RelaCtrl: Relevance-Guided Efficient Control for Diffusion Transformers](https://arxiv.org/abs/2502.14377v4)** (Published: 2025-02-20)  
  Authors: Ke Cao, Jing Wang, Ao Ma, Jiasong Feng, Zhanjie Zhang, Xuanhua He, Shanyuan Liu, Bo Cheng, Dawei Leng, Yuhui Yin, Jie Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.14377v4.pdf)  
  Keywords: video generation, Control, Controllable, text-to-image, diffusion transformer  
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
  Keywords: Control, video generation, diffusion transformer  
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
- **[Multi-subject Open-set Personalization in Video Generation](https://arxiv.org/abs/2501.06187v2)** (Published: 2025-01-10)  
  Authors: Tsai-Shien Chen, Aliaksandr Siarohin, Willi Menapace, Yuwei Fang, Kwot Sin Lee, Ivan Skorokhodov, Kfir Aberman, Jun-Yan Zhu, Ming-Hsuan Yang, Sergey Tulyakov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.06187v2.pdf)  
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
  Keywords: Control, video generation, diffusion transformer  
- **[Open-Sora: Democratizing Efficient Video Production for All](https://arxiv.org/abs/2412.20404v1)** (Published: 2024-12-29)  
  Authors: Zangwei Zheng, Xiangyu Peng, Tianji Yang, Chenhui Shen, Shenggui Li, Hongxin Liu, Yukun Zhou, Tianyi Li, Yang You  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.20404v1.pdf) | [![GitHub](https://img.shields.io/github/stars/hpcaitech/Open-Sora?style=social)](https://github.com/hpcaitech/Open-Sora)  
  Keywords: video generation, image generation, text-to-image, diffusion transformer  
- **[Accelerating Diffusion Transformers with Dual Feature Caching](https://arxiv.org/abs/2412.18911v1)** (Published: 2024-12-25)  
  Authors: Chang Zou, Evelyn Zhang, Runlin Guo, Haohang Xu, Conghui He, Xuming Hu, Linfeng Zhang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18911v1.pdf) | [![GitHub](https://img.shields.io/github/stars/Shenyi-Z/DuCa?style=social)](https://github.com/Shenyi-Z/DuCa)  
  Keywords: video generation, diffusion transformer  
- **[DiTCtrl: Exploring Attention Control in Multi-Modal Diffusion Transformer for Tuning-Free Multi-Prompt Longer Video Generation](https://arxiv.org/abs/2412.18597v1)** (Published: 2024-12-24)  
  Authors: Minghong Cai, Xiaodong Cun, Xiaoyu Li, Wenze Liu, Zhaoyang Zhang, Yong Zhang, Ying Shan, Xiangyu Yue  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.18597v1.pdf)  
  Keywords: video editing, Control, video generation, diffusion transformer  
- **[FFA Sora, video generation as fundus fluorescein angiography simulator](https://arxiv.org/abs/2412.17346v1)** (Published: 2024-12-23)  
  Authors: Xinyuan Wu, Lili Wang, Ruoyu Chen, Bowen Liu, Weiyi Zhang, Xi Yang, Yifan Feng, Mingguang He, Danli Shi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.17346v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[Video Diffusion Transformers are In-Context Learners](https://arxiv.org/abs/2412.10783v3)** (Published: 2024-12-14)  
  Authors: Zhengcong Fei, Di Qiu, Debang Li, Changqian Yu, Mingyuan Fan  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.10783v3.pdf) | [![GitHub](https://img.shields.io/github/stars/feizc/Video-In-Context?style=social)](https://github.com/feizc/Video-In-Context)  
  Keywords: Controllable, Control, video generation, diffusion transformer  
- **[LinGen: Towards High-Resolution Minute-Length Text-to-Video Generation with Linear Computational Complexity](https://arxiv.org/abs/2412.09856v1)** (Published: 2024-12-13)  
  Authors: Hongjie Wang, Chih-Yao Ma, Yen-Cheng Liu, Ji Hou, Tao Xu, Jialiang Wang, Felix Juefei-Xu, Yaqiao Luo, Peizhao Zhang, Tingbo Hou, Peter Vajda, Niraj K. Jha, Xiaoliang Dai  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09856v1.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://lineargen.github.io/.)  
  Keywords: video generation, diffusion transformer  
- **[MSC: Multi-Scale Spatio-Temporal Causal Attention for Autoregressive Video Diffusion](https://arxiv.org/abs/2412.09828v1)** (Published: 2024-12-13)  
  Authors: Xunnong Xu, Mengying Cao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09828v1.pdf)  
  Keywords: Control, video generation, diffusion transformer  
- **[From Slow Bidirectional to Fast Autoregressive Video Diffusion Models](https://arxiv.org/abs/2412.07772v2)** (Published: 2024-12-10)  
  Authors: Tianwei Yin, Qiang Zhang, Richard Zhang, William T. Freeman, Fredo Durand, Eli Shechtman, Xun Huang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07772v2.pdf)  
  Keywords: video generation, diffusion transformer  
- **[STIV: Scalable Text and Image Conditioned Video Generation](https://arxiv.org/abs/2412.07730v1)** (Published: 2024-12-10)  
  Authors: Zongyu Lin, Wei Liu, Chen Chen, Jiasen Lu, Wenze Hu, Tsu-Jui Fu, Jesse Allardice, Zhengfeng Lai, Liangchen Song, Bowen Zhang, Cha Chen, Yiran Fei, Yifan Jiang, Lezhi Li, Yizhou Sun, Kai-Wei Chang, Yinfei Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07730v1.pdf)  
  Keywords: video generation, diffusion transformer  
- **[ACDiT: Interpolating Autoregressive Conditional Modeling and Diffusion Transformer](https://arxiv.org/abs/2412.07720v2)** (Published: 2024-12-10)  
  Authors: Jinyi Hu, Shengding Hu, Yuxuan Song, Yufei Huang, Mingxuan Wang, Hao Zhou, Zhiyuan Liu, Wei-Ying Ma, Maosong Sun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07720v2.pdf)  
  Keywords: video generation, diffusion transformer  
- **[FlexDiT: Dynamic Token Density Control for Diffusion Transformer](https://arxiv.org/abs/2412.06028v1)** (Published: 2024-12-08)  
  Authors: Shuning Chang, Pichao Wang, Jiasheng Tang, Yi Yang  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.06028v1.pdf)  
  Keywords: image generation, video generation, Control, text-to-image, diffusion transformer  
- **[MotionStone: Decoupled Motion Intensity Modulation with Diffusion Transformer for Image-to-Video Generation](https://arxiv.org/abs/2412.05848v1)** (Published: 2024-12-08)  
  Authors: Shuwei Shi, Biao Gong, Xi Chen, Dandan Zheng, Shuai Tan, Zizheng Yang, Yuyuan Li, Jingwen He, Kecheng Zheng, Jingdong Chen, Ming Yang, Yinqiang Zheng  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05848v1.pdf)  
  Keywords: Control, video generation, diffusion transformer  
- **[Self-Guidance: Boosting Flow and Diffusion Generation on Their Own](https://arxiv.org/abs/2412.05827v2)** (Published: 2024-12-08)  
  Authors: Tiancheng Li, Weijian Luo, Zhiyang Chen, Liyuan Ma, Guo-Jun Qi  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05827v2.pdf)  
  Keywords: video generation, FLUX, text-to-image  
- **[Mind the Time: Temporally-Controlled Multi-Event Video Generation](https://arxiv.org/abs/2412.05263v2)** (Published: 2024-12-06)  
  Authors: Ziyi Wu, Aliaksandr Siarohin, Willi Menapace, Ivan Skorokhodov, Yuwei Fang, Varnith Chordia, Igor Gilitschenski, Sergey Tulyakov  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.05263v2.pdf)  
  Keywords: Control, video generation, diffusion transformer  
- **[Navigation World Models](https://arxiv.org/abs/2412.03572v1)** (Published: 2024-12-04)  
  Authors: Amir Bar, Gaoyue Zhou, Danny Tran, Trevor Darrell, Yann LeCun  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03572v1.pdf)  
  Keywords: Controllable, Control, video generation, diffusion transformer  
- **[Seeing Beyond Views: Multi-View Driving Scene Video Generation with Holistic Attention](https://arxiv.org/abs/2412.03520v2)** (Published: 2024-12-04)  
  Authors: Hannan Lu, Xiaohe Wu, Shudong Wang, Xiameng Qin, Xinyu Zhang, Junyu Han, Wangmeng Zuo, Ji Tao  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.03520v2.pdf) | [![Project](https://img.shields.io/badge/-Project-blue)](https://luhannan.github.io/CogDrivingPage/.)  
  Keywords: Control, video generation, diffusion transformer  
- **[SyncFlow: Toward Temporally Aligned Joint Audio-Video Generation from Text](https://arxiv.org/abs/2412.15220v1)** (Published: 2024-12-03)  
  Authors: Haohe Liu, Gael Le Lan, Xinhao Mei, Zhaoheng Ni, Anurag Kumar, Varun Nagaraja, Wenwu Wang, Mark D. Plumbley, Yangyang Shi, Vikas Chandra  
  Links: [![PDF](https://img.shields.io/badge/PDF-arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.15220v1.pdf)  
  Keywords: video generation  



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
