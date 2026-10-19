<img width="1908" height="945" alt="image" src="https://github.com/user-attachments/assets/a5a30caa-7363-498c-a950-c0665cb4f29a" />

# ForgePilot-AI-
 browser-based AI coding workspace inspired by Qoder.
Built and deployed ForgePilot AI a browser-based AI coding workspace inspired by Qoder.

# ForgePilot AI

AI-powered software engineering workspace

Live · Deployment successful

Launch ForgePilot AI&#x20;

[https://forgepilot-ai-v1yz78.v2.appdeploy.ai/](https://forgepilot-ai-v1yz78.v2.appdeploy.ai/?utm_source=chatgpt.com)

## What's included

Code editor and project explorer

Edit files, create new files, switch between files, and retain project content in your browser.

AI coding assistant

Ask for implementation plans, code explanations, debugging guidance, architecture reviews, and tests through a connected AI backend.

Developer workspace

Includes code and preview tabs, a demo terminal, Git branch indicators, and a responsive interface.

## Recommended next milestone

V2 will be upgrade soon with these capabilities next:

1. GitHub integration — import repositories, inspect project structure, and manage branches.
2. Agentic multi-file coding — let the AI propose changes across files with a reviewable diff before applying them.
3. Real build and test execution — isolated cloud environments for running code, tests, and debugging.
4. Codebase intelligence — semantic search, dependency analysis, and repository-aware reasoning.
5. Local LLM support — connect your Ollama models for local AI coding experiments.


version 2 will focus on turning it into a more capable agentic coding workspace, with repository importing, AI-generated multi-file changes, code intelligence, execution tools, and configurable model connections.

There are two important technical boundaries: running arbitrary code requires a properly isolated execution environment, and connecting a public HTTPS website to Ollama on your private computer requires a secure local bridge or gateway. I'll distinguish working features from integrations that still need infrastructure.

ForgePilot AI v2 has been deployed successfully.

## ForgePilot AI — Engineering Studio

Updated existing application with advanced development workflows.

Launch ForgePilot AI v2&#x20;

### What is available now

| Capability                | Implementation                                                       |
| ------------------------- | -------------------------------------------------------------------- |
| GitHub integration        | Public repository import, branch selection, source browsing          |
| Agentic multi-file coding | AI-generated file replacements with side-by-side review and approval |
| Execution tools           | JSON validation, merge-marker checks, sandboxed HTML preview         |
| Codebase intelligence     | Ranked code search and dependency inventory                          |
| Ollama                    | Configurable endpoint, model selection, connection testing           |

Open the application and select Engineering Studio using the settings icon or the bottom navigation link.

### Remaining infrastructure to be upgrade for version 3 soon:

Full private GitHub access, remote branch management, isolated cloud builds, actual test execution, vector-based semantic search, and reliable remote access to your home-lab Ollama still require additional integrations.

The updated deployment passed validation with no reported frontend or backend errors. There is one non-blocking CSS import-order warning.

Live application: [ForgePilot AI v2](https://forgepilot-ai-v1yz78.v2.appdeploy.ai/?utm_source=chatgpt.com)
