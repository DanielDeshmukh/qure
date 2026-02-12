# Qure

Qure is a web-first OPD queue management platform designed to eliminate long physical waiting times at clinics—especially for elderly patients by enabling real-time, remote queue participation without forcing digital literacy or smartphone dependency.

---

## The Problem

During a visit to an orthopaedic clinic, I observed elderly patients standing or sitting for hours outside the OPD, waiting for their turn.  
This is not an exception it is a daily reality across clinics.

Key problems observed:
- OPD queues are still managed manually (paper, verbal calls)
- Patients must remain physically present to avoid missing their turn
- Elderly patients suffer the most due to mobility, language, and technology barriers
- Clinics lose goodwill and efficiency due to chaotic waiting areas

Despite advancements in healthcare, **waiting itself has not evolved**.

---

## The Core Idea

Qure virtualizes the OPD queue.

Patients can:
- Discover nearby clinics
- Join OPD queues remotely
- Track their position in real time
- Arrive only when their turn is near

Clinics can:
- Digitally manage OPD queues
- Assign and advance patient numbers in real time
- Reduce overcrowding
- Improve patient satisfaction without changing medical workflows

Qure is **not just an app** it is a system that respects:
- elderly patients
- non-English speakers
- non-smartphone users

---

## Guiding Principles

- Web-first, no app-store dependency
- Accessibility over aesthetics
- Clinic-controlled queues (no patient-side chaos)
- Real-time accuracy
- Graceful fallbacks instead of dead ends

---

## Project Scope & Evolution

Qure is intentionally designed as a **multi-version system**, where complexity grows without breaking the core promise.

No features are removed only sequenced.

---

## Version 1  MVP (Foundational System)

### Goal:
Eliminate physical waiting while keeping clinic operations simple.

### Features:
- Multi-clinic platform
- Clinic & receptionist dashboard
- Digital OPD queue creation per clinic
- Automatic sequential token allocation
- Real-time queue updates using WebSockets
- Receptionist-controlled queue advancement
- Patient queue status visibility
- SMS notifications:
  - token number
  - number of patients ahead
- No patient login required (phone number as identity)

### Outcome:
- Elderly patients no longer need to stand outside clinics
- Clinics replace pen-and-paper queues
- Core value is delivered with minimal friction

---

## Version 2  Accessibility & Reach Expansion

### Goal:
Ensure inclusion of elderly and non-smartphone users.

### Added Features:
- Multi-language support (regional languages)
- WhatsApp notifications (in addition to SMS)
- Missed-call alert system (10–15 minutes before turn)
- Family-assisted queue joining
- Progressive Web App (PWA) for low-end devices
- Offline-safe clinic information access
- Estimated waiting time indicators

### Outcome:
- Qure works even when patients are not tech-savvy
- Families can assist elderly patients remotely
- Clinics reach a wider patient base without operational strain

---

## Version 3  Discovery & Ecosystem Growth

### Goal:
Transform Qure into a unified OPD access layer across clinics.

### Added Features:
- Map-based clinic discovery (nearest clinics)
- OPD availability visibility per clinic
- Queue joining directly from discovery
- Graceful fallback for non-onboarded clinics:
  - “This clinic is not yet partnered with Qure”
  - Patients can inform clinics about Qure
- Clinic reputation boost via reduced waiting times
- Scalable multi-city support

### Outcome:
- Qure becomes a default OPD interface
- Clinics gain patients through better experience
- Waiting outside clinics becomes optional, not mandatory

---

## Technology Overview

- **Frontend:** Vite React (Web-first)
- **Mobile:** Progressive Web App (PWA)
- **Backend:** Node.js + Express
- **Database:** PostgreSQL
- **Real-time:** WebSockets
- **Notifications:** SMS, WhatsApp, missed-call system
- **Deployment:** Cloud-based, scalable infrastructure

No native mobile apps (React Native / Kotlin) to reduce friction.

---

## What Qure Is Not

- Not a hospital management system
- Not appointment scheduling software
- Not dependent on smartphones
- Not limited to a single clinic

Qure focuses on **waiting**, not medicine.

---

## Status

 Actively under development  
 Building sequentially from V1 → V3  
 Core philosophy preserved across all versions

---

## Vision

A future where:
- Elderly patients wait at home, not on plastic chairs
- Clinics operate calmly, not chaotically
- Healthcare time is respected, not wasted

**Qure - care without the wait.**