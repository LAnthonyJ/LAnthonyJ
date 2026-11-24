<h1><picture><source media="(prefers-reduced-motion: reduce)" srcset="./assets/hello-anthony-still.svg?v=3e406b5a"><img src="./assets/hello-anthony.svg?v=299cab69" alt="Hi there! Anthony Zhang, data science student at SUSTech." width="100%"></picture></h1>

<p align="center"><strong>Hangyuan Zhang</strong> · Data science undergraduate<br>Southern University of Science and Technology (SUSTech) · Expected June 2027</p>
<p align="center"><a href="https://lanthonyj.github.io/Hangyuan-Zhang-CV.pdf">One-page CV (PDF)</a> · <a href="https://lanthonyj.github.io/">Portfolio</a> · <a href="#open-source-contributions">Open source contributions</a> · <a href="mailto:zhanghangyuan19@163.com">Email me</a></p>

## 🛠️ Selected projects

<h3><a href="https://github.com/LAnthonyJ/intelligent-scissors-java"><picture><source media="(prefers-reduced-motion: reduce)" srcset="./assets/intelligent-scissors-still.svg?v=abb467eb"><img src="./assets/intelligent-scissors.svg?v=11a0b895" alt="Intelligent Scissors — I connected clicks along image edges using shortest paths." width="100%"></picture></a></h3>

I used Sobel gradients to find strong edges and Dijkstra’s algorithm to connect the user’s clicks in a Java Swing editor. The leaf example shows how eight anchors become a transparent PNG. [Try the leaf sample](https://github.com/LAnthonyJ/intelligent-scissors-java#try-the-leaf-sample) · [Pathfinding code](https://github.com/LAnthonyJ/intelligent-scissors-java/blob/main/dsbb_project/src/PathFinder.java)

<h3><a href="https://github.com/LAnthonyJ/meteorite-classification-model"><picture><source media="(prefers-reduced-motion: reduce)" srcset="./assets/litholens-still.svg?v=82a69dff"><img src="./assets/litholens.svg?v=02d9b7f7" alt="Meteorite Classification Model. The team submitted test photo 000120 as a meteorite and 000070 as a non-meteorite." width="100%"></picture></a></h3>

I worked on modeling and evaluation in a five-person team. Our classifier combined image features with surface texture to distinguish meteorites from terrestrial rocks and reached **0.86046 F1** on the competition’s second-stage private test set. [See how the blend changed these two predictions](https://github.com/LAnthonyJ/meteorite-classification-model#which-images-did-the-blend-change) · [Competition results](https://github.com/LAnthonyJ/meteorite-classification-model#competition-results)

## More projects

- **[NLP in PyTorch](https://github.com/LAnthonyJ/-nlp-)** · I implemented Transformer attention and tested whether it could read ahead. Changing the fourth input left the first three outputs identical with a causal mask. [Run the four-token example](https://github.com/LAnthonyJ/-nlp-#can-a-future-token-change-an-earlier-output) · [Training experiments](https://github.com/LAnthonyJ/-nlp-/blob/main/docs/hard-pairs-v3-results/README.md)
- **[DataLens Lab](https://github.com/LAnthonyJ/datalens-lab)** · I fine-tuned Qwen3.5-0.8B and tested whether it could write runnable SQL and ask for missing data on 24 held-out prompts. [Experiment results](https://github.com/LAnthonyJ/datalens-lab#what-the-experiments-found)
- **[World Cup forecasting](https://github.com/LAnthonyJ/worldcup_prediction)** · I compared football score predictions with the outcomes of 70 matches. [Backtest](https://github.com/LAnthonyJ/worldcup_prediction/blob/master/PROJECT_PROGRESS.md)
- **[High-frequency stock factors with Hadoop](https://github.com/LAnthonyJ/hadoop-high-frequency-stock-factors)** · A Java MapReduce job computes 20 market-wide factors from five-level order books. In the course benchmark, single-pass aggregation cut runtime from over 100 seconds to 24 seconds. [Worked example](https://github.com/LAnthonyJ/hadoop-high-frequency-stock-factors#from-quotes-to-factors)
- **[CartPole reinforcement learning](https://github.com/LAnthonyJ/AI_Intellgence_B_Project)** · In this course team project, I updated the behavioral cloning training script to track training loss alongside evaluation scores. [My changes](https://github.com/TOGAWA-NAGASAKI/AI_Intellgence_B_Project/commit/959b80585514db05e79ac854873c558b4647e882)

## Open source contributions

<h3><a href="https://github.com/linshenkx/prompt-optimizer"><picture><source media="(prefers-reduced-motion: reduce)" srcset="./assets/prompt-optimizer-still.svg?v=3d68048f"><img src="./assets/prompt-optimizer.svg?v=ffdd64b6" alt="Prompt Optimizer: rewrite a draft, test both prompts on the same input, and compare the answers." width="100%"></picture></a></h3>

Prompt Optimizer lets you rewrite a prompt, run both versions on the same input, and compare the answers side by side. [Try the web app](https://prompt.always200.com) · [Walkthrough](https://docs.always200.com/en/user/quick-start/)

**My contribution.** I updated the shared parser for OpenAI-compatible APIs so developers can read token usage from non-streaming chat responses. I added tests for providers that omit counts, report zero tokens, or use a different field for cache hits. [Merged PR #379](https://github.com/linshenkx/prompt-optimizer/pull/379)
