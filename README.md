# Zhen He

**Java / AI application engineer.** Nine years shipping production systems end to end — now doing it with AI agents in the loop.

I build the unglamorous parts that have to actually work: video-surveillance and IoT backends, payment integrations, and the tooling that lets agents operate them safely.

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

**wvp-GB28181-pro** (open source, 7.3k★) — four open pull requests:
[SIP session cleanup / orphan-RTP fix #2244](https://github.com/648540858/wvp-GB28181-pro/pull/2244) ·
[hook callback authentication #2243](https://github.com/648540858/wvp-GB28181-pro/pull/2243) ·
[RecordInfo paging #2242](https://github.com/648540858/wvp-GB28181-pro/pull/2242) ·
[#2241](https://github.com/648540858/wvp-GB28181-pro/pull/2241)

**[openai/codex #48314](https://github.com/openai/codex/issues/48314)** — reported a Windows MCP startup failure, traced to a missing file in the installed plugin directory, with exact reproduction steps and root cause.

### Stack

`Java` `Spring Boot` `Spring Cloud` `MySQL` `Redis` `Kafka` `RocketMQ` `Vue 3` `Docker` `Python`
`MCP` `Claude Code` `agent skills` `YOLOv8` `GB28181` `GA-T 1400` `RTSP` `ZLMediaKit` `MQTT`

---

📫 [13381875196@163.com](mailto:13381875196@163.com) · 💼 [LinkedIn](https://www.linkedin.com/in/zhen-he-a2336a43a) · 📍 Baotou, Inner Mongolia, China (UTC+8)

<sub>中文：9 年 Java 全栈，主做视频监控 / 物联网平台与微信支付、小程序，近期专注 MCP / Agent 工具链。远程合作优先。</sub>
