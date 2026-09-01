# ⚡ Alessio Falanga
### **Software Architect & Systems Engineer**
*Distributed Architectures · Zero-Trust & GDPR-Compliant Systems · Deterministic AI & Vector Search*

[![Website](https://img.shields.io/badge/Portfolio-alessiofalanga.it-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://alessiofalanga.it)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/alessiofalanga)
[![Email](https://img.shields.io/badge/Contact-ciao%40alessiofalanga.it-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ciao@alessiofalanga.it)

---

### ❯ whoami
I design and engineer **resilient, high-concurrency systems** across full-stack cloud runtimes, privacy-critical enterprise platforms, and production Machine Learning pipelines.

I specialize in **turning complex business requirements and strict compliance constraints into deterministic, zero-trust architectures**. Whether it's field-level medical data encryption, sub-millisecond vector similarity search, or offline-first operational platforms, I engineer for reliability, latency, and business continuity.

---

### 🧠 Architectural Principles & Engineering Philosophy

* **🛡️ Zero-Trust & Privacy-by-Design (GDPR/HIPAA):** Security is not a patch at the edge; it is baked into the data layer. Multi-tenant database isolation, application-level **AES-256-GCM field encryption**, strict RBAC authorization boundaries, and immutable audit logs with multi-year retention policies.
* **🎯 Deterministic AI & Strict State Machines:** Generative AI is unreliable without rigorous constraints. I engineer LLM pipelines anchored to **cryptographic source hashes**, strict Pydantic/Zod schemas, automated evaluation gates, and graceful heuristic fallbacks.
* **⚡ Schema-First & Type-Safe Runtimes:** Relational integrity is paramount. I build on PostgreSQL utilizing modern type-safe ORMs (**Drizzle / Prisma**) with optimized compound indexing, automated migration pipelines, and zero-runtime overhead typing.
* **🌐 Edge & Latency-Optimized Architecture:** From high-throughput matrix-vector operations in memory ($L_2$-normalized vector dot-products) to serverless BFFs with custom cookie/session hydration to prevent SSR drops.

---

### 🏗️ Flagship Systems & Architectures

#### 🏥 ** *** - Enterprise Healthcare Management Platform**
> *High-Security Medical Coordination & Clinical Dispatch System*
* **Security & Compliance:** Built a multi-tenant platform complying with strict **GDPR** standards. Implemented **AES-256-GCM encryption** for sensitive clinical and patient records, 2FA/TOTP authentication, and tamper-resistant audit trails with 7-year retention.
* **Access Control & Routing:** Engineered a 5-tier hierarchical **RBAC** (`Superadmin → Admin → Regional Manager → Doctor → Patient`) enforcing strict server-side boundary checks between operational dispatch and clinical diagnosis data.
* **Fintech & Billing:** Integrated **Stripe Split Payments** for real-time commission calculation, partner wallet balances, and automated medical invoice/PDF generation.
* **Stack:** `Nuxt 4` · `PostgreSQL` · `Prisma ORM` · `Stripe API` · `Docker` · `OpenAI Triage`

---

#### 📦 **SoloB2B – Operational B2B Logistics Marketplace**
> *Zero-Trust Circular Inventory Platform for Industrial Professionals*
* **Serverless BFF Architecture:** Engineered a lightweight, ultra-fast B2B procurement platform optimized for job-site mobile devices and warehouse operations.
* **Zero-Drop SSR Auth:** Authored a custom serverless session & cookie parsing layer to eliminate authentication drops across SSR cold-starts.
* **Automated Compliance & AI Pipeline:** Integrated real-time European VAT verification via the **VIES protocol** and engineered an automated catalog parsing engine for complex technical SKUs/EANs.
* **Stack:** `Nuxt 4` · `Drizzle ORM` · `PostgreSQL` · `Gemini 1.5` · `TailwindCSS` · `Serverless`

---

#### ⚡ **Neural Vector Recommender & xAI Microservices**
> *Sub-Millisecond Vector Search & Real-Time Local Explainability*
* **Vector Dot-Product Inference:** Engineered an in-memory semantic discovery engine using HuggingFace Sentence Transformers (`all-MiniLM-L6-v2`, 384-d latent space). Pre-computes $L_2$-normalized embeddings, reducing Cosine Similarity to a single high-throughput vectorized **BLAS dot-product** with hybrid metadata scoring.
* **Real-Time Explainable AI (xAI):** Built a churn prediction service combining **LightGBM** ($>0.83$ ROC-AUC) with **SHAP TreeExplainer**, decomposing risk drivers into per-feature Shapley contributions in $<10\text{ms}$.
* **Production MLOps:** Async FastAPI lifespan handlers, Docker layer weight pre-caching to eliminate cold starts, and 100% test coverage with mock inference services.
* **Stack:** `Python 3.12` · `FastAPI` · `PyTorch` · `LightGBM` · `SHAP` · `Pydantic v2` · `Docker`
* 🔗 [Live Recommender Demo](https://Neural-Recommender-Engine.alessiofalanga.it/docs) · [Live Churn API Demo](https://churn-api.alessiofalanga.it/docs)

---

#### 🏛️ **Parlamento Trasparente – Semantic Open Data & Verifiable AI**
> *Institutional Civic-Tech Platform & Deterministic Summarization Engine*
* **Linked Data Pipeline:** Automated ingestion engine parsing complex institutional Linked Open Data via **SPARQL endpoints** (Camera dei Deputati & Senato) with SQLite local caching and stenographic report alignment.
* **Anti-Hallucination AI Architecture:** Built an automated legislative bill summarization pipeline using Google GenAI, bound to SHA-256 source document hashes for guaranteed auditability, automated cache invalidation, and strict output quality gating.
* **Stack:** `Next.js` · `TypeScript` · `SPARQL / RDF` · `SQLite` · `Google GenAI` · `Docker`

---

### 🛠️ Core Technology Matrix
┌──────────────────────────────┬──────────────────────────────────────────────────────────┐ 
│ Category                     │ Technologies & Frameworks                                │ 
├──────────────────────────────┼──────────────────────────────────────────────────────────┤ 
│ Core & Frameworks            │ TypeScript, Python 3.12, Dart, Nuxt 4 (Vue 3), FastAPI   │ 
│ Data & Storage               │ PostgreSQL, SQLite, Drizzle ORM, Prisma, Supabase        │ 
│ AI, ML & Semantic Search     │ PyTorch, HuggingFace, LightGBM, SHAP, SPARQL, Gemini/GPT │
│ Security & Protocols         │ AES-256-GCM, RBAC, TOTP 2FA, VIES, REST, OpenAPI v3      │ 
│ Cloud, DevOps & Testing      │ Docker, Docker Compose, GitHub Actions CI/CD, Pytest     │ └──────────────────────────────┴──────────────────────────────────────────────────────────┘

---

### 📬 Get In Touch

* **Direct Email:** [ciao@alessiofalanga.it](mailto:ciao@alessiofalanga.it)
* **Engineering Notes & Portfolio:** [alessiofalanga.it](https://alessiofalanga.it)
* **LinkedIn:** [linkedin.com/in/alessiofalanga](https://linkedin.com/in/alessiofalanga)
