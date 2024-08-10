# Python-Code-Generation-Using-Transformers

Tensors  are generalizations of a matrix that can be indexed in more than 2 dimensions. Tensors can be created from Python lists with the torch.tensor() function.


Transformer Architecture is a model that uses self-attention that transforms one whole sentence into a single sentence. This is a big shift from how older models work step by step, and it helps overcome the challenges seen in models like RNNs and LSTMs.


**Implemented Transformer-Based Text Generation:** Configured and deployed a text generation pipeline using the transformers library with PyTorch, leveraging AutoTokenizer and AutoModelForCausalLM to integrate the GuillenLuis03/PyCodeGPT model for advanced natural language generation.

**Ensured Model Reproducibility and Consistency:** Utilized PyTorch’s seed setting functionality to maintain reproducibility of results across multiple runs by managing random seeds for both CPU and CUDA environments, ensuring consistent performance and outputs.

**Engineered Custom Text Generation Pipeline:** Developed a specialized text generation function utilizing the TextGenerationPipeline for dynamic and efficient text generation. Fine-tuned parameters such as max_length and num_return_sequences to optimize generation quality and adapt outputs to specific requirements.
