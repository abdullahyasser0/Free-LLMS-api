# Free-LLMs-API

This notebook provides a curated list of **free APIs for Large Language Models (LLMs)** that you can integrate into your code or projects at no cost.

## Included APIs (with links to the notebook):

- 🔷 [Google Gemini API](https://github.com/abdullahyasser0/Free-LLMS-api/blob/main/Gemeni_API_.ipynb)
- 🔷 [Groq API](https://github.com/abdullahyasser0/Free-LLMS-api/blob/main/groq_api.ipynb)
- 🔷 [OpenRouter API](https://github.com/abdullahyasser0/Free-LLMS-api/blob/main/OpenRouter_API.ipynb)
- 🔷 [Hugging Face Inference API](https://github.com/abdullahyasser0/Free-LLMS-api/blob/main/Hugging_Face_Inference_API_.ipynb)
- 🔷 [Mistral AI API](https://github.com/abdullahyasser0/Free-LLMS-api/blob/main/Mistral_AI_API_.ipynb)

Each API is documented in the notebook with usage examples, authentication setup, and tips.

> 💡 Ideal for developers, students, and researchers looking for free access to powerful LLMs.

---

## Sample: Google Gemini API

> 📍 Refer to the notebook [here](https://github.com/abdullahyasser0/Free-LLMS-api/blob/main/Gemeni_API_.ipynb) and scroll to the **Google Gemini API** section.

- **Models:**  
  Includes **Gemini 2.0 Flash**, **Gemini 2.5 Flash**, and **Gemini-2.0-Flash-Preview-Image-Generation**. Known for **multimodal capabilities** (text, image generation, image editing), long context windows (up to 1M tokens), and advanced reasoning.

- **Free Tier Limits:**  
  Free API access with rate limits (varies by model and region). Requires an API key from Google AI Studio.

- **How to Access:**  
  - Sign up via [Google AI Studio](https://aistudio.google.com/prompts/new_chat) to generate a free API key  
  - Store the API key securely (e.g., in Colab secrets)  
  - Use the `google.genai` library or REST API for integration  

- **Best For:**  
  - Multimodal tasks (text generation, image generation, image editing)  
  - Multi-turn conversations and chatbots  
  - Long document analysis and content generation  

- **Notes:**  
  - Rate limits apply; heavy usage may require a paid plan  
  - Image generation and editing are in preview and may have additional restrictions  
  - Supports streaming responses for real-time applications  


---

## Sample: Groq API

> 📍 Refer to the notebook [here](https://github.com/abdullahyasser0/Free-LLMS-api/blob/main/groq_api.ipynb) and scroll to the **Groq API** section.

- **Models:**  
  Hosts models like **Llama-3.3-70B-Versatile**, **Llama-4-Scout-17B-16E-Instruct**, **DeepSeek-R1-Distill-Llama-70B**, and **PlayAI-TTS** (text-to-speech). Known for **high inference speed** due to custom hardware (**Language Processing Unit**) and multimodal capabilities (text, vision, audio).

- **Free Tier Limits:**  
  200–14,400 requests/day depending on the model. Some features (e.g., PlayAI-TTS) require accepting model terms.

- **How to Access:**  
  - Sign up at [Groq’s website](https://console.groq.com/keys) to generate a free API key  
  - Store the API key securely (e.g., in Colab secrets)  
  - Use the `groq` Python library or REST API for integration  

- **Best For:**  
  - High-speed text generation and reasoning tasks  
  - Multimodal applications (text-to-speech, speech-to-text, image description)  
  - Real-time chatbots and agentic tooling (e.g., web search, code execution)  

- **Notes:**  
  - Free tier has daily request limits; heavy usage may require a paid plan  
  - Speech-to-text supports English only; text-to-speech supports English and Arabic  
  - Agentic tooling (e.g., web search via Tavily) requires specific models like **compound-beta**  

---

## Sample: OpenRouter API

> 📍 Refer to the notebook [here](https://github.com/abdullahyasser0/Free-LLMS-api/blob/main/OpenRouter_API.ipynb) and scroll to the **OpenRouter API** section.

- **Models:**  
  Aggregates open-source models like **Llama-4-Maverick:Free**, **DeepSeek-Chat-V3-0324:Free**, and others. Acts as a **unified interface** for accessing multiple LLMs with vision and text capabilities.

- **Free Tier Limits:**  
  Free access to select models with token-based limits (varies by model). $1–$5 credits often provided upon signup for testing.

- **How to Access:**  
  - Register at [OpenRouter](https://openrouter.ai/settings/keys) to generate a free API key  
  - Store the API key securely (e.g., in Colab secrets)  
  - Use the `openai` Python library with OpenRouter’s base URL for integration  

- **Best For:**  
  - Experimenting with multiple open-source LLMs via a single interface  
  - Vision-based tasks (e.g., image description) and text generation  
  - Developers needing flexible model switching without multiple accounts  

- **Notes:**  
  - Free tier is **token-limited**; optimize prompts to stay within limits  
  - Some models may have **regional restrictions** or require extra headers for ranking  
  - Explore additional models at [OpenRouter Models](https://openrouter.ai/models)  

---


## Sample: Hugging Face Inference API

> 📍 Refer to the notebook [here](https://github.com/abdullahyasser0/Free-LLMS-api/blob/main/Hugging_Face_Inference_API_.ipynb) and scroll to the **Hugging Face Inference API** section.

- **Models:**  
  Supports a wide range of models like **Sarvam-m**, **Llama-4-Scout-17B-16E-Instruct**, and **FLUX.1-dev**. Known for **multimodal capabilities** including text, vision-language models (VLM), and text-to-image generation.

- **Free Tier Limits:**  
  Free API access with rate limits (varies by model and provider). Requires an API key from Hugging Face.

- **How to Access:**  
  - Sign up at [Hugging Face](https://huggingface.co/settings/tokens) to generate a free API key  
  - Store the API key securely (e.g., in Colab secrets)  
  - Use the `huggingface_hub` library or REST API for integration  

- **Best For:**  
  - Multimodal tasks (text, image generation, feature extraction)  
  - Chatbots, content generation, and vision-language applications  
  - Experimenting with diverse open-source models  

- **Notes:**  
  - Free tier has **rate limits**; heavy usage may require a paid plan  
  - Supports multiple providers like **HF Inference**, **Fireworks AI**, and **Together AI**  
  - Some models may require specific provider configurations  

---

## Sample: Mistral AI API

> 📍 Refer to the notebook [here](https://github.com/abdullahyasser0/Free-LLMS-api/blob/main/Mistral_AI_API_.ipynb) and scroll to the **Mistral AI API** section.

- **Models:**  
  Offers **Mixtral 8x7B**, **Mistral 7B**, and **Codestral**.  
  Open-weight models available for both research and commercial use.

- **Free Tier Limits:**  
  Free API access to smaller models like **Mistral 7B** with rate limits (e.g., **15 requests/minute**).  
  Available via providers like **OpenRouter** or **Cloudflare Workers AI**.

- **How to Access:**  
  - Visit [Mistral AI](https://mistral.ai) or partners like [OpenRouter](https://openrouter.ai/)  
  - Sign up and retrieve API keys  
  - Use simple RESTful API endpoints

- **Best For:**  
  - General text generation  
  - Coding tasks using **Codestral**

- **Notes:**  
  - Free access is limited  
  - Larger models may require a paid plan  
  - Performance varies by host/provider
