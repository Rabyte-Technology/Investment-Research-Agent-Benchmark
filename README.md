# IRAB — Investment Research Agent Benchmark

> A benchmark for evaluating agents in real investment research workflows.

[🏆 Leaderboard](http://irab.rabyte.cn/leaderboard/) · [📄 Report (coming soon)](#citation) · [License: CC BY 4.0](#license)

---

## What is IRAB

IRAB measures **how well an agent performs in real investment-research environments** — the open-ended, multi-step work a buy-side analyst does to support a decision, not synthetic Q&A. Tasks are desensitized from genuine analyst queries; each answer is graded by an LLM judge against a multi-dimensional rubric and an expert-written gold reference.

Tasks span company deep-dives, sector research, peer comparison, valuation & modeling, market reviews, macro & policy, event/mechanism analysis, strategy backtests, screening & monitoring, visualization, and tooling. Initial coverage centers on the Chinese stock market (A-share / HK / Chinese policy), while also reaching into US equities, commodities, and global macro.


---

## What's in this repo

This is the **public set** — a representative sample of IRAB for inspection and development:

| Path | Contents |
|------|----------|
| `data/tasks/` | The investment research questions |
| `data/rubrics/` | The scoring dimensions and weights bound to each task. |
| `data/gold/` | Gold reference for judge to score on each rubric |


**What's not in this repo**: the remaining held-out test set, and the detailed scoring criteria.

---

## Leaderboard

Official results are run on the **full benchmark**, including the private held-out set, so that scores remain meaningful even after the public sample is widely available.

➡️ **Leaderboard:** <http://irab.rabyte.cn/leaderboard/>
➡️ **Submit a model:** contact [fangst01@rabyte.cn](mailto:fangst01@rabyte.cn)


---

## License

Data in this repository is released under **[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)** (see [`LICENSE`](LICENSE)) — you are free to share and adapt the material for any purpose, including commercially, provided you give appropriate credit. 

---

## Citation

📄 A paper/technical report is forthcoming — citation details will be added here on publication.

---

## Contact

Maintained by **Rabyte Technology** — contact [fangst01@rabyte.cn](mailto:fangst01@rabyte.cn) or open an [issue](https://github.com/Rabyte-Technology/Investment-Research-Agent-Benchmark/issues).
