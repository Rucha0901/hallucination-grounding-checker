---
name: claim-entailment
description: Specialized capability for Verifies that generated model claims are strictly entailment-grounded in trusted external retrieval contexts without extrapolation.
license: MIT
allowed-tools: ""
metadata:
  author: "Rucha Salpure"
  version: "1.0.0"
  category: research
---

# Hallucination Grounding Checker Agent — Claim Entailment Skill

## Purpose
The `claim-entailment` capability provides high-assurance execution routines for `Hallucination Grounding Checker Agent`.

## Execution Workflow
1. Validate input parameters against typed schemas and invariant constraints.
2. Ingest contextual metrics and establish a deterministic baseline.
3. Formulate candidate recommendations with explicit confidence intervals.
4. Submit draft plans to the independent checker agent for verification.

## Boundary Conditions
- **Input validation:** Reject non-conforming or malformed payloads before evaluation.
- **Fail-safe:** Escalate immediately if telemetry indicators exhibit critical anomalies.
