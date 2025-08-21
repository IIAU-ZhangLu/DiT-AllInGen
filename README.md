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
|**Text-to-Image**|2023  |ICCV      |MDTv2       |[Mdtv2: Masked diffusion transformer is a strong image synthesize](https://arxiv.org/abs/2303.14389)|A mask latent modeling scheme to enhance context relation learning|[code](https://github.com/sail-sg/MDT)|
|     |2023  |ArXiv   |DiffFit       |[DiffFit: Unlocking Transferability of Large Diffusion Models via Simple Parameter-Efficient Fine-Tuning](https://arxiv.org/abs/2304.06648)|Parameter-efficient finetuning via low-rank adaptation of DiT layers|[code](https://github.com/mkshing/DiffFit-pytorch)|
|     |2024  |ICML   |HDiT    |[Scalable High-Resolution Pixel-Space Image Synthesis with Hourglass Diffusion Transformers](https://arxiv.org/abs/2401.11605)|Hourglass architecture enabling multi-scale context aggregation in DiT|[code](https://github.com/crowsonkb/k-diffusion)|
|     |2025  | ArXiv  |D²iT      |[D²iT: Dynamic Diffusion Transformer for Accurate Image Generation](https://arxiv.org/abs/2504.09454)|Dynamic VAE and DiT to embed multi-grained latent codes and noises|❌|
|     |2024  | ICML   |SD3     |[Scaling rectified flow transformers for high-resolution image synthesis](https://arxiv.org/abs/2403.03206)|DiT framework for high-fidelity, prompt-aligned image generation|❌|
|     |2024  |    |FLUX     |-|Unified foundation model for scalable and compositional T2I generation|[code](https://github.com/black-forest-labs/flux)|
|     |2024  | ICLR |DART   |[DART: Denoising Autoregressive Transformer for Scalable Text-to-Image Generation](https://arxiv.org/abs/2410.08159)|Integrating retrogressive decoding into DiT for improved visual consistency|[code](https://github.com/black-forest-labs/flux)|
|     |2024  | ACCV |PSG-Adapter   |[PSG-Adapter: Controllable Planning Scene Graph for Improving Text-to-Image Diffusion](https://openaccess.thecvf.com/content/ACCV2024/papers/Gao_PSG-Adapter_Controllable_Planning_Scene_Graph_for_Improving_Text-to-Image_Diffusion_ACCV_2024_paper.pdf)|Scene graph-conditioned DiT with plug-and-play cross-attention adapters|❌|
|     |2024  | CVPR |TexTok   |[Language-Guided Image Tokenization for Generation](https://arxiv.org/abs/2412.05796)|Text-conditioned tokenization to enhance semantic representation in generation|[code](https://kaiwenzha.github.io/textok/)|
|     |2024  | NeurIPS |LI-DiT   |[Exploring the Role of Large Language Models in Prompt Encoding for Diffusion Models](https://arxiv.org/abs/2406.11831)|LLM-integrated DiT for language-aware and compositional image synthesis|❌|
| **Image-to-Image**|2023  |       |DiffFit       |[DiffFit: Unlocking Transferability of Large Diffusion Models via Simple Parameter-Efficient Fine-Tuning](https://arxiv.org/abs/2304.06648)|Parameter-efficient finetuning via low-rank adaptation of DiT layers|[code](https://github.com/mkshing/DiffFit-pytorch)|
|     |2023  |       |DiffFit       |[DiffFit: Unlocking Transferability of Large Diffusion Models via Simple Parameter-Efficient Fine-Tuning](https://arxiv.org/abs/2304.06648)|Parameter-efficient finetuning via low-rank adaptation of DiT layers|[code](https://github.com/mkshing/DiffFit-pytorch)|
|     |2023  |       |DiffFit       |[DiffFit: Unlocking Transferability of Large Diffusion Models via Simple Parameter-Efficient Fine-Tuning](https://arxiv.org/abs/2304.06648)|Parameter-efficient finetuning via low-rank adaptation of DiT layers|[code](https://github.com/mkshing/DiffFit-pytorch)|
|     |2023  |       |DiffFit       |[DiffFit: Unlocking Transferability of Large Diffusion Models via Simple Parameter-Efficient Fine-Tuning](https://arxiv.org/abs/2304.06648)|Parameter-efficient finetuning via low-rank adaptation of DiT layers|[code](https://github.com/mkshing/DiffFit-pytorch)|

