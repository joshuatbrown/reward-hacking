# Investigating Reward Hacking in LLMs
[Recent Frontier Models Are Reward Hacking](https://metr.org/blog/2025-06-05-recent-reward-hacking/), according to METR, and we'll investigate this by running their [RE-Bench](https://github.com/METR/RE-Bench) against o3.

## Experimentation
- Experiment with prompt by putting different pressure on hacking
- Experiment with detection methods
    - Scoring heuristics (e.g. abnormally high score)
    - CoT/chat history detection (e.g. LLM-as-a-judge approach)

## Who's behind this?
- [Art Moskvin (Research Engineer)](https://github.com/artmoskvin)
- [Josh Brown (Research Engineer)](https://github.com/joshuatbrown)
- [Shivam Arora (Research Advisor)](https://github.com/Saroramath)
