# Formula Monitor

A read-only data pipeline for monitoring public discussions on Reddit related to 
infant formula safety signals, developed at the European Food Safety Authority (EFSA).

## Purpose

This tool performs keyword-based monitoring of public Reddit posts and comments to 
detect early signals of potential infant formula safety concerns — for example, 
co-occurrences of terms like "formula" with symptom-related vocabulary ("seizures", 
"rash", "recall", "contamination"). The goal is to identify emerging issues before 
they escalate into full safety crises.

## How it works

- Read-only access to Reddit's public API (no posting, voting, or user interaction)
- Monitors a defined set of parenting-related subreddits
- Extracts and aggregates post/comment data matching keyword patterns
- Feeds into an internal EFSA data pipeline (Microsoft Dataverse → Power BI)

## Target subreddits

r/beyondthebump, r/NewParents, r/breastfeeding, r/formula, r/predaddit

## Status

In development — proof of concept phase.

## Institution

European Food Safety Authority (EFSA) — Strategic Communications Unit  
https://www.efsa.europa.eu
