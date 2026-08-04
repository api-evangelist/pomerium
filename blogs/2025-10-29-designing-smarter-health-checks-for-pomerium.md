---
title: "Designing Smarter Health Checks for Pomerium"
url: "https://www.pomerium.com/blog/designing-smarter-health-checks-for-pomerium"
date: "2025-10-29"
feed_url: "https://www.pomerium.com/blog/feed/"
---
TL;DR We had a problem. Our services were technically “healthy,” but users didn’t see it that way. Containers would spin up, report as ready, and yet still fail requests because the underlying systems weren’t fully “initialized” — more on that later.
