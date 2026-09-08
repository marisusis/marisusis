# I'm Maris Usis (hi! 👋)

Firmware and systems engineer. C and Rust for solid-state power infrastructure at Vertiv. Experience in reverse engineering, embedded debugging, system design, and networking.

[LinkedIn](https://linkedin.com/in/marisusis) · [ORCID](https://orcid.org/0009-0004-3030-9081) · [marisusis0@protonmail.com](mailto:marisusis0@protonmail.com)

## Some of my projects

- **Mirror**: a low-latency, gaming-performance, accelerated headless remote desktop solution built on QUIC and Linux. Work-in-progress, will open source once end-to-end prototype with headless Linux host is functional.

  **Demo:** Streaming a MacOS host to an iOS client. Used Claude Opus 5 to scaffold the iOS-specific code based on my desktop client implementation (only had my one laptop at the time of recording). The same `wgpu` pipeline and networking code is used, but we render to a `SurfaceTargetUnsafe::CoreAnimationLayer`. [Find the demo video here.](https://usis.dev)

- **sdr-scraper**: async Rust collector recording from 50+ simultaneous WebSocket software-defined-radio endpoints (`tokio`, `tokio-tungstenite`). [repo](https://github.com/marisusis/sdr-scraper)
- **HC37 NOR flash driver for OpenOCD**: implemented a flash backend in OpenOCD for the chip in an off-the-shelf HF radio, enabling firmware extraction and reverse engineering. (C, OpenOCD, gdb)
- **route-suite**: graph-based `ASIO` audio routing on Windows (C++), sub-7ms latency between clients. (C, C++) [repo](https://github.com/marisusis/route-suite)
- **telugu-to-english-with-transformers**: transformer from scratch in `PyTorch`, 27.2 `BLEU` on 5M sentence pairs. [repo](https://github.com/marisusis/telugu-to-english-with-transformers)

## Publications

- Detecting changes in along-path HF propagation during the April 2024 total solar eclipse with radio amateurs and low-cost instrumentation. *Frontiers in Astronomy and Space Sciences*, 2026. [doi:10.3389/fspas.2025.1720301](https://doi.org/10.3389/fspas.2025.1720301)
- Hydropower and environmental flow management: System-level trade-offs at Glen Canyon Dam. *Journal of Hydrology: Regional Studies*, 2025. [doi:10.1016/j.ejrh.2025.102624](https://doi.org/10.1016/j.ejrh.2025.102624)
