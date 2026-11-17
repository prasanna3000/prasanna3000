<img src="assets/banner.svg" width="100%" alt="Terminal intro: Prasanna Reddy, Senior DevSecOps Full-Stack Engineer — security, backend, distributed systems, cloud, fintech; now exploring LLMs, RAG, vector search and agents"/>

<p align="center">
  <a href="mailto:iprasannareddy20@gmail.com"><img src="https://img.shields.io/badge/email-say_hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=prasanna3000&label=requests%20served&color=22d3ee&style=for-the-badge&labelColor=0d1117" alt="Profile views"/>
</p>

```console
$ systemctl status prasanna.service
● prasanna.service — Senior DevSecOps Full-Stack Security Engineer
     Loaded: loaded (/etc/careers/fintech.conf; enabled)
     Active: active (running) since Aug 2020; 6y+ ago
   Main PID: 2025 (standard-chartered-gbs)
      Tasks: sbom360, security-benchmark-apis, secure-code-tooling
   Security: sbom · cyclonedx · cdxgen · syft · trivy · cis/stig benchmarks
    Workers: python · fastapi · node · typescript · java · spring-boot · graphql
      Queue: kafka · rabbitmq · bullmq · sqs/sns — always draining, never dropping
     Memory: postgres · mongodb · mysql · dynamodb · redis
     Fork:   mira (local-first visual intelligence) — side project, running hot 🔥

Nov 17 09:00 prod prasanna[2025]: INFO  sbom generated · 0 unknown dependencies
Nov 17 09:01 prod prasanna[2025]: WARN  curiosity exceeded threshold → spawning LLM experiments
```

## 📈 `SELECT impact FROM career;`

<img src="assets/impact.svg" width="100%" alt="Impact dashboard: +45% revenue from an in-house video platform, −54% cloud spend, 20+ high-value clients onboarded, 95% customer satisfaction"/>

## 🌳 `git log --graph career`

```mermaid
gitGraph
  commit id: "2016 · B.CS @ Vignan's"
  commit id: "Jun 2020 · graduated, CGPA 9.5"
  branch myanatomy
  checkout myanatomy
  commit id: "MyMeeting — WebRTC video"
  commit id: "Storage microservice — S3"
  checkout main
  merge myanatomy tag: "Jan 2023"
  branch m2p-fintech
  checkout m2p-fintech
  commit id: "Switch-as-a-Service — txn auth"
  commit id: "CKYC platform"
  checkout main
  merge m2p-fintech tag: "Apr 2024"
  branch xoriant
  checkout xoriant
  commit id: "Instant Savings — GBP/EUR/USD"
  commit id: "NpmDocs (project lead)"
  checkout main
  merge xoriant tag: "Jan 2025"
  branch standard-chartered
  checkout standard-chartered
  commit id: "SBOM360 — supply-chain SBOMs"
  commit id: "CIS / STIG benchmark APIs"
  commit id: "HEAD — securing the bank" type: HIGHLIGHT
```

<details>
<summary><b>📦 <code>git show --stat</code> — what each commit actually contains</b></summary>
<br/>

| Commit | What it does | Stack |
|---|---|---|
| **SBOM360** · Standard Chartered | Automated SBOMs (CycloneDX) for in-house apps, vendor binaries, containers, OS & DB layers — aligned to SLSA / NTIA | `Python` `cdxgen` `syft` `trivy` `CycloneDX` |
| **Security benchmark reporting** · Standard Chartered | REST APIs + dashboard for CIS & STIG benchmark and security-inventory reporting | `Python` `FastAPI` `PostgreSQL` `Postman` |
| **Instant Savings Account** · Xoriant | Fixed-rate savings across GBP, EUR & USD balances, with recurring transfers | `Lambda` `DynamoDB` `GraphQL` `SNS` `CloudWatch` `Mambu` |
| **NpmDocs** · Xoriant *(lead)* | Discover and browse NPM package documentation | `Node.js` `React` `Redux` `TypeScript` `RabbitMQ` |
| **Switch as a Service** · M2P | Transaction lifecycle — authorization, rule validation, limit checks; request encryption via AWS KMS | `Spring Boot` `PostgreSQL` `MySQL` `MongoDB` `Kafka` `KMS` |
| **CKYC** · M2P | Fetch, update & store customer KYC records | `Node.js` `Express` `React` `BullMQ` `MySQL` `Cluster` |
| **MyMeeting** · MyAnatomy | Secure 1:1 video calls with moderator controls | `Socket.io` `Simple Peer` `TypeScript` `React` `MongoDB` |
| **Storage Microservice** · MyAnatomy *(lead)* | Uploads, deletion history & large-file processing | `S3` `Node.js` `BullMQ` `Redis` `MongoDB` |

</details>

## 🧰 `npm ls --depth=0`

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,java,nodejs,express,spring,graphql,react,redux&theme=dark" alt="Languages and frameworks"/><br/>
  <img src="https://skillicons.dev/icons?i=python,fastapi,kafka,rabbitmq,redis,mongodb,postgres,mysql,dynamodb&theme=dark" alt="Data, messaging and cloud"/><br/>
  <img src="https://skillicons.dev/icons?i=aws,gcp,jest,git,github,gitlab,postman&theme=dark" alt="Tooling"/>
</p>

## 🔭 `./mira --explain` &nbsp;<sub>side project, in progress</sub>

> Turn an ordinary folder of photos into a **private, searchable memory** — no cloud required.

```mermaid
flowchart LR
    P([📷 your photos]):::io --> V{{computer vision}}:::ml
    V --> O[objects]:::f & PE[people]:::f & PL[places]:::f & T[OCR text]:::f
    O & PE & PL & T --> E[[embeddings]]:::ml
    E --> DB[(vector index)]:::db
    Q([🔎 'beach trip with mom, 2019']):::io --> DB
    DB --> VLM{{vision-language model}}:::ml
    VLM --> S([✨ stories · albums · captions]):::io

    classDef io fill:#0e7490,stroke:#22d3ee,color:#fff
    classDef ml fill:#4c1d95,stroke:#a78bfa,color:#fff
    classDef f fill:#1f2937,stroke:#6b7280,color:#e5e7eb
    classDef db fill:#831843,stroke:#f472b6,color:#fff
```

## 🐍 `tail -f contributions.log`

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/prasanna3000/prasanna3000/output/github-snake-dark.svg"/>
  <img src="https://raw.githubusercontent.com/prasanna3000/prasanna3000/output/github-snake.svg" alt="Snake eating my contribution graph"/>
</picture>

<details>
<summary><b>🎓 <code>cat ~/.credentials</code></b> <sub>(the safe kind)</sub></summary>
<br/>

- **Bachelor of Computer Science** — Vignan's Deemed To Be University · Jun 2016 – Jun 2020 · CGPA **9.5 / 10**
- **AWS Solutions Architect – Associate** — SimpliLearn
- **MongoDB Authentication & Authorization** — MongoDB University

</details>

```diff
$ git log -1 --format=%B philosophy
- Good software is about making things work.
+ Good software is about understanding why it needs to exist in the first place.
```

<p align="center"><sub>building systems · learning constantly · breaking things occasionally (in staging, mostly)</sub></p>
