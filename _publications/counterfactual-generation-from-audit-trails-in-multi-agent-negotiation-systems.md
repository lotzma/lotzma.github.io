---
title: "Counterfactual Generation from Audit Trails in Multi-Agent Negotiation Systems"
collection: "publications"
category: "manuscripts"
permalink: "/publication/counterfactual-generation-from-audit-trails-in-multi-agent-negotiation-systems"
date: "2026-07-30"
venue: "Preprint"
paperurl: "/files/counterfactual-generation-from-audit-trails.pdf"
authors: "M Lotz, P Aluffi, M Bazzi, M Arderne, V Murevics"
excerpt: ""
---

**Abstract.** When autonomous agents negotiate on behalf of human principals, adverse outcomes raise the question of which changes would have altered the result. We formulate counterfactual audit as constrained intervention search in a structural causal model of an agent decision pipeline. An incomplete trace leaves uncertainty about the historical latent state, so an auditor must select one intervention that works across that uncertainty. We seek the least costly changes to evidence, policy checks or negotiation rules that would reverse a decision with a specified level of confidence. Our main result is that missing information can make combined changes essential for a cheap, reliable explanation. For a restricted class of decisions, we show how to select changes that reverse an approval with high probability. Finding the cheapest combination is computationally hard, but a simple search method has guarantees on cost and reliability. Exact affine and box-constrained optimisation references connect the audit margin to adversarial robustness while distinguishing boundary distance, feasible interventions and optimality certificates. Experiments in synthetic negotiation models show how explanations can fail when an audit ignores agents’ responses or keeps later messages and decisions fixed after an earlier change. The resulting guarantees hold under the declared model of the interaction and give a basis for explanations from incomplete records.
