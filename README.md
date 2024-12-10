# CS-263-NLP-Final-Project

For the purpose of studying attention mechanisms in large language models (LLMs) for use in subsequent applications, this repository includes the code, experiments, and analysis carried out. Examining and contrasting attention patterns between models such as BERT and LLaMA through tasks like sentiment analysis and text generation is the main goal. Additionally, we have visualized attention using different interpratability tools and methods to capture how the attention differes with these additions.

# Experiments Conducted 

### 1. Examining Attention Patterns in Different Models
Goal: Examine and contrast how attention is distributed in LLaMA and BERT.
The SQuAD dataset is the dataset.
Result: Knowledge of general versus task-specific attention techniques.

### 2. Interpreting Attention Through Several Techniques
Goal: Investigate attention through interpretability tools including attention visualization and gradient-based techniques.
The SQuAD dataset is the dataset.
Result: A greater comprehension of the allocation of attention among layers and tokens.


### 3. Assessment of Attention Rollout Analysis
Goal: Assess how attention moves between layers and how it affects performance on subsequent tasks.
Result: Knowledge on cumulative attention patterns and how they affect task adaptability.


### 4. Focus on Downstream tasks (LLaMA & BERT)
Goal: Examine attention mechanisms while performing downstream tasks in order to comprehend how they behave differently depending on the task.
LLaMA for Text Generation: Prioritized coherence and context by examining attention patterns during text generation.
For sentiment classification tasks, BERT for Sentiment Analysis examined attentional patterns with an emphasis on sentiment-laden tokens.
Datasets: IMDB dataset for BERT sentiment analysis.
Result: The results demonstrate task-adapted attention that concentrates on sentiment indicators for analysis and semantic context for production.

