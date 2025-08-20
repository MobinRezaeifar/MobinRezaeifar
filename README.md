<h1 align="center">Mobin Rezaeifar</h1>
<p align="center"><b>Tech Lead & Software Architect</b> · Web Platforms · Cloud · DX</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mbnrz"><img src="https://img.shields.io/badge/LinkedIn-mbnrz-0A66C2?logo=linkedin&logoColor=white" /></a>
  <a href="https://dev.to/mobinrezaeifar"><img src="https://img.shields.io/badge/dev.to-@mobinrezaeifar-0A0A0A?logo=devdotto&logoColor=white" /></a>
  <a href="https://stackoverflow.com/users/21860347"><img src="https://img.shields.io/badge/Stack%20Overflow-21860347-F48024?logo=stackoverflow&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=mobinrezaeifar&label=Profile%20Views&color=1f6feb" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=20&pause=1200&center=true&vCenter=true&width=900&lines=Leading+teams+to+ship+reliable+software;Architecture%2C+delivery%2C+and+developer+experience;React%2FNext.js+%7C+.NET%2FNode.js+%7C+Cloud%2FContainers" />
</p>

## Snapshot
- Tech Lead focused on **clarity, delivery, and DX**. I design systems, align stakeholders, and keep feedback loops short.
- Strengths: **architecture & trade-offs**, **team enablement**, **platform thinking**, **secure-by-default**.
- Toolbox (hands-on when needed): React/Next.js, TypeScript, .NET/Node.js, containers, CI/CD, observability.

## Selected Impact
- Led a squad of <N> engineers to ship <Product/Platform>, cutting lead time by **<XX>%** and reducing incidents by **<YY>%**.
- Re-architected <system/service> (event-driven + caching) to handle **<X>×** traffic with **<Y>%** cost reduction.
- Built an internal **DX platform** (templates, pipelines, docs) that bootstraps new services in **<Z> minutes**.
- Mentored <N> engineers; **<N promotions / N cross-team moves>**.

## Operating Principles
- **Clarity first** (ADR, concise RFCs) · **Small batches** (trunk-based + CI) · **Observability before scale** · **Security by default**

## Architecture (sample)
```mermaid
flowchart LR
  Client[Web / Mobile] --> BFF[API Gateway / BFF]
  BFF --> U[User Service]
  BFF --> O[Order Service]
  subgraph Data
    PG[(Postgres)]
    RD[(Redis)]
    MQ[[Kafka/RabbitMQ]]
  end
  U --> PG
  O --> PG
  U --> RD
  O --> MQ
  subgraph Platform
    CI[CI/CD]
    OBS[Logs+Metrics+Tracing]
  end
  CI --> U
  CI --> O
  OBS --> U
  OBS --> O
```

## Playbooks & Templates
- **Engineering Playbook** — ways of working, branching, release & on-call → [`/engineering-playbook`](https://github.com/mobinrezaeifar/engineering-playbook)
- **Service Template** — Next.js/.NET starter with CI, lint/test, container, CD → [`/service-template`](https://github.com/mobinrezaeifar/service-template)
- **ADR/RFC Template** — lightweight decisions with context → [`/adr-template`](https://github.com/mobinrezaeifar/adr-template)

## Talks & Writing
- <Talk title> — <Conf/Meetup, 2025> · slides/demo → `<link>`
- <Post title> — dev.to → `<link>`
- <Podcast/Panel> — `<link>`

## Tech Focus
TypeScript · React/Next.js · .NET/Node.js · Redis/RabbitMQ/Kafka · PostgreSQL  
Docker/K8s · Nginx · GitHub Actions · Observability (logs/metrics/traces)

## Contact
- LinkedIn: https://www.linkedin.com/in/mbnrz  
- dev.to: https://dev.to/mobinrezaeifar  
- Stack Overflow: https://stackoverflow.com/users/21860347  

<sub>PS: lines of code and language charts don’t reflect leadership impact. See “Selected Impact” above.</sub>

<details>
  <summary>Optional GitHub stats (collapsed)</summary>
  <p align="left">
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=mobinrezaeifar&show_icons=true&hide_border=true&theme=transparent" />
    <img height="165" src="https://github-readme-streak-stats.herokuapp.com?user=mobinrezaeifar&theme=transparent&hide_border=true" />
  </p>
  <p align="left">
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mobinrezaeifar&layout=compact&hide_border=true&theme=transparent" />
  </p>
</details>
