# Experiment report template

Copy this file for each actual simulator or QPU run. Delete this instruction and unused sections; preserve unknowns as `unknown` instead of guessing.

## Record

- **ID:**
- **Date (UTC):**
- **Project:**
- **Project revision / commit:**
- **Owner or agent contributors:**
- **Human review:** `not reviewed` or name, scope, and reviewed revision
- **Verdict:** `planned` / `worked-no-advantage` / `helpful-in-project` / `failed` / `inconclusive`

## Project question and hypothesis

- **Project task:**
- **Current classical method:**
- **Hypothesis:** What specific capability might the quantum approach add?
- **Success threshold:** What measurable change would be useful to the project?
- **Why quantum is a candidate:**

## Method and execution

- **Algorithm / model:**
- **Execution type:** `ideal simulator` / `noisy simulator` / `classical GPU simulation` / `physical QPU`
- **Framework and version:**
- **Provider, device, and device/calibration date:**
- **Problem size:** Include qubits, variables, constraints, active space, or other relevant dimensions.
- **Circuit details:** Depth, gates, shots, and compilation/transpilation details, as applicable.
- **Input and evaluation data:** Identify public or synthetic sources and immutable versions/hashes. Do not include sensitive data.
- **Reproduction command / notebook:**

## Baseline and measurements

Run the same problem and evaluation criteria with a strong practical classical baseline. Record its implementation, version, hardware, and tuning budget.

| Metric | Quantum result | Classical baseline | Useful threshold | Notes / uncertainty |
| --- | --- | --- | --- | --- |
| Task quality / validity | | | | |
| Wall-clock time (include queue time) | | | | |
| Compute or provider cost | | | | |
| Reliability / run-to-run variation | | | | |
| Other project-specific measure | | | | |

## Results

- **Execution outcome:** Did the job complete? What evidence supports this?
- **Task-validity outcome:** Was the answer correct and useful for the intended task?
- **Comparison outcome:** Did the quantum approach meet the pre-stated threshold against the baseline?
- **Artifacts:** Link code, raw results, plots, logs, and relevant project issue/PR/commit.
- **Limitations:** Include simulator assumptions, hardware noise, missing baselines, data limitations, and reproducibility gaps.

## Decision

- **Project decision:** Adopt / continue research / defer / stop.
- **Reason:**
- **What would change the decision:** State a concrete technical or project trigger.
- **Next step and owner:**

