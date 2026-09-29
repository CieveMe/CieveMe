# Zhen He

**Java / AI application engineer.** Nine years shipping production systems end to end — now doing it with AI agents in the loop.

I build the unglamorous parts that have to actually work: video-surveillance and IoT backends, payment integrations, and the tooling that lets agents operate them safely.

📄 **[Case studies](https://github.com/CieveMe/portfolio)** — how two production deliveries were actually built, with the constraints and the numbers.

---

### What I work on

| Area | Concrete experience |
|---|---|
| **Video & IoT platforms** | GB28181 / GA-T 1400 / RTSP integration with ZLMediaKit, H.264/H.265 playback with seek over HTTP Range, GA-T 1400 image and structured-data ingestion, MQTT (QoS 1, persistent sessions, topic-level permissions), RFID device onboarding |
| **Payments & WeChat** | Full WeChat Pay V3 loop (JSAPI payment → async callback → refund → refund callback), Alipay QR payment, WeChat Mini Programs, WeCom order management |
| **AI-assisted delivery** | MCP servers, agent skills, Claude Code workflows, read-only data-access patterns, prompt and context engineering |
| **Platform & ops** | Spring Boot services, MySQL / Redis, Kafka / RocketMQ, Docker deployment with backup and rollback validation, documentation and source handover |

### Selected work

**[mysql-ops-mcp](https://github.com/CieveMe/mysql-ops-mcp)** — a read-only-first MCP server that gives an AI agent safe access to a private MySQL database through its own SSH tunnel. 24 unit tests, mutating tools unregistered by default, and a SQL guard that accepts nothing but a single read statement.

**[agent-skills](https://github.com/CieveMe/agent-skills)** — the rule sets I give my coding agents, extracted from real deliveries and sanitised: payment integration traps, deployment failure modes, database-change safety, campaign hot-configuration.

**wvp-GB28181-pro** (open source, 7.3k★) — four open pull requests:
[SIP session cleanup / orphan-RTP fix #2244](https://github.com/648540858/wvp-GB28181-pro/pull/2244) ·
[hook callback authentication #2243](https://github.com/648540858/wvp-GB28181-pro/pull/2243) ·
[RecordInfo paging #2242](https://github.com/648540858/wvp-GB28181-pro/pull/2242) ·
[#2241](https://github.com/648540858/wvp-GB28181-pro/pull/2241)

**[openai/codex #48314](https://github.com/openai/codex/issues/48314)** — reported a Windows MCP startup failure, traced to a missing file in the installed plugin directory, with exact reproduction steps and root cause.

### Research & citable artifacts

Reproduction work built on pinned expectations, negative controls that must fail, and a versioned DOI
chain — every number produced by one command, and every correction published in the release body of the
next version rather than edited into the old one.

- **[autoresearch-experiment-runner](https://github.com/CieveMe/autoresearch-experiment-runner)** — a mechanism-level reproduction of two 2024 optimizer proposals, plus a task contract an agent submission can be scored against. Concept DOI: [10.5281/zenodo.23003610](https://doi.org/10.5281/zenodo.23003610)
- **[mcp-security-benchmark](https://github.com/CieveMe/mcp-security-benchmark)** — a probe corpus for MCP server security: six threat classes, fourteen cases, and a harness with controls that must fail. Concept DOI: [10.5281/zenodo.23003715](https://doi.org/10.5281/zenodo.23003715)
- **[mysql-ops-mcp](https://github.com/CieveMe/mysql-ops-mcp)** — a read-only-first MCP server for MySQL over its own SSH tunnel. Concept DOI: [10.5281/zenodo.23003962](https://doi.org/10.5281/zenodo.23003962)

ORCID: [0009-0009-1526-5793](https://orcid.org/0009-0009-1526-5793) — citation queries, corrections and
reproduction reports are welcome: open an issue on the repository, or write to the address below.

### Stack

`Java` `Spring Boot` `Spring Cloud` `MySQL` `Redis` `Kafka` `RocketMQ` `Vue 3` `Docker` `Python`
`MCP` `Claude Code` `agent skills` `YOLOv8` `GB28181` `GA-T 1400` `RTSP` `ZLMediaKit` `MQTT`

---

📫 [cieve94107@gmail.com](mailto:cieve94107@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/zhen-he-a2336a43a) · 📍 Baotou, Inner Mongolia, China (UTC+8)

<sub>中文：9 年 Java 全栈，主做视频监控 / 物联网平台与微信支付、小程序，近期专注 MCP / Agent 工具链。远程合作优先。</sub>
