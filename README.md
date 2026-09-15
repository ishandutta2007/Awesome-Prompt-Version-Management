# Awesome-Prompt-Version-Management

## Top Prompt Version Management Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Prompt Versioning, Registries, Experiments, Observability & LLM Application Lifecycle*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Prompt Version Management**. These tools help teams store, version, label, experiment with, and deploy prompts for LLM applications, often combined with tracing, evaluations, and observability.

**Examples** include Langfuse, PromptLayer, Humanloop, Portkey, Lunary, Helicone, PromptHub, Braintrust, LangSmith, and OpenPipe (the category leaders).

**Open-source emphasis**: Prompt management has strong open-source options. **Langfuse** is the leading self-hostable platform with first-class prompt versioning. Additional open tools and gateways support related workflows. This section prioritizes practical open alternatives.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Langfuse](https://www.langfuse.com/)**  
  Open-source LLM observability and prompt management platform with versioning, labels, experiments, tracing, and evaluations (cloud and self-hosted).

- **[PromptLayer](https://www.promptlayer.com/)**  
  Prompt management and observability platform focused on versioning, release labels, A/B testing, and collaboration for non-technical editors.

- **[Humanloop](https://humanloop.com/)**  
  Prompt engineering and evaluation platform (note: check current status as some tools in the space have evolved or wound down).

- **[Portkey](https://portkey.ai/)**  
  AI gateway and observability platform that includes prompt management, routing, and production controls for LLM applications.

- **[Lunary](https://www.lunary.ai/)**  
  Open-source-friendly LLM observability and prompt management tool for tracking and improving prompts in production.

- **[Helicone](https://www.helicone.ai/)**  
  LLM observability platform with logging, cost tracking, and prompt-related features (proxy-based integration).

- **[PromptHub](https://www.prompthub.us/)** (or similar registry tools)  
  Platforms focused on sharing, versioning, and discovering prompts.

- **[Braintrust](https://www.braintrust.dev/)**  
  Evaluation-first platform for prompt testing, versioning, and systematic improvement of LLM applications.

- **[LangSmith](https://www.langchain.com/langsmith)**  
  LangChain’s platform for tracing, evaluation, and prompt management, tightly integrated with LangChain/LangGraph workflows.

- **[OpenPipe](https://openpipe.ai/)**  
  Platform focused on fine-tuning and related LLM workflows that often intersects with prompt and model management.

## Open-Source GitHub Projects
- **[Langfuse](https://github.com/langfuse/langfuse)**  
  Leading open-source LLM engineering platform (MIT) with first-class prompt management: versioning, labels, protected releases, experiments, tracing, and evaluations. Fully self-hostable.

- **[Helicone](https://github.com/Helicone/helicone)**  
  Open-source LLM observability proxy that provides logging, analytics, and related production visibility (can complement prompt workflows).

- **[Agenta](https://github.com/Agenta-AI/agenta)**  
  Open-source LLMOps platform focused on prompt engineering, versioning, evaluation, and collaboration.

- **[Portkey / open gateway components](https://github.com/)**  
  Open or partially open AI gateway projects that support prompt routing and management features.

- **[Prompt registry and versioning open experiments](https://github.com/)**  
  Community tools for storing prompts as versioned artifacts with simple APIs.

- **[Evaluation and dataset open frameworks](https://github.com/)**  
  Open evaluation libraries that pair well with prompt versioning for systematic testing.

- **[LiteLLM and proxy open tools](https://github.com/)**  
  Open proxies that can sit in front of multiple LLM providers and support logging/versioning patterns.

- **[Self-hosted observability stacks for LLMs](https://github.com/)**  
  Combinations of open tracing, logging, and prompt storage that teams assemble for internal use.

- **[Prompt-as-code and Git-based workflows](https://github.com/)**  
  Approaches and tools that treat prompts as version-controlled code artifacts.

- **[Arize Phoenix and related open observability](https://github.com/Arize-ai/phoenix)**  
  Open-source observability and evaluation tools that can integrate with prompt management practices.

### Additional Strong Open-Source Options
- Starting with **Langfuse** for a complete, self-hostable prompt management + observability solution.
- Using **Agenta** when prompt-centric collaboration and evaluation are the primary needs.
- Combining open proxies (Helicone-style or LiteLLM) with a prompt registry for lighter-weight setups.
- Treating prompts as code in Git for simple versioning when a full platform is not yet required.
- Accepting that polished non-technical editors, advanced traffic-splitting, and enterprise collaboration features still favor commercial platforms (PromptLayer, LangSmith, Braintrust, etc.).

**Frameworks for building custom systems**: Deploy Langfuse (self-hosted or cloud) → store and version prompts with labels → link prompts to traces and evaluations → run experiments against datasets → promote versions to production via labels. This provides an open, production-grade prompt lifecycle. Commercial platforms remain attractive when teams want managed services, specialized UI for non-engineers, or deep integration with specific frameworks.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Prompt management tools handle application logic and often production traffic data. Self-hosted solutions require proper security, access control, and operational practices. Always evaluate tools against your data sensitivity and compliance needs. This list is not security or operational advice.

---
**Made for AI engineers, LLM application teams, and prompt engineers who want reliable version control and observability.**
Let's keep prompt management systematic, measurable, and as open as practical.
