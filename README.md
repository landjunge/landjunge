### I build open-source infrastructure for controllable AI agents.

**Context → Execution → Credentials → Network**

AI agents are becoming autonomous. The missing infrastructure is control.

These are **separate products** — experiments on one problem, not a merged stack.

| Layer | Project | One line |
|---|---|---|
| Context | **[ThreadDesk](https://github.com/landjunge/threaddesk)** | Persistent threads. Stores context. Never executes. |
| Execution | **[Gnom-Hub-V1](https://github.com/landjunge/gnom-hub-v1)** | Local multi-agent desk. Brainstorm freely. Execute on purpose. |
| Credentials | **[4AllPass](https://github.com/landjunge/4AllPass)** | Agents need access. They don't need your secrets. |
| Network / Safety | **[Tollgate](https://github.com/landjunge/tollgate)** | Safety layer between agents and the internet. Protect · Route · Prove. |

```text
ThreadDesk      context / work / threads
     ↓
Gnom-Hub-V1     execution
     ↓
4AllPass        credentials  “May I access?”
     ↓
Tollgate        network / cost / safety  “May I act?”
```

I'm exploring what infrastructure AI agents need to become useful autonomous workers without becoming uncontrollable.

- Tollgate: [site](https://landjunge.github.io/tollgate/) · [repo](https://github.com/landjunge/tollgate)
- Gnom-Hub-V1: [site](https://landjunge.github.io/gnom-hub-v1/) · [repo](https://github.com/landjunge/gnom-hub-v1)
- 4AllPass: [repo](https://github.com/landjunge/4AllPass) · [demo](https://github.com/landjunge/4AllPass/blob/main/docs/two-minute-demo.md)
- ThreadDesk: [repo](https://github.com/landjunge/threaddesk)

Feedback welcome.
