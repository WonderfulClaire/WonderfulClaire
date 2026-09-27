# Hi, I'm Claire

M.S. student at **Tsinghua University**, based in Shenzhen. My current focus is **LLM post-training, reinforcement learning, and tool-using agents**, with related work in multimodal learning and speech/audio processing.

I build small, inspectable training and evaluation systems: define the task, trace the learning signal, test the implementation, and document what the evidence supports.

[Academic homepage](https://wonderfulclaire.github.io/academic-homepage/) · [Email](mailto:wk1924321@163.com) · [X](https://x.com/ClaireWangke)

## Selected work

| Project | What to explore | Start here |
| --- | --- | --- |
| [Kimi K3 Deep Dive & Agentic Post-Training Lab](https://github.com/WonderfulClaire/kimi-k3-deep-dive) | Unified agent harness, secure verifier, reward-hacking cases, history/harness ablations, verified trajectories, LoRA-SFT and environment-owned GRPO | [Experiment protocol](https://github.com/WonderfulClaire/kimi-k3-deep-dive/blob/main/docs/experiments.md) · [SFT / GRPO training](https://github.com/WonderfulClaire/kimi-k3-deep-dive/blob/main/docs/training.md) |
| [5G Diagnostic Agent](https://github.com/WonderfulClaire/5G-Diagnostic-Agent) | Multi-turn tool use, evidence-gated diagnosis, LoRA-SFT/GRPO training, and layered evaluation | [Learning loop](https://github.com/WonderfulClaire/5G-Diagnostic-Agent/blob/main/docs/LEARNING_LOOP.md) · [Leakage-fixed curriculum experiment](https://github.com/WonderfulClaire/5G-Diagnostic-Agent/blob/main/reports/experiments/20260915-verified-curriculum/REPORT.md) |
| [BLM Multimodal Audit](https://github.com/WonderfulClaire/BLM-Multimodal-Audit) | Visual representation learning, distributed contrastive training, reviewed data production, and multimodal GRPO | [Data flywheel](https://github.com/WonderfulClaire/BLM-Multimodal-Audit/blob/main/docs/DATA_FLYWHEEL.md) · [Distributed experiments](https://github.com/WonderfulClaire/BLM-Multimodal-Audit/blob/main/reports/distributed/20260915/REPORT.md) |
| [RL From Scratch](https://github.com/WonderfulClaire/rl-from-scratch) | Mathematical and executable path from policy gradients to PPO/GRPO, then verifier and reward-hacking mechanics for agentic RL | [LLM post-training](https://github.com/WonderfulClaire/rl-from-scratch/tree/main/10_rlhf_dpo_grpo) · [Agentic post-training](https://github.com/WonderfulClaire/rl-from-scratch/tree/main/12_agentic_post_training) |
| [Agent the Hard Way](https://github.com/WonderfulClaire/agent-hard-way) | Go exercises on provider abstractions, tool loops, permissions, context budgets, persistence, compression, and memory | [Exercises and verification](https://github.com/WonderfulClaire/agent-hard-way#readme) |
| [HearWeave + BeamBench](https://github.com/WonderfulClaire/HearWeave) | Microphone-array simulation plus reproducible experiment/evidence tooling for spatial-audio research | [HearWeave tutorial](https://github.com/WonderfulClaire/HearWeave/blob/main/docs/TUTORIAL.md) · [BeamBench](https://github.com/WonderfulClaire/BeamBench) |

The research repositories distinguish synthetic experiments, implementation checks, and real-world validation. Training configurations and successful tool calls alone are not evidence of model improvement; the linked reports include limitations and unsuccessful experiments.

## What I'm learning

- **Post-training:** SFT, policy optimization, preference learning, verifiable reward, reward hacking, harness generalization, and training diagnostics.
- **Agents:** useful tool interactions, synthetic task data, context management, and evaluation.
- **Multimodal and audio learning:** connecting representation learning with signal processing and distributed computation.

For broader projects and learning resources: [Research Training Guide](https://github.com/WonderfulClaire/research-training-guide), [JobNebula](https://github.com/WonderfulClaire/JobNebula), [math foundations](https://github.com/WonderfulClaire/smart-wearable-math-foundations), and my [learning hub](https://github.com/WonderfulClaire/claire-learning-hub).
