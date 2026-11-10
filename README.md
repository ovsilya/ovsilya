# Ilya Ovsyannikov

**Forward Deployed Engineer · Solutions Architect · Applied AI**. I design and ship agentic AI systems inside enterprise environments, on GCP and AWS.

I embed with a business team, find the use case worth building, design it with the stakeholders, and take it to production. The path runs from discovery and data access through architecture, security review and deployment to handover. I'm currently the acting lead Forward Deployed Engineer in TELUS Digital's AI Accelerator FDE program, embedded with the Marketing business unit. Before that, I spent four years delivering LLM assistants, agentic microservices and evaluation platforms for enterprise clients in media, energy, satellite radio and ed-tech.

What I bring to a customer engagement:
- **Discovery and solution design:** turning a vague mandate into one owned use case, then into a design leadership approves.
- **Agentic architecture:** LangGraph state graphs, Google ADK agents and tools, A2A, RAG and guardrails. Where a decision must be auditable, rules decide and the LLM explains.
- **Production delivery:** FastAPI microservices on Cloud Run and GKE, IAM and identity-aware access, privacy by design, Terraform and CI/CD.
- **Evaluation:** ground-truth test suites, precision/recall harnesses and LLM-as-judge, so a model choice rests on numbers.

## Featured projects

*Sanitized versions of production systems from client and internal engagements. All client identifiers, data and credentials are removed.*

| Project | What it is | Stack |
|---|---|---|
| [website-visitor-lead-check-agent](https://github.com/ovsilya/website-visitor-lead-check-agent) | **Current FDE engagement.** An agent that turns ~3,000 identified website visitors a week into a short, explainable shortlist across 127+ key accounts: rules decide and write each reason and next step, Gemini explains. Includes per-user isolation from verified IAP tokens, memory-only personal data, 13 business-editable rule lists, and hub-and-spoke target architecture diagrams. | Google ADK · Gemini (Vertex AI) · Cloud Run · IAP · pandas · pytest |
| [ai-assistant-langgraph-backend](https://github.com/ovsilya/ai-assistant-langgraph-backend) | Conversational AI backend for a major media publisher: a per-request LangGraph agent with LLM-as-judge guardrails, intent routing, grounded RAG answers with article recommendations, multi-brand personas and a GDPR deletion worker. 304 tests, 95% coverage. | LangGraph · FastAPI · Claude / Gemini · DynamoDB · Redis · Kubernetes |
| [multi-agent-support-platform](https://github.com/ovsilya/multi-agent-support-platform) | A Slack-native multi-agent support platform for industrial pipeline operations, plus a Document AI pipeline that fills engineering workbooks from RFI documents, evaluated against ground truth. | Google ADK · Gemini · Cloud Run · BigQuery vector RAG · Document AI |
| [email-qa-llm-pipeline](https://github.com/ovsilya/email-qa-llm-pipeline) | An LLM email-QA system that scans 40k+ marketing emails for 15 issue types, with parallel Bedrock workers, checkpoint/resume, versioned prompts and a precision/recall evaluation harness. | AWS Bedrock (Claude) · S3 · pandas · boto3 |
| [llm-sentence-generation-eval](https://github.com/ovsilya/llm-sentence-generation-eval) | A dual-LLM benchmarking platform (GPT-4.1 vs Gemini 2.5) with parallel generation over CEFR-levelled data, token and cost accounting including thinking tokens, and an 8-metric NLP evaluation harness. | OpenAI · Vertex AI / Gemini · scikit-learn · NLTK |

**More:**
- [AI_news](https://github.com/ovsilya/AI_news): a personal daily AI brief that collects, ranks and summarises news with Gemini.
- [blu_baar_chatbot](https://github.com/ovsilya/blu_baar_chatbot): a bilingual chatbot API on Cloud Run with Cloud Build CI/CD.
- [aml-assistant](https://github.com/ovsilya/aml-assistant): a compliance RAG chatbot.
- [CBC-news-RAG](https://github.com/ovsilya/CBC-news-RAG): RAG over news articles and editorial guidelines.
- [receipt_scanner](https://github.com/ovsilya/receipt_scanner): a serverless Document AI workflow on GCP.
- [respondelligent_cpu](https://github.com/ovsilya/respondelligent_cpu): mBART fine-tuning and deployment.
- [code_portfolio_examples](https://github.com/ovsilya/code_portfolio_examples): classic ML and SQL samples.

## Toolbox

**Agents and LLMs:** Google ADK (agents, tools, plugins, A2A) · LangGraph · LangChain · Gemini (Vertex AI) · Claude (Bedrock) · OpenAI · LiteLLM gateway · RAG · guardrails · prompt engineering · LLM evaluation (ground truth, precision/recall, LLM-as-judge)
**Enterprise agent platforms:** Gemini Enterprise · Vertex AI Agent Engine · Salesforce Agentforce (Agent Builder, Prompt Builder, Flow / Apex actions, Data 360, Einstein Trust Layer, Testing Center)
**Cloud and architecture:** GCP (Cloud Run, GKE, Vertex AI, BigQuery, Document AI, IAP, IAM, Cloud Build, Artifact Registry) · AWS (Bedrock, S3, DynamoDB, SageMaker) · hub-and-spoke projects · Terraform · CI/CD · Workload Identity Federation
**Engineering:** Python · FastAPI · Docker · Kubernetes · pytest · pandas · Redis / Valkey · DynamoDB · Datadog · Sentry · OpenTelemetry
**Security and data governance:** identity-aware access (signed JWTs) · least-privilege service accounts · prompt-injection hardening · privacy by design · data-enablement reviews
**Delivery:** discovery workshops · use-case prioritisation · stakeholder management · architecture decision records · plain-language proposals and demos · Jira / Gantt planning

## Contact

[LinkedIn](https://www.linkedin.com/in/ovsilya) · [ovsyannikovilyavl@gmail.com](mailto:ovsyannikovilyavl@gmail.com)

*MSc; two IEEE publications on deep learning for computer vision.*
