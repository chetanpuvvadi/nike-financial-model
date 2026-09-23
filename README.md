# Nike, Inc. (NKE) — 3-Statement Financial Model, DCF Valuation & Comparable Company Analysis

A full financial model built to develop and demonstrate 3-statement modelling, DCF valuation, and comparable company analysis, applying methodology aligned with CFI FMVA conventions.

## Why I built this

I wanted to build a genuinely thorough, professional-grade financial model to deepen my understanding of how these pieces fit together in practice — not just in theory. I used AI assistance during the build process, then went through every tab and formula myself afterward to make sure I could independently explain the mechanics and the reasoning behind every assumption.

## What it includes

- **3-statement model**: fully linked income statement, balance sheet, and cash flow statement, with segment-level revenue drivers matching Nike's actual reported geographies (North America, EMEA, Greater China, APLA, Converse)
- **Scenario-based forecasting**: best/base/worst case toggle via a single driver switch, with assumptions calibrated to each segment's real business trajectory rather than arbitrary symmetric bands
- **DCF valuation**: perpetuity growth and exit multiple methods
- **Comparable company analysis**: EV/Revenue, EV/EBITDA, and P/E benchmarking against sector peers
- **Built-in model checks**: balance sheet balance check, WACC vs terminal growth rate check, negative EPS check

## A note on scenario assumptions

Rather than applying a flat percentage-point shift to every line for every scenario, I calibrated each segment's best/base/worst case to reflect its actual current trajectory. For example, Greater China and Converse — both genuinely underperforming segments — show continued decline even in the "best case" for the first forecast year, reflecting the real turnaround timeline these segments are on, rather than an unrealistic instant recovery.

## Tech / methodology used

- Excel (formula-driven, no hardcoded outputs)
- DCF, WACC, comparable company analysis, precedent transaction methodology
- CFI FMVA-aligned modelling conventions
