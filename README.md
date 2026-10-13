# Agent Entitlement Architecture

**Live page:** https://eshwarpotturi.github.io/agent-entitlement-architecture/
**Proof-of-concept results:** https://eshwarpotturi.github.io/agent-entitlement-loop/

Architecture brief for self-hardening entitlements for AI agents in a bank:
- **Run-time plane:** every agent action passes a deterministic entitlement gateway (call-chain identity, policy decision, untrusted-content flag, outbound content check, audit log).
- **Learning plane (sandbox only):** a red-team agent attacks the policy, plain code proves breaches, a designer agent proposes the narrowest fix, a regression gate measures the business cost, and a human approves each policy version.
- Leadership Q&A and a status table separating what is built from what comes next.
