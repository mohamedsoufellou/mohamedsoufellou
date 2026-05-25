<div align="center">

# ⬡ THE ARCHITECT

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=16&duration=4000&pause=1500&color=A1A1AA&center=true&width=600&lines=Full-Stack+Engineering;End-to-End+Systems;Architecture+&+Operations" alt="Typing SVG" />

<br/>

*I design for change, failure, and humans.*

<br/>
<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=333333&height=1&section=footer&text=&fontSize=0" width="40%"/>

</div>

<br/>

### 01. THE TRACE

Most teams split the stack and call it specialization. I refuse the split as an excuse for shallow thinking. If I cannot walk this path for my own features, I am assembling, not architecting.

```mermaid
flowchart TD
    A([User Click]) --> B[UI State & A11y]
    B --> C[Client Cache & Offline]
    C --> D[API Contract & Idempotency]
    D --> E[Auth Boundary & Invariants]
    E --> F[Persistence & Migrations]
    F --> G[Async Pipelines & Retries]
    G --> H[Observability & Tracing]
    H --> I([Deployment & Rollback])
    
    style A fill:none,stroke:#A1A1AA,stroke-width:1px,color:#A1A1AA
    style I fill:none,stroke:#A1A1AA,stroke-width:1px,color:#A1A1AA
    style B fill:none,stroke:#333333,stroke-width:1px
    style C fill:none,stroke:#333333,stroke-width:1px
    style D fill:none,stroke:#333333,stroke-width:1px
    style E fill:none,stroke:#333333,stroke-width:1px
    style F fill:none,stroke:#333333,stroke-width:1px
    style G fill:none,stroke:#333333,stroke-width:1px
    style H fill:none,stroke:#333333,stroke-width:1px
```

<br/>

### 02. AXIOMS

> **Shape before code.** Structure emerges from constraints (traffic patterns, team boundaries, failure tolerance). Code fills the shape. Starting with frameworks makes systems expensive to change.

> **Interfaces are promises.** REST endpoints, GraphQL schemas, React props, database foreign keys — each is a contract. Breaking changes are incidents waiting for a calendar date.

> **Simplicity is load-bearing.** Predictable behavior without archaeology. If the system requires a diagram to explain a single feature, the design has already failed.

> **Operational reality is design.** A feature that cannot be monitored, rolled back, or debugged at 2 AM is incomplete.

<br/>

### 03. LAYER FLUENCY

<div align="center">
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,nodejs,go,python,postgres,redis,docker,kubernetes,terraform,aws,linux,git&perline=14&theme=dark" />
</div>

<br/>

| Layer | Focus |
| :--- | :--- |
| **Frontend** | State models · render strategy · performance budgets · accessible error UX |
| **Backend** | Domain boundaries · idempotency · layered auth · sync & event-driven flows |
| **Data** | Schema-as-API · index design · consistency models · cache invalidation |
| **Platform** | IaC · containers · env parity · graceful degradation under slow deps |
| **Reliability**| Traces · SLOs · error budgets · load & chaos as design reviews |
| **Security** | Threat modeling · least privilege · supply chain · privacy by design |

<br/>

### 04. PATTERNS & ANTI-PATTERNS

<details>
<summary><b>View Architectural Stance</b></summary>
<br/>

#### Patterns I reach for
- **Modular monolith** — Default starting point until team scale forces a split.
- **Strangler fig** — Legacy migration without big-bang rewrites.
- **Outbox pattern** — Reliable side effects without dual-write bugs.
- **Circuit breaker** — Failure containment under dependency stress.
- **Feature flags** — Decoupling deployment from release.

#### What I reject
- **Resume-driven development** — Choosing tech because the market values it, not because throughput requires it.
- **Distributed monolith** — Microservices sharing a database and a deployment train.
- **Architecture astronautics** — Diagrams that never survived contact with an incident.
- **Premature abstraction** — Frameworks inside frameworks before the second use case exists.

#### Definition of Done
A feature is not done when it merges. It ships when:
1. Success, failure, and edge cases are specified.
2. Data migrations are backward compatible.
3. Auth is enforced server-side.
4. Metrics and logs exist to answer *why* in production.
5. Rollback path is verified.

</details>

<br/>
<br/>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mohamedsoufellou&show_icons=true&theme=transparent&hide_border=true&title_color=ffffff&text_color=A1A1AA&icon_color=ffffff&rank_icon=percentile" height="160"/>
</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=333333&height=1&section=footer&text=&fontSize=0" width="10%"/>
</div>
