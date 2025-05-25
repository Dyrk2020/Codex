# Stanford CS329A — Self-Improving AI Agents (Autumn 2025)

- Site: https://cs329a.stanford.edu/
- Instructors: Aakanksha Chowdhery, Azalia Mirhoseini
- Lectures: Mon/Fri 4:30–5:50 PM PT, Skilling Auditorium
- Grading: HW1 15% (Oct 13) · HW2 15% (Oct 23) · HW3 20% (Nov 7) · Proposal 2.5% (Oct 10) · Midterm 10% · Final 35% (Dec 10) · Poster 2.5% (Dec 12)
- Late policy: 4 free late days, max 2/assignment, 25%/extra day; no audits.

## Schedule & Paper Readings

| # | Date | Topic | Papers | Notes |
|---|------|-------|--------|-------|
| 1 | Mon Sep 22 | Course Overview | — | |
| 2 | Fri Sep 26 | Test-time Compute Scaling | [LLM Monkeys (Brown 2024)](https://arxiv.org/abs/2407.21787) · [Archon (2024)](https://arxiv.org/abs/2409.15254) · [Snell Test-Time Compute (2024)](https://arxiv.org/abs/2408.03314) · [LLM Power Laws](https://arxiv.org/abs/2502.17578) | |
| 3 | Mon Sep 29 | Robust Verification | [Weak Verifiers](https://arxiv.org/abs/2506.18203) · [Training Verifiers (Cobbe 2021)](https://arxiv.org/abs/2110.14168) · [Let's Verify Step by Step](https://arxiv.org/abs/2305.20050) · [Math-Shepherd](https://arxiv.org/abs/2312.08935) | |
| 4 | Fri Oct 3 | Learning from Feedback with Tools/Code | [ReAct (Yao 2022)](https://arxiv.org/abs/2210.03629) · [RLEF](https://arxiv.org/abs/2410.02089) · [Constitutional AI](https://arxiv.org/abs/2212.08073) | HW1 out (due Oct 13) |
| 5 | Mon Oct 6 | Multi-step Reasoning/Planning | [SWiRL](https://arxiv.org/abs/2504.04736) · [LATS (Zhou 2023)](https://arxiv.org/abs/2310.04406) · [SPRINT](https://arxiv.org/abs/2506.05745) · [ADaPT](https://arxiv.org/abs/2311.05772) · [Adaptive Branching Tree Search](https://arxiv.org/abs/2503.04412) | |
| 6 | Fri Oct 10 | Train Time Scaling/Scaling RL | [STaR (Zelikman 2022)](https://arxiv.org/pdf/2203.14465) · [DeepSeekMath](https://arxiv.org/abs/2402.03300) · [DAPO](https://arxiv.org/abs/2503.14476) | Proposal due |
| 7 | Mon Oct 13 | Open-Ended Evolution of Self-Improving Agents | [ADAS](https://arxiv.org/pdf/2505.22954) · [AI Scientist (Lu 2024)](https://arxiv.org/abs/2408.06292) · [AlphaEvolve](https://storage.googleapis.com/deepmind-media/DeepMind.com/Blog/alphaevolve-a-gemini-powered-coding-agent-for-designing-advanced-algorithms/AlphaEvolve.pdf) | HW2 out Oct 14 (due Oct 22) |
| 8 | Fri Oct 17 | Self Improvement with Search & Deep Research Agents | [AlphaCode](https://arxiv.org/pdf/2203.07814) · [AlphaCode 2](https://storage.googleapis.com/deepmind-media/AlphaCode2/AlphaCode2_Tech_Report.pdf) · [Search-o1](https://arxiv.org/pdf/2501.05366) | |
| 9 | Mon Oct 20 | Guest: Melvin Johnson (Google DeepMind) | Evolution of Post-training from Chatbots to Agents | |
| 10–12 | Fri Oct 24 – Fri Oct 31 | Midterm presentations | | HW3 out (due Nov 7) |
| 13 | Mon Nov 3 | Agentic Frameworks for Software Engineering | [CodeMonkeys](https://arxiv.org/abs/2501.14723) · [KernelBench](https://arxiv.org/pdf/2502.10517) · [LLM Optimizers Agent-System Interfaces](https://arxiv.org/abs/2410.15625) | |
| 14 | Fri Nov 7 | Augmenting Agents with Memory — Guest: Junchen Jiang (LMCache, UChicago) | [Cartridges](https://arxiv.org/abs/2506.06266) · [MemGPT](https://arxiv.org/abs/2310.08560) · [CacheBlend](https://arxiv.org/abs/2405.16444) | |
| 15 | Mon Nov 10 | Guest: Denny Zhou, Google DeepMind | LLM Reasoning | |
| 16 | Fri Nov 14 | Guest: Thang Luong, Google DeepMind | AlphaProof, AlphaGeometry & Gemini IMO Gold | |
| 17 | Mon Nov 17 | Agentic Evaluations & Long-Horizon Tasks | [Measuring AI Ability to Complete Long Tasks](https://arxiv.org/abs/2503.14499) · [GDPVal](https://arxiv.org/abs/2510.04374) · [DeepScholar-Bench](https://arxiv.org/abs/2508.20033) | |
| 18 | Fri Nov 21 | Guest: Misha Laskin (Reflection AI) | Building Agentic Systems for Autonomy | |
| — | Mon Nov 24 / Fri Nov 28 | Holiday | | |
| 19 | Mon Dec 1 | Guest: Danny Driess (Physical Intelligence) | Multimodal AI Agents in Robotics | |
| 20 | Fri Dec 5 | Future Research Areas | | |
| — | Wed Dec 10 / Fri Dec 12 | Final project due / Poster | | |

## Course description (verbatim summary)
Covers self-improvement techniques for LLMs (constitutional AI, verifiers, test-time compute scaling, search + LLMs, RL train-time scaling); tool use, code, and memory augmentation; multimodal orchestration; multi-step reasoning/planning for agentic workflows; evaluation frameworks. Students read papers, discuss suggested readings, and complete an original research project in teams of 2–4.