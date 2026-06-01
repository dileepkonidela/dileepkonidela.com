---
title: "Consumer Agents"
description: "An LLM-based consumer simulation exploring how agent memory shapes future decisions — and how reflection format can create or break behavioral echo chambers."
date: 2026-05-27
tech: ["Python", "Claude", "LLM", "Agent Memory"]
github: "https://github.com/dkonidela/consumer-agents"
featured: true
---

A simulation of synthetic consumers making daily purchase decisions, designed to study how LLM-based memory systems influence behavior over time.

## What it does

Three synthetic consumers — Maya, Raj, and Elena — each with distinct personas, incomes, and personalities, browse a small retail catalog and make daily decisions via a shared `BehaviorEngine` backed by Claude Sonnet 4.6.

Every seven simulated days, a Reflection engine summarizes each consumer's recent behavior into long-term memory. Those summaries feed into the next week's decisions.

## The surprising result

All three consumers converged on buying the same drip coffee for 80+ consecutive days, despite wildly different personas. The reflection loop had created an echo chamber: summaries described habits as identity, which made the next decision reinforce the habit, which made the next summary describe it as even more entrenched.

## The fix

Reframing memory from third-person behavioral analysis to first-person diary entries broke the loop. Between-persona behavioral similarity dropped from 0.99 to 0.69. Cart abandonments increased 25×.

The format of memory mattered as much as the content inside it.

## Write-up

Full experiment write-up: [Why Is Everyone Buying the Same Coffee?](/blog/why-is-everyone-buying-the-same-coffee)
