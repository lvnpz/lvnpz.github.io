---
layout: page
title: Projects
permalink: /projects/
---

Systems I have designed, built, and shipped — at Nokia Bell Labs (2022–present)
and during my PhD. Each one spans the full stack: algorithm design,
infrastructure, and a working end-to-end deployment.

## Nokia Bell Labs

### Network-aware XR delivery for multi-person tele-rehabilitation
*NSF "Breaking Low" project (~$3.5M) · Oct 2025 – present*

Multi-institution project with the University of Michigan (PI), USC, Columbia,
Duke, and Nokia Bell Labs (Co-PI), targeting motion-to-photon latency
requirements considered infeasible on today's Internet.

- Designed and implemented the mechanism that lets a 5G/O-RAN network recognize
  and prioritize the most latency-critical parts of a live XR stream.
- Built a fully interactive real-time XR application with a browser-based
  client, closing the end-to-end user–environment loop.
- Deployed and demonstrated the complete system on-site at the University of
  Michigan (June 2026), validating the project's central approach in practice.

### Edge–cloud scalable 3D Gaussian Splatting delivery
*Patented · Jun 2025 – Mar 2026*

- Architected an edge–cloud 3DGS scene-delivery system that folds live network
  state into splat selection and prioritization, jointly optimizing network-
  and application-level performance.
- Resolved 3DGS scalability limits for compute- and memory-constrained client
  devices and for simultaneous multi-user access under network contention.
- Approved by the Nokia Patent Board; assessed by expert reviewers as a
  first-of-its-kind cross-layer XR streaming approach, relevant to Nokia's
  MantaRay RIC and AI-RAN product lines.

### ML-driven spectrum defragmentation for optical transport networks
*Demonstrated at OFC 2025 · Mar 2024 – Mar 2025*

- Developed an automated, ML-driven spectrum-defragmentation method that
  improves energy efficiency in optical transport networks.
- Built the automation pipeline end to end and demonstrated it live at the
  Optical Fiber Communications Conference (OFC 2025).

### PSASlicing: SLA-aware reinforcement learning for O-RAN slice management
*IEEE GLOBECOM 2024 · Dec 2023 – Aug 2024*

- Designed a perpetual, SLA-aware reinforcement-learning method for O-RAN
  network-slice management that sustains SLA compliance over long operating
  horizons — RL that has to keep working in production conditions, not just in
  a training run.

### End-to-end 5G/O-RAN system and RIC applications
*Jun 2022 – Dec 2022*

- Implemented a complete 5G end-to-end system with OpenAirInterface, Open5GS,
  and O-RAN components.
- Developed xApps (near-RT RIC) and rApps (non-RT RIC) hosting ML-based radio
  resource management agents for RAN slicing.

## PhD systems work (UNCC / NJIT)

### FedVision — federated video analytics with edge computing
*IEEE OJ-CS 2020, 45+ citations*

- Designed a federated video analytics system that jointly optimizes on-device
  inference and computation offloading across an edge network, trading off
  detection accuracy against end-to-end latency.
- Built the testbed on NVIDIA Jetson TX2, nvidia-docker, OpenWRT, and desktop
  GPUs; used learned surrogates (neural processes) and black-box optimization
  to pick models, frame resolutions, and offloading rates at runtime.

### FLEX — trading edge computing resources for federated learning
*Demoed at IEEE INFOCOM 2021*

- Designed and implemented a blockchain marketplace (Ethereum smart contracts
  in Solidity) where edge nodes sell compute to federated learning tasks,
  including the TensorFlow-side workflow and interfaces between edge, global,
  and chain nodes.

### Earlier systems

- **Decentralized video analytics** — distributed testbed with heterogeneous
  edge hardware; consensus and incentive design accounting for both compute
  speed and network latency (2021).
- **SDN for power distribution systems** — learning-based network management
  and DoS mitigation for distributed grid controllers, on ONOS/Ryu SDN
  controllers with NS-3, OPAL-RT, and OpenDSS co-simulation (2019–2020).
- **Underwater communication system** — closed-loop underwater fault
  monitoring with custom RF/optical channel models in NS-3 and an
  OPAL-RT–GNU Radio bridge, prototyped in a lab seawater setup (2018).
- **Edge datastore for distributed vision analytics** — key-frame/feature
  store written in Go with REST APIs and SDN-fed network awareness
  (ACM/IEEE SEC 2017 poster).
