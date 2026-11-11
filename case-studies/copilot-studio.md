# Copilot Studio and AI assistants

My assistant work includes defining useful tasks, organizing topic routing and context, grounding responses in relevant information, and connecting tools to a conversation. I also work on the testing, documentation, and coaching needed for people to use these capabilities with appropriate judgment.

The important decisions are concrete: which tool is allowed to act, what information is needed before calling it, how ambiguity is resolved, what happens when evidence is missing, and when a human should review a proposed result. Prompt wording helps communicate intent, while the integration and application layers must enforce their own limits.

I distinguish an assistant configuration from a verified running integration. A saved topic does not establish that its connection works; a tool result does not establish that a later generated sentence is accurate. Reviewing actual outcomes and explaining these limits is part of both engineering and AI enablement.

This summary contains no employer prompts, exported agents, knowledge documents, conversation records, tenant identifiers, connection references, or private endpoints.

## Inspect independent examples

[Copilot Studio Workbench](https://github.com/dgoetz365/copilot-studio-workbench) includes original conversation topics, an OpenAPI connector definition, a runnable synthetic print-desk API, and reference cases. Local code and schema checks are recorded separately from the still-unverified tenant import and runtime behavior.

[Service Desk Assistant](https://github.com/dgoetz365/service-desk-assistant) shows a complementary code implementation: bounded read-only tools, source evidence, ambiguous matches, a deterministic offline demo, and an optional local-model adapter. The [AI Workshop Kit](https://github.com/dgoetz365/ai-workshop-kit) provides original facilitation and coaching materials for evaluating useful workflows.

[All work notes](../WORK.md) · [Profile](../README.md)
