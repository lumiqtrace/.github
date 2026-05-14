# LumiqTrace

  **Agent observability for production AI teams.**

  LumiqTrace traces every decision, tool call, and handoff your AI agents make in production. Debug faster, attribute costs, and ship with confidence.

  ## What it does

  - **Agent tracing** — full span tree for every agent run: planning, tool calls, delegations, responses
  - **Per-agent cost & latency** — know exactly which agent spent what, and how long it took
  - **Multi-agent delegation** — HANDOFF and CHAIN spans across agent boundaries, rendered as a swimlane timeline
  - **LLM-as-judge evals** — automatic quality scoring on every trace, no setup required
  - **AI anomaly detection** — surface regressions before users do
  - **LumiqPilot** — query your production trace data in plain English
  - **MCP server** — pull trace data directly into Claude or Cursor

  ## Quickstart

  ```bash
//Releasing Soon
  npm install @lumiqtrace/sdk
  # or
  pip install lumiqtrace

  import lumiqtrace
  lumiqtrace.init(api_key="lqtp_...")
```
  First trace appears in your dashboard within seconds.

  SDKs & integrations

  Models: OpenAI · Anthropic · Gemini · Mistral · OpenRouter
  Frameworks: LangChain · LangGraph · CrewAI · Google ADK · AutoGen · Vercel AI SDK
  Protocol: Native OpenTelemetry (OTel)

  Pricing
  Free tier: 10,000 traces/month · no credit card · 5-min setup
  Paid plans from $39/month.

  Links
  - https://lumiqtrace.com
  - Join the waitlist (https://lumiqtrace.com/)
  - X / Twitter (https://x.com/Lumiqtrace)
  - LinkedIn (https://www.linkedin.com/company/lumiqtrace)
