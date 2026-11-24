<h1><picture><source media="(prefers-reduced-motion: reduce)" srcset="./assets/hello-anthony-still.svg?v=3e406b5a"><img src="./assets/hello-anthony.svg?v=299cab69" alt="Hi there! Anthony Zhang, data science student at SUSTech." width="100%"></picture></h1>

<p align="center"><strong>Hangyuan Zhang</strong> · Data science undergraduate<br>Southern University of Science and Technology (SUSTech) · Expected June 2027</p>
<p align="center"><a href="https://lanthonyj.github.io/Hangyuan-Zhang-CV.pdf">One-page CV (PDF)</a> · <a href="https://lanthonyj.github.io/">Portfolio</a> · <a href="mailto:zhanghangyuan19@163.com">Email me</a></p>

## 🛠️ Selected projects

<h3><a href="https://github.com/linshenkx/prompt-optimizer/pull/379"><picture><source media="(prefers-reduced-motion: reduce)" srcset="./assets/prompt-optimizer-still.svg?v=84d8aa7c"><img src="./assets/prompt-optimizer.svg?v=9befba1f" alt="Prompt Optimizer — I fixed missing token counts for three providers. Merged PR 379." width="100%"></picture></a></h3>

**Open-source contribution.** OpenAI, MiniMax, and DeepSeek returned token counts in non-streaming chat responses, but Prompt Optimizer’s shared parser dropped them. I fixed the parser and added regression tests. In the MiniMax test, the caller now receives all 30 reported tokens (10 input and 20 output). [Merged PR #379](https://github.com/linshenkx/prompt-optimizer/pull/379) · [Code and tests](https://github.com/linshenkx/prompt-optimizer/pull/379/files)

<h3><a href="https://github.com/LAnthonyJ/intelligent-scissors-java"><picture><source media="(prefers-reduced-motion: reduce)" srcset="./assets/intelligent-scissors-still.svg?v=abb467eb"><img src="./assets/intelligent-scissors.svg?v=11a0b895" alt="Intelligent Scissors — I connected clicks along image edges using shortest paths." width="100%"></picture></a></h3>

I used Sobel gradients to find strong edges and Dijkstra’s algorithm to connect the user’s clicks in a Java Swing editor. The leaf example shows how eight anchors become a transparent PNG. [Try the leaf sample](https://github.com/LAnthonyJ/intelligent-scissors-java#try-the-leaf-sample) · [Pathfinding code](https://github.com/LAnthonyJ/intelligent-scissors-java/blob/main/dsbb_project/src/PathFinder.java)

<h3><a href="https://github.com/LAnthonyJ/-nlp-"><picture><img src="./assets/nlp-pytorch.svg?v=3ebb832e" alt="NLP in PyTorch — changing the fourth input leaves the first three outputs unchanged with causal masking." width="100%"></picture></a></h3>

I implemented Transformer attention in PyTorch and tested whether it could read ahead. I changed only the fourth input token. With the causal mask, the largest change in the first three outputs was **0.0**. Removing the mask changed those outputs. [Run the four-token example](https://github.com/LAnthonyJ/-nlp-#can-a-future-token-change-an-earlier-output) · [Attention implementation](https://github.com/LAnthonyJ/-nlp-/blob/main/src/nlp_course/transformer.py) · [Training experiments](https://github.com/LAnthonyJ/-nlp-/blob/main/docs/hard-pairs-v3-results/README.md)

<h3><a href="https://github.com/LAnthonyJ/LithoLens"><picture><source media="(prefers-reduced-motion: reduce)" srcset="./assets/litholens-still.svg?v=0c81d1f1"><img src="./assets/litholens.svg?v=1ed34fbb" alt="Meteorite Classification Model — meteorite specimen and its edge map." width="100%"></picture></a></h3>

I worked on modeling and evaluation in a five-person team. Our classifier combined image features with surface texture to distinguish meteorites from terrestrial rocks and reached **0.86046 F1** on the competition’s second-stage private test set. [Explore the specimens](https://github.com/LAnthonyJ/LithoLens#training-data) · [Competition results](https://github.com/LAnthonyJ/LithoLens#competition-results)

**More projects** · [DataLens Lab](https://github.com/LAnthonyJ/datalens-lab) · [A 70-match backtest of World Cup forecasts](https://github.com/LAnthonyJ/worldcup_prediction/blob/master/PROJECT_PROGRESS.md)
