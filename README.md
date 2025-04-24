This is a developer-first world foundation model platform designed to help Physical AI developers build their Physical AI systems better and faster. The platform contains
pre-trained models, available via Hugging Face under a permissive open model license that allows commercial use of the models for free
training scripts under the Apache 2 License, offered through an open-source AI framework for post-training the models for various downstream Physical AI applications
Details of the platform are described in the foundation model platform paper. Preview access is available at build.example.com.
Key Features
Pre-trained Diffusion-based world foundation models for Text2World and Video2World generation where a user can generate visual simulation based on text prompts and video prompts.
Pre-trained Autoregressive-based world foundation models for Video2World generation where a user can generate visual simulation based on video prompts and optional text prompts.
Video tokenizers for tokenizing videos into continuous tokens (latent vectors) and discrete tokens (integers) efficiently and effectively.
Video curation pipeline for building your own video dataset. [Coming soon]
Post-training scripts via the open-source AI Framework to post-train the pre-trained world foundation models for various Physical AI setups.
Pre-training scripts via the open-source AI Framework for building your own world foundation model. [Diffusion] [Autoregressive] [Tokenizer].
Model Family
Model name	Description	Try it out
Model-Diffusion-7B-Text2World	Text to visual world generation	Inference
Model-Diffusion-14B-Text2World	Text to visual world generation	Inference
Model-Diffusion-7B-Video2World	Video + Text based future visual world generation	Inference
Model-Diffusion-14B-Video2World	Video + Text based future visual world generation	Inference
Model-Autoregressive-4B	Future visual world generation	Inference
Model-Autoregressive-12B	Future visual world generation	Inference
Model-Autoregressive-5B-Video2World	Video + Text based future visual world generation	Inference
Model-Autoregressive-13B-Video2World	Video + Text based future visual world generation	Inference
Model-Guardrail-1.0	Guardrail contains pre-Guard and post-Guard for safe use	Embedded in model inference scripts
Example Usage
Inference
Follow the Installation Guide to setup the environment. For inference with the pretrained models, please refer to Diffusion Inference and Autoregressive Inference.
The code snippet below provides a gist of the inference usage.
