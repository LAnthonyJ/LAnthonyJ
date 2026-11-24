# Hi, I’m Hangyuan (Anthony) Zhang 👋

I study data science at Southern University of Science and Technology (SUSTech) and expect to graduate in June 2027. I work on ways to check AI-generated answers, from executing SQL queries to tracing scientific claims back to the source paper.

[One-page CV](https://lanthonyj.github.io/Hangyuan-Zhang-CV.pdf) · [Portfolio](https://lanthonyj.github.io/) · [Email](mailto:zhanghangyuan19@163.com)

## 🔬 Research and projects

**Finding evidence in cancer metabolism papers**  
Two papers can report conflicting findings about the same reaction. I built a search prototype that keeps both observations visible and checks generated citations against the original excerpts. [Research overview](https://lanthonyj.github.io/#research)

**DataLens Lab · Teaching a small model when to ask a question**  
“Seven packages arrived damaged. What percentage of shipments arrived damaged?” The assistant needs the total before it can answer. I fine-tuned Qwen3.5-0.8B and evaluated it on 24 held-out English prompts, checking when it asked for missing data and running its SQL against two SQLite fixtures. [Experiment results](https://github.com/LAnthonyJ/datalens-lab#what-the-experiments-found) · [Recorded demo](https://github.com/LAnthonyJ/datalens-lab/blob/main/12311701_%E5%BC%A0%E8%88%AA%E6%BA%90.mp4)

**NLP in PyTorch · Learning from a model’s mistakes**  
Does showing a model its own wrong answers help? I compared two methods using the same starting checkpoint and prompts. Across four tasks and 768 held-out questions, supervised training on correct answers averaged 52.73% accuracy, compared with 45.57% for direct preference optimization. [Experiment and scoring data](https://github.com/LAnthonyJ/-nlp-/blob/main/docs/hard-pairs-v3-results/README.md)

**LithoLens · Telling meteorites from terrestrial rocks**  
In a five-person team, I worked on modeling and evaluation. We combined image features with measurements of surface texture. Our submission reached 0.86046 F1 on the competition’s second-stage private test set. [Competition results and changed predictions](https://github.com/LAnthonyJ/LithoLens#competition-results)

## 🛠️ Open source

**Prompt Optimizer** merged my change to expose token counts from non-streaming OpenAI, MiniMax and DeepSeek responses. I added regression tests for cases where the provider reported usage but the caller never received it. [Merged PR #379](https://github.com/linshenkx/prompt-optimizer/pull/379)

Other projects include a Java tool for [tracing an object’s outline](https://github.com/LAnthonyJ/intelligent-scissors-java#try-the-leaf-sample) and a [70-match backtest of World Cup score forecasts](https://github.com/LAnthonyJ/worldcup_prediction/blob/master/PROJECT_PROGRESS.md).
