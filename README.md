# Hi, I’m Rajath U

I’m a computer science engineering student in Mysuru. I build real-time multiplayer applications and tools for testing AI systems. Two questions behind my projects are how to keep a drawing room in sync and how to reproduce an AI workflow failure offline.

[Play DOODL](https://doodl.rajath-raj2569.workers.dev) · [Connect on LinkedIn](https://www.linkedin.com/in/rajath-u-51b99a320/)

## Selected projects

### [DOODL](https://github.com/Rajath123562/doodl) · TypeScript, React, Cloudflare

A multiplayer drawing and guessing game. Players share a canvas over WebSockets, and each room keeps its state in a Cloudflare Durable Object backed by SQLite. To see it in action, open the same room in two browser windows and draw in one. The repository documents the two-browser Playwright tests.

### [ChaosHarness](https://github.com/Rajath123562/ChaosHarness) · Python, pytest

A tool for testing how AI workflows respond to failures and replaying the results offline. One replay bug appeared on Ubuntu because an image could be encoded differently from the recording. Saving the original image bytes made the replay reproducible across Windows and Linux. [Read the fix](https://github.com/Rajath123562/ChaosHarness/commit/bd60e3d9b4298c0e2614e11a5f57ec39d3a248c7) · [See the four CI jobs](https://github.com/Rajath123562/ChaosHarness/actions/runs/45581993599)

### [Matching Engine](https://github.com/Rajath123562/matching-engine) · C99, POSIX threads

A limit order book simulator. Separate heaps track the best bid and ask, trader threads submit orders, and a terminal dashboard displays market depth. [Explore the order book implementation](https://github.com/Rajath123562/matching-engine/blob/main/order_book.c)

## More work

- [SentinelVault](https://github.com/Rajath123562/SentinelVault) tracks privacy budgets for aggregate queries and records releases in a signed audit log.
- [Debtify](https://github.com/Rajath123562/debtify-dashboard) uses ticket estimates and completion times to explore the cost of technical debt.
- [RAG AI Assistant](https://github.com/Rajath123562/RAG-AI-Assistant) uses Python, Streamlit, and Gemini for Q&A grounded in supplied documents.
- [Heart Disease ML Pipeline](https://github.com/Rajath123562/heart-disease-ml-pipeline) implements logistic regression and decision trees in TypeScript.

<details>
<summary>Repository language breakdown</summary>

![Languages across my repositories](https://github-readme-stats.vercel.app/api/top-langs/?username=Rajath123562&exclude_repo=AeroDev&layout=compact&theme=tokyonight&hide_border=true)

</details>
