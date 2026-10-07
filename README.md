# AI Evidence-Based Occupational Safety Investigator

**Evidence-based LLM Benchmark → Requirements Engineering → AI Product Design**

## Project Overview

AI Evidence-Based Occupational Safety Investigator is an evidence-centric system concept for supporting occupational safety incident investigation.

The project addresses a key limitation of LLM-based investigation: a model may generate a plausible explanation or causal narrative that is not sufficiently supported by the available evidence.

The V1.0 approach therefore focuses on traceability:

**Evidence → Observation → Event → Timeline → Verification → Evidence-Based Report**

The system is designed to preserve the distinction between observed facts, reconstructed events, contradictions, missing evidence and conclusions requiring human verification.

---

## V1.0 Core Functions

The V1.0 scope consists of exactly seven functions:

1. **Evidence Intake**
2. **Fact Extraction**
3. **Evidence Timeline**
4. **Contradiction Detection**
5. **Regulatory Cross-Check**
6. **Missing Evidence**
7. **Evidence-Based Investigation Report**

The architecture is evidence-centric: conclusions must remain traceable to their supporting evidence.

---

## High-Level Architecture

```text
Evidence
   ↓
Observation
   ↓
Event
   ↓
Timeline
   ↓
Contradiction / Missing Evidence
   ↓
Regulatory Cross-Check
   ↓
Human Verification
   ↓
Evidence-Based Investigation Report
   ↕
Evidence Traceability
