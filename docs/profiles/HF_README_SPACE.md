---
title: README
emoji: 🌍
colorFrom: blue
colorTo: indigo
sdk: static
pinned: false
---

<div align="center">

# GeoStratum 🌍
### Geoscience Software & Applied Edge AI Solutions

**Digitizing the field. Centralizing your tools.**

[Official Website](https://www.geostratum.eu) • [Lithotheque (Google Play)](https://play.google.com/store/apps/details?id=com.lithotheque.app.release) • [GitHub](https://github.com/GeoStratum) • [Contact Us](mailto:communication@geostratum.eu)

---

</div>

GeoStratum combines Earth science methodology with production-grade software and **Local-First, Embedded Edge AI**. We develop tools for field geologists, researchers, and students, engineered for complete offline autonomy, zero cloud dependency, and total data ownership in harsh field environments.

---

## 🔬 Machine Learning & Edge AI Research

Our machine learning research focuses strictly on edge deployment and offline geological analysis:

### 1. Sub-Byte & Full-Integer Quantization (W4A8 & INT8)
- **Zero-FP32 Execution Graphs** : Enforcing strict integer kernels without floating-point fallback buffers, preventing memory stalls on mobile NPUs (Qualcomm Hexagon HTP, Google Tensor TPU, MediaTek APU, Intel NPU).
- **Per-Tensor Signed Asymmetry (`TENSOR_QUANT8_ASYMM_SIGNED`)** : Custom classification heads eliminating hardware partition breaks on mobile drivers.
- **Kernel-Fused Convolutions** : Structural absorption of 4D padding operators into native `SAME` convolution kernels.

### 2. Hierarchical Computer Vision (21-Pass Multi-Scale Tiling / 21-MST)
- Solving the fundamental resolution trade-off in geology: capturing both macroscopic outcrop textures and microscopic crystalline grains simultaneously in real-time, backed by C++23 SIMD auto-vectorization (ARM NEON / AVX2).

---

## 📦 Key Hub Repositories & Models

- **[GeoStratum/quantification-MobileNetV5-V4](https://huggingface.co/GeoStratum/quantification-MobileNetV5-V4)**  
  Technical documentation, full W4A8/INT8 quantization pipeline, and physical on-device benchmarks for `MobileNetV5-300M` and `MobileNetV4-Large` across Qualcomm Hexagon NPU (Copilot+ ARM64) and NVIDIA RTX Blackwell architectures.

---

## 🛠️ The GeoStratum Software Ecosystem

### AI-Powered Solutions:
- 🪨 **[Lithotheque](https://www.geostratum.eu/lithotheque)** : Digital field notebook for Android & Windows. 100% offline resilience, embedded LiteRT rock classification across 104 lithological classes, sub-millimeter scale metrology, and AES-256 local encryption *(Google Play, 1k+ downloads, 4.8★)*.
- 🏛️ **[Stratalog](https://www.geostratum.eu/stratalog)** : Native Windows 11 desktop application (C# WinUI 3 & C++ DLL) for vector stratigraphic column design, borehole logging, and local multimodal AI assistance (Google Gemma 4 E2B Instruct via Qualcomm QAIRT, Intel OpenVINO, and LLamaSharp).

### Physics & 3D Simulation (Non-AI):
- 🪐 **[SpaceGeol](https://www.geostratum.eu/spacegeol)** : Interactive 3D planetary geology and space mission simulator running in WebGL/Three.js. Powered exclusively by authentic Newtonian flight dynamics, Keplerian orbital mechanics, and real planetary mineralogy *(No AI involved)*.

---

<div align="center">

GeoStratum © 2026 — Founded by Lohan GUYON • Varades, France  
[Website](https://www.geostratum.eu) • [LinkedIn](https://www.linkedin.com/company/geostratum) • [Instagram](https://www.instagram.com/geostratum_communication/) • [Bluesky](https://bsky.app/profile/geostratum.bsky.social)

</div>
