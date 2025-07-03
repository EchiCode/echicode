# 👀 Welcome to the Hentai Dev Zone

Making the internet safe for degenerates — one embedding at a time.  
I build high-performance, privacy-first NSFW tools that run entirely in your browser. No servers. No leaks. No shame.

---

### 💻 Featured Project

- 🔍 **[Reverse Hentai Search](https://github.com/echicode/reverse-hentai-search)**  
  Drop in a hentai image, get the source.  
  Powered by CLIP embeddings, client-side clustering, and lazy metadata loading.  
  Everything runs **locally** — your kinks never leave your machine.

---

### 🧠 Tech Highlights

- **CLIP-only pipeline**  
  Embeddings generated via `clip-vit-base-patch32` in ONNX format using Xenova in-browser.  
  Exact match with Python-side embedding generation for offline tools and dataset prep.

- **Client-side clustering**  
  Cluster centroids precomputed offline. In-browser search first narrows results to top clusters before computing exact distances. Scales to 100k+ entries, even on weak hardware.

- **Lazy metadata system**  
  Metadata is stored in compressed chunks and loaded only when needed. Designed for scale and snappy UX.

- **Zero data leakage**  
  No network requests during search. Nothing is sent, nothing is logged, nothing is saved.

---

### 🛠 Stack

- Browser: TypeScript, React, WebAssembly, ONNX, Xenova Transformers  
- Offline tools: Python, faiss / scikit-learn, CLIP embedding generator, cluster builder  
- Search logic: pure vector similarity over clustered CLIP embeddings

---

### ✨ Philosophy

- 🍑 NSFW is not a second-class citizen  
- 🕶️ Privacy is default — not a feature  
- ⚡ Build fast enough that no one misses the server

---

### 💌 Want to simp, collab, or support?

Star the repo, open an issue, or [buy me a coffee](https://www.buymeacoffee.com/echicode) ☕

---

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=echicode&show_icons=true&theme=tokyonight)
