---
title: "Google Built an Agent Runtime on Kubernetes. Here's How to Build a Cloud-Agnostic One with Identity Included"
url: "https://www.pomerium.com/blog/google-built-an-agent-runtime-on-kubernetes-heres-how-to-build-a-cloud-agnostic-one-with-identity-included"
date: "2026-07-20"
feed_url: "https://www.pomerium.com/blog/feed/"
---
Google spent the last year quietly admitting what we already knew: Kubernetes was never designed to run AI agents. As Janakiram MSV writes in The New Stack , Google's GKE Agent Sandbox and the new Agent Substrate project amount to an indirect admission "that the platform that won the container decade is not the right control plane for AI agents." The analysis is worth reading in full, but the short version is this: an agent doesn't behave like a service. It's a long-running, stateful session that sits idle most of its life, wakes up to execute a burst of model-generated code, and goes back to 
