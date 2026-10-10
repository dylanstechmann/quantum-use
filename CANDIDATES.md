# Untested candidates

These are possible benchmark questions, not evidence that quantum computing has helped. Promote an item to an experiment only after defining a classical baseline, evaluation data, and a useful success threshold. Close or defer candidates that cannot be tied to a real project bottleneck.

| Candidate | Project | Possible quantum approach | Classical comparison | Current state |
| --- | --- | --- | --- | --- |
| Molecular electronic-structure subproblem | `regen-workbench` | Test a small, justified active-space problem with a quantum chemistry algorithm on a simulator, then physical QPU only if the simulation supports it | Best suitable classical quantum-chemistry method on the same Hamiltonian and accuracy target | Not designed or run; speculative research candidate |
| Discrete assignment or scheduling subproblem | Robotics project(s) | Encode a bounded problem as QUBO/BQM for an annealing or gate-based approach | A tuned classical solver such as OR-Tools, with identical constraints and objective | Not designed or run; speculative optimization candidate |

A proposed use should be omitted if a simpler feature, classical algorithm, or better data would solve the underlying project problem more directly.

