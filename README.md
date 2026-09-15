# Hey, I'm Priyanshu 👋

AI/ML engineer who likes the unglamorous half of ML — the part where a model has to actually
run somewhere, at a frame rate, without a GPU. CS grad (JIIT, '26), looking for **AI/ML or SDE roles**.

I grafted an extra detection head onto YOLOv8n to catch 8-pixel pedestrians, wrote ByteTrack from
scratch, and then got the whole thing running in a browser tab with no server at all. That's
roughly my entire personality.

When I'm not at a keyboard: anime, gaming, and losing ranked matches I definitely should've won.

---

### 🧠 What I build

**[The Aerial Guardian](https://github.com/Halok600/The-Aerial-Guardian)** — 🔴 **[live demo, runs in your browser](https://halok600.github.io/The-Aerial-Guardian/)**
Multi-object tracking for drone footage. A custom **YOLOv8n-P2** detector (extra stride-4 head tuned
for 8–16px targets) → OpenCV **ECC** camera-motion compensation → **ByteTrack written from scratch**
(Kalman filter + 3-stage Hungarian IoU association). Trained on VisDrone on a laptop RTX 3050, then
ported detector *and* tracker to **ONNX Runtime Web** — the demo runs client-side, no backend, no signup.
`PyTorch · YOLOv8 · OpenCV · Kalman Filter · ONNX Runtime Web`

**[Enagram.io](https://github.com/Halok600/Enagram.io)** — 🔴 **[live](https://enagram-io.vercel.app)**
A conversational AI agent over your own Gmail, Drive & Calendar. RAG over **Postgres + pgvector**
hybrid search, agent tool-calling for real Calendar CRUD and correctly-threaded Gmail reply drafting,
cross-source entity graph linking, persistent preference memory, behind Google OAuth.
`Next.js · TypeScript · Vercel AI SDK · Gemini · pgvector · NextAuth`

**[WeaponShield AI](https://github.com/Halok600/WeaponShield-AI)** — 🔴 **[live](https://weapon-sheild-ai.vercel.app)**
Real-time weapon detection (Pistol / Rifle / Knife) across CCTV video, static images, and live webcam.
Two-stage fine-tune of YOLOv8s on a merged 31,600-image dataset → **0.833 mAP50**. Dual PyTorch/ONNX
inference engines and K-of-N multi-frame confirmation to kill false alarms.
`YOLOv8 · FastAPI · React · ONNX Runtime · OpenCV`

**[MedFusionAI](https://github.com/Halok600/MedFusionAI)**
CT + MRI brain scan fusion using a hybrid **Transformer-CNN with cross-attention**, trained
unsupervised (no ground-truth fused images). Sobel edge-preservation module, 4-term loss
(intensity + gradient + SSIM + perceptual), evaluated on 12+ metrics.
`PyTorch · Transformers · Streamlit`

**[Drone Tilt TinyML](https://github.com/Halok600/Drone-Internship)**
A neural net small enough to live on a microcontroller. TFLite classifier trained on **MPU6050**
accelerometer + gyro data, quantised and converted to a C byte array for on-device use, alongside
**ESP32-S3** firmware running a complementary filter (α = 0.96) that fuses accel-derived roll/pitch
with integrated gyro rates for real-time attitude estimation. Built during the India Space Lab
summer training program.
`TensorFlow Lite · C++ · ESP32-S3 · Sensor Fusion · Wokwi`

**[DSA_HOTS](https://github.com/Halok600/DSA_HOTS)** — 600+ LeetCode problems, solved topic-wise, in C++.

---

### 📊 The DSA half

**603 solved** · 216 Easy / 317 Medium / **70 Hard** · contest rating **1533** (top 36%) over 11 contests

I like algorithms more than is strictly reasonable.

---

### 🛠 Stack

**ML:** PyTorch · YOLOv8 / Ultralytics · OpenCV · Transformers · ONNX Runtime · RAG + pgvector · LLM APIs (Gemini)
**Backend:** FastAPI · Node.js · Express · PostgreSQL · MongoDB · Redis · Docker
**Frontend:** Next.js · React · TypeScript · Tailwind
**Core:** Python · C++ · Java · Data Structures & Algorithms

---

### 🚧 Currently building

**LeetCoach** — an AI coach that reads your actual LeetCode history and tells you which problems
you'd fail if you saw them again. Pattern auto-tagging, embedding-based weakness detection, spaced
repetition. Building it in public — follow along on [LinkedIn](https://www.linkedin.com/in/priyanshu-halok600/).

---

### 📬 Reach me

[LinkedIn](https://www.linkedin.com/in/priyanshu-halok600/) · **pkt.codes@gmail.com** · Open to remote / relocation

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Halok600&show_icons=true&theme=default&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Halok600&layout=compact&hide_border=true)
