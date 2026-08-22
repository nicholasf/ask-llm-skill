---
name: ask-llm
description: Drive an LLM as an interactive agent with local tooling. Bridge mode (local) proxies tool calls on the orchestrating machine. Bridge mode (SSH) executes tool calls on a remote node via SSH. Depends on topology-skill to identify available nodes.
depends_on:
  - topology-skill
---

Read the topology (topology-skill) to find the node hostname and verify it is online before invoking. Invoke `/ask-llm` for the full workflow.
