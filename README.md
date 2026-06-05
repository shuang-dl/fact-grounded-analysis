# Fact-Grounded Analysis Skill

## Overview

The Fact-Grounded Analysis Skill is designed to make AI responses more reliable, auditable, and evidence-based. It instructs the AI to prioritize verified facts, cite sources when available, disclose uncertainty, and clearly separate facts from assumptions, inference, and hypothesis.

This skill is intended for analytical work where accuracy, source quality, and decision confidence matter.

## Purpose

Use this skill to ensure that AI responses:

- Do not present assumptions as facts
- Ground factual claims in reliable evidence
- Research or source-check when appropriate
- Clearly label uncertainty, inference, and hypothesis
- Avoid overconfident or unsupported conclusions
- Provide structured, thorough analysis

## When to Use

Use this skill for analytical questions involving:

- Business analysis
- Product analysis
- Operations analysis
- Technical research
- Market or competitive research
- Company-specific questions
- Legal, financial, medical, compliance, or regulatory topics
- Current events or time-sensitive information
- Any decision-impacting question where factual accuracy matters

## What the Skill Enforces

The skill requires the AI to follow a strict factuality standard:

1. Material factual claims must be supported by a reliable source, user-provided material, internal knowledge base, or widely established general knowledge.
2. Unsupported claims must be labeled as unknown, unverified, inference, or hypothesis.
3. The AI must not silently fill evidence gaps with plausible assumptions.
4. Conflicting sources must be disclosed and compared.
5. Conclusions must not be stronger than the available evidence supports.

## Recommended Response Structure

For substantive analysis, the AI should structure responses using:

1. Executive Summary
2. Verified Facts
3. Evidence
4. Analysis
5. Assumptions and Limitations
6. Inference or Hypothesis
7. Recommendation or Next Step

## Confidence Labels

The skill uses these confidence labels:

- **Confirmed**: Directly supported by strong evidence
- **Likely**: Supported by evidence, but not conclusively proven
- **Unverified**: Plausible, but not sufficiently supported
- **Unknown**: Not enough information is available to assess

## Files

This package includes:

- `SKILL.md` — the core instruction file for the skill
- `README.md` — this overview and usage guide

## Installation Notes

For ChatGPT Skills, upload the `SKILL.md` file or package it according to the platform’s current Skill upload requirements.

For Claude or other AI tools, the same instructions can be used as a project instruction, custom instruction, or reusable Markdown guidance file.

## Important Limitation

No instruction file can guarantee that AI will be 100% factual at all times. This skill materially improves factual discipline by forcing source-checking, uncertainty disclosure, and separation of fact from inference, but outputs should still be reviewed when the stakes are high.

## Suggested Usage Prompt

After installing or attaching this skill, use prompts such as:

> Analyze this using the Fact-Grounded Analysis Skill. Do not make unsupported claims. Clearly separate verified facts, assumptions, inference, and unknowns.

## Version

Version: 1.0
