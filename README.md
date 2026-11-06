<!-- ====== BERSERK • MINIMAL & COMPACT ====== -->
<p align="center">
  <img src="https://github.com/AnderMendoza/AnderMendoza/raw/main/assets/line-neon.gif" width="100%" alt="Neon divider" />
</p>

<div align="center">
  <!-- Hero -->
  
<div align="center">
  <img src="https://github.com/UchihaIthachi/UchihaIthachi/blob/main/img/guts.gif" alt="Intro" style="height: 230px; width: 930px;" />
</div>
  
  <h1>Harshana Lakshara Fernando</h1>
  <p><b>Software Engineer – Trading Systems @ CAL</b> • Go &amp; Kubernetes open source • Distributed Systems • Cloud-Native</p>

  <!-- Socials / quick links (keep only working links) -->
  <a href="" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="linkin" height="30" width="40" /></a> <a href="" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/facebook.svg" alt="facebook" height="30" width="40" /></a> <a href="https://www.hackerrank.com/profile/210167e_cse_21" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/hackerrank.svg" alt="hackerrank" height="30" width="40" /></a> <a href="https://leetcode.com/HarshanaUOM/" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/leetcode.svg" alt="leetcode" height="30" width="40" /></a> <a href="" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/geeksforgeeks.svg" alt="akash_chowrasia" height="30" width="40" /></a> <a href="mailto:harshanalf.work@gmail.com"><img align="center" src="https://simpleicons.org/icons/gmail.svg" height="30" width="40" /></a> <a href="https://harshanalf.netlify.app/" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/internetexplorer.svg" alt="3D Portfolio" height="30" width="40" /></a>

  <!-- Quick facts -->
  <img src="https://img.shields.io/badge/Focus-Cloud%20%26%20DevOps-00B140?style=flat-square" alt="Focus" />
  <img src="https://img.shields.io/badge/Base-Sri%20Lanka-000?style=flat-square" alt="Base" />
  <img src="https://img.shields.io/badge/Languages-English%20%26%20Sinhala-00B140?style=flat-square" alt="Languages" />
  <img src="https://komarev.com/ghpvc/?username=UchihaIthachi&color=brightgreen&style=flat-square" alt="Profile views" />
</div>

<p align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" alt="Divider" />
</p>

<!-- ===== 🙋 About ===== -->
<details>
  <summary><b>🙋 About me</b></summary>

  <p align="center">
    <em>
      Hello! I'm Harshana Fernando, a <b>Software Engineer – Trading Systems</b> at CAL in Colombo, Sri Lanka
      (Computer Science &amp; Engineering, <a href="https://uom.lk/" title="Wisdom is all wealth"><b>University of Moratuwa</b></a>).<br>
      I'm a <b>passionate self-learner</b>
      <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Developer.gif" width="30">
      and a <b>software engineer</b>
      <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Designer.gif" width="36">.
    </em>
  </p>

  <p>
    I build scalable, cloud-native applications with strengths in full-stack development, microservices, and event-driven systems using <b>Java (Spring Boot)</b>, <b>Go</b>, and modern tooling.
    I'm passionate about Generative AI with hands-on experience in RAG pipelines and LLM integration, plus exposure to Web3 and DevOps.
  </p>

  <p>
    At CAL I build an in-house electronic trading platform connected directly to the Colombo Stock Exchange
    (FIX 5.0 SP2 order routing, an event-sourced engine on Chronicle Queue, Java 21). Outside work I contribute to CNCF and Kubeflow projects in Go.
    When I’m not shipping production-grade backends or tuning infra, I’m grinding <b>LeetCode</b> &amp; <b>HackerRank</b>.
  </p>

</details>


<!-- ===== 💼 Experience ===== -->
<details open>
<summary><b>💼 Experience</b></summary>

