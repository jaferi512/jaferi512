<h1 align="center">Hi, I'm Adnan Haider 👋</h1>
<h3 align="center">ML Researcher in Medical Generative AI · Ex-Senior Software Engineer</h3>

<p align="center">
  <a href="mailto:adnanjaferi512@outlook.com"><img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/adnanjaferi512/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <!-- Add once you have a profile: -->
  <!-- <a href="GOOGLE_SCHOLAR_URL"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"/></a> -->
  <!-- <a href="HUGGINGFACE_URL"><img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/></a> -->
</p>

---

### About me

- 🎓 **Master's researcher** in Computer Science at **UESTC**, Chengdu, China (GPA 3.96/4.00, graduating July 2027)
- 🧠 Working on **few-shot medical image generation** with latent diffusion models, vision-language models and parameter-efficient fine-tuning
- 🛠️ **5 years in industry** as a Senior Software Engineer and App Team Lead, shipping full-stack and mobile products for 20+ clients
- 🎯 My focus: **medical AI that works beyond the paper**, from research to deployed, efficient models
- 🤝 Open to **PhD positions** and **ML engineering / applied research roles** in Europe from 2027

---

### 🔬 Current research

**Contextual Multi-Token Hypergraph Adaptation for Few-Shot Brain MRI Generation**
- A lightweight hypergraph adapter (1.18M params) that refines all CLIP token embeddings to steer Stable Diffusion toward clinical semantics
- Combined with LoRA: **2.78M trainable parameters, 310× fewer** than full fine-tuning
- **~37–40% lower FID** than the textual-inversion baseline on BraTS 2021 (T1, T1CE, T2, FLAIR)
- Synthetic images alone train a classifier to **65.0%** modality accuracy vs. 60.0% from 15 real images per modality
- 📄 Manuscript in preparation · code will be released after publication

---

### 📌 Featured projects

<!-- Replace each placeholder with a real repo link as you publish them. Keep only projects that are finished. -->

| Project | What it shows | Stack |
|---|---|---|
| **HGNN Medical Diffusion** *(coming soon)* | Few-shot MRI generation with a hypergraph adapter + LoRA | PyTorch · Diffusers · CLIP |
| **On-Device Medical Screening App** *(coming soon)* | Compressed model running offline on mobile | React Native · ONNX / Core ML / TFLite |
| [**TB Detection on Chest X-rays**](https://github.com/jaferi512/tb_lung_segmentation_study) | Controlled study: does lung segmentation help TB detection? U-Net (Dice 0.975) + ResNet-18, leakage-free 5-fold CV, DeLong test, Grad-CAM · code for my paper | PyTorch · OpenCV · scikit-learn |
| [**How few labels do you need?**](https://github.com/jaferi512/fewshot-medmnist-benchmark) | Few-shot benchmark on 4 imaging modalities: fine-tuned ResNet-18 vs frozen DINOv2/CLIP vs classical features · paired draws, 95% CIs, 400 runs | PyTorch · Hugging Face · scikit-learn |

---

### 📚 Publications

- **A. Haider**, I. Ullah, S. Hakeem, K. Ali. *Accurate lung segmentation does not improve deep learning detection of tuberculosis on chest radiographs: a controlled U-Net and ResNet-18 study.* Pak J Med Cardiol Rev, 2026. [DOI](https://pakjmcr.com/index.php/1/article/view/1834) · [Code](https://github.com/jaferi512/tb_lung_segmentation_study)
- S. Zheng, W. Zhang, C. Tian, **A. Haider**, et al. *Masked Implicit Neural Representation.* Under review at IEEE Transactions on Industrial Informatics, 2026.
- F. D. Puspitasari, C. Zhang, **A. Haider**, et al. *Sora as a World Model? A Complete Survey on Text-to-Video Generation.* Under review at ACM Computing Surveys, 2026.

---

### ⚙️ Tech stack

**AI & Research**

<p>
  <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,opencv,linux" alt="AI stack"/>
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA"/>
  <img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" alt="LaTeX"/>
</p>

Diffusion models (Stable Diffusion, DDPM) · Vision-language models (CLIP, BLIP, MedSigLIP, MedGemma) · LoRA / PEFT · Graph neural networks · FID, KID, SSIM evaluation

**Software Engineering**

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,react,nodejs,django,graphql,postgres,mysql,docker,aws,git" alt="Software stack"/>
</p>

React Native · Full-stack SaaS · CI/CD · Code review & team leadership

---

### 📊 GitHub stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=jaferi512&hide_border=true" alt="GitHub streak"/>
</p>
