# 📦 Atriva AI — Repository Directory

A complete map of all public repositories across both Atriva AI organizations.

---

## Core Platform — [github.com/atriva-ai](https://github.com/atriva-ai)

These repos contain the real implementation code. Submit PRs here.

| Repo | Description | Language | Hardware |
|------|-------------|----------|----------|
| [`ai-inference-ov`](https://github.com/atriva-ai/ai-inference-ov) | FastAPI + OpenVINO inference service (YOLOv8, LPRNet, Vehicle Tracking) | Python | x86 CPU/GPU |
| [`ai-inference-rk3588`](https://github.com/atriva-ai/ai-inference-rk3588) | Inference API for Rockchip RK3588 NPU | Python | RK3588 NPU |
| [`video-pipeline-ffmpeg-x86`](https://github.com/atriva-ai/video-pipeline-ffmpeg-x86) | FFmpeg video decoder + frame extractor for x86 | Python | x86 |
| [`video-pipeline-ffmpeg-rk3588`](https://github.com/atriva-ai/video-pipeline-ffmpeg-rk3588) | FFmpeg video pipeline for Rockchip | Python | RK3588 |
| [`atriva-ai-platform-backend`](https://github.com/atriva-ai/atriva-ai-platform-backend) | Platform API — cameras, zones, analytics (FastAPI + PostgreSQL) | Python | Any |
| [`deepstream-api-jetson`](https://github.com/atriva-ai/deepstream-api-jetson) | DeepStream inference API for Jetson | Python | Jetson |
| [`edge-retail-intelligence`](https://github.com/atriva-ai/edge-retail-intelligence) | Retail intelligence engine based on DeepStream | C++ | Jetson |

---

## Community Hub — [github.com/atriva-ai-community](https://github.com/atriva-ai-community)

These repos contain templates, governance, and onboarding material.

| Repo | Description |
|------|-------------|
| [`community`](https://github.com/atriva-ai-community/community) | Governance, roadmap, contribution guides, issue tracker |
| [`app-template`](https://github.com/atriva-ai-community/app-template) | Reference app template wiring the platform components together |

---

## Platform Architecture

The repos work together as a pipeline:

```
[Camera / RTSP Stream]
        │
        ▼
[video-pipeline-ffmpeg-x86]   ← decodes frames to shared volume
        │
        ▼
[ai-inference-ov]             ← runs inference on frames
        │
        ▼
[atriva-ai-platform-backend]  ← stores results, exposes analytics API
        │
        ▼
[Your App / Dashboard / Agent]
```

See [app-template](https://github.com/atriva-ai-community/app-template) for a working `docker-compose.yml` that wires these together.

---

## Documentation

Full docs for each component are available at [atriva.ai/docs](https://atriva.ai/docs).

*Last updated: April 2026*
