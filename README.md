# CL_Anthology

This repository collects a list (non-exhaustive and under-development) of recent **continual learning (CL) papers**, with the intention of providing the reader with a structured overview of the state-of-the-art CL papers divided by the *category* (e.g., rehearsal, regularization, architectural) and the *modality*  (e.g., audio/speech, text/NLP, image/vision) considered in the papers. Given my constant quest to keep up with brand-new papers, I deem this collection can come in handy for other people. 

I would like to include papers that **in my opinion** are compelling and noteworthy, nevertheless any suggestion is warmly appreciated, so if you think a paper is worth being listed here, please let me know!

**Legend**:
- **ARC**: *architectural*-based approach; **REH**: *rehearsal*-based approach; **REG**: *regularization*-based approach.

## CL Surveys

- G. I. Parisi, R. Kemker, J. L. Part, C. Kanan, and S. Wermter, “**Continual lifelong learning with neural networks: A review**,” *Neural Networks*, vol. 113, pp. 54–71, 2019. **[[Paper](https://arxiv.org/abs/1802.07569)**]
- T. Lesort, V. Lomonaco, A. Stoian, D. Maltoni, D. Filliat, and N. Diaz-Rodriguez, "**Continual learning for
robotics: Definition, framework, learning strategies, opportunities and challenges**". *Information Fusion*, 58:52–68, 2020. **[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1566253519307377)]**
- Kilickaya, M., van de Weijer, J. and Asano, "**Towards Label-Efficient Incremental Learning: A Survey**", *arXiv preprint*, 2023. **[[Paper](https://arxiv.org/abs/2302.00353)]**
- M. De Lange, R. Aljundi, M.Masana, et al., “**A continual learning survey: Defying forgetting in classification tasks**,” *TPAMI*, vol. 44, no. 7, pp. 3366–3385, 2021. **[[Paper](https://arxiv.org/abs/1909.08383)]**
- L. Wang, X. Zhang, H. Su, and J. Zhu. "**A comprehensive survey of continual learning: Theory, method and application**". *arXiv preprint*, 2023. **[[Paper](https://arxiv.org/abs/2302.00487)]**
- D. Zhou, Q. Wang, Z. Qi, H. Ye, D. Zhan, and Z. Liu, "**Deep Class-Incremental Learning: A Survey**
", *arXiv preprint*, 2023. **[[Paper](https://arxiv.org/abs/2302.03648)]**

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

### CL for Image Segmentation

- Yang, G., Fini, E., Xu, D., Rota, P., Ding, M., Nabi, M., Alameda-Pineda, X. and Ricci, E., "**Uncertainty-aware contrastive distillation for incremental semantic segmentation**", *TPAMI*, 2022. **REG** **[[Paper](https://ieeexplore.ieee.org/abstract/document/9745778)]** 
- Zhao, D., Yuan, B. and Shi, Z., "**Inherit With Distillation and Evolve With Contrast: Exploring Class Incremental Semantic Segmentation Without Exemplar Memory**", *TPAMI*, 2023. **REG** **[[Paper](https://ieeexplore.ieee.org/document/10120962)]**
- Cermelli, F., Cord, M. and Douillard, A., "**CoMFormer: Continual Learning in Semantic and Panoptic Segmentation**", *CVPR*, 2023. **REG** **[[Paper](https://arxiv.org/abs/2211.13999)]**

## CL for Audio and Speech

- U. Cappellazzo, D. Falavigna, and A. Brutti, "**An Investigation of the Combination of Rehearsal and Knowledge Distillation in Continual Learning for Spoken Language Understanding**", *INTERSPEECH*, 2023. **REH + REG** **[[Paper](https://arxiv.org/abs/2211.08161)]**
- Wang, Z., Subakan, C., Jiang, X., Wu, J., Tzinis, E., Ravanelli, M. and Smaragdis, P., "**Learning Representations for New Sound Classes With Continual Self-Supervised Learning**", *IEEE Signal Processing Letters*, 2023. **REG** **[[Paper](https://arxiv.org/abs/2205.07390)]**
- U. Cappellazzo, M. Yang, D. Falavigna, and A. Brutti, "**Sequence-Level Knowledge Distillation for Class-Incremental End-to-End Spoken Language Understanding**", *INTERSPEECH*, 2023. **REH + REG** **[[Paper](https://arxiv.org/abs/2305.13899)]**

## CL in NLP

- A. Razdaibiedina, Y. Mao and R. Hou, M. Khabsa, M. Lewis, and A. Almahairi, "**Progressive prompts: Continual learning for language models**", *ICLR*, 2023. **ARC** **[[Paper](https://arxiv.org/abs/2301.12314)]**
- Ke, Z., Shao, Y., Lin, H., Konishi, T., Kim, G. and Liu, B., "**Continual Pre-training of Language Models**", *ICLR*, 2023. **REG** **[[Paper](https://arxiv.org/abs/2302.03241)]**


## CL for Vision-Language

- D. Zhou, Y. Zhang, J. Ning, H. Ye, D. Zhan, and Z. Liu, "**Learning without Forgetting for Vision-Language Models**", *arXiv preprint*, 2023. **ARC** **[[Paper](https://arxiv.org/abs/2305.19270)]**
- He X, Feng W, Fu TJ, Jampani V, Akula A, Narayana P, Basu S, Wang WY, Wang XE, "**Discriminative Diffusion Models as Few-shot Vision and Language Learners**", *arxiv preprint*, 2023. **ARC** **[[Paper](https://arxiv.org/abs/2305.10722)]**

