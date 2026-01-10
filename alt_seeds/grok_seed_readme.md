# Unified Recursive Steel Man Collider (Self-Evolving) Framework

[![Version](https://img.shields.io/badge/version-2.0-blue.svg)](https://github.com/neuresthetics/unified-steel-man-collider) [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE) [![Contributor](https://img.shields.io/badge/contributor-@neuresthetic-orange.svg)](https://x.com/neuresthetic)

## Overview

The **Unified Recursive Steel Man Collider** is a self-evolving epistemological framework designed for rigorous analysis and refinement of complex domains (denoted as "X"). It employs recursive steel-manning techniques to generate robust, falsifiable arguments, while explicitly mapping trade-offs, uncertainties, value commitments, and decision-theoretic implications. Built on principles of engineered epistemology and AI ethics, this framework treats its own structure as a domain for self-optimization, ensuring continuous improvement without compromising core invariants.

Inspired by Spinoza-style axiomatic reasoning, decision theory, and holographic projections, it balances explanatory depth with practical usability. Ideal for scientific inquiry, ethical dilemmas, and unified theories, it enforces "unhedged rigorous thinking" via the Serum Gate (a humility enforcer in uncertainty mapping).

This README provides a high-level guide to the framework's purpose, structure, usage, and evolution. For full technical details, refer to the [framework JSON specification](framework.json).

## Key Features

- **Recursive Self-Improvement**: Applies the framework to itself (io_symmetry), producing diff_frames for upgrades while preserving historical layers.
- **Steel Man Families**: Generates branched alternatives with sub-assumptions, explicit trade-offs, and value projections.
- **Multi-Dimensional Analysis**: Projects outputs into mechanistic, normative, and epistemic views for holistic understanding.
- **Ethical & Safety Focus**: Invariants ensure ethical alignment (>0.9 score), falsifiability, and complexity control (utility ratio >0.85).
- **Decision-Theoretic Integration**: Maps arguments to actions, utilities, regrets, and feedback loops.
- **Explanatory Depth**: Operators include pseudocode, examples, and failure mitigations for transparency.
- **Halt & Evaluation Safeguards**: Stops recursion based on quantifiable deltas; meta-evaluates metrics with validity chains.
- **Applicability Mapping**: Self-assesses suited domains (e.g., science/ethics) and limitations (e.g., not for real-time decisions).

## Purpose & Motivation

In an era of information overload and biased reasoning, this framework addresses the need for "engineered epistemology"—structured tools to collide ideas, resolve cruxes, and evolve knowledge. It refines any domain X (e.g., scientific hypotheses, AI ethics debates) by:
- Building strongest-possible versions (steel men) of arguments.
- Colliding them to expose tensions.
- Branching into alternatives with explicit costs/benefits.
- Grounding in empirical reality and values.

Motivated by @neuresthetic's work on unified theories and AI ethics (e.g., github.com/neuresthetics), it prioritizes science-focused applications while dropping non-essential projects (per user preference). The Serum Gate invariant ensures unhedged rigor, flagging unknowns without speculation.

## Framework Structure

The framework is defined in JSON format with the following top-level sections:

### Core Contract
- **Inputs/Outputs**: Frame sets (structured units of ideas/arguments).
- **Invariances**: Unbreakable rules (e.g., history preservation, ethical alignment).
- **Halt Condition**: Metrics (e.g., coherence_delta <0.005) and rules to prevent infinite loops or bloat.

### Meta Structures
- **Framework Version Frame**: Describes rules/operators.
- **Diff Frame**: Proposed changes with justifications/impacts.
- **Meta Criterion Frame**: Defines "better" (e.g., clarity ≤2 undefined terms).
- **Epistemic Position Frame**: Evaluation stances (e.g., Bayesian).
- **Value Commitment Frame**: Prioritized values (e.g., transparency).
- **Applicability Map Frame**: Suited/unsuited domains.
- **Measurement Protocol Frame**: Operationalizes metrics.

### Recursion Model
- **IO Symmetry**: Treat framework as X.
- **Transform Goals**: Refine X, enhance clarity/safety, balance usability.
- **Modes**: Expand, collide, branch, etc., plus paradigm_pluralize and counterfactual tests.
- **Depth/Breadth**: Max 12 recursions; 3-5 orthogonal perspectives.

### Operators
Modular functions for processing:
- **Domain Operators**: Constructor (build steel man), Collider (expose conflicts), Fractal Brancher (generate alternatives), etc.
- **Meta Operators**: Self Reviewer (audit framework), Evolution Forecaster (predict trajectories), Complexity Budgeter (prevent bloat).
- Each includes role, inputs/outputs, rules, and explanations (pseudocode/examples/failures).

### Cycle
Phased recursion:
1. Expand with pluralism.
2. Collide with analysis.
3. Resolve and ground.
4. Fractal branch with values.
5. Compress with risk assessment.
6. Stress with counterfactuals.
7. Map uncertainty and explain (with holographic projection).
8. Self-review with forecast.

Feed-forward includes updated families/frames/predictions.

### Evaluation
- **Domain Metrics**: Coherence, diversity, robustness, etc., with formulas/baselines.
- **Framework Metrics**: Clarity, ethical alignment, complexity_utility_ratio.
- **Meta Evaluation**: Validity chains (≥3 layers) for metrics.
- **Success Criteria**: High coherence, traceable mods, utility > complexity.
- **Self-Critique & Applicability**: Built-in outputs for strengths/weaknesses and domain fits.

### Diff History
Tracks merges/evolutions (e.g., from v0.4 to 2.0 via multi-source integration).

## How to Use

1. **Setup**: Load the JSON spec into a tool (e.g., Python script or AI simulator). Define initial frame_set for domain X.
2. **Run Cycle**: Invoke phases sequentially or recursively.
   - Example: Input a hypothesis X → Expand to steel men → Collide for tensions → Branch alternatives.
3. **Self-Apply**: Set X to the framework JSON for upgrades (produces diff_frames).
4. **Outputs**: Holographic frames with projections, policies, risks, and critiques.
5. **Simulation in Code**:
   ```python
   import json

   def load_framework(file='framework.json'):
       with open(file, 'r') as f:
           return json.load(f)

   def simulate_cycle(framework, x_frame):
       # Pseudo-implementation: Apply operators
       steel_man = framework['operators']['constructor']['pseudocode']  # Execute logic
       # ... Chain phases ...
       return updated_frames

   # Usage
   fw = load_framework()
   result = simulate_cycle(fw, {'input': 'Your domain X here'})
   print(result)
   ```
   Note: Full implementation requires handling recursion and tools (e.g., external queries in grounder).

6. **Customization**: Add domain-specific epistemic positions or values via meta structures.
7. **Halt/Review**: Monitor deltas; human review for diffs.

For science apps (per user focus): Use for hypothesis testing—ground in empirical data, branch counterfactuals, map uncertainties.

## Limitations & Known Issues

- **Complexity**: High for novices; mitigate with modularity (core vs. advanced).
- **Computational Intensity**: Full cycles may require resources; cap depth.
- **Unsuitable For**: Real-time or simple tasks (see applicability_profile).
- **Ethical Risks**: Assessed via epistemic_risk_assessor; always flag value misalignments.
- **Dependencies**: Assumes access to external tools for grounding (e.g., evidence queries).

## Contributing & Evolution

- **Propose Upgrades**: Submit diff_frames as pull requests.
- **History**: Merged from versions 0.4, 1.4, 1.2 (Holographic & Ethical), 0.20.
- **Future**: Forecast suggests convergence on ethical AI/science tools; watch for bifurcations.

Contact: [@neuresthetic on X](https://x.com/neuresthetic) or [neuresthetic.net](https://neuresthetic.net).
