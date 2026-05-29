<h1 align="center">Hi, I'm Muhammad Naeem 👋</h1>

<p align="center">
  <b>AI/ML Engineer · GenAI & LLM Systems · Multimodal AI Researcher</b><br/>
  CS Graduate (Class of 2026) · FAST-NUCES · Data Science & AI Specialization · Dean's Honor List
</p>

<p align="center">
  <a href="mailto:naeemubeen639@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://linkedin.com/in/naeaeaem"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://medium.com/@naeemubeen639"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" /></a>
</p>

---

### About

I build production-ready AI systems that don't just work — they're **explainable**.

My focus is the intersection of **multimodal deep learning**, **explainable AI (XAI)**, and **clinical machine learning**. I'm equally comfortable implementing diffusion models and ViT-MAEs from base PyTorch as I am building hybrid RAG pipelines, fine-tuning vision-language models with QLoRA, or deploying full ML stacks on cloud infrastructure.

I default to agentic coding workflows (Claude Code, Cursor) and ship working v1s fast, then iterate on what actually breaks in real use.

---

### 🚀 Featured Projects

#### 🧠 [NeuroVerse — Multimodal Explainable AI for Neurodegenerative Disease Screening](https://github.com/nemo639) <sub>*(Final Year Thesis)*</sub>

A smartphone-based platform that turns an ordinary phone into a non-invasive screening tool for Alzheimer's and Parkinson's diseases. Fuses speech, cognitive, motor, and facial biomarkers across **five trained deep learning models** with **seven complementary XAI methods** (SHAP, LIME, GradCAM, Integrated Gradients, Counterfactuals, Attention Visualization, Clinical Interpretation) and a **confidence-weighted Bayesian fusion engine**.

- Clock Drawing Test classifier (EfficientNet-B0, 16,926 images): **93% accuracy** on 6-class Shulman scoring
- Spiral PD classifier: **95.5% accuracy, AUC 0.955**
- Meander PD classifier: **91.4% accuracy, AUC 0.971**
- Speech AD risk regression (35 acoustic features, 4,804 samples): **MAE 0.14**
- Stack: PyTorch · Flutter · FastAPI · PostgreSQL/Supabase · Google Cloud Run · Next.js
- **165 automated tests, 100% pass rate** (backend, ML/XAI, mobile, end-to-end)

#### 🔍 [Clinical RAG on MIMIC-IV (DiReCT)](https://github.com/nemo639)

Hybrid retrieval-augmented generation pipeline over 50,000+ MIMIC-IV-Ext clinical records.

- Hybrid retrieval: **BM25 (sparse) + dense FAISS embeddings**
- Generation: Groq LLaMA 3.3 via LangChain
- **89% precision@5** across 200+ RAGAS-evaluated queries (faithfulness + answer relevancy)
- Deployed Streamlit frontend · [Medium write-up](https://medium.com/@naeemubeen639)

#### 📄 [Qwen2-VL Fine-Tuning with QLoRA for Document-to-Markdown](https://github.com/nemo639)

Fine-tuned **Qwen2-VL-2B-Instruct** on the Nougat document dataset for structured image-to-Markdown generation.

- **4-bit NF4 quantization**, frozen base weights, LoRA adapters (rank 8–16)
- ChatML-formatted image-text pairs, gradient accumulation on Kaggle T4×2
- Real-time inference via Gradio app

#### ⚙️ [LLM Fine-Tuning Suite: BERT · GPT-2 · T5 across Three Architectures](https://github.com/nemo639)

Three-architecture transformer fine-tuning study with **LoRA/PEFT** on **4-GPU PyTorch DDP**.

- BERT (encoder-only): 3-class sentiment classification
- GPT-2 (decoder-only): pseudo-code → Python on SPoC
- T5 (encoder-decoder): summarization on CNN/DailyMail
- **~90% reduction in trainable parameters** vs full fine-tuning
- Evaluated with BLEU, CodeBLEU, ROUGE-1/2/L, F1

#### 🎨 [Generative Models from Base PyTorch — DDPM, MAE, GANs](https://github.com/nemo639)

Three generative paradigms implemented from base PyTorch with no pre-trained pipelines.

- **DDPM**: Full diffusion pipeline (forward/reverse, sinusoidal time embeddings, residual U-Net 64→128→256) on CelebA-HQ, FFHQ, WikiArt at 128×128 and 256×256
- **MAE**: Asymmetric Transformer (ViT-Base encoder + ViT-Small decoder) reconstructing 75% masked patches on TinyImageNet 224×224
- **GANs**: DCGAN baseline + WGAN-GP (critic, λ=10 gradient penalty) — comparative mode collapse study

#### 🌐 [Urdu Conversational Transformer (From Scratch)](https://github.com/nemo639)

Transformer encoder-decoder built from base PyTorch for low-resource Urdu conversational generation. Preceded by a BiLSTM Urdu-to-Roman Urdu transliteration system on urdu_ghazals_rekhta. Evaluated with BLEU, ROUGE-L, chrF, perplexity.

---

### 🛠️ Tech Stack

**Machine Learning & Deep Learning**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

**LLMs · RAG · Vision-Language Models**  
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![LoRA](https://img.shields.io/badge/LoRA%2FQLoRA-7C3AED?style=flat-square)
![PEFT](https://img.shields.io/badge/PEFT-FF6F61?style=flat-square)
![RAGAS](https://img.shields.io/badge/RAGAS-2EAD33?style=flat-square)

**Generative & Multimodal**  
![Diffusion](https://img.shields.io/badge/DDPM%2FDiffusion-9333EA?style=flat-square)
![ViT](https://img.shields.io/badge/Vision%20Transformers-1E40AF?style=flat-square)
![GANs](https://img.shields.io/badge/GANs%20%7C%20WGAN--GP-DC2626?style=flat-square)
![Qwen2-VL](https://img.shields.io/badge/Qwen2--VL-6366F1?style=flat-square)

**Engineering & Deployment**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

**Mobile · Cloud · Demos**  
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=flat-square)

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nemo639&theme=dark&hide_border=true&include_all_commits=false&count_private=false" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nemo639&theme=dark&hide_border=true&include_all_commits=false&count_private=false&layout=compact" />
</p>

---

### ✍️ Writing

I publish technical writing on Medium covering retrieval-augmented generation, transformer fine-tuning with PEFT, Urdu NLP, and cloud-distributed Hadoop infrastructure.

📖 [medium.com/@naeemubeen639](https://medium.com/@naeemubeen639)

---

### 📫 Reach Me

I'm available for **AI Engineer / ML Engineer / Applied AI roles** (remote-first or hybrid) and open to research collaborations.

📧 **naeemubeen639@gmail.com**  
🔗 [LinkedIn](https://linkedin.com/in/naeaeaem) · [Medium](https://medium.com/@naeemubeen639)
