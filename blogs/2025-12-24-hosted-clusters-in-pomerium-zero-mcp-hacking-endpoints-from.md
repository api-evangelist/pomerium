---
title: "Hosted Clusters in Pomerium Zero & MCP Hacking (endpoints from localhost via ssh)"
url: "https://www.pomerium.com/blog/hosted-clusters-in-pomerium-zero-mcp-hacking-endpoints-from-localhost-via-ssh"
date: "2025-12-24"
feed_url: "https://www.pomerium.com/blog/feed/"
---
If you’re building an MCP server and you want a public model (ChatGPT, Claude, or Gemini) to actually call it, you hit the same wall: All the frontier models need a public HTTPS URL. So instead of hacking on whatever MCP tool you were working on, now you’ve got to figure out tunneling, infra, or weird gNAT issues when you are just trying to hack. Hosted Clusters in Pomerium Zero (beta) Today we shipped Hosted Clusters in Pomerium Zero — our first hosted data plane — built for remote MCP servers .
