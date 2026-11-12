# nn-zero-to-hero-notes

My study notes for the first phase of Andrej Karpathy's [Neural Networks: Zero to Hero](https://github.com/karpathy/nn-zero-to-hero): from a scalar autograd engine to a small GPT and its tokenizer. I worked through each lecture and its code and wrote a self-contained review page for it, with the key ideas, annotated code, my own checks, and quiz questions that hide the answer until clicked.

The notes are in **Portuguese** (my study language for this course). Each one is a single HTML file: download it and open it in a browser.

| # | Note | What it covers |
|---|---|---|
| 01 | [micrograd por dentro](notes/01-micrograd-por-dentro.html) | Scalar autograd: the `Value` class, the chain rule, topological sort, a tiny neural net |
| 02 | [Bigramas, contados e aprendidos](notes/02-bigramas-contados-e-aprendidos.html) | Character bigram model by counting, then the same model learned by gradient descent; negative log-likelihood |
| 03 | [Um MLP que lembra três letras](notes/03-mlp-de-tres-letras.html) | Embeddings and an MLP language model (Bengio et al. 2003); train/dev/test splits, learning-rate search |
| 04 | [Redes que treinam bem](notes/04-redes-que-treinam-bem.html) | Initialization (Kaiming), tanh saturation, BatchNorm, activation and gradient histograms |
| 05 | [Backprop à mão, tensor por tensor](notes/05-backprop-a-mao-em-tensores.html) | Manual backward pass through cross-entropy, BatchNorm and linear layers, checked against PyTorch autograd |
| 06 | [WaveNet em miniatura](notes/06-wavenet-em-miniatura.html) | Hierarchical (dilated) architecture, building PyTorch-like modules |
| 07 | [GPT do zero](notes/07-gpt-do-zero.html) | Self-attention, query/key/value, the Transformer block; a ~210k-parameter character-level GPT |
| 08 | [Tokens, bytes e BPE](notes/08-tokens-bytes-e-bpe.html) | Unicode and UTF-8, byte-pair encoding from scratch; GPT (tiktoken) vs Llama (sentencepiece) tokenizers |

## Credits

Course, notebooks and datasets by Andrej Karpathy ([nn-zero-to-hero](https://github.com/karpathy/nn-zero-to-hero), MIT license). Code excerpts in the notes are shortened and commented versions of the course notebooks; each note lists its sources at the end. The explanations, simulations and quiz questions are mine.
