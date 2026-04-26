<!-- Licensed under the Apache License, Version 2.0 (see LICENSE) -->

# 🛠️ Contributing to Atriva AI Community

Thank you for your interest in contributing!  
Our goal is to make **Edge AI product development** approachable for everyone — from recent graduates to experienced engineers.

We welcome all contributions, large or small.  
Whether it's fixing a typo, adding a new feature, or proposing a new example project, your input helps the entire community grow.

---

## 📦 Where the Code Lives

Atriva AI uses two GitHub organizations:

| Org | What's Here | How to Contribute |
|-----|-------------|-------------------|
| [atriva-ai](https://github.com/atriva-ai) | Core implementation repos (inference, video pipeline, platform API) | Fork repo → submit PR |
| [atriva-ai-community](https://github.com/atriva-ai-community) | Templates, examples, governance, onboarding | Fork repo → submit PR |

### Core Repos — submit PRs to `atriva-ai` org

| Repo | Description | Hardware |
|------|-------------|----------|
| [`ai-inference-ov`](https://github.com/atriva-ai/ai-inference-ov) | OpenVINO inference service (YOLOv8, LPRNet, Vehicle Tracking) | x86 CPU/GPU |
| [`ai-inference-rk3588`](https://github.com/atriva-ai/ai-inference-rk3588) | Inference API for Rockchip RK3588 NPU | RK3588 |
| [`video-pipeline-ffmpeg-x86`](https://github.com/atriva-ai/video-pipeline-ffmpeg-x86) | FFmpeg video decoder + frame extractor | x86 |
| [`video-pipeline-ffmpeg-rk3588`](https://github.com/atriva-ai/video-pipeline-ffmpeg-rk3588) | FFmpeg video pipeline for Rockchip | RK3588 |
| [`atriva-ai-platform-backend`](https://github.com/atriva-ai/atriva-ai-platform-backend) | Platform API (cameras, zones, analytics) | Any |
| [`deepstream-api-jetson`](https://github.com/atriva-ai/deepstream-api-jetson) | DeepStream inference API for Jetson | Jetson |

---

## 💡 Ways to Contribute

| Type | Examples |
|------|-----------|
| 🧩 **Code Contributions** | Improve modules, fix bugs, add new hardware backends |
| 📝 **Documentation** | Add tutorials, improve READMEs, create setup guides |
| 🎨 **UI/UX Contributions** | Improve front-end or dashboard experience |
| 📦 **Product Examples** | Build end-to-end demos for edge vision applications |
| 💬 **Community Engagement** | Review PRs, answer Discussions, mentor new devs |

---

## 🚀 Getting Started

1. **Fork** the repository you want to contribute to  
2. **Clone** your fork and create a new branch  
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit  
4. Open a Pull Request with a clear description  

For code contributions, please open an issue first to discuss the change.

---

## 📋 Contribution Guidelines

- Follow existing code style and structure
- Add tests where applicable
- Update documentation to reflect your changes
- Keep PRs focused — one feature or fix per PR
- Reference related issues in your PR description

---

## 🤝 Code of Conduct

By participating, you agree to our [Code of Conduct](./CODE_OF_CONDUCT.md).

---

*Last updated: April 2026*
