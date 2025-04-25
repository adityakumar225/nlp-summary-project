# Abstractive Summarization with NLP Models

This project develops an abstractive summarization pipeline using pre-trained models like LLaMA and T5. The goal is to generate summaries of text, evaluate their quality using traditional NLP metrics (ROUGE, STS), and provide a custom evaluation using the OpenAI GPT model.

## Project Workflow

The project follows a three-step workflow:

1. **Summarization**  
   The first notebook (`Summarize.ipynb`) generates abstractive summaries using pre-trained models like LLaMA and T5.

2. **Evaluation**  
   The second notebook (`Evaluation.ipynb`) evaluates the generated summaries using traditional metrics like ROUGE and STS, as well as a custom judging criteria prompt evaluation based on OpenAI GPT model.

3. **Visualization**  
   The third notebook (`Visualization.ipynb`) visualizes the comparison between generated summaries, reference summaries, and the evaluation metrics.

## Tools and Technologies

- Python (Hugging Face Transformers, OpenAI API)
- Pre-trained models: LLaMA, T5
- NLP Evaluation: ROUGE, STS
- Custom Evaluation: OpenAI GPT model, prompt engineering
