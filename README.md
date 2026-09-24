# MARL-Handover

Research experiment on two-arm object handover with multi-agent RL (PPO).

## Question

Does adding a learned latent communication channel between the two agents improve
handover performance compared to no communication / hand-crafted observation sharing?

## Structure

- `src/envs/` — handover environment + observation spec
- `src/algo/` — PPO implementation and rollout collection
- `src/conditions/` — experiment conditions (e.g. no-comm baseline, hand-crafted comm, learned latent)
- `configs/` — experiment configs
- `scripts/` — training/eval entry points
- `results/` — run outputs (gitignored)
- `notes.md` — running research notes

## Status

Early scaffolding — implementation in progress.
