<div align="center">

<h1>Xu Shuyao</h1>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=58A6FF&center=true&vCenter=true&width=640&lines=AI+%C3%97+Quantitative+Trading;Regime+models+%C2%B7+Market+world+models+%C2%B7+Autonomous+agents;EE+%40+NUS+(minor+AI+%26+CS)+%C2%B7+Stanford+IHP+'26+%C2%B7+Co-founder+%40+Alpha+Flow)](https://git.io/typing-svg)

<p>NUS EE (minor AI &amp; CS) '29 &nbsp;·&nbsp; Stanford IHP '26</p>

<p>
<a href="mailto:xushuyao@u.nus.edu"><img src="https://img.shields.io/badge/Email-xushuyao%40u.nus.edu-blue?style=flat-square&logo=gmail" /></a>
<a href="https://www.linkedin.com/in/xushuyao-nus/"><img src="https://img.shields.io/badge/LinkedIn-Xu_Shuyao-0A66C2?style=flat-square&logo=linkedin" /></a>
<a href="https://davidxu277.github.io"><img src="https://img.shields.io/badge/Website-davidxu277.github.io-222?style=flat-square&logo=googlechrome&logoColor=white" /></a>
</p>

</div>

---

> *Markets change regimes. Models that don't, break.*

I study Electrical Engineering (minor in AI & CS) at NUS and build machine-learning systems for markets — models that first figure out **what state the market is in**, then decide what to do about it.

I co-founded **Alpha Flow**, where we build world-model training infrastructure for AI-driven quantitative trading.

---

## How I Got Here

- **2025** — NUS Electrical Engineering (minor AI & CS), Science & Technology Scholarship
- **Jun 2026** — Stanford IHP: CS 229 Machine Learning, EE 364A Convex Optimization
- **Jun 2026** — Built Alpha Timing, a regime-aware trading system
- **Jul 2026** — Co-founded Alpha Flow

---

## Focus Areas

<table>
<tr>
<td align="center" width="180"><b>🧭 Market Regimes</b><br/><sub>Bull · Bear · Sideways · Crisis<br/>Nowcasting · Routing</sub></td>
<td align="center" width="180"><b>🌍 World Models</b><br/><sub>Market dynamics<br/>Multi-agent simulation</sub></td>
<td align="center" width="180"><b>📈 ML for Alpha</b><br/><sub>Gradient boosting · Backtesting<br/>Out-of-sample discipline</sub></td>
</tr>
<tr>
<td align="center" width="180"><b>🤖 Autonomous Agents</b><br/><sub>LLM tool use · Self-verification<br/>Agent control loops</sub></td>
<td align="center" width="180"><b>∑ Optimization</b><br/><sub>Convex optimization<br/>Linear algebra</sub></td>
<td align="center" width="180"><b>🛠 Full-Stack Systems</b><br/><sub>TypeScript · PostgreSQL<br/>Docker · CI/CD</sub></td>
</tr>
</table>

---

## Projects

### Quant

#### 📊 [Alpha Timing](https://github.com/davidxu277/alpha-timing) — Regime-Aware Quantitative Trading
*Jun – Jul 2026 · Python · scikit-learn* · **[▶ Live dashboard](https://davidxu277.github.io/alpha-timing/)**

A regime classifier routes each trading day to one of four specialist return predictors; a cost-aware dual-threshold rule with volatility targeting sets the position.

```
Data:     39 tickers · 245K rows · 2000–2026 · 28 trailing, vol-normalized features
SPY out-of-sample, net of 5 bps costs:
          Sharpe 1.05   vs  0.69 buy-and-hold
          Max DD  −14%  vs  −25%
```

Honest post-mortem: I first tried a reinforcement-learning agent (DQN). Under the low signal-to-noise of daily returns it was unstable, so I replaced it with supervised regime specialists — and used oracle-routing ablations to show the classifier was not the bottleneck.

#### 🧭 [Regime Classifier](https://github.com/davidxu277/regime-classifier) — Market-Regime Nowcaster
*Jul 2026 · Python · RandomForest*

The first stage of Alpha Timing: classifies *today's* market state from trailing price and macro features.

```
Out-of-sample 2019–2026:  accuracy 0.877 · macro F1 0.846
```

#### 🌍 Alpha Flow research: [MicroWorld](https://github.com/hongjin-he/MicroWorld)
A multi-agent world model of US equity markets — institutional players, information asymmetry, emergent price dynamics. Research at Alpha Flow, with co-founder HongJin He.

### Agent Systems

#### 🩺 [ML Doctor](https://github.com/davidxu277/GOAT-LeBron) — Autonomous ML Research Agent
*Aug – Sep 2026 · TikTok TechJam 2026*

Runs the full model-improvement loop unattended — diagnose, propose and justify a remedy, write the code, retrain, then check whether the hypothesis held. I owned the agent brain: a four-role LLM relay plus the outer control loop. Deterministic code, not the LLM, verifies whether the metric a hypothesis named actually moved.

#### 💰 [Financial AI Agent](https://github.com/davidxu277/financial-ai-agent) — Savings Planning System
*Aug – Oct 2026 · TypeScript*

Next.js + Fastify + PostgreSQL/Prisma monorepo with an OpenAI Agents SDK workflow and human-in-the-loop review of AI classifications.

---

## Stack

```python
ml      = ["PyTorch", "scikit-learn", "NumPy", "Gradient Boosting", "Transformers"]

quant   = ["Regime Modeling", "Backtesting", "Volatility Targeting", "Out-of-sample Validation"]

agents  = ["Claude API", "OpenAI Agents SDK", "Tool Use", "Self-verifying Loops"]

systems = ["Python", "C", "TypeScript", "Next.js", "Fastify", "PostgreSQL", "Docker", "GitHub Actions"]
```

---

<div align="center">
<sub>Electrical Engineering → Machine Learning → Markets · NUS × Stanford · 2026</sub>
</div>
