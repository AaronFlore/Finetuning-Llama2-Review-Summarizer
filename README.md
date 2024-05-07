# Fine Tuning Llama 2 to Generate Better Summaries of Amazon Product Reviews

## Project Description

This project focuses on fine tuning llama 2 to summarize user reviews for amazon products into a single sentence. The project first gives an example of generating training data for llama 2 chat. This training data can be refined by the user or another AI model until the desired responses are good enough to fine tune the model. Next, this project fine-tunes a llama 2 chat model to perform better for our use-case of summarizing amazon product reviews. Then, we can utlize our new fine-tuned model to generate review summaries.

### Why create an unbiased review summarizer for Amazon products?
In today's digital marketplace, where countless products compete for consumer attention, making informed purchasing decisions can be daunting. Consumers often turn to user reviews for insights into product performance and quality. However, the large volume of reviews can overwhelm even the typical shopper. This project aims to address this challenge by providing an unbiased Amazon review summarizer.

Unlike Amazon's AI-generated review feature, which may have inherent biases, our project seeks transparency and impartiality. By condensing numerous user reviews into a single, concise, and informative summary, consumers can make informed decisions. Our approach utilizes fine-tuning Meta's Llama-2, a free and open-source solution, to generate unbiased summaries directly from raw data.

## Installation

- The project was created and run on [Google Colab](https://colab.research.google.com/). However, upgrading Google Colab's GPU may be necessary for running the fine-tuned model.

- To run on your local machine, clone this repository
```bash
git clone https://github.com/LMU-CMSI-Korpusik/project-tsa.git
```
- Navigate to the project directory
```bash
cd project-tsa
```
- If not already installed, install Jupyter Notebook
```bash
pip install notebook
```

- Launch Jupyter Notebook
```bash
jupyter notebook
```

- Download and add ["Reviews.csv"](https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews) to the project folder.
  
- Open the provided Jupyter Notebook file and execute the cells to run the project.

## Results
- The fine-tuned model can be found here on Hugging Face: [https://huggingface.co/aaronfloreani/Llama-2-7b-chat-online-reviews](https://huggingface.co/aaronfloreani/Llama-2-7b-chat-online-reviews)
- The formatted training data can be found here on Hugging Face: [https://huggingface.co/datasets/aaronfloreani/online-reviews-llama2-100](https://huggingface.co/datasets/aaronfloreani/online-reviews-llama2-100)
