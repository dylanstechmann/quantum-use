# Quantum Use

A small evidence ledger for quantum-computing experiments across personal projects. It records what was attempted, what ran, whether the result was valid, and whether it improved a project against a classical baseline.

This is an AI-assisted hobby and learning project. Each report should identify agent-assisted work and any human review accurately. Literature reviews and discussions are useful context, but they are not hardware or simulator experiments.

## Ground rules

- A successful QPU submission is evidence that the program ran; it is not evidence of project value.
- Separate execution, correctness, and practical improvement in every report.
- Distinguish physical QPU runs from ideal simulation, noisy simulation, and GPU-accelerated classical simulation.
- Define the project outcome, classical baseline, metrics, and what improvement would matter before running the experiment.
- Record costs, queue time, software and device versions, and negative or inconclusive results.
- Keep experiments reproducible with public or synthetic data. Do not commit API keys, credentials, private datasets, or sensitive project data.

## Verdicts

- `planned` — a proposed test that has not been executed.
- `worked-no-advantage` — it ran and produced a valid result, but did not materially improve on the baseline.
- `helpful-in-project` — it demonstrated a pre-defined, meaningful improvement in quality, speed, cost, reliability, or a previously unavailable capability.
- `failed` — it did not execute successfully, or its result was invalid or unreliable for the intended task.
- `inconclusive` — evidence was insufficient to decide.

Every report also records the separate execution and task-validity outcomes. A result can be technically successful while its project verdict is `worked-no-advantage`.

## Workflow

1. Copy [the experiment template](EXPERIMENT_TEMPLATE.md) to `experiments/<ID>.md` and add an entry to [the experiment index](EXPERIMENTS.md).
2. State the project question, baseline, evaluation data, metrics, and success threshold before running anything.
3. Start with a simulator to validate the implementation. Label its type and classical hardware clearly.
4. Run on physical quantum hardware only when that run answers a defined question; record provider, device, calibration or run date, shots, queue time, and all charges.
5. Record the outcome, limitations, artifacts, and a concrete decision about whether the project should adopt the method.

## Credentials and attribution

Keep credentials in a local secret store or environment variables. `.gitignore` excludes common quantum-provider credential files, but verify `git status` before committing. Rotate any credential that has been pushed to a remote repository.

Identify whether code, analysis, and interpretation were owner-run, agent-assisted, or otherwise generated. Record human review only after a person has reviewed the specified artifacts.

## Initial state

The [initial inventory](reviews/2026-10-10-initial-inventory.md) found no quantum-computing integrations or simulator/QPU runs in the local project workspace. Candidate ideas are listed separately in [CANDIDATES.md](CANDIDATES.md); they are not experiment results.

