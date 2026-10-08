---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
published: true
---

## AI Agent Memory Privacy Protection

**2026-present.** Received the Cybersecurity Professional Funding Program from the Cybersecurity Association of China for research on hardware-level privacy protection for AI agent long-term memory.

- Built threat models for plaintext embedding storage, embedding inversion, privileged OS reads, cross-user leakage, and memory poisoning.
- Designed a four-layer protection architecture across the agent, middleware, TEE, and storage layers.
- Implemented a compatible `ProtectedVectorStore` middleware prototype with user-level key isolation, encrypted storage, and TEE-side streaming vector retrieval.

## Cryptographic Testing Engine

**2023-2025.** Served as a student lead for commercial cryptographic testing engine development.

- Developed deep learning based side-channel analysis software that integrates advanced AI attack methods and fast classical side-channel analysis routines.
- Built a software and hardware platform for post-quantum cryptographic fault injection analysis on embedded devices.
- Implemented a full post-quantum side-channel analysis workflow covering trace collection, preprocessing, deep learning based analysis, and key recovery.

## TAME: Blind Side-Channel Analysis

**2026.** Designed a deep learning based blind side-channel analysis framework for scenarios where plaintext and ciphertext are unavailable.

- Proposed multi-point clustering deep representation and trusted-anchor meta-weighting modules.
- Reduced the impact of noisy automatic labels through bi-level sample-weight learning.
- Validated the framework on AES, ASCON, and Kyber, including random delay protected settings.

## ML-KEM Single-Trace Side-Channel Analysis

**2024-2025.** Developed a deep learning based single-trace side-channel analysis approach for ML-KEM.

- Designed end-to-end multi-output neural networks and cross-device transfer learning architecture.
- Combined neural leakage modeling with GPU-optimized belief propagation for key recovery.
- Evaluated the approach on noisy, misaligned, cross-device embedded traces.

## LLM Agent for Cryptographic Evaluation

**2025.** Developed a domain-specific LLM agent for cryptographic evaluation report generation.

- Combined open-source model fine-tuning, a RAG knowledge base, document operation tools, and image recognition.
- Automated report drafting and standardized output for applied cryptographic evaluation workflows.

## RISC-V V2X Cryptographic Implementation

**2023.** Worked on a next-generation V2X security interaction system based on high-speed cryptographic algorithms for RISC-V.

- Implemented SM4 on a RISC-V processor with support for ECB, CBC, OFB, and other modes.
- Validated correctness using at least 10,000 OpenSSL-generated test cases.
- Improved SM4 performance from 175 cycles/byte to 20 cycles/byte through instruction extension and software optimization.
