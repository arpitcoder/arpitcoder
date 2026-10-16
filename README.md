# arpit nigam

founder @ [gotoursafe.xyz](https://gotoursafe.xyz) + [MavOps](https://mavops.xyz)

right now i'm building two things.

**gotoursafe.xyz** — real-time road, weather, and safety intel for travel across india. 75 live scrapers feeding one search bar. ask it in english or hinglish and get a straight answer. because "is manali safe next week" shouldn't need three tabs open.

**MavOps** — a control plane for AI agents in production. deterministic rules decide what an agent is allowed to do; a model can only ever make that decision *stricter*, never more permissive. when a call needs a person, the agent freezes and a human approves it from a link — about five seconds end to end, no account needed to review.

recent write-up: [they were renting compute they already owned](https://mavops.xyz/case-studies/hybrid-k3s) — swapping managed Kubernetes for a cloud control plane over the client's own rack. $120k a year, and the parts that went wrong.

---

*things i keep coming back to*

- how you make an agent's actions safe at enterprise scale without blocking every real use case
- why checking indian road status is still a whatsapp-forwarded pdf in 2026
- whether SOC 2 protects anyone or is just a tax we all pay

---

infra: kubernetes · k3s · terraform · proxmox · postgres · redis · nats
building with: go · python · typescript · react

happy to talk about platform or agent-governance work — founder@mavops.xyz
