# Prediction Guard: The Sovereign AI Control Plane

Prediction Guard gives regulated enterprises **operational control of every agent action, inside their own boundary**.

We're a self-hosted control plane for organizations that operate under strict security and regulatory obligations and need to run fleets of autonomous agents at scale. Prediction Guard runs in your cloud VPC, on your own hardware, or fully air-gapped, so prompts, tool calls, and logs never leave your trust boundary.

---

## What you control

* **Agent identity and scoped access**: Every agent gets its own identity and only the models, MCP servers, and tools it needs. Least agency by default.
* **Runtime Controls**: Component input and output controls (PII, injection attempts, toxicity) and agent behavior controls (tool misuse, memory poisoning, runaway token use) are enforced on every call, not after the fact.
* **Interventions**: Kill switches, human-in-the-loop approvals, and token and spend enforcement stop bad behavior as it happens and limit the blast radius.
* **Supply chain**: One registry for the models, MCP servers, and tools your agents rely on, with AIBOM export and model risk scoring.
* **Evidence**: Every agent action lands in an Immutable Audit Log mapped to NIST AI RMF, OWASP, and ISO 42001, and streams to your SIEM.
* **Agent Forge**: A no-code builder for agents that run under the same controls as everything else.

## Start here

* [**docker-pg-experiment**](https://github.com/predictionguard/docker-pg-experiment): Run coding agents in a Docker Sandbox with Prediction Guard as the second gate of defense.
* [**pg-accelerator-recipes**](https://github.com/predictionguard/pg-accelerator-recipes): Starter recipes for code-first agents, Agent Forge, and hybrid patterns.
* [**agentic-ai-security**](https://github.com/predictionguard/agentic-ai-security): Red-team agents and tests for the OWASP Top 10 for Agentic Applications.

## Industry Perspective

> "Prediction Guard is working to unlock the potential of AI for critical missions by bringing the power of the **control plane** right behind the customer's own firewall and ensuring alignment. It's a game-changer for high-security environments."
>
> **Bill Streilein**, CTO, Noblis

---

### Get Started

Stop relying on rented convenience and start building permanent sovereignty.
[**Get started with Prediction Guard**](https://predictionguard.com/get-started)
