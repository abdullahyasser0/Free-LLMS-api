# Free-LLMs-API

This notebook provides a curated list of **free APIs for Large Language Models (LLMs)** that you can integrate into your code or projects at no cost.

## Included APIs (with links to the notebook):

- 🔷 [Google Gemini API](https://github.com/abdullahyasser0/Free-LLMS-api/blob/main/Gemeni_API_.ipynb)
- 🔷 [DeepSeek API]
- 🔷 [Groq API](https://github.com/abdullahyasser0/Free-LLMS-api/blob/main/groq_api.ipynb)
- 🔷 [OpenRouter API](https://github.com/abdullahyasser0/Free-LLMS-api/blob/main/OpenRouter_API.ipynb)
- 🔷 [Cloudflare Workers AI]
- 🔷 [Together AI API]
- 🔷 [Hugging Face Inference API]
- 🔷 [Mistral AI API]
- 🔷 [Ollama API]

Each API is documented in the notebook with usage examples, authentication setup, and tips.

> 💡 Ideal for developers, students, and researchers looking for free access to powerful LLMs.

---

## Sample: Google Gemini API

> 📍 Refer to the notebook [here](https://github.com/abdullahyasser0/Free-LLMS-api/blob/main/Gemeni_API_.ipynb) and scroll to the **Google Gemini API** section.

- **Models:**  
  Includes **Gemini 2.0 Flash** and **Gemini 2.5 Flash** models. Known for **multimodal capabilities** and **long context windows** (up to 1M tokens).

- **How to Access:**  
  - Sign up via [Google AI Studio](https://makersuite.google.com/app)  
  - Documentation: [Google AI for Developers](https://ai.google.dev)

- **Best For:**  
  - Multimodal reasoning  
  - Long documents and conversations  
  - Chatbots, content generation, code assistance

- **Notes:**  
  - Fast, cost-effective, widely available  
  - May hit rate limits on very frequent requests

---

## Sample: Groq API

> 📍 Refer to the notebook and scroll to the **Groq API** section.

- **Models:**  
  Hosts open-source models like **Llama 3.1 (8B, 70B)**, **Gemma 2**, and **Mixtral**. Known for **high inference speed** due to custom hardware (**Language Processing Unit**).

- **Free Tier Limits:**  
  200–14,400 requests/day depending on the model.  
  **Llama 3.1 70B** available with free tier on providers like **OpenRouter** or **Together AI**.

- **How to Access:**  
  - Sign up at [Groq’s website](https://console.groq.com/)  
  - Or use third-party providers like [OpenRouter](https://openrouter.ai/)  
  - Simple API integration via REST or libraries like `requests`

- **Best For:**  
  - High-speed inference  
  - Chatbots  
  - Lightweight applications needing fast responses
 

## Sample: OpenRouter API

> 📍 Refer to the notebook and scroll to the **OpenRouter API** section.

- **Models:**  
  Aggregates multiple open-source LLMs, including **DeepSeek R1**, **Llama 3.2**, **Qwen 2.5**, **Mistral**, and more. Acts as a **unified interface** for various providers.

- **Free Tier Limits:**  
  Free access to models like **DeepSeek-V3**, **Llama 3.1**, and **Qwen** with token-based limits (varies by model).  
  $1–$5 credits often provided upon signup for testing.

- **How to Access:**  
  - Register at [OpenRouter](https://openrouter.ai/)  
  - Configure API keys  
  - Easily switch between models using a **single base URL**

- **Best For:**  
  - Experimenting with multiple LLMs  
  - Centralized access without managing separate accounts

- **Notes:**  
  - Free tier is **token-limited**  
  - Optimize prompts to stay within limits  
  - Some models may have **regional restrictions**

- **Notes:**  
  - Free tier is limited by daily requests  
  - Heavy usage may require paid credits  
  - Ideal for developers needing **ultra-fast** responses
