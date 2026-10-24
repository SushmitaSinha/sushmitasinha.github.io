# EV Charger Health Diagnosis

**Status:** Product specification | **Area:** AI Operations

## Problem
Operations teams must inspect large volumes of OCPP messages to investigate charging issues.

## Approach
A specified operations copilot combining deterministic event processing with explainable LLM diagnosis.

## Product decisions
- Reconstruct sessions and compress repetitive telemetry before model reasoning.
- Separate observed facts from inferred root causes.
- Return supporting evidence, missing data and suggested actions.

## Evidence and limits
Project-Context.txt establishes the product and technical objectives, not a deployed implementation. Sub-minute investigation is a goal, not a measured result.

## Next evidence to attach
Create a sanitized sample-log demo and evaluate diagnosis against expert-labeled incidents.

Original implementation source is not included unless explicitly stated. This folder is a portfolio case study.
