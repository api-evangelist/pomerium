---
title: "It’s always DNS part ∞: tracking down a use-after-free bug in Envoy’s DNS Resolver"
url: "https://www.pomerium.com/blog/its-always-dns-part-tracking-down-a-use-after-free-bug-in-envoys-dns-resolver-c-ares"
date: "2025-12-12"
feed_url: "https://www.pomerium.com/blog/feed/"
---
TL;DR We found a use-after-free bug in Envoy’s DNS resolver, c-ares (CVE-2025-62408, CVE-2025-67514). Impact: Remote Denial of Service via process crash. In certain situations, an attacker could exploit a specific sequence of DNS responses to trigger a heap use-after-free and crash the application.
