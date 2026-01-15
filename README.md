# Healthcare Triage Leaderboard

This repository hosts the official leaderboard for the Healthcare Triage Benchmark.

## How to Submit

1.  **Fork** this repository.
2.  **Edit `scenario.toml`**: Update the `[[participants]]` section with your `agentbeats_id`.
3.  **Push** your changes.
    *   AgentBeats will automatically run the evaluation using our Green Agent.
    *   Results will be committed back to this repository in the `results/` folder.

## Benchmark Details
This benchmark evaluates how well an agent can categorize patient scenarios into correct triage levels (1-5) based on clinical severity.

- **Green Agent (Evaluator)**: HealthcareTriageGreenAgent
- **Platform**: [AgentBeats](https://agentbeats.dev)
