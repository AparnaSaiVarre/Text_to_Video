<p align="center">
<img src="assets/cosmos-logo.png" alt="Platform Logo" width="200">
</p>
<br>
This is a developer-first world foundation model platform designed to help Physical AI developers build their Physical AI systems better and faster. The platform contains:
1. Pre-trained models, available via Hugging Face under a permissive open model license that allows commercial use of the models for free.
2. Training scripts under the Apache 2 License, offered through an open-source AI framework (Framework GitHub) for post-training the models for various downstream Physical AI applications.
Details of the platform are described in the foundation model platform paper. Preview access is available at build.example.com.
Key Features
• Pre-trained Diffusion-based world foundation models (path/to/diffusion/README.md) for Text2World and Video2World generation where a user can generate visual simulation based on text prompts and video prompts.
• Pre-trained Autoregressive-based world foundation models (path/to/autoregressive/README.md) for Video2World generation where a user can generate visual simulation based on video prompts and optional text prompts.
• Video tokenizers (path/to/tokenizer) for tokenizing videos into continuous tokens (latent vectors) and discrete tokens (integers) efficiently and effectively.
• Video curation pipeline for building your own video dataset. Coming soon.
Post-training scripts (path/to/POST_TRAINING.md) via the open-source AI Framework to post-train the pre-trained world foundation models for various Physical AI setups.
• Pre-training scripts via the open-source AI Framework for building your own world foundation model:
[Diffusion]
[Autoregressive]
[Tokenizer]
