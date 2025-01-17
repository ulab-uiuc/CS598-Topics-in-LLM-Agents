# Topics in LLM Agents(25'Spring)
## Course Console
**Lectures**: Room 1304 | Siebel Center for Comp Sci , Tuesday/Thursday 03:30 PM - 04:45 PM.
| Member (NetID) | Role | Office Hours |
| :---------------- | :--- | :----------- |
| [Jiaxuan You](https://cs.stanford.edu/~jiaxuan/) (jiaxuan) | Instructor | 
| [Jinwei Yao](https://kivi-yao.github.io/) (jinweiy) | TA | 

**Canvas**: for homework/report submission;

**Github**: (1) most of course information is here, including schedule and paper lists; (2) Github issues for any questions.

**OpenReview**: for the simulation of review and response as part of the course  projects.

<span style="color:red;">**Note:** Please use **GitHub Issues** to submit your questions. Please **DON'T** email the TA or Professor You, unless the matter is private.</span>
## Course Description
**Learning Objectives**: This course offers an in-depth exploration of the fascinating field of LLM agents. Designed as a seminar-style course, it guides students through the fundamental methods that power LLM agents and examines their practical applications in real-world contexts. At the end of this course, you will be able to:
- Have a great overview of state-of-the-art LLM agent papers;
- Familiar with the process of research process including paper submission, paper review and rebuttal;
- Critique and evaluate the design details of LLM agent papers.

**Structure**: The course is structured around reading cutting-edge research papers, student-led presentations, interactive discussions, and collaborative semester-long projects. We begin with an introduction to the core concepts of LLM agents, then delve into the latest research on building agents, covering topics including:  
- Agent ability
  - Reasoning
  -  Memory
  -  Planning
  -  Multimodal understanding
- Agent evaluation
- Agent framework
  - Tool use
  - Retrieval-augmented generation
  - Multi-agent systems
- Agent application
  - Auto-research
  - Code generation
  - Web agents
  - Gaming agents
- Challenges from agents to AGI
  - Data
  - Safety
  - Human-agent interaction
  - Alignment

## Tentative Schedule and Reading List
*Note: (1) This is an evolving list; (2) For each topic, there would be 2-3 "required" papers that presenter should include in their in-class presentation.*

| Date    | Readings                                                                                                             | Pilot-Presenter                               | Copilot-Companion                            | Copilot-Reviewer                                   |
| ------- | -------------------------------------------------------------------------------------------------------------------- | --------------------------------------- | ------------------------------------- | ------------------------------------------- |
|         |  **Course Introduction** |              |	|
| Jan 21  | (Required) Section 1 of [How far are we from AGI?](https://openreview.net/pdf?id=H2ZKqfNd0U) <br> (Required) [How to Write a Paper](https://cs.stanford.edu/people/widom/paper-writing.html)<br> (Required) [Language Agents: Foundations, Prospects, and Risks](https://language-agent-tutorial.github.io/slides/I-Introduction.pdf) <br>[How to Give a Bad Talk](http://www.cs.berkeley.edu/~pattrsn/talks/BadTalk.pdf) | [Jiaxuan]()        |                                       |                                           |
|         |  **Overview of LLM Agents** |              |	|
| Jan 23  | [AI Agent Overview I]<br> (Required) Section 2-3 of [How far are we from AGI?](https://openreview.net/pdf?id=H2ZKqfNd0U) | [Jiaxuan]() |                                       |                                           |
| Jan 28  | [AI Agent Overview II]<br> (Required) Section 4-5 of [How far are we from AGI?](https://openreview.net/pdf?id=H2ZKqfNd0U) | [Jiaxuan]() |                                       |                                           |
| Jan 30  | [AI Agent Overview III]<br> (Required) Section 6-7 of [How far are we from AGI?](https://openreview.net/pdf?id=H2ZKqfNd0U) | [Jiaxuan]() |                                       |                                           |
| Feb 4  | **No Lecture / Work on Project Proposal** |  |
| Feb 6  | **No Lecture / Work on Project Proposal** |  |
|         |  **Agent Ability** |              |	|
| Feb 11  | [Reasoning]<br> (Required) [Tree of Thoughts: Deliberate Problem Solving with Large Language Models]( https://arxiv.org/abs/2305.10601)<br>(Required) [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)<br> [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903) |  |
| Feb 13   | [Memory]<br>(Required) [HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models](https://arxiv.org/abs/2405.14831)<br>(Required) [Cognitive Architectures for Language Agents](https://arxiv.org/abs/2309.02427)<br>[Fine-Tuning and Prompt Optimization: Two Great Steps that Work Better Together](https://arxiv.org/abs/2407.10930) |           |           |          |
| Feb 18   | [Planning]<br>(Required) [LLM+P: Empowering Large Language Models with Optimal Planning Proficiency](https://arxiv.org/abs/2304.11477)<br>(Required) [Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models](https://arxiv.org/abs/2310.04406)<br>[TravelPlanner: A Benchmark for Real-World Planning with Language Agents](https://arxiv.org/abs/2402.01622) |           |           |          |
| Feb 20   | [Multi-modal Understanding]<br>(Required) [Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs](https://arxiv.org/abs/2401.06209)<br>(Required) [GroundingGPT: Language Enhanced Multi-modal Grounding Model](https://arxiv.org/abs/2401.06071) |           |           |          |
|          | **Agent Evaluation**                                                                                         |           |           |          |
| Feb 25   | [via benchmarks/LLMs/VLMs]<br>(Required) [Autonomous Evaluation and Refinement of Digital Agents](https://arxiv.org/abs/2404.06474)<br>(Required) [Chatbot Arena: An Open Platform for Evaluating LLMs by Human Preference](https://arxiv.org/abs/2403.04132)<br>[AI Agents That Matter](https://arxiv.org/pdf/2407.01502) |           |           |          |
|          | **Agent Framework**                                                                                          |           |           |          |
| Feb 27   | [Tool Use]<br>(Required) [ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs](https://arxiv.org/abs/2307.16789)<br>(Required) [Gorilla: Large Language Model Connected with Massive APIs](https://openreview.net/forum?id=tBRNC6YemY)<br>[ToolkenGPT: Augmenting Frozen Language Models with Massive Tools via Tool Embeddings](https://arxiv.org/abs/2305.11554) |           |           |          |
| March 4  | [Retrieval-Augmented Generation]<br>(Required) [Adaptive-RAG: Learning to Adapt Retrieval-Augmented Large Language Models through Question Complexity](https://arxiv.org/abs/2403.14403)<br>(Required) [Corrective Retrieval-Augmented Generation](https://arxiv.org/pdf/2401.15884)<br>[Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection](https://arxiv.org/pdf/2310.11511) |           |           |          |
| March 6  | **No Lecture / Work on Mid-term Presentation**                                                               |           |           |          |
| March 11 | [Mid-term Presentation]                                                                                      |           |           |          |
| March 13 | [Mid-term Presentation]                                                                                      |           |           |          |
| March 25 | [Multi-agent Systems]<br>(Required) [AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework](https://huggingface.co/papers/2308.08155)<br>(Required) [CAMEL: Communicative Agents for "Mind" Exploration of Large Language Model Society](https://arxiv.org/abs/2303.17760)<br>[Improving Factuality and Reasoning in Language Models through Multiagent Debate](https://arxiv.org/abs/2305.14325) |           |           |          |
|          | **Agent Application**                                                                                        |           |           |          |
| March 27 | [Auto-research]<br>(Required) [ResearchTown: Simulator of Human Research Community](https://github.com/ulab-uiuc/research-town)<br>(Required) [Can Large Language Models Provide Useful Feedback on Research Papers? A Large-scale Empirical Analysis](https://arxiv.org/pdf/2310.01783)<br>[The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery](https://arxiv.org/abs/2408.06292) |           |           |          |
| April 1  | [Code Generation]<br>(Required) [SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770)<br>(Required) [If LLM Is the Wizard, Then Code Is the Wand: A Survey on How Code Empowers Large Language Models to Serve as Intelligent Agents](https://arxiv.org/abs/2401.00812)<br>[A Survey on Large Language Models for Code Generation](https://arxiv.org/pdf/2406.00515) |           |           |          |
| April 3  | [Social Simulation]<br>(Required) [SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents](https://arxiv.org/abs/2310.11667)<br>(Required) [SOTOPIA-π: Interactive Learning of Socially Intelligent Language Agents](https://aclanthology.org/2024.acl-long.698.pdf) |           |           |          |
| April 8  | [Gaming Agents]<br>(Required) [Voyager: An Open-Ended Embodied Agent with Large Language Models](https://voyager.minedojo.org)<br>(Required) [MineDojo: Building Open-Ended Embodied Agents with Internet-Scale Knowledge](https://arxiv.org/abs/2206.08853)<br>[A Survey on Large Language Model-Based Game Agents](https://arxiv.org/pdf/2404.02039) |           |           |          |
|          | **Challenges from Agents to AGI**                                                                            |           |           |          |
| April 10 | [Data]<br>(Required) [BAGEL: Bootstrapping Agents by Guiding Exploration with Language](https://arxiv.org/abs/2403.08140)<br>(Required) [SOAR: Autonomous Improvement of Instruction Following Skills via Foundation Models](https://auto-improvement.github.io/)<br>[Latent Action Pretraining from Videos](https://arxiv.org/abs/2410.11758) |           |           |          |
| April 15 | [Safety]<br>(Required) [Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043)<br>(Required) [Extracting Training Data from Large Language Models](https://www.usenix.org/conference/usenixsecurity21/presentation/carlini-extracting)<br>[The Emerged Security and Privacy of LLM Agent: A Survey with Case Studies](https://arxiv.org/html/2407.19354v1) |           |           |          |
| April 17 | [Human-Agent Interaction]<br>(Required) [Why Johnny Can’t Prompt: How Non-AI Experts Try (and Fail) to Design LLM Prompts](https://dl.acm.org/doi/10.1145/3544548.3581388)<br>(Required) [AI Chains: Transparent and Controllable Human-AI Interaction by Chaining Large Language Model Prompts](https://arxiv.org/abs/2110.01691)<br>[Evaluating Human-Language Model Interaction](https://arxiv.org/abs/2212.09746) |           |           |          |
| April 22 | [Alignment]<br>(Required) [Training Language Models to Follow Instructions with Human Feedback](https://arxiv.org/abs/2203.02155)<br>(Required) [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/pdf/2305.18290)<br>[Position: A Roadmap to Pluralistic Alignment](https://arxiv.org/pdf/2402.05070) |           |           |          |
| April 24 | **No Lecture / Work on Final Presentation** |  |
| April 29 | **No Lecture / Work on Final Presentation** |  |
| May 1 | **Final Presentation** |  |
| May 6 | **Final Presentation** |  |
 ## Tentative Grading
 | Component                 | Weight | Breakdown                      |
|---------------------------|--------|--------------------------------|
| Pre-class Idea/Question Proposal | 10%   |                                |
| In-class Discussion       | 25%   | - 15% In-class Pilot Presentation<br>- 10% In-class Co-pilot Summary |
| Projects                  | 65%   | - 5% Proposal Report<br>- 5% Midterm Presentation<br>- 30% Final Survey Report<br>- 10% Review and Response<br>- 15% Final Presentation |


## Policies

### Pre-class: Pre-class Idea/Question Proposal

### In-class: Presentation & Discussion
In each class after **Overview of LLM Agents** taught by Prof.You, the students are expected to conduct the presentation and discussion. 

This discussion will involve three distinct roles played by different **student groups**, simulating an interactive and dynamic scholarly exchange. Each group will be assigned to the following three roles once:
1. **The Pilot Presenter:**
2. **The Co-pilot Authors:**
3. **The Co-pilot Reviewers:**

**Rest of the Class:** feel free to actively ask questions and engage in the dialogue.
#### Guidelines for the Pilot Presenter
#### Guidelines for the Co-pilot Authors
#### Guidelines for the Co-pilot Reviewers

### Project: A Survey on LLM Agents

### Summary of Deadlines

### **Acknowledgements**
In course structure design, this course is heavily inspired by other seminar-like courses, particularly [UIUC CS598-GenAI System](https://github.com/fanlai0990/CS598). Acknowledgments to [Prof.Fan Li](https://fanlai.me/) for his generous sharing of his great course. For course topics and paper lists, we mainly refer to [UC Berkeley CS294/194-196 Large Language Model Agents](https://rdi.berkeley.edu/llm-agents/f24) and [EMNLP 2024 Tutorial:
Language Agents: Foundations, Prospects, and Risks](https://language-agent-tutorial.github.io/).
