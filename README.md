<p align="center">
  <img src="./assets/profile-banner.svg" alt="Xiang Liu - Efficient LLM Inference and Agent Systems" width="100%">
</p>

<p align="center">
  <a href="https://xiangl-ml.github.io/"><img alt="Homepage" src="https://img.shields.io/badge/Homepage-xiangl--ml.github.io-0F766E?style=for-the-badge"></a>
  <a href="https://scholar.google.com/citations?user=VtK5lwUAAAAJ"><img alt="Google Scholar" src="https://img.shields.io/badge/Google%20Scholar-citations-2563EB?style=for-the-badge"></a>
  <a href="https://twitter.com/Dominicliu12"><img alt="X" src="https://img.shields.io/badge/X-@Dominicliu12-111827?style=for-the-badge"></a>
</p>

<p align="center">
  <b>Ph.D. student @ HKUST(GZ)</b> · <b>Research Intern @ Mind Lab</b><br>
  Efficient and reliable LLMs: inference, long context, KV cache, retrieval, and agentic workflows.
</p>

<br>

<table>
  <tr>
    <td align="center" width="33%">
      <b>40+ stars</b><br>
      <sub>personal public non-fork repos</sub>
    </td>
    <td align="center" width="33%">
      <b>8.4k+ / 1.1k+</b><br>
      <sub>contributed projects: LMFlow / kvpress</sub>
    </td>
    <td align="center" width="33%">
      <b>benchmark → method → artifact</b><br>
      <sub>how I like research to ship</sub>
    </td>
  </tr>
</table>

## Current Focus

<table>
  <tr>
    <td width="50%">
      <b>Inference efficiency</b><br>
      <sub>KV-cache compression, token-efficient reasoning, energy-to-token evaluation, serving bottlenecks.</sub>
    </td>
    <td width="50%">
      <b>Long-context evaluation</b><br>
      <sub>Generation-focused benchmarks, dense reasoning integrity, multi-turn coherence.</sub>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <b>Agent systems</b><br>
      <sub>Tool use, post-training, harness design, local-first agent workflow infrastructure.</sub>
    </td>
    <td width="50%">
      <b>Research infrastructure</b><br>
      <sub>Reproducible artifacts, project pages, scholar tracking, figure and report tooling.</sub>
    </td>
  </tr>
</table>

## Selected Work

<table>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/OptimalScale/LMFlow">LMFlow</a></h3>
      <p>Contributed to an extensible toolkit for fine-tuning and inference of large foundation models.</p>
      <p>
        <img alt="stars" src="https://img.shields.io/github/stars/OptimalScale/LMFlow?style=social">
        <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
      </p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/Dominic789654/LongGenBench">LongGenBench</a></h3>
      <p>Long-context generation benchmark for coherent, context-aware long-form responses.</p>
      <p>
        <img alt="stars" src="https://img.shields.io/github/stars/Dominic789654/LongGenBench?style=social">
        <img alt="paper" src="https://img.shields.io/badge/EMNLP%20Findings-2024-7C3AED?style=flat-square">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/Dominic789654/quantarena-clean">QuantArena</a></h3>
      <p>Policy-conditioned live-market evaluation for LLM trading agents. Benchmark the policy, not just the model.</p>
      <p>
        <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
        <img alt="agents" src="https://img.shields.io/badge/agent%20eval-0F766E?style=flat-square">
      </p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/Dominic789654/agent-hub">agent-hub</a></h3>
      <p>Local-first agent task hub with SQLite queueing, dependency-aware dispatch, templates, and dashboards.</p>
      <p>
        <img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white">
        <img alt="workflow" src="https://img.shields.io/badge/workflow%20runtime-1F2937?style=flat-square">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/Dominic789654/tinker2openai-tool">tinker2openai-tool</a></h3>
      <p>Adapters between XML-like tool calls and OpenAI-style structured tool-call histories.</p>
      <p>
        <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
        <img alt="tool use" src="https://img.shields.io/badge/tool%20use-2563EB?style=flat-square">
      </p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/Dominic789654/energy-to-token">energy-to-token</a></h3>
      <p>Project page for evaluating LLM inference as energy-to-token production.</p>
      <p>
        <img alt="HTML" src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white">
        <img alt="serving" src="https://img.shields.io/badge/LLM%20serving-92400E?style=flat-square">
      </p>
    </td>
  </tr>
</table>

## Research Map

```text
long-context generation ──┬── LongGenBench
                          ├── semantic integrity under KV compression
                          └── multi-turn coherence / FlowKV

agent capability eval ────┬── QuantArena
                          ├── tool-use adapters
                          └── local-first agent workflow runtime

efficient inference ──────┬── ChunkKV / KV compression
                          ├── token-efficient reasoning
                          └── energy-to-token production
```

## Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white">
  <img alt="LaTeX" src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white">
</p>

<p align="center">
  <img height="156" src="https://github-readme-stats.vercel.app/api?username=Dominic789654&show_icons=true&hide_border=true&hide_title=true&theme=transparent" alt="GitHub stats">
  <img height="156" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dominic789654&layout=compact&hide_border=true&theme=transparent" alt="Top languages">
</p>

<p align="center">
  <a href="https://github.com/Dominic789654?tab=repositories">repositories</a>
  ·
  <a href="https://xiangl-ml.github.io/#publications">publications</a>
  ·
  <a href="https://scholar.google.com/citations?user=VtK5lwUAAAAJ">citations</a>
</p>
