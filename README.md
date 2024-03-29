# CL_Anthology

This repository collects a list (non-exhaustive and under-development) of recent **continual learning (CL) papers**, with the intention of providing the reader with a structured overview of the state-of-the-art CL papers divided by the *category* (e.g., rehearsal, regularization, architectural) and the *modality*  (e.g., audio/speech, text/NLP, image/vision) considered in the papers. Given my constant quest to keep up with brand-new papers, I hope this collection can come in handy for other people. 

I would like to include papers that **in my opinion** are compelling and noteworthy, nevertheless any suggestion is warmly appreciated, so if you think a paper is worth being listed here, please let me know!

**Legend**:
- **ARC**: *architectural*-based approach; **REH**: *rehearsal*-based approach; **REG**: *regularization*-based approach.

## CL Surveys

- G. I. Parisi, R. Kemker, J. L. Part, C. Kanan, and S. Wermter, “**Continual lifelong learning with neural networks: A review**,” *Neural Networks*, vol. 113, pp. 54–71, 2019. **[[Paper](https://arxiv.org/abs/1802.07569)**]
- T. Lesort, V. Lomonaco, A. Stoian, D. Maltoni, D. Filliat, and N. Diaz-Rodriguez, "**Continual learning for
robotics: Definition, framework, learning strategies, opportunities and challenges**". *Information Fusion*, 58:52–68, 2020. **[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1566253519307377)]**
- M. De Lange, R. Aljundi, M.Masana, et al., “**A continual learning survey: Defying forgetting in classification tasks**,” *TPAMI*, vol. 44, no. 7, pp. 3366–3385, 2021. **[[Paper](https://arxiv.org/abs/1909.08383)]**
- L. Wang, X. Zhang, H. Su, and J. Zhu. "**A comprehensive survey of continual learning: Theory, method and application**". *arXiv preprint*, 2023. **[[Paper](https://arxiv.org/abs/2302.00487)]**
- D. Zhou, Q. Wang, Z. Qi, H. Ye, D. Zhan, and Z. Liu, "**Deep Class-Incremental Learning: A Survey**
", *arXiv preprint*, 2023. **[[Paper](https://arxiv.org/abs/2302.03648)]**
- Wang, Z., Yang, E., Shen, L. and Huang, H., "**A Comprehensive Survey of Forgetting in Deep Learning Beyond Continual Learning**", *arXiv preprint*, 2023. **[[Paper](https://arxiv.org/abs/2307.09218)]**
- Kilickaya, M., van de Weijer, J. and Asano, "**Towards Label-Efficient Incremental Learning: A Survey**", *arXiv preprint*, 2023. **[[Paper](https://arxiv.org/abs/2302.00353)]**

## CL in Vision

- Wang, K., Herranz, L. and van de Weijer, J., "**Continual learning in cross-modal retrieval**", *CVPR*, 2021. **REG** **[[Paper](https://openaccess.thecvf.com/content/CVPR2021W/CLVision/papers/Wang_Continual_Learning_in_Cross-Modal_Retrieval_CVPRW_2021_paper.pdf)]**
- Wang, Z., Zhang, Z., Lee, C.Y., Zhang, H., Sun, R., Ren, X., Su, G., Perot, V., Dy, J. and Pfister, T., "**Learning to prompt for continual learning**", CVPR, 2022. **ARC** **[[Paper](https://arxiv.org/abs/2112.08654)]**
- Sun, S., Calandriello, D., Hu, H., Li, A. and Titsias, M., "**Information-theoretic online memory selection for continual learning**", *ICLR*, 2022. **REH** **[[Paper](https://arxiv.org/abs/2204.04763)]**
- Boschini, M., Bonicelli, L., Buzzega, P., Porrello, A. and Calderara, S., "**Class-incremental continual learning into the extended der-verse**", *TPAMI*, 2022. **REH + REG** **[[Paper](https://arxiv.org/abs/2201.00766)]**
- Smith, J. and Karlinsky, L. and Gutta, V. and Cascante-Bonilla, P. et al., "**CODA-Prompt: COntinual Decomposed Attention-based Prompting for Rehearsal-Free Continual Learning**", CVPR, 2023. **ARC** **[[Paper](https://arxiv.org/abs/2211.13218)]**
- Jeeveswaran K, Bhat P, Zonooz B, Arani E., "**BiRT: Bio-inspired Replay in Vision Transformers for Continual Learning**", *ICML*, 2023. **REH** + **REG** **[[Paper](https://arxiv.org/abs/2305.04769)]**
- Frascaroli, E., Benaglia, R., Boschini, M., Moschella, L., Fiorini, C., Rodolà, E. and Calderara, S., "**CaSpeR: Latent Spectral Regularization for Continual Learning**", *arxiv preprint*, 2023. **REG** **[[Paper](https://arxiv.org/abs/2301.03345)]**
- Jiang, S., Fang, Y., Zhang, H., Wang, P., Qi, Y. and Liu, Q., "**Teacher Agent: A Non-Knowledge Distillation Method for Rehearsal-based Video Incremental Learning**", *arxiv preprint*, 2023. **REH** + **REG** **[[Paper](https://arxiv.org/pdf/2306.00393.pdf)]**
- S. Paul, L. Frey, R. Kamath, K. Kersting, M. Mundt, "**Masked Autoencoders are Efficient Continual Federated Learners**", *arxiv preprint*, 2023. **REG** **[[Paper](https://arxiv.org/abs/2306.03542)]**
- De Lange, M., van de Ven, G. and Tuytelaars, T., "**Continual evaluation for lifelong learning: Identifying the stability gap**", *ICLR*, 2023. **[[Paper](https://arxiv.org/abs/2205.13452)]**
- Kang, Z., Fini, E., Nabi, M., Ricci, E. and Alahari, K., "**A soft nearest-neighbor framework for continual semi-supervised learning**", *ICCV*, 2023. **REG + REH** **[[Paper](https://arxiv.org/abs/2212.05102)]**
- Yoon, J., Hwang, S.J. and Cao, Y., "**Continual Learners are Incremental Model Generalizers**", *ICML*, 2023. **REG + ARC** **[[Paper](https://arxiv.org/abs/2306.12026)]**
- Zhao, H., Zhou, T., Long, G., Jiang, J. and Zhang, C., "**Does Continual Learning Equally Forget All Parameters?**", *ICML*, 2023. **REH** **[[Paper](https://arxiv.org/pdf/2304.04158.pdf)]**
- Wang, Z., Zhan, Z., Gong, Y., Shao, Y., Ioannidis, S., Wang, Y. and Dy, J., "**DualHSIC: HSIC-Bottleneck and Alignment for Continual Learning**", *ICML*, 2023. **REH + REG** **[[Paper](https://arxiv.org/abs/2305.00380)]**
- Ni, Z., Wei, L., Tang, S., Zhuang, Y. and Tian, Q., "**Continual Vision-Language Representaion Learning with Off-Diagonal Information**", *ICML*, 2023. **REG** **[[Paper](https://arxiv.org/abs/2305.07437)]**
- Hu, Z., Lyu, J., Gao, D. and Vasconcelos, N., **POP: Prompt Of Prompts for Continual Learning**, *arxiv preprint*, 2023. **REH + ARCH** **[[Paper](https://arxiv.org/abs/2306.08200)]**
- Zhai, J.T., Liu, X., Bagdanov, A.D., Li, K. and Cheng, M.M., **Masked Autoencoders are Efficient Class Incremental Learners**, *ICCV*, 2023. **REH + REG** **[[Paper](https://arxiv.org/abs/2308.12510)]**
- Khan, M.G.Z.A., Naeem, M.F., Van Gool, L., Stricker, D., Tombari, F. and Afzal, M.Z., **Introducing Language Guidance in Prompt-based Continual Learning**, *ICCV*, 2023. **ARCH** **[[Paper](https://arxiv.org/abs/2308.15827)]**

### CL for Image Segmentation

- Yang, G., Fini, E., Xu, D., Rota, P., Ding, M., Nabi, M., Alameda-Pineda, X. and Ricci, E., "**Uncertainty-aware contrastive distillation for incremental semantic segmentation**", *TPAMI*, 2022. **REG** **[[Paper](https://ieeexplore.ieee.org/abstract/document/9745778)]** 
- Zhao, D., Yuan, B. and Shi, Z., "**Inherit With Distillation and Evolve With Contrast: Exploring Class Incremental Semantic Segmentation Without Exemplar Memory**", *TPAMI*, 2023. **REG** **[[Paper](https://ieeexplore.ieee.org/document/10120962)]**
- Cermelli, F., Cord, M. and Douillard, A., "**CoMFormer: Continual Learning in Semantic and Panoptic Segmentation**", *CVPR*, 2023. **REG** **[[Paper](https://arxiv.org/abs/2211.13999)]**

## CL for Audio and Speech

- U. Cappellazzo, D. Falavigna, and A. Brutti, "**An Investigation of the Combination of Rehearsal and Knowledge Distillation in Continual Learning for Spoken Language Understanding**", *INTERSPEECH*, 2023. **REH + REG** **[[Paper](https://arxiv.org/abs/2211.08161)]**
- Wang, Z., Subakan, C., Jiang, X., Wu, J., Tzinis, E., Ravanelli, M. and Smaragdis, P., "**Learning Representations for New Sound Classes With Continual Self-Supervised Learning**", *IEEE Signal Processing Letters*, 2023. **REG** **[[Paper](https://arxiv.org/abs/2205.07390)]**
- U. Cappellazzo, M. Yang, D. Falavigna, and A. Brutti, "**Sequence-Level Knowledge Distillation for Class-Incremental End-to-End Spoken Language Understanding**", *INTERSPEECH*, 2023. **REH + REG** **[[Paper](https://arxiv.org/abs/2305.13899)]**
- Jiang, X., Li, Y.A. and Mesgarani, N., "**DeCoR: Defy Knowledge Forgetting by Predicting Earlier Audio Codes**", *INTERSPEECH*, 2023. **REG** **[[Paper](https://arxiv.org/abs/2305.18441)]**
- Diwan, A., Yeh, C.F., Hsu, W.N., Tomasello, P., Choi, E., Harwath, D. and Mohamed, A., "**Continual Learning for On-Device Speech Recognition using Disentangled Conformers**", *ICASSP*, 2023. **ARC** **[[Paper](https://arxiv.org/abs/2212.01393)]**
- Selvaraj, N.M., Guo, X., Kong, A., Shen, B. and Kot, A., **Adapter Incremental Continual Learning of Efficient Audio Spectrogram
Transformers**, *INTERSPEECH*, 2023. **ARC** **[[Paper](https://arxiv.org/abs/2302.14314)]**
- Michieli, U., Parada, P.P. and Ozay, M., "**Online Continual Learning in Keyword Spotting for Low-Resource Devices via Pooling High-Order Temporal Statistics**", *INTERSPEECH*, 2023. **REG** **[[Paper](https://arxiv.org/abs/2307.12660)]**

## CL in NLP

- Cao, Y., Wei, H.R., Chen, B. and Wan, X., "**Continual learning for neural machine translation**", *NAACL-HLT*, 2021. **REG** **[[Paper](https://arxiv.org/pdf/2212.09097.pdf)]**
- A. Razdaibiedina, Y. Mao and R. Hou, M. Khabsa, M. Lewis, and A. Almahairi, "**Progressive prompts: Continual learning for language models**", *ICLR*, 2023. **ARC** **[[Paper](https://arxiv.org/abs/2301.12314)]**
- Ke, Z., Shao, Y., Lin, H., Konishi, T., Kim, G. and Liu, B., "**Continual Pre-training of Language Models**", *ICLR*, 2023. **REG** **[[Paper](https://arxiv.org/abs/2302.03241)]**
- Wang, J., Dong, D., Shou, L., Chen, K. and Chen, G., "**Effective Continual Learning for Text Classification with Lightweight Snapshots**", *AAAI*, 2023. **REG + ARC** **[[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/26206)]**


## CL for Vision-Language

- D. Zhou, Y. Zhang, J. Ning, H. Ye, D. Zhan, and Z. Liu, "**Learning without Forgetting for Vision-Language Models**", *arXiv preprint*, 2023. **ARC** **[[Paper](https://arxiv.org/abs/2305.19270)]**
- He X, Feng W, Fu TJ, Jampani V, Akula A, Narayana P, Basu S, Wang WY, Wang XE, "**Discriminative Diffusion Models as Few-shot Vision and Language Learners**", *arxiv preprint*, 2023. **ARC** **[[Paper](https://arxiv.org/abs/2305.10722)]**

