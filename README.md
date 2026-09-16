## Lewis Zhao (Luyu Zhao)

CS at NYU '27. I work on **edge AI and embodied systems** — getting multimodal models to run
on hardware that can't afford a cloud round trip.

Most of what I build lands on the same class of device more than once — a Jetson Orin NX pair on a
factory line, a Jetson Orin Nano on a tutor robot.

---

### What I'm working on

**NYU SCENT Lab** · *Software & Embedded Systems Team Lead* — leading a 7-person team building an
offline multimodal assistant for laboratory workflows, running on edge hardware.
*(NYU project under NDA — repository private and details limited.)*

**NYU FAMS Lab** · *HRI Team Lead* — perception stack for a humanoid tutor robot, running
on-device in real time rather than offloaded. Code is public → [`nyu-fams-hri-cv`](https://github.com/liyteku/nyu-fams-hri-cv)

**Publication** — co-author on *Real-World Evaluation of Segmentation–Localization Consistency in
Endoscopic Deep Learning Models*, accepted for **oral presentation** at SPIE Security + Defence
2026. We showed that a U-Net moving from Kvasir-SEG to an unseen CVC-ClinicDB set drops from
0.854 to 0.746 Dice while pointing-game localization holds at 92.3% — boundary precision and
coarse localization fail at different rates, which matters for anything used as clinical guidance.
Code: [`ilayd-a/endoscopy-multitask-guidance`](https://github.com/ilayd-a/endoscopy-multitask-guidance)

---

### Public repositories

| Repo | What it is |
|---|---|
| [**nyu-fams-hri-cv**](https://github.com/liyteku/nyu-fams-hri-cv) | Real-time multimodal perception (expression, gaze, skeleton action) plus a rule-based policy layer driving a humanoid tutor robot. Includes the ST-GCN and MobileNetV3 training pipelines and their results. |
| [**fams-hri-ai-tutor**](https://github.com/liyteku/fams-hri-ai-tutor) | Earlier iteration: a webcam-based engagement monitor (nodding, gaze-away, frowning) that generates a session report via the Gemini API. |
| [**eg-1004-armax**](https://github.com/liyteku/eg-1004-armax) | First-year design project — an Arduino wrist brace for pediatric arm rehab. Kept for the record. |

---

### Tools I reach for

**Edge / robotics** — NVIDIA Jetson · TensorRT · CUDA · NVIDIA VPI · ROS 2 · llama.cpp · 4-bit quantization
**ML / CV** — PyTorch · timm · OpenCV · YOLO · U-Net · ST-GCN · MediaPipe
**Systems** — Python · C/C++ · FastAPI · React · TypeScript · WebSocket · Docker · Linux

---

📍 New York, NY → open to **Hong Kong** and **NYC** from mid-2027
✉️ [lewis.z@nyu.edu](mailto:lewis.z@nyu.edu) · [LinkedIn](https://linkedin.com/in/lewiszhao)
