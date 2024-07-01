# Code-generating LLMs

My course work consists of researching modern LLMs for automatic code generation for their training data, quality of understanding the Russian language, benchmark scores, response to prompt changes, etc. During the work, I first studied the construction of embeddings, transformer architecture, and the design of popular models (BERT family, Llama etc.), tokenizers, generation methods and methods for evaluating generative models. Then I made an approximate rating of these models based on the quality of benchmarks and read original articles about them. Afterwards I learned how to infer models in Google Colab. Next, deepseek-6.7B-instruct was chosen for a deeper study, on which I experimented: I tried to recreate the results on the MBPP and HumanEval benchmarks from the original article, tried zero-shot and few-shot, changed the system prompt, tested on the Russian version of HumanEval and experimented with quantization. 
