# sentimentanalyser

this is the first time im working with a transformer model. 
i tried to use the transformer approach written in paper "Attention is all you need" by ashish vaswani. 

i used dataset dair-ai/emotion from hugging face. which has about
16k training samples
2k validation samples
2k test samples

# architecture
as i said ive used the transformer block from that paper. as this is just classification problem, ig only encoder part works best. 
i used only one transformer block for this. you can check out architecture in the code. 

# dataset up
after getting dataset from huggingface, i got a bug when i fed that to model (even it was converted to numpy array) , so i had to use tensorflow data pipeline and it worked. also i used tokenizer from tensorflow. 

# training
you can check this in the code !
