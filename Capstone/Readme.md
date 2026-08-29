# FlyRank Content Performance & Opportunity Prioritization

## Project Overview

This capstone project develops a **content-performance analysis and prioritization system** for identifying pages that show meaningful changes in recent search performance. The system analyzes historical impressions, clicks, CTR, and average search position across multiple time windows to determine whether content is **growing, declining, recovering, or worth reviewing**.

The main objective is to help search teams convert large-scale performance data into an **interpretable content-opportunity queue**, allowing them to prioritize pages for content refresh or manual investigation based on observed performance changes and estimated impressions at stake.

## Key Features

* 📊 Analyzes content performance using impressions, clicks, CTR, and search position.
* 📅 Compares three consecutive 30-day performance windows.
* 📈 Classifies content into:

  * **Growing**
  * **Declining**
  * **Recovering**
  * **Worth Review**
* 🔎 Generates interpretable **reason codes** for declining or ambiguous content.
* 🎯 Prioritizes opportunities using estimated impressions at stake.
* 🛡️ Uses a minimum impression threshold to reduce unstable percentage changes.
* 🧪 Uses client-grouped validation to reduce data leakage during evaluation.
* 📋 Produces an actionable queue for content refresh and manual review.

## Data & Methodology

The project uses the public-safe **FlyRank internship warehouse** dataset. The analysis uses three consecutive 30-day windows ending on **June 25, 2026**, with content retained when prior and older periods contain at least 100 impressions. The resulting feature table contains **91,587 content/client observations**.

A rule-based scoring methodology is used to identify performance trajectories and generate explainable opportunity signals. Reason codes include worsening average position, query dependence, impression volatility, CTR decline, and severe broad decline.

## Goal

The final system is designed as a **decision-support and prioritization tool**, rather than a causal model of Google's ranking algorithm. It helps search teams answer:

> **Which content should we investigate or refresh first, and why?**