**Software Engineer – Trading Systems** · CAL · Colombo, Sri Lanka · *Sep 2026 – Present*
- Building CAL's in-house electronic trading platform: a direct gateway to the **Colombo Stock Exchange (CSE)**, plus the dealing, operations and testing tools around it
- Led CSE's **188-case exchange certification**, with a Certification Runner that drives each case and explains every field difference, backed by durable message logs and a CI-enforced test register
- **Event-sourced CQRS** order path: a **Chronicle Queue** write-ahead journal with **PostgreSQL** as an async read model, so no database write sits between a trader and the exchange
- **FIX 5.0 SP2** order routing and drop copy (**QuickFIX/J**), and a custom Java NIO decoder for the **MITCH** UDP multicast feed (A/B feeds, snapshot recovery)
- Designed an **exchange simulator** that replays 1,700+ real exchange conversations with **zero parity failures**
- Failover, sequence and feed-gap recovery, drop-copy reconciliation, health-gated deploys with rollback; **~1,050 automated tests** in CI

**Research and Development Engineer (Internship)** · Empathic Computing Laboratory, University of Auckland · Remote · *Mar 2026 – Aug 2026*
- Technical design of a modular mobile–wearable sensing pipeline (**Kotlin**, **WearOS**) for digital mental health research
- Turned high-frequency time-series sensor data into structured features for machine learning

**Co-founder & Lead Engineer (Freelance)** · ScaleX · Remote · *Jul 2025 – Aug 2026*
- Built **AgriNova** (Next.js, Prisma, Supabase/PostgreSQL): inventory and commission management across 5 branches, 194K+ units tracked, 860+ invoices processed
- Cut repeat dashboard data-fetch latency from ~384 ms to under 1 ms with React Query caching and pagination

**Software Engineer (Internship)** · Information Systems Associates (ISA) · Colombo, Sri Lanka · *Dec 2024 – May 2026*
- Owned a **Kafka**-backed PNR generation microservice, live in production: 25+ PNRs/sec/node at <100 ms latency
- Led the AeroMART → AeroOrder modernization (Strangler Fig, feature toggles, **gRPC** bridge into a Java 8 monolith)

<sub>Java 21 · Spring Boot · QuickFIX/J · Chronicle Queue · PostgreSQL · Kafka · Go · Kotlin</sub>
</details>


<!-- ===== 🌱 Open Source ===== -->
<details open>
<summary><b>🌱 Open Source</b></summary>

<!-- OSS:START -->
<p>
  <img src="https://img.shields.io/badge/PRs%20merged-6-2ea44f?style=flat-square&logo=github" alt="6 PRs merged" />
  <img src="https://img.shields.io/badge/In%20review-6-dbab09?style=flat-square&logo=github" alt="6 PRs in review" />
  <img src="https://img.shields.io/badge/Projects-7-6f42c1?style=flat-square&logo=cncf&logoColor=white" alt="7 projects" />
  <img src="https://img.shields.io/badge/Shipped%20in-kgateway%20v2.5-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Shipped in kgateway v2.5" />
  <img src="https://img.shields.io/badge/Language-Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Updated-6%20Nov%202026-555?style=flat-square" alt="Updated 6 Nov 2026" />
</p>

**Pull requests**

