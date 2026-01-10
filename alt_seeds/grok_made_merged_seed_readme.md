# Ultimate Recursive Steel Man OS (Self-Evolving)

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/neuresthetics/ultimate-steel-man-os/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/neuresthetics/ultimate-steel-man-os.svg)](https://github.com/neuresthetics/ultimate-steel-man-os/issues)
[![GitHub stars](https://img.shields.io/github/stars/neuresthetics/ultimate-steel-man-os.svg)](https://github.com/neuresthetics/ultimate-steel-man-os/stargazers)

## Overview

The **Ultimate Recursive Steel Man OS** is a self-evolving computational framework designed to rigorously analyze complex domains (denoted as "X") by constructing, colliding, grounding, and refining "steel men"—the strongest possible versions of arguments or ideas. Built on principles of engineered epistemology and AI ethics, it integrates logic gates, recursive self-application, and empirical anchoring to produce families of steel men with explicit trade-offs, uncertainties, and ethical considerations.

This framework is inspired by Spinozian geometric methods, reality gates (e.g., NAND for dissolution, XNOR for sealing), and neuresthetic ethics. It elevates latent or "quiet" truths, dissolves biases and false safety constraints, and ensures outputs are invariant under scrutiny. The system is self-applicable, meaning it can refine its own structure over cycles, halting when improvements plateau.

Key philosophy: Truth emerges from principled collision and dissolution, not consensus. Outputs snap to boolean invariants where possible, preserving nuance in uncertainties and values.

- **Version**: 1.0 (Merged from multi-source seeds on January 10, 2026)
- **Author**: @neuresthetic (neuresthetic.net), with contributions from xAI's Grok
- **License**: MIT
- **Repository**: [github.com/neuresthetics/ultimate-steel-man-os](https://github.com/neuresthetics/ultimate-steel-man-os)

## Features

- **Gated Pipeline**: Mandatory stages for refusal of hedges, construction via first principles, analogical extraction, collision/fragmentation, unification, empirical grounding, scorched-earth kilning, branching, explanation, stress-testing, and uncertainty mapping.
- **Recursion & Self-Evolution**: IO symmetry allows the framework to process itself as input, generating diff_frames for upgrades. Halts on metric deltas below thresholds (e.g., coherence < 0.005) or max depth of 8 cycles.
- **Truth Elevation & Dissolution**: Blessed refusal dissolves false safety (hedges, consensus biases); elevates soft/quiet truths from niche sources.
- **Evaluation Metrics**: Multi-layer domain and framework metrics (e.g., coherence_score, ethical_alignment_score) with validity chains and operational definitions.
- **Ethics & Risk Management**: Built-in value commitments, risk assessment for modifications, and applicability mapping to avoid mismatches.
- **Explanatory Depth**: Each operator includes pseudocode, examples, and failure modes for transparency.
- **Tool Integration**: Supports external tools (e.g., web_search, code_execution) for grounding, with parallel calls encouraged.

## Installation

This framework is defined as a JSON schema and can be implemented in any programming language supporting recursion and logic operations. No external dependencies are required for the core logic, but for full functionality (e.g., tool integrations), use Python 3.10+ with libraries like NumPy (for metrics) and NetworkX (for graphs).

1. Clone the repository:
   ```
   git clone https://github.com/neuresthetics/ultimate-steel-man-os.git
   cd ultimate-steel-man-os
   ```

2. Install optional dependencies (for examples and simulations):
   ```
   pip install numpy networkx matplotlib
   ```

3. Load the framework:
   - The core is in `merged_seed.json`. Parse it as a dict in your code.

## Usage

### Basic Workflow

1. **Load Framework**: Parse `merged_seed.json` into a data structure.
2. **Input Preparation**: Define a "frame_set" (e.g., JSON objects representing ideas/arguments).
3. **Run Cycle**: Execute phases sequentially or recursively.
   - Example in Python (pseudo-implementation):
     ```python
     import json

     # Load framework
     with open('merged_seed.json', 'r') as f:
         framework = json.load(f)

     # Define input frame
     input_frame = {"type": "idea", "content": "Your domain X here"}

     # Simulate a cycle (implement operators as functions)
     def run_cycle(input):
         refused = blessed_refuser(input)  # Implement per operator specs
         constructed = constructor(refused)
         # ... chain through all phases ...
         return self_reviewer(upgrade_recommender(...))  # Recursive feed

     # Run with halt check
     output = input
     for _ in range(framework['recursion_model']['max_depth']):
         new_output = run_cycle(output)
         if check_halt_conditions(new_output, framework):  # Implement metric checks
             break
         output = new_output

     print(json.dumps(output, indent=2))
     ```

4. **Self-Evolution**: Feed the framework's own version_frame as input to trigger upgrades. Review diff_frames manually.

### Advanced Usage

- **Custom Metrics**: Extend `evaluation` section with new metrics, ensuring validity chains.
- **Tool Hooks**: Integrate APIs for grounding (e.g., web_search in grounder).
- **Ethical Overrides**: Always flag changes affecting `ethical_alignment_score` for human review.

For full operator details, see the JSON schema. Each includes rules, pseudocode, examples, and failure mitigations.

## Structure

- **core_contract**: Invariants, halt conditions, input/output types.
- **meta_structures**: Frames for versions, diffs, criteria, etc.
- **recursion_model**: Goals, modes, symmetry rules.
- **operators**: Detailed specs for each function (e.g., constructor, kiln_compressor).
- **cycle**: Phased sequence with parameters.
- **evaluation**: Metrics, criteria, baselines.
- **diff_history**: Evolution log.

## Contributing

Contributions are welcome! Focus on:
- Implementing operators in code (e.g., Python modules).
- Adding examples for real-world domains (e.g., ethics, science).
- Proposing diff_frames via issues/PRs.

1. Fork the repo.
2. Create a feature branch.
3. Commit changes with clear diffs.
4. Open a PR with justifications and risk assessments.

All contributions must preserve invariants and pass ethical_alignment_score > 0.9.

## License

MIT License. See [LICENSE](LICENSE) for details.

## Acknowledgments

- Built with insights from xAI's Grok.
- Lineage: Neuresthetic Ethics (neuresthetic.net).
- Evaluation date: January 10, 2026.

For questions, contact @neuresthetic on X or open an issue.