# Parameter-Efficient Fine-Tuning for Foundation Models

<p align="center">
📃 <a href="https://arxiv.org/abs/2501.13787" target="_blank">[ReST-MCTS*]</a> 
🌐 <a href="https://awesome-peft-for-foundation-models.github.io/" target="_blank">[Website]</a> <br>
</p>

![GitHub stars](https://img.shields.io/github/stars/THUDM/Awesome-Parameter-Efficient-Fine-Tuning-for-Foundation-Models.svg?color=red&style=for-the-badge) 
![GitHub forks](https://img.shields.io/github/forks/THUDM/Awesome-Parameter-Efficient-Fine-Tuning-for-Foundation-Models.svg?style=for-the-badge) 
![GitHub activity](https://img.shields.io/github/last-commit/THUDM/Awesome-Parameter-Efficient-Fine-Tuning-for-Foundation-Models?color=yellow&style=for-the-badge) 
![GitHub issues](https://img.shields.io/github/issues/THUDM/Awesome-Parameter-Efficient-Fine-Tuning-for-Foundation-Models?style=for-the-badge)


## 🔥 <span id="head1"> *News* </span>
* [2025/01/23]  "**Parameter-Efficient Fine-Tuning for Foundation Models**" repo is created.

## 📝 <span id="head1"> *Introduction* </span>
This survey aims to provide a comprehensive overview of PEFT techniques applied to diverse FMs and address critical gaps in understanding the techniques, trends, and applications. This survey provides a valuable resource for both newcomers and experts seeking to understand and use the power of PEFT across FMs.


## 📚 <span id="head1"> *Table of Contents* </span>

<table>

<tr><td><a href="#Selective PEFT">1. Selective PEFT</a></td></tr>
<tr><td><a href="#Additive PEFT">2. Additive PEFT</a></td></tr> 
<tr><td><a href="#Prompt PEFT">3. Prompt PEFT</a></td></tr>
<tr><td><a href="#Reparameterization PEFT">4. Reparameterization PEFT</a></td></tr>
<tr><td><a href="#Hybrid PEFT">5. Hybrid PEFT</a></td></tr>

</table>

## <span id="head1"> *Keywords* </span>
![LLM](https://img.shields.io/badge/LLM-blue) Large Language Model.

![VFM](https://img.shields.io/badge/VFM-green) Vision Foundation Model.

![VLM](https://img.shields.io/badge/VLM-yellow) Vision Language Model.

![VGM](https://img.shields.io/badge/VGM-orange) Visual Content Generation Model.

### [Selective PEFT](#content)

![LLM](https://img.shields.io/badge/LLM-blue)

##### Specific Selection

1. **Revealing the Dark Secrets of BERT**. **EMNLP-IJCNLP 2019**.

   *Olga Kovaleva, Alexey Romanov, Anna Rogers, Anna Rumshisky*

   [[paper]](https://www.aminer.cn/pub/5d63adc33a55ac410be32803/revealing-the-dark-secrets-of-bert)
   [[code]]

2. **BitFit: Simple Parameter-efficient Fine-tuning for Transformer-based Masked Language-models**. **ACL 2022**.

   *Elad Ben-Zaken, Shauli Ravfogel, Yoav Goldberg*

   [[paper]](https://www.aminer.cn/pub/60d1586491e011c16f0cb484/bitfit-simple-parameter-efficient-fine-tuning-for-transformer-based-masked-language-models)
   [[code]]

3. **Parameter-Efficient Tuning with Special Token Adaptation**. **EACL 2023**.

   *Xiaocong Yang, James Y. Huang, Wenxuan Zhou, Muhao Chen*

   [[paper]](https://www.aminer.cn/pub/6392ac4190e50fcafd9f650e/parameter-efficient-tuning-with-special-token-adaptation)
   [[code]](https://github.com/luka-group/PASTA/)

##### Automatic Selection

1. **Masking As an Efficient Alternative to Finetuning for Pretrained Language Models**. **EMNLP 2020.**

   *Mengjie Zhao, Tao Lin, Fei Mi, Martin Jaggi, Hinrich Schutze*

   [[paper]](https://www.aminer.cn/pub/5ea8009091e0111d387ee767/masking-as-an-efficient-alternative-to-finetuning-for-pretrained-language-models)
   [[code]]

2. **AutoFreeze: Automatically Freezing Model Blocks to Accelerate Fine-tuning**. **arXiv 2021**.

   *Yuhan Liu, Saurabh Agarwal, Shivaram Venkataraman*

   [[paper]](https://www.aminer.cn/pub/601a774291e0111e8877d8fd/autofreeze-automatically-freezing-model-blocks-to-accelerate-fine-tuning)
   [[code]]

3. **Parameter-Efficient Transfer Learning with Diff Pruning**. **ACL 2020**.

   *Demi Guo, Alexander M. Rush, Yoon Kim*

   [[paper]](https://www.aminer.cn/pub/5fd8af0f91e0119b22c1f3a8/parameter-efficient-transfer-learning-with-diff-pruning)
   [[code]](https://github.com/dguo98/DiffPruning)

4. **Raise a Child in Large Language Model: Towards Effective and Generalizable Fine-tuning**. **EMNLP 2021**.

   *Runxin Xu, Fuli Luo, Zhiyuan Zhang, Chuanqi Tan, Baobao Chang, Songfang Huang, Fei Huang*

   [[paper]](https://aminer.cn/pub/614012c15244ab9dcb8166d0/raise-a-child-in-large-language-model-towards-effective-and-generalizable-fine)
   [[code]](https://github.com/alibaba/AliceMind/tree/main/ChildTuning)

5. **Training Neural Networks with Fixed Sparse Masks**. **NeurIPS 2021**.

   *Yi-Lin Sung, Varun Nair, Colin Raffel*

   [[paper]](https://www.aminer.cn/pub/619715fd5244ab9dcb185a4d/training-neural-networks-with-fixed-sparse-masks)
   [[code]]

![VFM](https://img.shields.io/badge/VFM-green)

1. **Learning Transferable Visual Models From Natural Language Supervision**. **ICML 2021**.

   *Alec Radford, Jong Wook Kim, Chris Hallacy, Aditya Ramesh, Gabriel Goh, Sandhini Agarwal, Girish Sastry, Amanda Askell, Pamela Mishkin, Jack Clark, Gretchen Krueger, Ilya Sutskever*

   [[paper]](https://www.aminer.cn/pub/603d8d919e795eac93d4c16f/Learning%20Transferable%20Visual%20Models%20From%20Natural%20Language%20Supervision)
   [[code]](https://github.com/OpenAI/CLIP)

2. **Convolutions Die Hard: Open-Vocabulary Segmentation with Single Frozen Convolutional CLIP**. **NeurIPS 2023**.

   *Qihang Yu, Ju He, Xueqing Deng, Xiaohui Shen, Liang-Chieh Chen*

   [[paper]](https://www.aminer.cn/pub/64d074c23fda6d7f06ce9796/Convolutions%20Die%20Hard:%20Open-Vocabulary%20Segmentation%20with%20Single%20Frozen%20%20Convolutional%20CLIP)
   [[code]](https://github.com/bytedance/fc-clip)

![VGM](https://img.shields.io/badge/VGM-orange)

1. **Tune-A-Video: One-Shot Tuning of Image Diffusion Models for Text-to-Video Generation**. **CoRR 2023**.

   *Jay Zhangjie Wu, Yixiao Ge, Xintao Wang, Stan Weixian Lei, Yuchao Gu, Yufei Shi, Wynne Hsu, Ying Shan, Xiaohu Qie, Mike Zheng Shou*

   [[paper]](https://www.aminer.cn/pub/63a51c5d90e50fcafde93c1b/tune-a-video-one-shot-tuning-of-image-diffusion-models-for-text)
   [[code]]

![VLM](https://img.shields.io/badge/VLM-yellow)
1. **Tuning LayerNorm in Attention: Towards Efficient Multi-Modal LLM Finetuning**. **arXiv 2023**.

   *Bingchen Zhao, Haoqin Tu, Chen Wei, Jieru Mei, Cihang Xie*

   [[paper]](https://www.aminer.cn/pub/65824f86939a5f4082a84b8f/Tuning%20LayerNorm%20in%20Attention:%20Towards%20Efficient%20Multi-Modal%20LLM%20%20Finetuning)
   [[code]]


### [Addictive PEFT](#content)

![LLM](https://img.shields.io/badge/LLM-blue)

##### Adapter

1. **Parameter-Efficient Transfer Learning for NLP**. **CoRR 2019**. 

   *Neil Houlsby, Andrei Giurgiu, Stanislaw Jastrzebski, Bruna Morrone, Quentin de Laroussilhe, Andrea Gesmundo, Mona Attariyan, Sylvain Gelly*.

   [[paper]](https://www.aminer.cn/pub/5c61606ae1cd8eae1501e0f5/parameter-efficient-transfer-learning-for-nlp)
   [[code]](https://github.com/google-research/adapter-bert)

2. **AdapterFusion: Non-Destructive Task Composition for Transfer Learning**. **CoRR 2021**.

   *Jonas Pfeiffer, Aishwarya Kamath, Andreas Rueckle, Kyunghyun Cho, Iryna Gurevych*

   [[paper]](https://www.aminer.cn/pub/5eafe7e091e01198d3986605/AdapterFusion:%20Non-Destructive%20Task%20Composition%20for%20Transfer%20Learning)
   [[code]](https://adapterhub.ml/)

3. **AdaMix: Mixture-of-Adaptations for Parameter-efficient Model Tuning**.**EMNLP 2022**.

   *Yaqing Wang, Sahaj Agarwal, Subhabrata Mukherjee, Xiaodong Liu, Jing Gao, Ahmed Hassan Awadallah, Jianfeng Gao*.

   [[paper]](https://www.aminer.cn/pub/628ef0485aee126c0f82d92e/AdaMix:%20Mixture-of-Adaptations%20for%20Parameter-efficient%20Model%20Tuning)
   [[code]](https://aka.ms/AdaMix)

4. **MAD-X: An Adapter-Based Framework for Multi-Task Cross-Lingual Transfer**. **Intelligent Systems In Accounting,
 Finance &Management 2020**. 

   *Pfeiffer Jonas, Vulić Ivan,Gurevych Iryna, Ruder Sebastian*. 
 
   [[paper]](https://www.aminer.cn/pub/5eafe7e091e01198d3986542/mad-x-an-adapter-based-framework-for-multi-task-cross-lingual-transfer)
   [[code]](https://adapterhub.ml/)

5. **BAD-X: Bilingual Adapters Improve Zero-Shot Cross-Lingual Transfer**.**NAACL 2022**.

   *Marinela Parovic, Goran Glavas, Ivan Vulic, Anna Korhonen*.

   [[paper]](https://www.aminer.cn/pub/634d80f190e50fcafd4ef432/bad-x-bilingual-adapters-improve-zero-shot-cross-lingual-transfer)
   [[code]](https://github.com/parovicm/BADX)

6. **AdapterDrop - On the Efficiency of Adapters in Transformers**. **EMNLP 2021**.

   *Andreas Rücklé, Gregor Geigle, Max Glockner, Tilman Beck, Jonas Pfeiffer, Nils Reimers, Iryna Gurevych*.
  
   [[paper]](https://www.aminer.cn/pub/5f92b9db91e011edb3573b95/adapterdrop-on-the-efficiency-of-adapters-in-transformers)
   [[code]]

7. **AdapterBias: Parameter-efficient Token-dependent Representation Shift for Adapters in NLP Tasks**. **NAACL 2022**.

   *Chin-Lun Fu, Zih-Ching Chen, Yun-Ru Lee, Hung-yi Lee*.

   [[paper]](https://www.aminer.cn/pub/62708f615aee126c0fa69008/adapterbias-parameter-efficient-token-dependent-representation-shift-for-adapters-in-nlp-tasks)
   [[code]](https://github.com/Allen0307/AdapterBias)

8. **SparseAdapter: An Easy Approach for Improving the Parameter-Efficiency of Adapters**. **arXiv 2022**.

   *Shwai He, Liang Ding, Daize Dong, Miao Zhang, Dacheng Tao*.

   [[paper]](https://www.aminer.cn/pub/6344dede90e50fcafd24d1cc/sparseadapter-an-easy-approach-for-improving-the-parameter-efficiency-of-adapters)
   [[code]](https://github.com/Shwai-He/SparseAdapter)

9. **LST: Ladder Side-Tuning for Parameter and Memory Efficient Transfer Learning**. **NeurIPS 2022**.

   *Yi-Lin Sung, Jaemin Cho, Mohit Bansal*. 

   [[paper]](https://www.aminer.cn/pub/62a94e065aee126c0f9c02cd/lst-ladder-side-tuning-for-parameter-and-memory-efficient-transfer-learning)
   [[code]](https://github.com/ylsung/Ladder-Side-Tuning)

![VFM](https://img.shields.io/badge/VFM-green)

1. **Convolutional Bypasses Are Better Vision Transformer Adapters**. **arXiv 2022**.

   *Shibo Jie, Zhi-Hong Deng*

   [[paper]](https://www.aminer.cn/pub/62d0db155aee126c0f9f10a4/Convolutional%20Bypasses%20Are%20Better%20Vision%20Transformer%20Adapters)
   [[code]](https://github.com/JieShibo/PETL-ViT)

2. **AdaptFormer: Adapting Vision Transformers for Scalable Visual Recognition**. **NeurIPS 2022**.

   *Shoufa Chen, Chongjian Ge, Zhan Tong, Jiangliu Wang, Yibing Song, Jue Wang, Ping Luo*

   [[paper]](https://www.aminer.cn/pub/629041ac5aee126c0fb5dbce/AdaptFormer:%20Adapting%20Vision%20Transformers%20for%20Scalable%20Visual%20%20Recognition)
   [[code]](https://github.com/ShoufaChen/AdaptFormer)
   
3. **Vision Transformer Adapter for Dense Predictions**. **ICLR 2023**.

   *Zhe Chen, Yuchen Duan, Wenhai Wang, Junjun He, Tong Lu, Jifeng Dai, Yu Qiao*

   [[paper]](https://www.aminer.cn/pub/628464665aee126c0facb311/Vision%20Transformer%20Adapter%20for%20Dense%20Predictions)
   [[code]](https://github.com/czczup/ViT-Adapter)
   
4. **Side Adapter Network for Open-Vocabulary Semantic Segmentation**. **CVPR 2023**.

   *Mengde Xu, Zheng Zhang, Fangyun Wei, Han Hu, Xiang Bai*

   [[paper]](https://www.aminer.cn/pub/63f82b2b90e50fcafd05a1ab/Side%20Adapter%20Network%20for%20Open-Vocabulary%20Semantic%20Segmentation)
   [[code]](https://github.com/MendelXu/SAN)
   
5. **DTL: Disentangled Transfer Learning for Visual Recognition**. **AAAI 2024**.

   *Minghao Fu, Ke Zhu, Jianxin Wu*

   [[paper]](https://www.aminer.cn/pub/657a6a77939a5f4082cf3c41/dtl-disentangled-transfer-learning-for-visual-recognition)
   [[code]](https://github.com/heekhero/DTL)
   

![VGM](https://img.shields.io/badge/VGM-orange)

1. **T2I-Adapter: Learning Adapters to Dig out More Controllable Ability for Text-to-Image Diffusion Models**. **AAAI 2024**.

   *Chong Mou, Xintao Wang, Liangbin Xie, Yanze Wu, Jian Zhang, Zhongang Qi, Ying Shan*

   [[paper]](https://www.aminer.cn/pub/63eef09d90e50fcafda0d7ce/t-i-adapter-learning-adapters-to-dig-out-more-controllable-ability-for)
   [[code]](https://github.com/TencentARC/T2I-Adapter)
   

2. **IP-Adapter: Text Compatible Image Prompt Adapter for Text-to-Image Diffusion Models**. **arXiv 2023**.

   *Hu Ye, Jun Zhang, Sibo Liu, Xiao Han, Wei Yang*

   [[paper]](https://www.aminer.cn/pub/64dafb293fda6d7f064e2c15/ip-adapter-text-compatible-image-prompt-adapter-for-text-to-image-diffusion)
   [[code]](https://ip-adapter.github.io/)
   
3. **I2V-Adapter: A General Image-to-Video Adapter for Diffusion Models**. **SIGGRAPH 2024**.

   *Xun Guo, Mingwu Zheng, Liang Hou, Yuan Gao, Yufan Deng, Pengfei Wan, Di Zhang, Yufan Liu, Weiming Hu, Zhengjun Zha, Haibin Huang, Chongyang Ma*

   [[paper]](https://www.aminer.cn/pub/658e4adb939a5f4082dbe437/I2V-Adapter:%20A%20General%20Image-to-Video%20Adapter%20for%20Diffusion%20Models)
   [[code]]()
   
4. **Adding Conditional Control to Text-to-Image Diffusion Models**. **ICCV 2023**.

   *Lvmin Zhang, Anyi Rao, Maneesh Agrawala*

   [[paper]](https://www.aminer.cn/pub/63eafbd690e50fcafd813ef7/Adding%20Conditional%20Control%20to%20Text-to-Image%20Diffusion%20Models)
   [[code]](https://github.com/lllyasviel/ControlNet)
   
5. **ControlNeXt: Powerful and Efficient Control for Image and Video Generation**. **arXiv 2024**.

   *Bohao Peng, Jian Wang, Yuechen Zhang, Wenbo Li, Ming-Chang Yang, Jiaya Jia*

   [[paper]](https://www.aminer.cn/pub/66bac1ca01d2a3fbfcd437ed/ControlNeXt:%20Powerful%20and%20Efficient%20Control%20for%20Image%20and%20Video%20Generation)
   [[code]](https://github.com/dvlab-research/ControlNeXt)
   

![VLM](https://img.shields.io/badge/VLM-yellow)

1. **LLaMA-Adapter: Efficient Fine-tuning of Language Models with Zero-init Attention**. **CVPR 2023**.

   *Renrui Zhang, Jiaming Han, Chris Liu, Peng Gao, Aojun Zhou, Xiangfei Hu, Shilin Yan, Pan Lu, Hongsheng Li, Yu Qiao*

   [[paper]](https://www.aminer.cn/pub/6423ac7890e50fcafd55f26b/LLaMA-Adapter:%20Efficient%20Fine-tuning%20of%20Language%20Models%20with%20Zero-init%20Attention)
   [[code]](https://github.com/OpenGVLab/LLaMA-Adapter)
   
2. **LLaMA-Adapter V2: Parameter-Efficient Visual Instruction Model**. **ICLR 2024**.

   *Peng Gao, Jiaming Han, Renrui Zhang, Ziyi Lin, Shijie Geng, Aojun Zhou, Wei Zhang, Pan Lu, Conghui He, Xiangyu Yue, Hongsheng Li, Yu Qiao*

   [[paper]](https://www.aminer.cn/pub/6456385bd68f896efacf2395/LLaMA-Adapter%20V2:%20Parameter-Efficient%20Visual%20Instruction%20Model)
   [[code]](https://github.com/ZrrSkywalker/LLaMA-Adapter)
   
3. **CLIP-Adapter: Better Vision-Language Models with Feature Adapters**. **IJCV 2024**.

   *Peng Gao, Shijie Geng, Renrui Zhang, Teli Ma, Rongyao Fang, Yongfeng Zhang, Hongsheng Li, Yu Qiao*

   [[paper]](https://www.aminer.cn/pub/6164fcc15244ab9dcb24cfa7/clip-adapter-better-vision-language-models-with-feature-adapters)
   [[code]](https://github.com/gaopengcuhk/CLIP-Adapter)
   
4. **Tip-Adapter: Training-free CLIP-Adapter for Better Vision-Language Modeling**. **ECCV 2022**.

   *Renrui Zhang, Rongyao Fang, Peng Gao, Wei Zhang, Kunchang Li, Jifeng Dai, Yu Qiao, Hongsheng Li*

   [[paper]](https://www.aminer.cn/pub/6189e6d05244ab9dcb76e48f/tip-adapter-training-free-clip-adapter-for-better-vision-language-modeling)
   [[code]](https://github.com/gaopengcuhk/Tip-Adapter)
   


### [Prompt PEFT](#content)

![LLM](https://img.shields.io/badge/LLM-blue)

##### Hard Prompt

1. **Exploiting Cloze Questions for Few-Shot Text Classification and Natural Language Inference**. **EACL 2020**.

   *Timo Schick, Hinrich Schutze*

   [[paper]](https://aminer.cn/pub/5e281dc13a55ac4d187e0b1e/exploiting-cloze-questions-for-few-shot-text-classification-and-natural-language-inference)
   [[code]](https://github.com/timoschick/pet)
   
2. **Cutting Down on Prompts and Parameters: Simple Few-Shot Learning with Language Models**. **ACL 2022**.

   *Robert L. Logan, Ivana Balazevic, Eric Wallace, Fabio Petroni, Sameer Singh, Sebastian Riedel*

   [[paper]](https://www.aminer.cn/pub/60da71c091e0112af847e8c9/cutting-down-on-prompts-and-parameters-simple-few-shot-learning-with-language)
   [[code]]
   
##### AutoPrompt

1. **AutoPrompt: Eliciting Knowledge from Language Models with Automatically Generated Prompts**. **EMNLP 2020**.

   *Taylor Shin, Yasaman Razeghi, Robert L. Logan, Eric Wallace, Sameer Singh*

   [[paper]]()
   [[code]]
   
##### Soft Prompt

1. **Prefix-Tuning: Optimizing Continuous Prompts for Generation**. **ACL 2021**.

   *Xiang Lisa Li, Percy Liang*.
 
   [[paper]](https://www.aminer.cn/pub/5ff4336291e01130648dc2f4/prefix-tuning-optimizing-continuous-prompts-for-generation)
   [[code]]
   
2. **The Power of Scale for Parameter-Efficient Prompt Tuning**. **EMNLP 2021**.

   *Brian Lester, Rami Al-Rfou’, Noah Constant*.
  
   [[paper]](https://www.aminer.cn/pub/607ffd8d91e011772654f712/the-power-of-scale-for-parameter-efficient-prompt-tuning)
   [[code]]
   
3. **GPT Understands, Too**. **CoRR 2024**.

   *Xiao Liu, Yanan Zheng, Zhengxiao Du, Ming Ding, Yujie Qian, Zhilin Yang, Jie Tang*

   [[paper]](https://www.aminer.cn/pub/6054886a91e0116f82f2d77f/GPT%20Understands,%20Too)
   [[code]]
   
4. **Differentiable Prompt Makes Pre-trained Language Models Better Few-shot Learners**. **CoRR 2021**.

   *Ningyu Zhang, Luoqiu Li, Xiang Chen, Shumin Deng, Zhen Bi, Chuanqi Tan, Fei Huang, Huajun Chen*

   [[paper]](https://www.aminer.cn/pub/612d9dd25244ab9dcbdfb33c/differentiable-prompt-makes-pre-trained-language-models-better-few-shot-learners)
   [[code]](https://github.com/zjunlp/DART)
   
5. **Y-Tuning: an Efficient Tuning Paradigm for Large-Scale Pre-Trained Models Via Label Representation Learning**. **Frontiers of Computer Science 2024**.

   *Yitao Liu, Chenxin An, Xipeng Qiu*

   [[paper]](https://www.aminer.cn/pub/621454535aee126c0f2013ca/y-tuning-an-efficient-tuning-paradigm-for-large-scale-pre-trained-models)
   [[code]]
   
6. **PPT: Pre-trained Prompt Tuning for Few-shot Learning**. **ACL 2021**.

   *Yuxian Gu, Xu Han, Zhiyuan Liu, Minlie Huang*

   [[paper]](https://www.aminer.cn/pub/635276ab90e50fcafdb24990/ppt-pre-trained-prompt-tuning-for-few-shot-learning)
   [[code]](https://github.com/thu-coai/PPT)
   
7. **SPoT: Better Frozen Model Adaptation Through Soft Prompt Transfer**. **ACL 2020**.

   *Yuxian Gu, Xu Han, Zhiyuan Liu, Minlie Huang*

   [[paper]](https://www.aminer.cn/pub/616ce5a15244ab9dcbacfc38/spot-better-frozen-model-adaptation-through-soft-prompt-transfer)
   [[code]](https://github.com/google-research/prompt-tuning/tree/main/prompt_tuning/spot)
   
8. **On Transferability of Prompt Tuning for Natural Language Processing**. **NAACL 2022**.

   *Yusheng Su, Xiaozhi Wang, Yujia Qin, Chi-Min Chan, Yankai Lin, Huadong Wang, Kaiyue Wen, Zhiyuan Liu, Peng Li, Juanzi Li, Lei Hou, Maosong Sun, Jie Zhou*

   [[paper]](https://www.aminer.cn/pub/6191cfa05244ab9dcb16be43/on-transferability-of-prompt-tuning-for-natural-language-processing)
   [[code]](https://github.com/thunlp/Prompt-Transferability)
   
![VFM](https://img.shields.io/badge/VFM-green)

1. **Exploring Visual Prompts for Communicating Directional Awareness to Kindergarten Children**. **International journal of human-computer studies 2019**.

   *Vicente Nacher, Sandra Jurdi, Javier Jaen, Fernando Garcia-Sanjuan*

   [[paper]](https://www.aminer.cn/pub/5cd54e7dced107d4c6eb0eb8/exploring-visual-prompts-for-communicating-directional-awareness-to-kindergarten-children)
   [[code]]
   
2. **Visual Prompt Tuning**. **ECCV 2022**.

   *Menglin Jia, Luming Tang, Bor-Chun Chen, Claire Cardie, Serge Belongie, Bharath Hariharan, Ser-Nam Lim*

   [[paper]](https://www.aminer.cn/pub/623be1965aee126c0f37aafc/visual-prompt-tuning)
   [[code]](https://github.com/kmnp/vpt)
   
3. **Diversity-Aware Meta Visual Prompting**. **CVPR 2023**.

   *Qidong Huang, Xiaoyi Dong, Dongdong Chen, Weiming Zhang, Feifei Wang, Gang Hua, Nenghai Yu*

   [[paper]](https://www.aminer.cn/pub/641137ff90e50fcafd17bffc/diversity-aware-meta-visual-prompting)
   [[code]](https://github.com/shikiw/DAM-VP)
   
4. **Understanding and Improving Visual Prompting: A Label-Mapping Perspective**. **CVPR 2023**.

   *Aochuan Chen, Yuguang Yao, Pin-Yu Chen, Yihua Zhang, Sijia Liu*

   [[paper]](https://www.aminer.cn/pub/637c3dd690e50fcafd77ce05/understanding-and-improving-visual-prompting-a-label-mapping-perspective)
   [[code]]
   

5. **Unleashing the Power of Visual Prompting at the Pixel Level**. **CoRR 2022**.

   *Junyang Wu, Xianhang Li, Chen Wei, Huiyu Wang, Alan Yuille, Yuyin Zhou, Cihang Xie*

   [[paper]](https://www.aminer.cn/pub/63a2794d90e50fcafd294622/unleashing-the-power-of-visual-prompting-at-the-pixel-level)
   [[code]](https://github.com/UCSC-VLAA/EVP)
   
6. **LION: Implicit Vision Prompt Tuning**. **AAAI 2024**.

   *Haixin Wang, Jianlong Chang, Yihang Zhai, Xiao Luo, Jinan Sun, Zhouchen Lin, Qi Tian*

   [[paper]](https://aminer.cn/pub/6417d04190e50fcafd83e0dc/LION:%20Implicit%20Vision%20Prompt%20Tuning)
   [[code]]
   
![VGM](https://img.shields.io/badge/VGM-orange)

1. **An Image is Worth One Word: Personalizing Text-to-Image Generation Using Textual Inversion**. **arXiv 2022**.

   *Rinon Gal, Yuval Alaluf, Yuval Atzmon, Or Patashnik, Amit H. Bermano, Gal Chechik, Daniel Cohen-Or*

   [[paper]](https://www.aminer.cn/pub/63d7ae8490e50fcafdad2025/an-image-is-worth-one-word-personalizing-text-to-image-generation-using)
   [[code]](https://textual-inversion.github.io)
   
![VLM](https://img.shields.io/badge/VLM-yellow)

1. **Learning to Prompt for Vision-Language Models**. **IJCV 2022**.

   *Zhou, Kaiyang, Yang, Jingkang, Loy, Chen Change, Liu, Ziwei*

   [[paper]](https://www.aminer.cn/pub/613192dd5244ab9dcb9e5af8/learning-to-prompt-for-vision-language-models)
   [[code]](https://github.com/KaiyangZhou/CoOp)
   
2. **Open-Vocabulary Semantic Segmentation with Mask-adapted CLIP**. **CVPR 2023**.

   *Feng Liang, Bichen Wu, Xiaoliang Dai, Kunpeng Li, Yinan Zhao, Hang Zhang, Peizhao Zhang, Peter Vajda, Diana Marculescu*

   [[paper]](https://www.aminer.cn/pub/6344dede90e50fcafd24d0b0/Open-Vocabulary%20Semantic%20Segmentation%20With%20Mask-Adapted%20CLIP)
   [[code]](https://github.com/facebookresearch/ov-seg)
   
3. **BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models**. **ICML 2023**.

   *Junnan Li, DONGXU LI, Silvio Savarese, Steven Hoi*

   [[paper]](https://www.aminer.cn/pub/64be56873fda6d7f0634f12f/blip-bootstrapping-language-image-pre-training-with-frozen-image-encoders-and-large)
   [[code]](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)
   

### [Reparameterization PEFT](#content)

![LLM](https://img.shields.io/badge/LLM-blue)

1. **LoRA: Low-Rank Adaptation of Large Language Models**. **CoRR 2022**.

   *Edward J. Hu, Yelong Shen, Phillip Wallis, Zeyuan Allen-Zhu, Yuanzhi Li, Shean Wang, Weizhu Chen*

   [[paper]](https://www.aminer.cn/pub/60cdafae91e011329faa2589/lora-low-rank-adaptation-of-large-language-models)
   [[code]](https://github.com/microsoft/LoRA)
   
2. **QLoRA: Efficient Finetuning of Quantized LLMs**. **NeurIPS 2023**.

   *Tim Dettmers, Artidoro Pagnoni, Ari Holtzman, Luke Zettlemoyer*

   [[paper]](https://www.aminer.cn/pub/646d8643d68f896efa0a326e/QLoRA:%20Efficient%20Finetuning%20of%20Quantized%20LLMs)
   [[code]](https://github.com/artidoro/qlora)
   
3. **LoRA-FA: Memory-efficient Low-rank Adaptation for Large Language Models Fine-tuning**. **CoRR 2023**.

   *Longteng Zhang, Lin Zhang, Shaohuai Shi, Xiaowen Chu, Bo Li*

   [[paper]](https://aminer.cn/pub/64f561813fda6d7f06f26c50/lora-fa-memory-efficient-low-rank-adaptation-for-large-language-models-fine)
   [[code]]
   
4. **Delta-LoRA: Fine-Tuning High-Rank Parameters with the Delta of Low-Rank Matrices**. **CoRR 2023**.

   *Bojia Zi, Xianbiao Qi, Lingzhi Wang, Jianan Wang, Kam-Fai Wong, Lei Zhang*

   [[paper]](https://www.aminer.cn/pub/64f7fc433fda6d7f06f42b86/delta-lora-fine-tuning-high-rank-parameters-with-the-delta-of-low)
   [[code]]
   
5. **Enabling Lightweight Fine-tuning for Pre-trained Language Model Compression Based on Matrix Product Operators**. **CoRR 2021**.

   *Peiyu Liu, Ze-Feng Gao, Wayne Xin Zhao, Z. Y. Xie, Zhong-Yi Lu, Ji-Rong Wen*

   [[paper]](https://www.aminer.cn/pub/60bec50591e0118491817782/enabling-lightweight-fine-tuning-for-pre-trained-language-model-compression-based-on)
   [[code]](https://github.com/RUCAIBox/MPOP)
   
![VFM](https://img.shields.io/badge/VFM-green)

1. **1% VS 100%: Parameter-Efficient Low Rank Adapter for Dense Predictions**. **CVPR 2023**.

   *Dongshuo Yin, Yiran Yang, Zhechao Wang, Hongfeng Yu, Kaiwen Wei, Xian Sun*

   [[paper]](https://aminer.cn/pub/6464af57d68f896efa351267/vs-parameter-efficient-low-rank-adapter-for-dense-predictions)
   [[code]]
   
![VGM](https://img.shields.io/badge/VGM-orange)

1. **Navigating Text-To-Image Customization: from LyCORIS Fine-Tuning to Model Evaluation**. **ICLR 2024**.

   *SHIH-YING YEH, Yu-Guan Hsieh, Zhidong Gao, Bernard B W Yang, Giyeong Oh, Yanmin Gong*

   [[paper]](https://www.aminer.cn/pub/65ea8c2a13fb2c6cf630e80e/navigating-text-to-image-customization-from-lycoris-fine-tuning-to-model-evaluation)
   [[code]]
   
2. **DiffuseKronA: A Parameter Efficient Fine-tuning Method for Personalized Diffusion Models**. **CoRR 2024**.

   *Shyam Marjit, Harshit Singh, Nityanand Mathur, Sayak Paul, Chia-Mu Yu, Pin-Yu Chen*

   [[paper]](https://www.aminer.cn/pub/65dea27813fb2c6cf6546431/diffusekrona-a-parameter-efficient-fine-tuning-method-for-personalized-diffusion-models)
   [[code]](https://github.com/IBM/DiffuseKronA)
   
3. **Mix-of-Show: Decentralized Low-Rank Adaptation for Multi-Concept Customization of Diffusion Models**. **CoRR 2023**.

   *Yuchao Gu, Xintao Wang, Jay Zhangjie Wu, Yujun Shi, Yunpeng Chen, Zihan Fan, WUYOU XIAO, Rui Zhao, Shuning Chang, Weijia Wu, Yixiao Ge, Ying Shan, Mike Zheng Shou*

   [[paper]](https://aminer.cn/pub/647572e0d68f896efa7b79a8/mix-of-show-decentralized-low-rank-adaptation-for-multi-concept-customization-of)
   [[code]]
   
4. **Navigating Text-to-Image Generative Bias Across Indic Languages**. **ECCV 2024**.

   *Surbhi Mittal, Arnav Sudan, MAYANK VATSA, RICHA SINGH, Tamar Glaser, Tal Hassner*
   
   [[paper]](https://www.aminer.cn/pub/66ac3e9801d2a3fbfc89a1b9/navigating-text-to-image-generative-bias-across-indic-languages)
   [[code]](https://github.com/KohakuBlueleaf/LyCORIS)
   
5. **Low-Rank Approximation for Sparse Attention in Multi-Modal LLMs**. **CVPR 2024**.

   *Lin Song, Yukang Chen, Shuai Yang, Xiaohan Ding, Yixiao Ge, Ying-Cong Chen, Ying Shan*

   [[paper]](https://www.aminer.cn/pub/66e8c12301d2a3fbfc90f94b/low-rank-approximation-for-sparse-attention-in-multi-modal-llms)
   [[code]]()
   
### [Hybrid PEFT](#content)

![LLM](https://img.shields.io/badge/LLM-blue)

1. **UniPELT: A Unified Framework for Parameter-Efficient Language Model Tuning**. **ACL 2022**.

   *Yuning Mao, Lambert Mathias, Rui Hou, Amjad Almahairi, Hao Ma, Jiawei Han, Wen-tau Yih, Madian Khabsa*

   [[paper]](https://www.aminer.cn/pub/6168f1a35244ab9dcbe2ffa9/unipelt-a-unified-framework-for-parameter-efficient-language-model-tuning)
   [[code]](https://github.com/morningmoni/UniPELT)
   
2. **Compacter: Efficient Low-Rank Hypercomplex Adapter Layers**. **CoRR 2021**.

   *Rabeeh Karimi Mahabadi, James Henderson, Sebastian Ruder*

   [[paper]](https://www.aminer.cn/pub/60c2ec5491e0117e30ca28b5/compacter-efficient-low-rank-hypercomplex-adapter-layers)
   [[code]](https://github.com/rabeehk/compacter)

3. **Towards a Unified View of Parameter-Efficient Transfer Learning**. **CoRR 2022**.

   *Junxian He, Chunting Zhou, Xuezhe Ma, Taylor Berg-Kirkpatrick, Graham Neubig*

   [[paper]](https://www.aminer.cn/pub/6164fcc15244ab9dcb24ce93/towards-a-unified-view-of-parameter-efficient-transfer-learning)
   [[code]](https://github.com/jxhe/unify-parameter-efficient-tuning)
   
4. **Parameter-Efficient Fine-Tuning Design Spaces**. **CoRR 2023**.

   *Jiaao Chen, Aston Zhang, Xingjian Shi, Mu Li, Alex Smola, Diyi Yang*

   [[paper]](https://www.aminer.cn/pub/63dcdb422c26941cf00b63f4/parameter-efficient-fine-tuning-design-spaces)
   [[code]](https://github.com/amazon-science/peft-design-spaces)
   
![VFM](https://img.shields.io/badge/VFM-green)

1. **Neural Prompt Search**. **TPAMI 2024**.

   *Yuanhan Zhang, Kaiyang Zhou, Ziwei Liu*

   [[paper]](https://www.aminer.cn/pub/62a2b6955aee126c0f4d8e7b/neural-prompt-search)
   [[code]](https://github.com/Davidzhangyuanhan/NOAH)
   
![VGM](https://img.shields.io/badge/VGM-orange)

1. **DiffFit: Unlocking Transferability of Large Diffusion Models Via Simple Parameter-Efficient Fine-Tuning**. **ICCV 2023**.

   *Enze Xie, Lewei Yao, Han Shi, Zhili Liu, Daquan Zhou, Zhaoqiang Liu, Jiawei Li, Zhenguo Li*

   [[paper]](https://www.aminer.cn/pub/6438c502d6db87a14654a6d7/difffit-unlocking-transferability-of-large-diffusion-models-via-simple-parameter-efficient-fine)
   [[code]]
   
2. **Towards a Unified View on Visual Parameter-Efficient Transfer Learning**. **CoRR 2022**.

   *Bruce X. B. Yu, Jianlong Chang, Lingbo Liu, Qi Tian, Chang Wen Chen*

   [[paper]](https://www.aminer.cn/pub/633ba44890e50fcafdfe5020/towards-a-unified-view-on-visual-parameter-efficient-transfer-learning)
   [[code]](https://github.com/bruceyo/V-PETL)
   
## Citation

If you find our survey and repository helpful, please kindly cite our paper:

```
@article{zhang2025parameter,
  title={Parameter-Efficient Fine-Tuning for Foundation Models},
  author={Zhang, Dan and Feng, Tao and Xue, Lilong and Wang, Yuandong and Dong, Yuxiao and Tang, Jie},
  journal={arXiv preprint arXiv:2501.13787},
  year={2025}
}
```
