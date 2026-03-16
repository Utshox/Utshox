<div align="center">

# Hi, I’m Istiaque (Utshox)

**ML Engineer / Computer Vision · Medical Imaging · Research-to-Engineering**

I like building systems where **experiments turn into reliable code**: solid baselines, clean preprocessing, reproducible training, and verification-focused inference.

**CV / timeline:** https://istiaque.cv

</div>

---

## What I work on (most in-demand areas I’m leaning into)
- **ML Engineering (production mindset):** reproducible pipelines, evaluation, inference, and verification
- **Computer Vision / Segmentation (medical imaging):** resolution-preserving training, label efficiency
- **Applied GenAI (selectively):** RAG + evaluation/quality (when it solves a real workflow)

---

## Engineering velocity & footprint
<div align="center">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Utshox&theme=radical" alt="GitHub Stats" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Utshox&theme=radical" alt="Top Languages" />
</div>

---

## Featured projects

### 🧠 High-Resolution Patch-Based Pancreas Segmentation (v2)
**Domain:** Computer Vision / Healthcare AI  
**Repo:** https://github.com/Utshox/pancreas-segmentation-resolution-study-v2  
**Stack:** Python, TensorFlow/Keras, medical imaging preprocessing, HPC workflow

**What it is:** A patch-based segmentation framework designed to **preserve native CT slice resolution** instead of downsampling away detail.  
**Results (from repo logs/README):**
- Reported **Dice up to ~0.85**, with a verified average **≈ 0.815** on a small test subset
- **Mean Teacher SSL ~0.83 Dice with 50% labeled data**, approaching full-supervision performance

**Why it matters:** In medical segmentation, practical gains often come from “boring” fundamentals done well: **resolution, preprocessing, inference strategy, verification**.

---

### 🧪 Pancreas Segmentation Resolution Study (v1)
**Domain:** Computer Vision / Semi-supervised learning  
**Repo:** https://github.com/Utshox/pancreas-segmentation-resolution-study  
**Stack:** Python, TensorFlow/Keras, NIfTI preprocessing

**Key finding (repo README):**
- **Dice 0.73 → 0.85** by preserving resolution with patching  
- **Mean Teacher (50% labeled): ~0.83 Dice**, outperforming FixMatch in this setting

**Implementation highlights:**
- HU windowing **[-125, 275]** + normalization
- balanced patch sampling (foreground/background)
- sliding-window inference to reconstruct full-resolution predictions

---

### 🔎 Scientific Article Similarity (Semantic Search)
**Domain:** NLP / ML  
**Repo:** https://github.com/Utshox/Machine-Learning-based-Scientific-Article-Similarity-Checking-Research  

A research-oriented prototype for detecting semantic overlap in academic text using **embeddings + similarity** (beyond lexical matching).

---

### 🛒 Symfony eCommerce Pilot (Full-stack)
**Domain:** Web Engineering  
Repo: https://github.com/Utshox/Symfony-E-commerce-  

A portfolio-ready Symfony project demonstrating structured backend architecture, ORM usage, and pragmatic full-stack delivery.

---

## Strengths (what teams hire for)
- **Experiment discipline:** baselines → ablations → verification
- **Data-to-inference ownership:** I don’t stop at training; I care about how results are produced and reproduced
- **Polyglot engineering:** ML + web/product skills when needed (React/TS, Symfony/PHP, SQL)

---

## Open to opportunities
I’m currently open to roles in **ML Engineering / Computer Vision / Research Engineering**.

Best contact: https://istiaque.cv

<sub>Last updated: 2026-03-16</sub>
