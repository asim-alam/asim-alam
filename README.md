<img src="./assets/banner.png" width="100%" alt="Pixel-art workspace overlooking Dhaka at night, with an AI dashboard and a small rover on the desk." />

<h1 align="center">Asim Alam Chowdhury</h1>

<p align="center">
  <img src="./assets/typing-loop.gif" width="520" alt="Multi-Agent AI, Hybrid RAG and Search, TinyML and ESP32 Robotics" />
</p>

I study Software Engineering at the University of Dhaka. I build AI agents that work with local documents, tools that show where their answers come from, and robots that can listen and see on-device.

[Portfolio](https://www.asim-alam.me/) · [LinkedIn](https://www.linkedin.com/in/asim-alam-chowdhury/) · [Repositories](https://github.com/asim-alam?tab=repositories)

## Selected work

<img src="./assets/selected-work.png" width="100%" alt="Three technical illustrations showing a desktop research dashboard, a voice-first maternal health app, and a camera-equipped rover." />

**Explore by interest** · [AI agents](#the-eye) · [Bangla voice and retrieval](#maasathi-ai) · [Embedded robotics](#voice-controlled-tracking-robot)

### The Eye

A desktop research dashboard where cooperating agents search local documents and the web. I built a runtime context manager that decides what each agent sees on each turn.

`Electron` · `Next.js` · `Hybrid RAG` · [Project write-up ↗](https://www.asim-alam.me/work/the-eye)

<details>
<summary>Trace a research query</summary>

```text
Question → Local document search and web research
         → Runtime context manager → Cooperating agents
```

Local search combines semantic similarity with BM25 keyword matching. The context manager controls which material each agent receives on each turn.

</details>

### MaaSathi AI

A Bangla voice-first maternal health companion. Answers include references, and the app can route urgent cases to health workers.

`TypeScript` · `LangGraph` · `Supabase` · [Project write-up ↗](https://www.asim-alam.me/work/maasathi-ai)

<details>
<summary>Follow a spoken question</summary>

```text
Bangla voice input → Query classification
                   → Source retrieval → Answer with citations
```

Retrieved passages are reranked before the app answers. A rules-first triage flow can escalate urgent cases to a health worker.

</details>

### Voice-Controlled Tracking Robot

A small rover that recognizes spoken commands, tracks objects with an onboard camera, and avoids obstacles. Recognition runs on the ESP32 hardware.

`C++` · `ESP32-S3` · `TinyML` · [Source code ↗](https://github.com/asim-alam/voice-controlled-object-tracking-robot)

<details>
<summary>Follow a command through the rover</summary>

```text
Microphone → ESP32-S3 keyword spotting
Camera     → ESP32-CAM object detection
Ultrasonic → Obstacle distance
```

A finite-state machine selects the rover’s behavior. PID control adjusts its movement as it tracks a target.

</details>

## GitHub activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/asim-alam/asim-alam/output/snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/asim-alam/asim-alam/output/snake.svg" width="100%" alt="Animated snake tracing Asim’s GitHub contribution calendar" />
  </picture>
</p>

<details>
  <summary>Stats and repository languages</summary>

  <p align="center">
    <img src="https://github-stats-extended.vercel.app/api?username=asim-alam&amp;show_icons=true&amp;theme=tokyonight&amp;hide_border=true" height="155" alt="Asim’s GitHub stats" />
    <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=asim-alam&amp;layout=compact&amp;theme=tokyonight&amp;hide_border=true&amp;langs_count=6" height="155" alt="Most-used languages in Asim’s public repositories" />
  </p>
</details>
