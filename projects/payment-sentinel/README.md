# Payment Sentinel

**Status:** Built prototype | **Area:** Predictive AI

## Problem
Payment failures create repair queues and delay straight-through processing.

## Approach
A predictive payment-risk prototype connecting a model experiment, a prediction API and an operations-facing interface.

## Product decisions
- Compared Logistic Regression and XGBoost on synthetic payments.
- Connected prediction to understandable risk explanations and a review workflow.
- Kept proposed repair logic separate from the prediction model.

## Evidence and limits
Prior project discussions describe a Colab experiment, Render API and Lovable interface. Training used synthetic transactions; production impact has not been established.

## Next evidence to attach
Attach the notebook, model card, current evaluation report and a recorded walkthrough. Confirm personal versus team contribution before interviews.

Original implementation source is not included unless explicitly stated. This folder is a portfolio case study.
