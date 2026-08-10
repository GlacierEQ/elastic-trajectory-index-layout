# Issue contract — Trajectory Index Layout

## Problem
Agent traces are high-cardinality and expensive to re-join for full-session forensics.

## Desired outcome
A bounded, open, testable implementation of **Trajectory Index Layout** that demonstrates Cluster spans/tool calls by trajectory id + time so forensic queries avoid full-mesh joins.

## Non-goals
- Elastic affiliation or proprietary integration
- Portfolio-wide scale/performance claims
- UI marketing site

## Acceptance
1. Mechanism module implements allow + refuse with structured receipts
2. pytest behavioral suite green
3. operate.py cold-start produces JSON receipt
4. Non-affiliation disclaimer preserved
