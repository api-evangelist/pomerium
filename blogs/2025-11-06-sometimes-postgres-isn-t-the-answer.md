---
title: "Sometimes Postgres isn’t the Answer"
url: "https://www.pomerium.com/blog/sometimes-postgres-isnt-the-answer"
date: "2025-11-06"
feed_url: "https://www.pomerium.com/blog/feed/"
---
Pomerium v0.31 introduces a new custom local file storage backend with a clustered mode implemented via Raft for automatic failover and recovery as an alternative to our existing Postgres backend. On the face of it, this would seem to fly in the face of much received wisdom regarding system design: that Postgres is sufficient for almost any task, and the panoply of services used in modern microservice system design is overengineering at its worst. And yet here we are, basically rolling our own custom database and moving away from Postgres.
