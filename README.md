<div align="center">

# Muhammad Naeem

**AI/ML Engineer — GenAI & LLM Systems — Multimodal AI Researcher**

CS Graduate, Class of 2026 · FAST-NUCES · Data Science & AI · Dean's Honor List

[naeemubeen639@gmail.com](mailto:naeemubeen639@gmail.com) · [LinkedIn](https://linkedin.com/in/naeaeaem) · [Medium](https://medium.com/@naeemubeen639)

</div>

<br/>

## About

I build production-ready AI systems that don't just work — they're explainable.

My focus is at the intersection of multimodal deep learning, explainable AI (XAI), and clinical machine learning. I'm comfortable implementing diffusion models and vision transformers from base PyTorch, building hybrid RAG pipelines, fine-tuning vision-language models with QLoRA, and deploying full ML stacks on cloud infrastructure.

I default to agentic coding workflows (Claude Code, Cursor), ship a working v1 fast, then iterate on what actually breaks in real use.

<br/>

## Currently

Available for **AI Engineer / ML Engineer / Applied AI roles** (remote-first or hybrid). Open to research collaborations in multimodal AI, explainability, and clinical ML.

<br/>

## Selected Work

### NeuroVerse — Multimodal Explainable AI for Neurodegenerative Disease Screening
<sub>Final Year Thesis · PyTorch · Flutter · FastAPI · PostgreSQL · Google Cloud Run</sub>

A smartphone-based platform that turns an ordinary phone into a non-invasive screening tool for Alzheimer's and Parkinson's diseases. The system fuses speech, cognitive, motor, and facial biomarkers across five trained deep learning models, with seven complementary XAI methods — SHAP, LIME, GradCAM, Integrated Gradients, Counterfactuals, Attention Visualization, and Clinical Interpretation — combined through a confidence-weighted Bayesian fusion engine with Dempster-Shafer alternatives.

| Component | Result |
|---|---|
| Clock Drawing Test classifier (EfficientNet-B0, 16,926 images) | **93%** accuracy on 6-class Shulman scoring |
| Spiral drawing PD classifier | **95.5%** accuracy · AUC 0.955 |
| Meander drawing PD classifier | **91.4%** accuracy · AUC 0.971 |
| Speech AD risk regression (35 acoustic features, 4,804 samples) | **MAE 0.14** |
| Automated test coverage (backend, ML/XAI, mobile, end-to-end) | **165 tests · 100% pass rate** |

[View repository](https://github.com/nemo639)

<br/>

### Clinical RAG on MIMIC-IV-Ext (DiReCT)
<sub>LangChain · FAISS · BM25 · Groq LLaMA 3.3 · RAGAS · Streamlit</sub>

Hybrid retrieval-augmented generation pipeline over 50,000+ MIMIC-IV-Ext clinical records combining BM25 sparse retrieval with dense FAISS embeddings. Generation via Groq LLaMA 3.3 through LangChain. End-to-end faithfulness and answer relevancy evaluated with RAGAS.

| Metric | Result |
|---|---|
| Precision@5 across 200+ test queries | **89%** |
| Retrieval architecture | Hybrid sparse + dense |
| Frontend | Streamlit · [Medium write-up](https://medium.com/@naeemubeen639) |

[View repository](https://github.com/nemo639)

<br/>

### Vision Language Model Fine-Tuning — Qwen2-VL with QLoRA
<sub>Qwen2-VL-2B-Instruct · QLoRA · 4-bit NF4 · ChatML · PEFT · Gradio</sub>

Fine-tuned the pretrained Qwen2-VL-2B-Instruct multimodal model on the Nougat document dataset using QLoRA — 4-bit NF4 quantization with frozen base weights and lightweight LoRA adapters (rank 8–16) — for structured document-image-to-Markdown generation. Image-text pairs preprocessed into ChatML format, trained on Kaggle T4×2 with gradient accumulation. Real-time inference exposed via Gradio.

[View repository](https://github.com/nemo639)

<br/>

### LLM Fine-Tuning Suite — Three Transformer Architectures
<sub>BERT · GPT-2 · T5 · LoRA · PEFT · PyTorch DDP · 4-GPU</sub>

Comparative parameter-efficient fine-tuning study across all three transformer architectures: encoder-only (BERT for sentiment classification), decoder-only (GPT-2 for pseudo-code to Python generation on SPoC), and encoder-decoder (T5 for summarization on CNN/DailyMail). LoRA/PEFT reduced trainable parameters by approximately **90%** versus full fine-tuning. Benchmarked across 4-GPU PyTorch DDP, evaluated with BLEU, CodeBLEU, ROUGE-1/2/L, and F1.

[View repository](https://github.com/nemo639)

<br/>

### Generative Models from Base PyTorch — DDPM, MAE, GANs
<sub>Diffusion · Vision Transformers · Adversarial · Self-Supervised</sub>

Three generative paradigms implemented end-to-end from base PyTorch layers, with no pre-trained pipelines.

| Model | Implementation |
|---|---|
| **DDPM** | Full diffusion pipeline (forward/reverse process, sinusoidal time embeddings, residual U-Net 64→128→256) on CelebA-HQ, FFHQ, and WikiArt at 128×128 and 256×256 |
| **MAE** | Asymmetric Transformer (ViT-Base encoder + ViT-Small decoder) reconstructing 75% masked patches on TinyImageNet 224×224 |
| **GANs** | DCGAN baseline + WGAN-GP (critic, λ=10 gradient penalty, 5 critic updates per generator step) — comparative mode collapse study |

[View repository](https://github.com/nemo639)

<br/>

### Urdu Conversational Transformer (From Scratch)
<sub>Multi-Head Attention · Positional Encoding · BiLSTM · Seq2Seq</sub>

Transformer encoder-decoder built from base PyTorch — multi-head self-attention, positional encoding, scaled dot-product attention — for low-resource Urdu conversational generation. Preceded by a BiLSTM Urdu-to-Roman Urdu transliteration system on the urdu_ghazals_rekhta dataset. Evaluated with BLEU, ROUGE-L, chrF, and perplexity.

[View repository](https://github.com/nemo639)

<br/>

## Tech Stack

**Machine Learning & Deep Learning**
PyTorch · Hugging Face Transformers · scikit-learn · NumPy · Pandas · Multi-Head Attention · Vision Transformers · U-Net · ResNet · BiLSTM · Multimodal Fusion · SHAP · LIME · Integrated Gradients · GradCAM

**LLMs · RAG · Vision-Language Models**
LangChain · FAISS · BM25 · LoRA · QLoRA · PEFT · 4-bit Quantization · Qwen2-VL · GPT-2 · T5 · BERT · Groq LLaMA 3.3 · RAGAS · Prompt Engineering

**Generative Models**
DDPM · Diffusion · Masked Autoencoders · DCGAN · WGAN-GP · Wasserstein Loss · Gradient Penalty · Self-Supervised Learning

**Engineering & Deployment**
Python · C++ · SQL · Git · REST APIs · FastAPI · Docker · PyTorch DDP · Mixed Precision (AMP) · Google Cloud Run · AWS · PostgreSQL · Supabase · Streamlit · Gradio · Hugging Face Hub · Flutter

**Evaluation Metrics**
BLEU · ROUGE · chrF · F1 · CodeBLEU · PSNR · SSIM · FID · RAGAS Faithfulness · Answer Relevancy · Precision@K

<br/>

## Writing

I publish technical writing on Medium covering retrieval-augmented generation, parameter-efficient fine-tuning, Urdu NLP, and cloud-distributed Hadoop infrastructure.

[medium.com/@naeemubeen639](https://medium.com/@naeemubeen639)

<br/>

<div align="center">
<sub>Open to roles · Open to research conversations · naeemubeen639@gmail.com</sub>
</div>
