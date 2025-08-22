#  🔍 A Survey on Diffusion Transformers: Models, Applications, and Advances
<p align="center">
     <strong>Lu Zhang</strong> · <strong>Runhao Yang</strong> · <strong>Yunzhi Zhuge</strong> · <strong>Ping Hu</strong> · <strong>Xu Jia</strong> · <strong>Pingping Zhang</strong> · <strong>Dong Wang</strong> · <strong>Huchuan Lu</strong> · <strong>You He</strong>
    </p>
  <p align="center">
    <a href="">
      <img src='https://img.shields.io/badge/Paper-PDF-green?style=flat&logo=arXiv&' alt='arXiv PDF'>
    </a>
  </p>

⭐ Welcome to the official repository of our survey paper. 

💗Please feel free to [open issues](https://github.com/IIAU-ZhangLu/DiT-AllInGen/issues) for any possibly missed wonderful work related to Diffusion Transformers (DiT).


## ✨ Introduction
Our survey provides a comprehensive overview of recent advances in DiT, with a focus on their application across diverse generative tasks.We categorize existing methods by domain, including image generation, video synthesis, 3D content creation, audio generation, and other specialized tasks. 

## 📜 Table of Contents Diagram
<p align="center">
  <img src="figs/survey.png" width="100%">
</p>

## 📷 DiT for Image Generation
In this chapter, we categorize DiT-based image generation methods into four representative task types based on the nature of their input conditions and transformation goals.
|Task Setting  | Year | Venue | Paper Abbr | Paper Title | Highlight | Project/Code |
|--------------|------|-------|------------|-------------|-----------|--------------|
|**Text-to-Image**|2023  |ICCV      |MDTv2       |[Mdtv2: Masked diffusion transformer is a strong image synthesize](https://arxiv.org/abs/2303.14389)|A mask latent modeling scheme to enhance context relation learning|[Code](https://github.com/sail-sg/MDT)|
|     |2023  |ArXiv   |DiffFit       |[DiffFit: Unlocking Transferability of Large Diffusion Models via Simple Parameter-Efficient Fine-Tuning](https://arxiv.org/abs/2304.06648)|Parameter-efficient finetuning via low-rank adaptation of DiT layers|[Code](https://github.com/mkshing/DiffFit-pytorch)|
|     |2024  |ICML   |HDiT    |[Scalable High-Resolution Pixel-Space Image Synthesis with Hourglass Diffusion Transformers](https://arxiv.org/abs/2401.11605)|Hourglass architecture enabling multi-scale context aggregation in DiT|[Project](https://github.com/crowsonkb/k-diffusion)|
|     |2025  | ArXiv  |D²iT      |[D²iT: Dynamic Diffusion Transformer for Accurate Image Generation](https://arxiv.org/abs/2504.09454)|Dynamic VAE and DiT to embed multi-grained latent codes and noises|❌|
|     |2024  | ICML   |SD3     |[Scaling rectified flow transformers for high-resolution image synthesis](https://arxiv.org/abs/2403.03206)|DiT framework for high-fidelity, prompt-aligned image generation|❌|
|     |2024  |    |FLUX     |-|Unified foundation model for scalable and compositional T2I generation|[Code](https://github.com/black-forest-labs/flux)|
|     |2024  | ICLR |DART   |[DART: Denoising Autoregressive Transformer for Scalable Text-to-Image Generation](https://arxiv.org/abs/2410.08159)|Integrating retrogressive decoding into DiT for improved visual consistency|❌|
|     |2024  | ACCV |PSG-Adapter   |[PSG-Adapter: Controllable Planning Scene Graph for Improving Text-to-Image Diffusion](https://openaccess.thecvf.com/content/ACCV2024/papers/Gao_PSG-Adapter_Controllable_Planning_Scene_Graph_for_Improving_Text-to-Image_Diffusion_ACCV_2024_paper.pdf)|Scene graph-conditioned DiT with plug-and-play cross-attention adapters|❌|
|     |2024  | CVPR |TexTok   |[Language-Guided Image Tokenization for Generation](https://arxiv.org/abs/2412.05796)|Text-conditioned tokenization to enhance semantic representation in generation|[Project](https://kaiwenzha.github.io/textok/)|
|     |2024  | NeurIPS |LI-DiT   |[Exploring the Role of Large Language Models in Prompt Encoding for Diffusion Models](https://arxiv.org/abs/2406.11831)|LLM-integrated DiT for language-aware and compositional image synthesis|❌|
|     |2024  | NeurIPS |EvolveDirector   |[EvolveDirector: Approaching Advanced Text-to-Image Generation with Large Vision-Language Models](https://arxiv.org/abs/2410.07133)|Vision-language model-guided DiT with evolutionary prompt planning|[Code](https://github.com/showlab/EvolveDirector)|
|     |2025  | ArXiv |Zuo et al. |[Zero-Shot Subject-Centric Generation for Creative Application Using Entropy Fusion](https://arxiv.org/abs/2503.10697)|Entropy-based fusion for zero-shot subject-centric image generation|❌|
|     |2025  |ICASSP  |DiTPipe   |[Enhancing Image Generation Fidelity via Progressive Prompts](https://arxiv.org/abs/2501.07070)|Region-aware prompt-following generation without extra finetuning|[Code](https://github.com/ZhenXiong-dl/ICASSP2025-RCAC)
|     |2025  |ArXiv  |LDGen   |[LDGen: Enhancing Text-to-Image Synthesis via Large Language Model-Driven Language Representation](https://arxiv.org/abs/2502.18302)|Multilingual T2I enabled by LLM-driven hierarchical text representations|[Project](https://zrealli.github.io/LDGen/)
|**Image-to-Image**|2024  |CVPR  |FoundHand   |[FoundHand: Large-Scale Domain-Specific Learning for Controllable Hand Image Generation](https://arxiv.org/abs/2412.02690)|Domain-specific hand image generation via prompt and geometry control|[Project](https://github.com/arthurchen0518/FoundHand)
|     |2024  |ICML  |MDPT   |[Cross-view Masked Diffusion Transformers for Person Image Synthesis](https://arxiv.org/abs/2402.01516)|Cross-view masked diffusion for pose-guided person image synthesis|[Code](https://github.com/trungpx/xmdpt)
|     |2025  |ArXiv  |U-StyDiT   |[U-StyDiT: Ultra-high Quality Artistic Style Transfer Using Diffusion Transformers](https://arxiv.org/abs/2503.08157)|High-fidelity artistic style transfer with transformer-enhanced latent diffusion|❌|
| **Image-Editing**|2024  |ArXiv |LazyDiffusion|[Lazy Diffusion Transformer for Interactive Image Editing](https://arxiv.org/abs/2404.12382)|Fast interactive editing via mask-aware DiT with context encoder|[Project](https://lazydiffusion.github.io/)|
|     |2024  |CVPR |LayerDecomp |[Generative Image Layer Decomposition with Visual Effects](https://arxiv.org/abs/2411.17864)|Layer-wise RGB-alpha decomposition guided by masks in DiT framework|[Project](https://rayjryang.github.io/LayerDecomp/)|
|     |2024  |ArXiv|FluxSpace |[FluxSpace: Disentangled Semantic Editing in Rectified Flow Transformers](https://arxiv.org/abs/2412.09611)|Semantic disentanglement for localized and subject-consistent editing|[Project](https://fluxspace.github.io/)|
|     |2025  |CVPR|ObjectMover |[ObjectMover: Generative Object Movement with Video Prior](https://arxiv.org/abs/2503.08037)|Unified object manipulation using video-trained DiT with multiple instructions|[Project](https://xinyu-andy.github.io/ObjMover/)|
|     |2024  |ArXiv|DiT4Edit |[DiT4Edit: Diffusion Transformer for Image Editing](https://arxiv.org/abs/2411.03286)|Patch-wise attention control across generation and reconstruction branches|❌|
|     |2025  |ICCV|KV-Edit |[KV-Edit: Training-Free Image Editing for Precise Background Preservation](https://arxiv.org/abs/2502.17363)|Key-Value caching for consistent background preservation during editing|[Project](https://xilluill.github.io/projectpages/KV-Edit/)|
|     |2025  |ArXiv|DCEdit |[DCEdit: Dual-Level Controlled Image Editing via Precisely Localized Semantics](https://arxiv.org/abs/2503.16795)|Semantic localization for dual-level editing at feature and latent scales|❌|
| **Multi-modal Control**|2024  |ArXiv|EMMA |[EMMA: Your Text-to-Image Diffusion Model Can Secretly Accept Multi-Modal Prompts](https://arxiv.org/abs/2406.09162)|Text-image-fusion DiT for human-centric multi-modal generation|[Project](https://tencentqqgylab.github.io/EMMA/)|
|     |2024  |ICCV|InfU|[InfiniteYou: Flexible Photo Recrafting While Preserving Your Identity](https://arxiv.org/abs/2503.16418)|Identity-preserving generation via diffusion-based subject guidance|[Project](https://bytedance.github.io/InfiniteYou/)|
|     |2025  |ArXiv|XVerse |[XVerse: Consistent Multi-Subject Control of Identity and Semantic Attributes via DiT Modulation](https://arxiv.org/abs/2506.21416)|Multi-subject, attribute-controllable generation via token-wise DiT modulation|[Project](https://bytedance.github.io/XVerse/)|
|     |2024  |ICCV|OminiControl |[OminiControl: Minimal and Universal Control for Diffusion Transformer](https://arxiv.org/abs/2411.15098)|A unified image-conditional control generation framework|[Code](https://github.com/Yuanshi9815/OminiControl)|
|     |2025  |ArXiv|OminiControl2 |[OminiControl2: Efficient Conditioning for Diffusion Transformers](https://arxiv.org/abs/2503.08280)|An efficient multi-condition control framework based on Ominicontrol|[Code](https://github.com/Yuanshi9815/OminiControl)|
|     |2025  |ICCV|UniCombine |[UniCombine: Unified Multi-Conditional Combination with Diffusion Transformer](https://arxiv.org/abs/2503.09277)|Unified DiT with LoRA-based attention for multi-condition compositional synthesis|[Code](https://github.com/Xuan-World/UniCombine)|

