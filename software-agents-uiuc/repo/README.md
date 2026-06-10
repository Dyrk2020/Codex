# Software Engineering with LLM Agents

- **Instructor:** [Lingming Zhang](https://lingming.cs.illinois.edu/) (lingming)  
- **TA:** [Yuxiang Wei](https://yuxiang.cs.illinois.edu/) (ywei40)
- **Class Time:** Tue/Thu 09:30 AM - 10:45 AM (Central Time)
- **Location:** 3025 Campus Instructional Facility
- **Instructor Office Hours:** Tue/Thu 10:45 AM - 11:45 AM (Central Time)
- **TA Office Hours:** Thu 3:00 PM - 5:00 PM (Central Time) | [Zoom Link](https://illinois.zoom.us/j/6160435916?pwd=RVlRVGgvWE9QN3VJY2l2WGxJbklRdz09)
- **Communication:** [Campuswire](https://campuswire.com/) (Use `netid@illinois.edu` to join)

> [!IMPORTANT]
> Join the **Campuswire** forum before the first class as all notifications, assignments, and project submissions will be managed there.
---

## 📖 Course Overview
Modern Large Language Models (LLMs) and agents have demonstrated remarkable capabilities across diverse fields, with software engineering as one of their most successful applications. This course dives deep into the intersection of LLM agents and software engineering, exploring how recent advances in generative AI can substantially transform the way people build and maintain software systems.

This is a **research-driven course** targeting students interested in research. Students must possess:
* Research background in PL/FM/SE or NLP/ML fields.
* Proficiency in Python programming.
* Completion of NLP/ML coursework.
* Solid background in algorithms and strong problem-solving skills.

*For course restrictions, see:* [go.cs.illinois.edu/csregister](http://go.cs.illinois.edu/csregister)

---

## Tentative Schedule

### Module I: Background and Basics

| Date | Topic | Readings / Resources |
| :--- | :--- | :--- |
| **01/20** | Course Intro | • [How to read a research paper?](https://www.eecs.harvard.edu/~michaelm/postscripts/ReadPaper.pdf)<br> • [Small guide to giving presentations](https://users.ece.cmu.edu/~pueschel/teaching/guides/guide-presentations.pdf)|
| **01/22** | Software Engineering basics (I) | • [Compilers: Principles, Techniques, and Tools](https://dl.acm.org/doi/10.5555/1177220) (book, optional read) <br> • [Introduction to Software Testing](https://dl.acm.org/doi/10.5555/1355340) (book, optional read) <br>|
| **01/27** | Software Engineering basics (II) | • [Feedback-directed Random Test Generation](https://homes.cs.washington.edu/~mernst/pubs/feedback-testgen-icse2007.pdf)<br> • [Finding and Understanding Bugs in C Compilers](https://users.cs.utah.edu/~regehr/papers/pldi11-preprint.pdf) <br> • [Fuzzing with Code Fragments](https://www.usenix.org/conference/usenixsecurity12/technical-sessions/presentation/holler) <br> • [Compiler Validation via Equivalence Modulo Inputs](https://www.vuminhle.com/pdf/pldi14-emi.pdf) <br> |
| **01/29** | LLM basics | • [Attention Is All You Need](https://arxiv.org/abs/1706.03762)<br>• [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)<br>• [Training language models to follow instructions with human feedback](https://arxiv.org/pdf/2203.02155)<br>• [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) |
| **02/03** | Software Testing with LLMs | • [Large Language Models are Zero-Shot Fuzzers: Fuzzing Deep-Learning Libraries via Large Language Models](https://arxiv.org/abs/2212.14834)<br>• [Fuzz4All: Universal Fuzzing with Large Language Models](https://arxiv.org/abs/2308.04748) <br>• [No More Manual Tests? Evaluating and Improving ChatGPT for Unit Test Generation](https://arxiv.org/abs/2305.04207)|
| **02/05** | Software Debugging with LLMs | • [Less Training, More Repairing Please: Revisiting Automated Program Repair via Zero-shot Learning](https://arxiv.org/abs/2207.08281)<br>• [Keep the Conversation Going: Fixing 162 out of 337 bugs for $0.42 each using ChatGPT](https://arxiv.org/abs/2304.00385)<br> |


### Module II: Software Engineering Agents

| Date | Topic | Readings / Resources |
| :--- | :--- | :--- |
| **02/10** | Coding agents | • [SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering](https://arxiv.org/abs/2405.15793)<br>• [OpenHands: An Open Platform for AI Software Developers as Generalist Agents](https://arxiv.org/abs/2407.16741)<br>• *Additional:* [The 100 line AI agent that solves GitHub issues & more](https://github.com/SWE-agent/mini-swe-agent)<br>• *Additional:* [Trae Agent: An LLM-based Agent for Software Engineering with Test-time Scaling](https://arxiv.org/abs/2507.23370) |
| **02/12** | Coding agents with SE insights | • [AutoCodeRover: Autonomous Program Improvement](https://arxiv.org/abs/2404.05427)<br>• [Agentless: Demystifying LLM-based Software Engineering Agents](https://arxiv.org/abs/2407.01489)<br>• *Additional:* [Prometheus: Unified Knowledge Graphs for Issue Resolution in Multilingual Codebases](https://arxiv.org/abs/2507.19942) |
| **02/17** | Coding agents with memory supports | • [EXPEREPAIR: Dual-Memory Enhanced LLM-based Repository-Level Program Repair](https://arxiv.org/abs/2506.10484)<br>• [Confucius Code Agent: Scalable Agent Scaffolding for Real-World Codebases](https://arxiv.org/abs/2512.10398)<br>• *Additional:* [A-MEM: Agentic Memory for LLM Agents](https://arxiv.org/abs/2502.12110)<br>• *Additional:* [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://arxiv.org/abs/2504.19413)<br>• *Additional:* [Memory-R1: Enhancing Large Language Model Agents to Manage and Utilize Memories via Reinforcement Learning](https://arxiv.org/abs/2508.19828)<br>• *Additional:* [Recursive Language Models](https://arxiv.org/abs/2512.24601) |
| **02/19** | **Proposal Presentation** | |
| **02/24** | Coding agents for scientific discovery | • [AlphaEvolve: A coding agent for scientific and algorithmic discovery](https://arxiv.org/abs/2506.13131)<br>• [ShinkaEvolve: Towards Open-Ended And Sample-Efficient Program Evolution](https://arxiv.org/abs/2509.19349) |
| **02/26** | Self-improving coding agents (I) | • [A Self-Improving Coding Agent](https://arxiv.org/abs/2504.15228)<br>• [Darwin Godel Machine: Open-Ended Evolution of Self-Improving Agents](https://arxiv.org/abs/2505.22954)<br>• [Automated Design of Agentic Systems](https://arxiv.org/abs/2408.08435) |
| **03/03** | Self-improving coding agents (II) | • [Live-SWE-agent: Can Software Engineering Agents Self-Evolve on the Fly?](https://arxiv.org/abs/2511.13646)<br>• [Huxley-Gödel Machine: Human-Level Coding Agent Development by an Approximation of the Optimal Self-Improving Machine](https://arxiv.org/abs/2510.21614)<br>• [GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning](https://arxiv.org/abs/2507.19457) |


### Module III: Benchmarks and Datasets

| Date | Topic | Readings / Resources |
| :--- | :--- | :--- |
| **03/05** | Software benchmarks | • [SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770)<br>• [SWE-Bench Pro: Can AI Agents Solve Long-Horizon Software Engineering Tasks?](https://arxiv.org/abs/2509.16941)<br>• [SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks](https://arxiv.org/abs/2506.11791)<br>• *Additional:* [Introducing SWE-bench Verified](https://openai.com/index/introducing-swe-bench-verified/) |
| **03/10** | Multilingual benchmarks | • [Multi-SWE-bench: A Multilingual Benchmark for Issue Resolving](https://arxiv.org/abs/2504.02605)<br>• [SWE-PolyBench: A multi-language benchmark for repository-level evaluation of coding agents](https://arxiv.org/abs/2504.08703) |
| **03/12** | Automated benchmark construction | • [SWE-bench Goes Live!](https://arxiv.org/abs/2505.23419)<br>• [SWE-rebench: An Automated Pipeline for Task Collection and Decontaminated Evaluation of Software Engineering Agents](https://arxiv.org/abs/2505.20411) |
| **03/17** | **Spring Break** | |
| **03/19** | **Spring Break** | |
| **03/24** | Environments for training coding agents | • [Training Software Engineering Agents and Verifiers with SWE-Gym](https://arxiv.org/abs/2412.21139)<br>• [R2E-Gym: Procedural Environments and Hybrid Verifiers for Scaling Open-Weights SWE Agents](https://arxiv.org/abs/2504.07164)<br>• [SWE-Universe: Scale Real-World Verifiable Environments to Millions](https://www.arxiv.org/abs/2602.02361)<br>• *Additional:* [Skywork-SWE: Unveiling Data Scaling Laws for Software Engineering in LLMs](https://arxiv.org/abs/2506.19290) |
| **03/26** | Synthetic training data generation (I) | • [SWE-smith: Scaling Data for Software Engineering Agents](https://arxiv.org/abs/2504.21798)<br>• [SWE-Synth: Synthesizing Verifiable Bug-Fix Data to Enable Large Language Models in Resolving Real-World Bugs](https://arxiv.org/abs/2504.14757) <br>• [SERA: Soft-Verified Efficient Repository Agents](https://arxiv.org/abs/2601.20789) |
| **03/31** | **Project Midterm Presentation** | |
| **04/02** | **Project Midterm Presentation** | |
| **04/07** | Synthetic training data generation (II) | • [SWE-Mirror: Scaling Issue-Resolving Datasets by Mirroring Issues Across Repositories](https://arxiv.org/abs/2509.08724)<br>• [BugPilot: Complex Bug Generation for Efficient Learning of SWE Skills](https://arxiv.org/abs/2510.19898) <br>• [Training Versatile Coding Agents in Synthetic Environments](https://arxiv.org/abs/2512.12216)|


### Module IV: Training Software Agents with RL

| Date | Topic | Readings / Resources |
| :--- | :--- | :--- |
| **04/09** | RL on simple code and math data | • [DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning](https://arxiv.org/abs/2501.12948)<br>• [Kimi k1.5: Scaling Reinforcement Learning with LLMs](https://arxiv.org/abs/2501.12599) |
| **04/14** | Scaling RL to real-world software data (I) | • [SWE-RL: Advancing LLM Reasoning via Reinforcement Learning on Open Software Evolution](https://arxiv.org/abs/2502.18449)<br>• [Kimi-Dev: Agentless Training as Skill Prior for SWE-Agents](https://arxiv.org/abs/2509.23045) |
| **04/16** | Scaling RL to real-world software data (II) | • [DeepSWE: Training a Fully Open-sourced, State-of-the-Art Coding Agent by Scaling RL](https://www.together.ai/blog/deepswe)<br>• [SWE-RM: Execution-free Feedback For Software Engineering Agents](https://www.arxiv.org/abs/2512.21919) <br>• [MiniMax-M1: Scaling Test-Time Compute Efficiently with Lightning Attention](https://arxiv.org/abs/2506.13585) |
| **04/21** | Training LLMs with agentic intelligence | • [CWM: An Open-Weights LLM for Research on Code Generation with World Models](https://arxiv.org/abs/2510.02387)<br>• [Kimi K2: Open Agentic Intelligence](https://arxiv.org/abs/2507.20534)<br>• [Qwen3-Coder-Next Technical Report](https://github.com/QwenLM/Qwen3-Coder/blob/main/qwen3_coder_next_tech_report.pdf) |
| **04/23** | Training superintelligent coding agents | • [Toward Training Superintelligent Software Agents through Self-Play SWE-RL](https://arxiv.org/abs/2512.18552)<br>• [Self-Adapting Language Models](https://arxiv.org/abs/2506.10943) |
| **04/28** | **Project Final Presentation** | |
| **04/30** | **Project Final Presentation** | |
| **05/05** | Yinfang Chen (Invited Speaker) | [Zoom Link](https://illinois.zoom.us/j/88213728791?pwd=Tl2JabHUFyhESXGo3RC4Nwq7qRUdkm.1) |

---

## 🏫 Class Organization
There is **no required textbook**. The course is discussion-based, and students are expected to read assigned papers **before** each class.

During class, students may be randomly selected to discuss the following aspects of a paper:
1.  **Problem:** What is the problem and why does it matter?
2.  **Solution:** What is the proposed solution and how does it differ from prior work?
3.  **Evaluation:** What benchmarks and metrics were used? Is it convincing?
4.  **Results:** What were the results and did they meet expectations?
5.  **Critique:** What are the strengths (pros) and limitations (cons)?
6.  **Future Work:** What are the potential next steps?

---

## 📊 Grading Details
There is **no exam**. Grades are calculated based on the following:

| Component | Weight | Description |
| :--- | :--- | :--- |
| **Homework Assignments** | 20% | Released via Campuswire ("Assignments" page). No late submissions without prior approval/documentation. |
| **Paper Presentation** | 20% | Lead discussion for one paper. **Select at least five classes you would like to present by Jan. 30th** (submission link shown in Campuswire "Assignments"). **Upload your initial slides to Campuswire a week before your presentation slot for comments, and upload the final version of the slides 48 hours before the lecture**. Make it clear if you reuse any of the original slides from the authors. |
| **Class Participation** | 10% | This is a discussion-based course, so it does matter that you show up in our class meetings and participate in the discussion. |
| **Course Project** | 50% | The best way to learn software engineering is go there and do software engineering! You will undertake your own course project in a group (3-5 students). We will provide a list of directions (available on Campuswire) to get you started thinking, but I highly encourage you to pursue your own ideas. You are encouraged to use GitHub to host your development history and all the code/data. **For the teams proposing your own ideas, you are required to meet with Lingming before Feb. 9th to discuss your proposal.** |

### Project Breakdown
* **Proposal submission/presentation:** 5% 
* **Midterm project report/presentation:** 20%.
* **Final project report/presentation:** 25%.

### Grading Scale
| Grade | Percent | Grade | Percent |
| :--- | :--- | :--- | :--- |
| **A** | 93% | **C+** | 77% |
| **A-** | 90% | **C** | 73% |
| **B+** | 87% | **C-** | 70% |
| **B** | 83% | **D+** | 67% |
| **B-** | 80% | **D** | 63% |
| **F** | <60% | **D-** | 60% |

---

