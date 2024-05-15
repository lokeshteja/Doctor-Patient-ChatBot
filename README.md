# Healthcare Chatbot Development

## Overview
This project involves developing a healthcare chatbot using an open-source large language model (LLM). The chatbot is fine-tuned on a healthcare dataset and responds to user queries. The project includes data preprocessing, model fine-tuning, chatbot interface development, and performance evaluation.

## Project Structure
- `preprocessing.py`: Script for data preprocessing.
- `fine_tuning.py`: Script for fine-tuning the LLM.
- `evaluation.py`: Script for evaluating the model's performance.
- `interface.py`: Script for the chatbot interface.
- `requirements.txt`: List of dependencies.
- `output_dir`: Directory to save model checkpoints and evaluation results.

## Prerequisites
Ensure you have the following installed:
- Python 3.7 or higher
- PyTorch
- Transformers library from Hugging Face
- Datasets library from Hugging Face
- Gradio for the chatbot interface
- Additional libraries as listed in `requirements.txt`

## Setup and Installation

### Clone the Repository
```bash
git clone https://github.com/lokeshteja/Healthcare-Chatbot-Development
cd Healthcare-Chatbot-Development
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

## Summary of Approach and Challenges
### Approach
The project involved loading a healthcare dataset, preprocessing it, fine-tuning a LLM, evaluating its performance, and creating an interface for user interaction.


## Example Queries for the Chatbot
Here are some example queries you can try with the chatbot:
- "Hi Doctor, my sugar level is 220 what to do?"
- "I am feeling sick after travel and my body is hot what might be reason?"
- "How should I control my thyroid levels?"
