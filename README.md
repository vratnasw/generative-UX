# Ideas for using Generative AI along with causal inference for website design

* Use free generative models - natural language processing (NLP) or image-based - to create images and text for a website

* Automate the task of image and text generation by using [generative AI agents]( https://python.langchain.com/docs/use_cases/agent_simulations/characters ) via [langchain]( https://langchain.com/ )

* Look at [causal inference]( https://en.wikipedia.org/wiki/Causal_inference ) for the behavior of clients to different websites

* Integrate sentiment and emotional analysis into the causal inference

## Free generative LLM models

 * OpenLLaMA ~ https://github.com/openlm-research/open_llama
 * Stanford Alpaca ~ https://github.com/tatsu-lab/stanford_alpaca
 * Baize V2 ~ https://github.com/project-baize/baize-chatbot
 * CalderaAI ~ https://huggingface.co/CalderaAI
 * Lit-LLaMA ️~ https://github.com/Lightning-AI/lit-llama

## Free stable diffusion models

 * Dreamlike Photoreal 2.0 ~ https://huggingface.co/dreamlike-art
 * Stable-Diffusion-v1-5 ~ https://huggingface.co/spaces/runwayml/stable-diffusion-v1-5

One will need to find the suitable stable diffusion model that suits the needs of the client and the designer. What this amounts to is taking a stable diffusion model then fine tuning it with images from the designer. There is a substantial amount of models on HuggingFace that are free, many of which are fine-tuned already.  In a similar vein, we would use a freely available LLM and fine-tune it or use a finetuned model for text on a website.

 ## Using an LLM to generate the code for the website
 
 We can use a freely available LLM for code generation for the website. Two possibilites are:
  * BigCode ~ https://www.bigcode-project.org/
  * StarCoder ~ https://huggingface.co/bigcode/starcoder

## Causal ML

The issue is that designer wants to acquire a client by showing them initial designs of the website. 
