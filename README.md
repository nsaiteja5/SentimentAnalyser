#SentimentAnalyser
This is my first time working with a Transformer model.
I experimented with the Transformer architecture described in the paper "Attention is All You Need" by Ashish Vaswani et al.

#Dataset
I used the dair-ai/emotion dataset from Hugging Face, which contains:

~16,000 training samples

~2,000 validation samples

~2,000 test samples

#Architecture
As this is a classification task, I only used the encoder part of the Transformer architecture.
I implemented a single Transformer block based on the original paper. You can find the full architecture in the code.

#Dataset Setup
After loading the dataset from Hugging Face, I encountered a bug when feeding it into the model (even after converting it to a NumPy array).
To resolve this, I used the TensorFlow data pipeline, and it worked smoothly.
The tokenizer used is also from TensorFlow.

Training
You can find all the training details in the code! 🔧
