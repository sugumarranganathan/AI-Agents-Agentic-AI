Different frameworks (LangGraph, AutoGen, CrewAI, OpenAI Agents SDK, Google ADK, Microsoft Semantic Kernel, etc.) implement similar ideas using different terminology.

However, the following 15 Multi-Agent Design Patterns are the most widely used in Agentic AI systems today.

| **No.** | **Multi-Agent Design Pattern**                  | **Primary Use Case**                                                                                                                                        |
| ------: | ----------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
|       1 | **Sequential Pipeline**                         | Tasks are executed step-by-step, where each agent passes its output to the next. Ideal for document processing, ETL, legal review, and workflow automation. |
|       2 | **Hierarchical (Manager–Worker)**               | A coordinator assigns work to specialized agents and combines their outputs. Used in enterprise assistants and project management.                          |
|       3 | **Collaborative (Peer-to-Peer)**                | Agents communicate directly and work together without a central controller. Suitable for distributed systems and collaborative planning.                    |
|       4 | **Orchestrator–Worker**                         | An orchestrator dynamically selects and invokes the appropriate agents based on the task. Common in enterprise AI workflows.                                |
|       5 | **Supervisor Pattern**                          | A supervisor monitors, validates, retries, or reroutes work when agents fail. Improves reliability and fault tolerance.                                     |
|       6 | **Reviewer–Critic Pattern**                     | One agent generates content while another reviews and critiques it before approval. Used for code review, legal review, and writing assistants.             |
|       7 | **Consensus / Voting Pattern**                  | Multiple agents solve the same problem independently, and the final answer is chosen by voting or confidence scoring. Improves accuracy.                    |
|       8 | **Nested Agents**                               | A parent agent invokes specialized sub-agents to complete complex subtasks. Useful for legal Q&A, research, and report generation.                          |
|       9 | **Reflection / Self-Improvement Pattern**       | An agent evaluates and refines its own output before returning the final answer. Improves reasoning quality.                                                |
|      10 | **Retrieval-Augmented Generation (RAG) Agents** | Agents retrieve relevant documents from a knowledge base before generating responses. Used in customer support, enterprise search, and legal systems.       |
|      11 | **Event-Driven Multi-Agent**                    | Agents react automatically to events such as new emails, market updates, IoT events, or notifications. Ideal for monitoring systems.                        |
|      12 | **Guardrail-Based Agents**                      | Dedicated safety, compliance, and policy agents validate outputs before release. Used in healthcare, HR, finance, and legal applications.                   |
|      13 | **Human-in-the-Loop (HITL)**                    | AI agents perform most tasks, while humans approve or correct critical decisions. Essential for high-risk domains.                                          |
|      14 | **Fault-Tolerant / Resilient Agents**           | Includes retries, fallback agents, health monitoring, and load balancing to ensure continuous operation during failures.                                    |
|      15 | **Adaptive / Learning Multi-Agent**             | Agents learn from user feedback, interaction history, and changing environments to improve future decisions and personalization.                            |


==========

Summary by Domain

| **Domain**           | **Common Multi-Agent Pattern**               | **Example Project**                 |
| -------------------- | -------------------------------------------- | ----------------------------------- |
| Legal                | Sequential Pipeline, Nested, Reviewer–Critic | Legal Contract Review, Legal Q&A    |
| Healthcare           | Supervisor, Consensus, HITL                  | Medical Diagnosis Assistant         |
| Finance              | Event-Driven, RAG, Guardrails                | Investment Advisor, Fraud Detection |
| HR                   | Guardrail-Based, HITL                        | Secure HR Document Generator        |
| Education            | Adaptive, Hierarchical                       | AI Tutoring System                  |
| E-Commerce           | Fault-Tolerant, Orchestrator, RAG            | Shopping Assistant, Order Tracking  |
| Software Development | Reviewer–Critic, Consensus                   | AI Code Review Platform             |
| Enterprise Knowledge | RAG, Orchestrator                            | Enterprise Knowledge Chatbot        |
| Manufacturing        | Collaborative                                | Smart Factory Automation            |
| Marketing            | Event-Driven, Adaptive                       | AI Marketing Campaign Planner       |


==========

Common Specialized Agents Used Across These Patterns

| **Agent Name**                   | **Purpose**                                                  |
| -------------------------------- | ------------------------------------------------------------ |
| Planner Agent                    | Breaks complex goals into smaller tasks                      |
| Coordinator / Orchestrator Agent | Assigns and coordinates tasks among agents                   |
| Task Agent                       | Executes a specific task                                     |
| Retrieval Agent                  | Fetches relevant information from databases or vector stores |
| RAG Agent                        | Combines retrieval with LLM reasoning                        |
| Research Agent                   | Collects information from multiple sources                   |
| Memory Agent                     | Maintains long-term and short-term context                   |
| Review Agent                     | Reviews generated output                                     |
| Critic Agent                     | Identifies mistakes and suggests improvements                |
| Validation Agent                 | Checks correctness and completeness                          |
| Safety / Guardrail Agent         | Enforces security, privacy, and policy compliance            |
| Compliance Agent                 | Ensures regulatory compliance                                |
| Monitoring Agent                 | Tracks agent health and performance                          |
| Feedback Agent                   | Learns from user feedback                                    |
| Human Approval Agent             | Requests human approval for sensitive actions                |


=========