| Project | PR | What I did | Size | Timeline | Status |
|---|---|---|---|---|---|
| [Apache Camel K](https://github.com/apache/camel-k) | [#6934](https://github.com/apache/camel-k/pull/6934) | Complexity linters (gocyclo, gocognit, cyclop) enabled at current-max thresholds ([#5486](https://github.com/apache/camel-k/issues/5486)), so complexity can't grow |  | Opened 5 Nov 2026 | <img src="https://img.shields.io/badge/In%20review-dbab09?style=flat-square&logo=github&logoColor=white" alt="In review" /> |
| [Apache Camel K](https://github.com/apache/camel-k) | [#6933](https://github.com/apache/camel-k/pull/6933) | Apache Pulsar scaler for the KEDA trait ([#6932](https://github.com/apache/camel-k/issues/6932)): scaler mapping, unit tests, an e2e test in the KEDA workflow and docs | 7 files · +426 −1 | Issue #6932 + PR opened 5 Nov 2026 | <img src="https://img.shields.io/badge/In%20review-dbab09?style=flat-square&logo=github&logoColor=white" alt="In review" /> |
| [Apache SkyWalking BanyanDB](https://github.com/apache/skywalking-banyandb) | [#1462](https://github.com/apache/skywalking-banyandb/pull/1462) | MCP HTTP server rejected `bearer` tokens (case-sensitive auth scheme); fix accepts any case with 4 new tests. Found it myself and filed [apache/skywalking#14199](https://github.com/apache/skywalking/issues/14199), now assigned to me; milestone BanyanDB 0.12.0 |  | Opened 5 Nov 2026 · issue #14199 assigned to me · milestone 0.12.0 | <img src="https://img.shields.io/badge/In%20review-dbab09?style=flat-square&logo=github&logoColor=white" alt="In review" /><br><img src="https://img.shields.io/badge/Milestone-0.12.0-1f6feb?style=flat-square&logo=apache&logoColor=white" alt="Milestone 0.12.0" /> |
| [kgateway](https://github.com/kgateway-dev/kgateway) (CNCF) | [#14851](https://github.com/kgateway-dev/kgateway/pull/14851) | New `kgateway_build_info` Prometheus metric (version, revision, Go version, OS/arch) so operators can see which build every pod runs. The maintainer extended it into a reusable `metrics.NewInfo` helper; issue [#13457](https://github.com/kgateway-dev/kgateway/issues/13457) closed as completed | 5 files · +113 | Opened 18 Oct → merged 20 Oct 2026 | <img src="https://img.shields.io/badge/Merged-2ea44f?style=flat-square&logo=github&logoColor=white" alt="Merged" /><br><img src="https://img.shields.io/badge/Shipped%20in-v2.5.0--beta.2-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Shipped in-v2.5.0-beta.2" /> |
| [kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) | [#1549](https://github.com/containers/kubernetes-mcp-server/pull/1549) | Test that every tool, prompt, resource and resource template across all 12 toolsets declares valid RBAC metadata, using a real cluster inspector. All 14 CI checks green on the first run, approved on the first review (closes [#1435](https://github.com/containers/kubernetes-mcp-server/issues/1435)) | 1 file · +33 | Opened 20 Oct → merged 26 Oct 2026 | <img src="https://img.shields.io/badge/Merged-2ea44f?style=flat-square&logo=github&logoColor=white" alt="Merged" /> |
| [kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) | [#1482](https://github.com/containers/kubernetes-mcp-server/pull/1482) | Fixed flaky HTTP server startup on the slow macOS CI runner: a 5 s readiness poll instead of a ~0.5 s retry loop, and test setup now cleans up before failing. Two review rounds (closes [#1445](https://github.com/containers/kubernetes-mcp-server/issues/1445)) | 2 files · +14 −14 | Opened 8 Oct → merged 15 Oct 2026 | <img src="https://img.shields.io/badge/Merged-2ea44f?style=flat-square&logo=github&logoColor=white" alt="Merged" /> |
| [Kubeflow Spark Operator](https://github.com/kubeflow/spark-operator) | [#3249](https://github.com/kubeflow/spark-operator/pull/3249) | 20 Ginkgo specs for executor metrics: every pod-phase transition, label sanitising and registration error paths, 100% of `sparkpod_metrics.go`; plus a fix for a wrong failure-count log message. Requested by a maintainer under [#3202](https://github.com/kubeflow/spark-operator/issues/3202); review changes done | 4 files · +234 −1 | Opened 18 Oct · LGTM 20 Oct · waiting for /approve | <img src="https://img.shields.io/badge/In%20review-dbab09?style=flat-square&logo=github&logoColor=white" alt="In review" /><br><img src="https://img.shields.io/badge/LGTM-0e8a16?style=flat-square&logo=kubernetes&logoColor=white" alt="LGTM" /> |
| [KEDA](https://github.com/kedacore/keda) (CNCF) | [#8317](https://github.com/kedacore/keda/pull/8317) | `onlyReadyPods` option for the Kubernetes workload scaler: counts only pods that are Running and Ready (not terminating), so scaling ignores pods that can't serve yet. Design agreed with a maintainer on [#4394](https://github.com/kedacore/keda/issues/4394); labelled `kind/feature` | 5 files · +207 −9 | Opened 27 Oct → merged 1 Nov 2026 | <img src="https://img.shields.io/badge/Merged-2ea44f?style=flat-square&logo=github&logoColor=white" alt="Merged" /> |
| [KEDA](https://github.com/kedacore/keda) (CNCF) | [#8331](https://github.com/kedacore/keda/pull/8331) | Follow-up to [#8317](https://github.com/kedacore/keda/pull/8317) suggested by a maintainer: a shared `IsPodReady` helper in `pkg/util` (with tests) used by the workload scaler and fallback, replacing two copies | 5 files · +91 −37 | Opened 1 Nov → merged 5 Nov 2026 | <img src="https://img.shields.io/badge/Merged-2ea44f?style=flat-square&logo=github&logoColor=white" alt="Merged" /> |
| [KEDA docs](https://github.com/kedacore/keda-docs) | [#1919](https://github.com/kedacore/keda-docs/pull/1919) | Documentation for the new `onlyReadyPods` parameter (companion to #8317) | 1 file · +4 | Opened 27 Oct → merged 1 Nov 2026 | <img src="https://img.shields.io/badge/Merged-2ea44f?style=flat-square&logo=github&logoColor=white" alt="Merged" /> |
| [Jaeger](https://github.com/jaegertracing/jaeger) (CNCF) | [#9997](https://github.com/jaegertracing/jaeger/pull/9997) | Found and reported a bug in the MCP `get_trace_topology` tool ([#9991](https://github.com/jaegertracing/jaeger/issues/9991)): reused span IDs looped and parent cycles silently dropped spans. The fix links spans by position, expands each ID once and keeps output deterministic; 6 tests (self-parent, two cycles, shared IDs, depth limit) | 2 files · +192 −4 | Issue #9991 filed → PR opened 1 Nov 2026 | <img src="https://img.shields.io/badge/In%20review-dbab09?style=flat-square&logo=github&logoColor=white" alt="In review" /> |
| [kgateway](https://github.com/kgateway-dev/kgateway) (CNCF) | [#14945](https://github.com/kgateway-dev/kgateway/pull/14945) | `rateLimit.local.statPrefix` on the traffic policy, with route template tokens, so local rate-limit stats can be told apart per route ([#14925](https://github.com/kgateway-dev/kgateway/issues/14925)); unit and translator tests incl. strict mode; labelled `kind/feature` | 11 files · +555 −8 | Opened 29 Oct 2026 | <img src="https://img.shields.io/badge/In%20review-dbab09?style=flat-square&logo=github&logoColor=white" alt="In review" /> |
| [kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) | [#1521](https://github.com/containers/kubernetes-mcp-server/pull/1521) | Fixed `main` not building after two PRs merged out of order (Kiali status probe). The maintainer merged his own fix ([#1526](https://github.com/containers/kubernetes-mcp-server/pull/1526)) with the same code change plus a test | 1 file · +6 −2 | Opened 17 Oct · closed 20 Oct 2026 | <img src="https://img.shields.io/badge/Superseded-6e7781?style=flat-square&logo=github&logoColor=white" alt="Superseded" /> |

**Issues, debugging and design work**

| Project | Issue | What I did | When | Status |
|---|---|---|---|---|
| [Apache SkyWalking BanyanDB](https://github.com/apache/skywalking-banyandb) | [#14194](https://github.com/apache/skywalking/issues/14194) | Found and reported that the MCP server ignored `.env` values and silently accepted malformed settings (`1MiB` read as 1, invalid `TRANSPORT` falling back), with a reproduction; fix by another contributor in [banyandb#1460](https://github.com/apache/skywalking-banyandb/pull/1460), which credits the report | Reported 4 Nov 2026 · fix in banyandb#1460 (another contributor) | <img src="https://img.shields.io/badge/Bug%20reported-8250df?style=flat-square&logo=github&logoColor=white" alt="Bug reported" /> |
| [kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) | [#1568](https://github.com/containers/kubernetes-mcp-server/issues/1568) | Showed a "flaky" test on another contributor's PR was a real merge-order bug, reproduced it and suggested the fix; the author confirmed, applied it and closed the issue as root-caused | 25 Oct 2026 | <img src="https://img.shields.io/badge/Root--caused-8250df?style=flat-square&logo=go&logoColor=white" alt="Root-caused" /> |
| [Kubeflow Spark Operator](https://github.com/kubeflow/spark-operator) | [#3130](https://github.com/kubeflow/spark-operator/issues/3130) | Evaluated crd-ref-docs vs genref for migrating the API reference docs generator: sample output, line counts and field-accuracy checks (genref marked some optional fields as required); recommended crd-ref-docs | Assigned 22 Oct 2026 | <img src="https://img.shields.io/badge/Assigned-1f6feb?style=flat-square&logo=kubeflow&logoColor=white" alt="Assigned" /> |
| [kgateway](https://github.com/kgateway-dev/kgateway) (CNCF) | [#14835](https://github.com/kgateway-dev/kgateway/issues/14835) | Metrics audit: posted an inventory of findings and offered a cleanup PR for the maintainer to pick | 22 Oct 2026 | <img src="https://img.shields.io/badge/Awaiting%20reply-6e7781?style=flat-square&logo=github&logoColor=white" alt="Awaiting reply" /> |

<!-- OSS:END -->
<sub>Also on my <a href="https://harshanalf.netlify.app/portfolio#open-source">portfolio</a> and <a href="https://uchihaithachi.github.io/cv/open-source.html">CV site</a>.</sub>
</details>


<!-- ===== 🎯 Goals & Focus ===== -->
<details>
<summary><b>🎯 Goals & Focus</b></summary>

- Build **scalable, cloud-native systems** (microservices, event-driven, high-throughput)  
- Ship **Java/Spring** & **Go** backends; optimize latency & reliability  
- Practical **RAG** and **LLM** integration  
- **Kubernetes** + **AWS** + secure CI/CD  
- Explore **Web3** (governance & identity)
</details>

<!-- ===== 🧰 Tech Stack (compact) ===== -->
<details>
<summary><b>🧰 Tech Stack (compact)</b></summary>

**Core**
  
<img src="https://img.shields.io/badge/Java-%23ED8B00?logo=java&logoColor=white" />
<img src="https://img.shields.io/badge/Go-%2300ADD8?logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/Python-%233776AB?logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-%23007ACC?logo=typescript&logoColor=white" />

**Backend / APIs**
  
<img src="https://img.shields.io/badge/Spring%20Boot-%236DB33F?logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Gin-%2300ADD8?logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/Express.js-%23000000?logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/REST-royalblue" />
<img src="https://img.shields.io/badge/gRPC-%2366595C?logo=grpc&logoColor=white" />
<img src="https://img.shields.io/badge/WebSockets-black" />

**Frontend**
  
<img src="https://img.shields.io/badge/React-%2361DAFB?logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Next.js-%23000000?logo=nextdotjs&logoColor=white" />

**Data / Messaging**
  
<img src="https://img.shields.io/badge/PostgreSQL-%23336791?logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-%23DC382D?logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Elasticsearch-%23005571?logo=elasticsearch&logoColor=white" />
<img src="https://img.shields.io/badge/Kafka-%23231F20?logo=apachekafka&logoColor=white" />
<img src="https://img.shields.io/badge/RabbitMQ-%23FF6600?logo=rabbitmq&logoColor=white" />

**Cloud / DevOps**
  
<img src="https://img.shields.io/badge/AWS-%23232F3E?logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-%232496ED?logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Kubernetes-%23326CE5?logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub%20Actions-%232088FF?logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Terraform-%237B42BC?logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/Argo%20CD-%23EF7B4D?logo=argo&logoColor=white" />
<img src="https://img.shields.io/badge/Nginx-%23009639?logo=nginx&logoColor=white" />

**GenAI**
  
<img src="https://img.shields.io/badge/LangChain-%23000000?logo=chainlink&logoColor=white" />
<img src="https://img.shields.io/badge/RAG-%23007ACC" />
<img src="https://img.shields.io/badge/Hugging%20Face-%23FFD21E?logo=huggingface&logoColor=black" />

> trimmed for speed. full toolbelt & projects live on my <b>Portfolio</b>.
</details>

<!-- ===== 📊 Stats ===== -->
<details>
<summary><b>📊 GitHub Stats</b></summary>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=UchihaIthachi&theme=transparent&hide_border=true" alt="GitHub Streak" />
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=UchihaIthachi&show_icons=true&include_all_commits=true&count_private=true&theme=transparent&hide_border=true" alt="GitHub Stats" />
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=UchihaIthachi&layout=compact&langs_count=8&theme=transparent&hide_border=true" alt="Top Languages" />
</p>
</details>

<!-- ===== 🏆 Extras ===== -->
<details>
<summary><b>🏆 Trophies & Fun</b></summary>
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=UchihaIthachi&theme=matrix&no-bg=true&no-frame=true&row=1&column=6" alt="Trophies" />
</p>
<p align="center">
  <img alt="Snake eating my contributions" src="https://raw.githubusercontent.com/UchihaIthachi/UchihaIthachi/output/github-contribution-grid-snake.svg" />
</p>
<!-- only works if the file exists in your repo -->
<p align="center">
  <img src="./profile-3d-contrib/profile-green-animate.svg" alt="3D contribution graph" />
</p>
</details>

<!-- ===== 🩸 BERSERK ===== -->
<details>
<summary><b>🩸 Berserk</b></summary>

<p align="center">
  <img src="https://github.com/UchihaIthachi/UchihaIthachi/blob/main/img/griffith-berserk-sacrifice.gif" alt="Griffith" />
</p>
<p align="center"><i>“A dream can make a man feel alive. It gives him something to live for. But when that dream is over, it becomes a burden.” — Griffith</i></p>

</details>

<!-- ===== ☎️ Contact ===== -->
<details>
<summary><b>☎️ Contact</b></summary>

<p>
  <a href="https://harshanalf.netlify.app/">
    <img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-harshanalf.netlify.app-222?style=for-the-badge&logo=vercel" />
  </a>
  <a href="mailto:harshanalf.work@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-harshanalf.work%40gmail.com-red?style=for-the-badge&logo=gmail" />
  </a>
  <a href="https://leetcode.com/HarshanaUOM/">
    <img alt="LeetCode" src="https://img.shields.io/badge/LeetCode-HarshanaUOM-ffa116?style=for-the-badge&logo=leetcode&logoColor=white" />
  </a>
  <a href="https://www.hackerrank.com/profile/210167e_cse_21">
    <img alt="HackerRank" src="https://img.shields.io/badge/HackerRank-210167e__cse__21-2ec866?style=for-the-badge&logo=hackerrank&logoColor=white" />
  </a>
  <!-- Optional: add when ready -->
  <a href="LINKEDIN_URL">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="GFG_URL">
    <img alt="GeeksforGeeks" src="https://img.shields.io/badge/GeeksforGeeks-Profile-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" />
  </a>
 
</p>
</details>

<p align="center">
  <sub>Thanks for visiting — Projects & details live on my <a href="https://harshanalf.netlify.app/">Portfolio</a>. Last updated: 2026-10-28</sub>
</p>

<p align="center">
  <img src="https://github.com/UchihaIthachi/UchihaIthachi/blob/main/img/pixel-art-asarge.gif" alt="Guts vs Griffith" height="230" width="90%" />
</p>

<p align="center">
  <img src="https://github.com/AnderMendoza/AnderMendoza/raw/main/assets/line-neon.gif" width="100%" alt="Neon divider" />
</p>
