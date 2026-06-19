# Project Architecture

## System Goal

This project is designed as one integrated AI-driven precision agriculture decision-support system. It combines crop recommendation with fertilizer optimization, soil health intelligence, and resource readiness to support more informed farming decisions.

## Input Data Layer

The shared input data includes:

- N
- P
- K
- temperature
- humidity
- ph
- rainfall
- crop label

These inputs provide soil nutrient, environmental, and crop suitability signals. Together, they allow the project to connect field conditions with crop selection, nutrient balance, soil health, and resource planning.

## Project 1: Crop Intelligence Layer

Project 1 focuses on identifying suitable crops based on soil and environmental conditions. This layer is expected to support crop recommendation, crop suitability prediction, classification modeling, and feature importance or explainability.

This section is intentionally flexible so the Project 1 workflow can be updated as the crop intelligence notebook evolves.

## Project 2: Fertilizer and Resource Optimization Layer

Project 2 extends the system by analyzing nutrient balance, soil health, fertilizer readiness, and operational resource needs. This layer is expected to support:

- NPK ratio analysis
- nutrient deficiency or excess detection
- soil health scoring
- fertilizer adjustment recommendations
- irrigation and resource readiness indicators
- sustainability considerations

## Integrated Decision Flow

The integrated workflow is:

```text
Soil and environmental inputs
-> Crop recommendation
-> Nutrient and fertilizer analysis
-> Soil health and resource readiness scoring
-> Farmer-facing recommendation
```

## Why This Architecture Matters

This integrated design avoids treating crop recommendation as a standalone classifier. Instead, it frames the project as an operational farming decision-support system that can help with planting decisions, fertilizer planning, soil management, and sustainability.

## Current Scope Boundary

This project does not claim direct yield prediction because the dataset does not include actual yield values.

This project does not claim exact fertilizer application quantities because the dataset does not include historical fertilizer application records.

Recommendations should be framed as decision-support indicators, not prescriptive agronomy advice.
