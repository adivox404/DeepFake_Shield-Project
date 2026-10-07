# DeepFake Shield

### Multimodal AI for Media Authenticity & Misinformation Risk

**Team:** Divyansh Pathak & Aditya Kumar  
**Event:** Logic League 2026  
**Team Size:** 2-Person Team

> **DETECT → EXPLAIN → WARN → LET THE USER DECIDE**

---

## 1. Problem Statement

AI-generated and manipulated images, videos, and audio are becoming increasingly difficult for everyday users to assess.

However, misinformation is not limited to manipulated media. A genuine image or video can also become misleading when it is combined with:

- False claims
- Old events presented as current
- Incorrect locations
- Misleading captions or context

Users also lack a simple **"pause-and-verify"** layer before suspicious content is shared widely.

### Our Goal

Create a moment of verification before misleading content gains further reach.

---

## 2. Existing Solutions

Several approaches already exist in the media-authenticity ecosystem:

### AI Detectors
Neural models inspect visual, acoustic, or video signals for potential manipulation patterns.

### C2PA / Provenance
Content Credentials can provide tamper-evident provenance when provenance information is embedded and preserved.

### Watermarking
Embedded signatures can help identify AI-generated media in supported ecosystems.

### Commercial APIs
Sophisticated multimodal services exist, but many are designed primarily for enterprise or platform moderation workflows.

### The Gap

DeepFake Shield proposes a unified, user-facing layer that:

- Combines multiple signals
- Communicates uncertainty
- Explains evidence
- Suggests the next verification action

---

## 3. Proposed Solution

**DeepFake Shield** is a proposed multimodal AI/ML assessment layer for media authenticity and misinformation risk.

The system follows five major stages:

```text
INPUT
Image • Video • Audio • Claim
        ↓
ANALYZE
AI/ML Models + Provenance Checks
        ↓
FUSE
Signal Weighting + Risk Calibration
        ↓
EXPLAIN
Indicators + Model Limitations
        ↓
ACT
Warn • Verify • Pause Sharing
