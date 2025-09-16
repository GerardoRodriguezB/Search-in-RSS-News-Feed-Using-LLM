# Search-in-RSS-News-Feed-Using-LLM

In this repository we use `intfloat/e5-base-v2` model to perform real-time semantic search over the BBC News RSS feed. The model, developed by Microsoft and released under the MIT license, is specialized for generating text embeddings that capture semantic meaning. This allows the system to identify and retrieve news articles that are semantically relevant to a user's input query, rather than relying solely on keyword matching.


## Environment Setup

Create an Anaconda environment using `python=3.10`. Navigate to the root folder of the project and install requeriments

```bash
pip install -r requeriments.txt
```

## Install PyTORCH

If your machine has a CUDA compatible GPU, install:

```bash
pip install torch==2.8.0 torchvision==0.23.0 torchaudio==2.8.0 --index-url https://download.pytorch.org/whl/cu126
```
Otherwise, install the versions for CPU

```bash
pip install torch==2.8.0 torchvision==0.23.0 torchaudio==2.8.0
```















