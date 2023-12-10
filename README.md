# <center> Generative NLP Model </center>

## Dataset Information:

Dataset Used: [Daily Dialog Dataset](https://huggingface.co/datasets/daily_dialog)  

Features:   
`dialog` : Dialog between 2 people, text used for fine tuning  
`act` : contains the index of speaker, not used to train model  
`emotion` : emotion of the speaker, not used to train model  


## Model Used:

`distilgpt2`: DistilGPT2 (short for Distilled-GPT2) is an English-language model pre-trained with the supervision of the smallest version of Generative Pre-trained Transformer 2 (GPT-2). Like GPT-2, DistilGPT2 can be used to generate text. Users of this model card should also consider information about the design, training, and limitations of GPT-2.  
Get more info [here](https://huggingface.co/distilgpt2)  

The Model was fined tuned to the above dataset


## Evaluation Metric:

`perplexity` : Perplexity in NLP is a measure of how well a language model predicts a given sequence of words. It quantifies the model's uncertainty, with lower perplexity indicating better performance. It's computed based on the probability distribution assigned by the model to a sequence, reflecting the model's predictive accuracy.  

## Contributed by

Aryan Ramani

- [LinkedIn](https://www.linkedin.com/in/aryan-ramani-a516b5212/)

