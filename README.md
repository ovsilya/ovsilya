# Hi, I'm Ilya Ovsyannikov 👋

**GenAI / Machine Learning Engineer** — production LLM and agentic systems on GCP & AWS.

I spend my days shipping LLM systems end-to-end: data prep, model integration, agent orchestration, evaluation, deployment (GKE / Cloud Run), and observability. Recent work centers on **agentic architectures** (LangGraph state graphs, Google ADK hierarchical agents), **RAG**, and **LLM evaluation at scale**.

## 🚀 Featured projects

*Sanitized portfolio versions of production systems built during client engagements at TELUS Digital — all client identifiers, data, and credentials removed.*

| Project | What it is | Stack |
|---|---|---|
| [ai-assistant-langgraph-backend](https://github.com/ovsilya/ai-assistant-langgraph-backend) | Conversational AI backend for a major media publisher: per-request LangGraph agent with LLM-as-judge guardrails, intent routing, grounded RAG answers with article recommendations, multi-brand personas, GDPR deletion worker. 304 tests, 95% coverage | LangGraph · FastAPI · Claude/Gemini · DynamoDB · Redis · k8s |
| [multi-agent-support-platform](https://github.com/ovsilya/multi-agent-support-platform) | Slack-native multi-agent support platform for industrial pipeline operations + a Document AI pipeline that fills engineering workbooks from RFI documents, with ground-truth evaluation | Gemini · Google ADK · Cloud Run · BigQuery vector RAG · Document AI |
| [email-qa-llm-pipeline](https://github.com/ovsilya/email-qa-llm-pipeline) | LLM email-QA system scanning 40k+ marketing emails for 15 issue types: parallel Bedrock workers, checkpoint/resume, versioned prompts, precision/recall evaluation harness | AWS Bedrock (Claude) · S3 · pandas · boto3 |
| [llm-sentence-generation-eval](https://github.com/ovsilya/llm-sentence-generation-eval) | Dual-LLM benchmarking platform (GPT-4.1 vs Gemini 2.5): parallel generation over CEFR-leveled data, token/cost accounting incl. thinking tokens, 8-metric NLP evaluation harness | OpenAI · Vertex AI/Gemini · scikit-learn · NLTK |

**More:** [CBC-news-RAG](https://github.com/ovsilya/CBC-news-RAG) (RAG over news + editorial guidelines) · [aml-assistant](https://github.com/ovsilya/aml-assistant) (compliance RAG chatbot) · [receipt_scanner](https://github.com/ovsilya/receipt_scanner) (serverless GCP Document AI workflow) · [respondelligent_cpu](https://github.com/ovsilya/respondelligent_cpu) (mBART fine-tuning & deployment) · [code_portfolio_examples](https://github.com/ovsilya/code_portfolio_examples) (classic ML & SQL)

## 🛠️ Toolbox

**LLM / agents:** LangGraph · LangChain · Google ADK · OpenAI · Claude (Bedrock) · Gemini (Vertex AI) · RAG · prompt engineering · LLM evaluation
**Cloud:** GCP (Vertex AI, Cloud Run, GKE, BigQuery, Document AI, Cloud Functions) · AWS (Bedrock, S3, DynamoDB, SageMaker)
**Engineering:** Python · FastAPI · Docker · Kubernetes · pytest · pandas · scikit-learn · Datadog/Sentry observability

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/ovsilya) · ovsyannikovilyavl@gmail.com

*MSc, two IEEE publications on deep learning for computer vision.*
