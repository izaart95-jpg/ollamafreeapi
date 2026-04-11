# 🦙 OllamaFreeAPI · Free Open LLM Access

📦 PyPI v2.4.1 · 🐍 Python 3.8+ · ✅ MIT License · ♾️ Free Forever

---

## Unlock AI Innovation for Free

**Access the world's best open language models in one place!** OllamaFreeAPI provides free access to leading open-source LLMs — no payments, no credit cards. Just pure AI power at your fingertips.

---

## ✨ Models You Get

| Family | Models | Key Capability |
|--------|--------|----------------|
| 🦙 LLaMA (Meta) | `llama3.2:3b`, `llama3:latest` | Efficient, high-performance chat |
| 🌪️ Mistral AI | `mistral:latest`, `mistral-nemo:custom` | Strong reasoning, open weights |
| 🔍 DeepSeek | `deepseek-r1:latest` | Advanced reasoning on Qwen-base |
| 🦄 Qwen (Alibaba) | `qwen:7b`, `qwen:14b` | Multilingual & instruction tuned |
| ⚡ Gemma-based | `gpt-oss:20b`, `gemma2:latest` | High-quality completion & chat |

---

## 🆕 What's New

✨ **OpenAI-compatible proxy server** — now you can use OllamaFreeAPI with any OpenAI-compatible client (LangChain, LiteLLM, custom apps). Zero friction.

---

## 🚀 Install / Upgrade (latest version)

```bash
pip install ollamafreeapi --upgrade
```

---
## ⚡ Quick Start – Code Examples
### 📡 Streaming Example (real-time)
```python
from ollamafreeapi import OllamaFreeAPI

client = OllamaFreeAPI()

# Stream responses in real-time
for chunk in client.stream_chat('What is quantum computing?', model='llama3.2:3b'):
    print(chunk, end='', flush=True)
```
### ⚙️ Non-Streaming Example (instant)
```python
from ollamafreeapi import OllamaFreeAPI

client = OllamaFreeAPI()
response = client.chat(
    model="gpt-oss:20b",
    prompt="Explain neural networks like I'm five",
    temperature=0.7
)
print(response)
```

---
## 📊 Project Statistics & Infrastructure

| Metric                | Value                                                      |
| --------------------- | ---------------------------------------------------------- |
| ✅ Active Models       | **16** (ready-to-use & tested)                             |
| 🧩 Model Families     | Gemma, LLaMA, Qwen + more                                  |
| 🌍 Reliable Endpoints | 6+ high-availability server nodes                          |
| ⚡ Load balancing      | Automatic server selection & real-time availability checks |

## 🏆 Why Choose OllamaFreeAPI?

| Feature           | Others           | OllamaFreeAPI                       |
| ----------------- | ---------------- | ----------------------------------- |
| Free Access       | ❌ Limited trials | ✅ Always free                       |
| Model Variety     | 3-5 models       | Verified endpoints only, 16+ active |
| Reliability       | Highly variable  | Validated active models             |
| Ease of Use       | Complex setup    | Zero-config, one-liner install      |
| Community Support | Paid only        | Free & active                       |

## 📚 API Reference – Core Methods
```python
# List available models
api.list_models()  

# Get model details
api.get_model_info("mistral:latest")  

# Generate text (chat completion)
api.chat(model="llama3.2:3b", prompt="Your message")

# Stream responses
for chunk in api.stream_chat(prompt="Hello!", model="llama3:latest"):
    print(chunk, end='')

```
### ⚙️ Advanced Features
```python
# List available models
api.list_models()  

# Get model details
api.get_model_info("mistral:latest")  

# Generate text (chat completion)
api.chat(model="llama3.2:3b", prompt="Your message")

# Stream responses
for chunk in api.stream_chat(prompt="Hello!", model="llama3:latest"):
    print(chunk, end='')
```
## 🌟 Featured Models & Capabilities
- `llama3.2:3b` – efficient 3.2B
- `deepseek-r1:latest` – reasoning
- `gpt-oss:20b` – Gemma-based 20B
- `mistral:latest` – high-performance baseline
- `mistral-nemo:custom` – 12.2B open weights
- `bakllava:latest` – vision + language
- `smollm2:135m` – lightweight assistant
## 🌐 Global Nodes 
Distributed community infrastructure → fast response times, automatic load balancing, real-time availability checks.
### 📄 License
Open-source MIT license

---

**🐙 OllamaFreeAPI** – democratizing open LLMs, forever free.

**⚡ OllamaFreeAPI** · Free API for LLaMA, Mistral, DeepSeek, Qwen · Zero payments, pure innovation.
