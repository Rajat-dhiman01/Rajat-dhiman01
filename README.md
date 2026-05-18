# Hey, I'm Rajat

Final-year ECE student at GB Pant Engineering College. I got into coding properly about two years ago and haven't really stopped since.

I build full-stack web apps with a heavy lean toward AI integration - not wrappers around ChatGPT, but actual pipelines: retrieval systems, identity-preserving image generation, real-time pricing engines. I also care about shipping things that people actually use. One of my apps is live and serving real customers right now.

Open to **junior full-stack or AI integration roles**. I work in React, Python/FastAPI, and Node - and I'm comfortable going deep on the AI layer.

---

## What I've shipped

**[NotesMind](https://notesmind.pro)** &nbsp;·&nbsp; `FastAPI · FAISS · Groq · React · Vite`

RAG SaaS - upload any PDF, ask questions, get answers grounded strictly in your document. Hybrid retrieval pipeline: FAISS semantic search + BM25 keyword retrieval with score fusion, then cross-encoder reranked (ms-marco-MiniLM-L-6-v2). LLM is Llama 3.1 8B via Groq with real-time SSE token streaming. Google OAuth + demo auth, JWT sessions, rate limiting, security headers, custom domain. Live at notesmind.pro.

**[Yatri Baba](https://yatribaba.com)** &nbsp;·&nbsp; `React · Firebase · OpenAI · Vercel Serverless`

Production taxi booking PWA for a real Himalayan travel business (Rishikesh / Haridwar). Live and handling real bookings. Two-layer AI fare estimation: keyword-matched route lookup across 100+ routes in 7 pickup zones, GPT-4o Mini fallback for anything unrecognized. Real-time admin dashboard via Firestore onSnapshot. All API keys server-side via Vercel functions, full input sanitization, security headers. PWA - installs on Android, opens full-screen.

**[FaceGen](https://github.com/Rajat-dhiman01/facethumb)** &nbsp;·&nbsp; `React · Express · fal.ai · Firebase · Konva.js`

AI YouTube thumbnail generator that preserves your actual face. Upload one photo → background removal (birefnet) → 3 AI-generated backgrounds (Flux Dev) → composite your face onto each → Konva.js canvas editor to drag and style title text. The core problem it solves: generic AI tools generate a different person's face entirely. This one keeps yours. Firebase Auth, rate limiting, Stripe payments in progress.

---

## Stack

**Languages:** JavaScript, Python, C++, HTML/CSS  
**Frontend:** React, Vite, Tailwind CSS, Framer Motion, Next.js  
**Backend:** FastAPI, Node.js/Express, Vercel Serverless Functions  
**AI/ML:** RAG, FAISS, BM25, cross-encoder reranking, sentence-transformers, OpenAI API, Groq, fal.ai  
**Auth & DB:** Firebase Auth + Firestore, Supabase, JWT, Google OAuth  
**DevOps:** Vercel, Railway, Cloudinary, PWA, Git

---

## Currently going deeper on

- Advanced RAG - hybrid retrieval, reranking, agentic flows  
- PDE-based medical image denoising (SRAD + wavelet + Guided Filter for ultrasound speckle)  
- System design fundamentals

---

## A bit more

- 📍  open to remote
- 🎓 ECE @ GB Pant Engineering College (2026)
- 🏭 Interned at THDC India Limited - hydro power station, electro-mechanical dept
- 📬 rkdhiman831@gmail.com
- 💼 [linkedin.com/in/rajatdhiman](https://linkedin.com/in/rajatdhiman)
