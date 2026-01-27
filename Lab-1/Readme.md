## Unit 1 Assignment: The Model Benchmark Challenge
Objective: In this assignment, you will step beyond simply using a model and instead evaluate the architectural differences between BERT, RoBERTa, and BART. You will force these models to perform tasks they might not be designed for, to observe why architecture matters.
### The Models to Test
- BERT (bert-base-uncased): An Encoder-only model (designed for understanding, not generation).
- RoBERTa (roberta-base): An optimized Encoder-only model.
- BART (facebook/bart-base): An Encoder-Decoder model (designed for seq2seq tasks like translation/generation).

### Experiment 1: Text Generation
Task: Try to generate text using the prompt: "The future of Artificial Intelligence is"

Hypothesis: Which models will fail? Why? (Hint: Can an Encoder generate new tokens easily?)
### Experiment 2: Masked Language Modeling (Missing Word)
Task: Predict the missing word in: "The goal of Generative AI is to [MASK] new content."

Hypothesis: This is how BERT/RoBERTa were trained. They should perform well.
### Experiment 3: Question Answering
Task: Answer the question "What are the risks?" based on the context: "Generative AI poses significant risks such as hallucinations, bias, and deepfakes."
