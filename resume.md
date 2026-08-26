# Ilya Eliseev

## Contact Information

Email: 3mptinessy@gmail.com  
Telegram: @empyempt  

## Professional Summary

Senior ML Engineer specializing in Computer Vision, Multimodal, and LLM-agent systems. Built and shipped the world's first AI judging system for rhythmic gymnastics — deployed live at an international competition in Beijing. I don't just build models; I own outcomes: from research and training through optimization, MLOps, backend, frontend, and production deployment including mainland China. 4+ years turning hard problems into working systems.

## Key skills

- Core ML & Vision: 2D/3D pose, tracking, action/temporal recognition, keypoints, motion analysis, video understanding at scale; camera calibration, homography & multi-view geometry; multimodal (video + audio + VLM), alignment, captioning
- LLM & Agents: production agentic systems, tool use, multi-provider routing (Anthropic, OpenRouter), per-task model selection, cost tracking
- Modeling & Training: PyTorch, DDP/FSDP multi-node, distillation, quantization, TensorRT, ONNX Runtime
- GPU & Performance: CUDA, latency/throughput tuning, NVENC/NVDEC
- Inference & MLOps: Triton, FastAPI/gRPC, batch/streaming pipelines, Airflow, Docker, CI/CD, DVC, ClearML/W&B
- Streaming & Media: ffmpeg, RTSP/RTMP/SRT/NDI/WebRTC, Kafka, NATS, Redis, Nginx
- Backend & Systems: FastAPI, PostgreSQL, Redis, OAuth2/JWT; production deployment including mainland China
- Frontend & Mobile: JavaScript, Dart/Flutter — full delivery from ML pipeline to user-facing product
- Data & Storage: PostgreSQL, ClickHouse, Milvus/Vector DBs, data versioning, curation, labeling ops
- Languages: Python (primary), C++, Dart, JS, Bash
- Leadership: team lead, mentorship, stakeholder comms, live-ops readiness

---

## Experience

***4+ Years of experience in the field***

### *Lead Machine Learning & Full-Stack Engineer* at Sber AI

*(August 2024 – Present)*

- Built and shipped the **world's first AI-assisted judging system for rhythmic gymnastics**, deployed live at Sky Grace Cup (Beijing, November 2025) — the first time in the history of the sport that AI-based judging was introduced at an international competition.
- Architected a near real-time multimodal pipeline integrating ~12 SOTA models across video, audio, and vision-language modalities; system detects deductions with 80% retrospective validation rate from professional judges — in a domain with no ground truth and ~30% inter-rater consistency between human judges.
- Owned full stack end-to-end: ML research → training → optimization → MLOps → backend → web frontend → production deployment. Built and shipped what a 3-person IT team couldn't deliver in 2 weeks, in under 3 days.
- Navigated mainland China deployment including network isolation, infrastructure constraints, and compliance requirements — production ML deployment in this environment is a known hard problem.
- Advanced a production football video-analytics pipeline: ball tracking and 3D ball-height estimation, plus a panoramic camera auto-calibration stage (~14× projection error reduction) shipped as a pipeline plugin; corrected previously published accuracy figures through rigorous re-evaluation.
- Orchestrated multi-GPU video processing at scale: Airflow DAGs for transcoding and roster automation over ClickHouse/NATS-backed pipelines.
- Designed and shipped LLM-agent systems in production: an AI-collaborative choreography-generation product (multi-provider Anthropic/OpenRouter routing with per-task model selection and cost tracking; backend covered by 1,000+ tests) and an autonomous GitLab MR-review agent providing team-wide code review.
- Led a team of 4, managed stakeholder communication, and maintained live-ops readiness throughout active competition season.

### *Middle Machine Learning Engineer* at Nanosemantics

*(April 2023 – August 2024)*

- Trained and deployed a SOTA person identification pipeline (based on face recognition)
- Created SOTA Russian sign language recognition and Russian lip reading models running real-time on mobile devices
- Extended and upgraded CV functionality in existing products (tracking, identification, embedding search)
- Implemented video captioning in Russian under highly constrained resources and initially low-quality data
- Drove internal process and code-quality improvements

### *Data Scientist* at Ulyanovsk State University

*(September 2021 – February 2022)*

- Created an AI-assisted video surveillance system
- [Contributed to a research paper on anemia (ML + analysis of tabular data — presence/absence of antigens)](https://github.com/EmpyEmpt/Anemia-modeling)
- Implemented a recommendation system offering relevant campus activities to students
- Created a data mart of students' records spanning over 10 years
- Delivered several lectures on machine learning

### *Teacher/Mentor* at OTUS Online School

*(October 2022 – August 2024)*

- Mentored over 100 students through homework and graduation projects
- Reworked and modernized ML, DL and Computer Vision courses

---

## Fun facts

- Reverse-engineered a commercial Electron sports-video app and shipped a clean-room desktop rebuild (camera-calibration solver included) — macOS/Windows installers used daily by a professional analyst team.

---

## Education

- Master in CS and applied mathematics, 2026, Ulyanovsk State University
- Bachelor in CS and applied mathematics, 2024, Ulyanovsk State University
