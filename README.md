# Roman Pristavka

Software engineer working on the unglamorous half: backend services, AI gateways
and the infrastructure that keeps them running. Two years of commercial experience
across backend, AI infrastructure and robotics. Founder of Ocelotiq, software and
robotics engineer at Indrobo.

Student at Saint Petersburg State University of Aerospace Instrumentation (SUAI).
Graduated from ASIT Perm as a software developer. Writing code since 2020.

---

### AI infrastructure

![Python](https://img.shields.io/badge/Python-326CE5?style=for-the-badge&logo=python&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI%20API-326CE5?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic API](https://img.shields.io/badge/Anthropic%20API-326CE5?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini%20API-326CE5?style=for-the-badge&logo=googlegemini&logoColor=white)
![Llama](https://img.shields.io/badge/Llama-326CE5?style=for-the-badge&logo=meta&logoColor=white)
![REST](https://img.shields.io/badge/REST-326CE5?style=for-the-badge)

[Ocelotiq](https://ocelotiq.ru) — an OpenAI-compatible gateway: point an existing
OpenAI client at it and reach GPT-4o, Claude, Gemini and Llama through one endpoint.
Built from scratch: request normalization across providers, auth, API keys with
per-key quotas, routing by availability, latency and price, analytics on tokens,
spend, errors and uptime. I run it in production.

### Networking

![Rust](https://img.shields.io/badge/Rust-B45309?style=for-the-badge&logo=rust&logoColor=white)
![TLS 1.3](https://img.shields.io/badge/TLS%201.3-B45309?style=for-the-badge)
![HTTP/2](https://img.shields.io/badge/HTTP%2F2-B45309?style=for-the-badge)
![QUIC](https://img.shields.io/badge/QUIC-B45309?style=for-the-badge)
![ChaCha20-Poly1305](https://img.shields.io/badge/ChaCha20--Poly1305-B45309?style=for-the-badge)
![Ed25519](https://img.shields.io/badge/Ed25519-B45309?style=for-the-badge)
![Tokio](https://img.shields.io/badge/Tokio-B45309?style=for-the-badge)
![Quinn](https://img.shields.io/badge/quinn-B45309?style=for-the-badge)
![rustls](https://img.shields.io/badge/rustls-B45309?style=for-the-badge)
![HKDF](https://img.shields.io/badge/HKDF-B45309?style=for-the-badge)
![Windows](https://img.shields.io/badge/Windows-B45309?style=for-the-badge&logo=windows&logoColor=white)
![Android](https://img.shields.io/badge/Android-B45309?style=for-the-badge&logo=android&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-B45309?style=for-the-badge&logo=linux&logoColor=white)
![Cloudflare WARP](https://img.shields.io/badge/Cloudflare%20WARP-B45309?style=for-the-badge&logo=cloudflare&logoColor=white)

Chaff — a custom tunneling protocol with a Rust client and server. IP traffic rides
inside browser-like TLS 1.3 sessions on port 443, over HTTP/2 or QUIC DATAGRAM with
automatic fallback to TCP. Ed25519 auth, ChaCha20-Poly1305 keyed off the TLS exporter,
anti-replay window, rekeying, adaptive batching and four parallel links.
Up to 500 Mbps over QUIC, codec at 9.5 Gbit/s on a single core.

### Robotics & embedded

![C](https://img.shields.io/badge/C-9F1239?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-9F1239?style=for-the-badge&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-9F1239?style=for-the-badge&logo=rust&logoColor=white)
![Embedded](https://img.shields.io/badge/Embedded-9F1239?style=for-the-badge)
![PCB Design](https://img.shields.io/badge/PCB%20Design-9F1239?style=for-the-badge)
![ROS 2](https://img.shields.io/badge/ROS%202-9F1239?style=for-the-badge&logo=ros&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-9F1239?style=for-the-badge&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-9F1239?style=for-the-badge&logo=pytorch&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-9F1239?style=for-the-badge)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-9F1239?style=for-the-badge)
![Synthetic Data](https://img.shields.io/badge/Synthetic%20Data-9F1239?style=for-the-badge)
![Inverse Kinematics](https://img.shields.io/badge/Inverse%20Kinematics-9F1239?style=for-the-badge)
![Sensor Fusion](https://img.shields.io/badge/Sensor%20Fusion-9F1239?style=for-the-badge)

At Indrobo: control software for robotic platforms and industrial automation lines,
integration of sensors, controllers and embedded devices, infrastructure to deploy
and maintain hardware in the field.

Computer vision for robots: detection and segmentation models trained on synthetic
data, so a new object doesn't need a hand-labeled dataset. Inverse kinematics for
manipulators, sensor fusion and calibration between cameras and the robot frame.

On the side: a home-made full-body tracker — IR transmitters and receivers on custom
PCBs, my own firmware and node-to-node protocol.

### Backend & data

![Node.js](https://img.shields.io/badge/Node.js-2F6F4E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Go](https://img.shields.io/badge/Go-2F6F4E?style=for-the-badge&logo=go&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-2F6F4E?style=for-the-badge&logo=php&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-2F6F4E?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-2F6F4E?style=for-the-badge&logo=mysql&logoColor=white)

Server-side services and REST APIs in Python and Node.js over PostgreSQL and MySQL.

### Infrastructure

![Kubernetes](https://img.shields.io/badge/Kubernetes-475569?style=for-the-badge&logo=kubernetes&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-475569?style=for-the-badge&logo=linux&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-475569?style=for-the-badge&logo=nginx&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-475569?style=for-the-badge&logo=proxmox&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-475569?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-475569?style=for-the-badge&logo=docker&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-475569?style=for-the-badge&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-475569?style=for-the-badge&logo=git&logoColor=white)

Server administration on Linux, virtualization on Proxmox, containers with Docker
and Kubernetes, Nginx in front. Linux and Docker every day, from development to production.

### Frontend

![React](https://img.shields.io/badge/React-6E5494?style=for-the-badge&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-6E5494?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-6E5494?style=for-the-badge&logo=vuedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-6E5494?style=for-the-badge&logo=javascript&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-6E5494?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-6E5494?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-6E5494?style=for-the-badge&logo=css&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-6E5494?style=for-the-badge)
![Web Performance](https://img.shields.io/badge/Web%20Performance%20Optimization-6E5494?style=for-the-badge)

Two years building client web apps in web studios before moving to backend.
