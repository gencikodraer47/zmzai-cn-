[zmzai-cn-README.md](https://github.com/user-attachments/files/28084391/zmzai-cn-README.md)
<div align="center">

# ⚡ ZMZ AI — 500+ Models. Lowest Prices. Enterprise-Ready.

**The Most Affordable AI Model Relay Hub. Backed by a Real Company. Built for Production.**

[![Website](https://img.shields.io/badge/Website-ZMZAI.CN-1E90FF?logo=googlechrome&logoColor=white)](https://zmzai.cn)
[![Models](https://img.shields.io/badge/Models-500+-00C853?logo=openai&logoColor=white)](https://zmzai.cn)
[![Pricing](https://img.shields.io/badge/Pricing-70--90%25_Savings-FF6600?logo=databricks&logoColor=white)](https://zmzai.cn)
[![Enterprise](https://img.shields.io/badge/Enterprise-Ready-7B00D4?logo=amazonaws&logoColor=white)](https://zmzai.cn)

</div>

---

## 🏢 Why ZMZ AI?

| | **Other AI Proxies** | **ZMZ AI** |
|---|---------------------|------------|
| **Models** | 50–100 models | **500+ models** from 50+ providers |
| **Pricing** | 20–40% off official | **70–90% cheaper** than direct API |
| **Company** | Anonymous individuals | **Registered company** with real operations |
| **Concurrency** | 10–50 concurrent, easy to throttle | **1,000+ concurrent** with auto scaling |
| **Stability** | Frequent downtime, no SLA | **99.9% uptime SLA** with failover |
| **Support** | Discord/Telegram only | **Dedicated enterprise support** + ticketing system |

---

## ⚡ 500+ Models. One API Key.

Stop managing 50 different API accounts. Access everything through ZMZ AI:

```
┌─────────────────────────────────────────────────────────────┐
│                    ONE API KEY → 500+ MODELS                │
├──────────────┬──────────────┬──────────────┬───────────────┤
│   OpenAI     │   Anthropic  │   Google     │     Meta      │
│  GPT-4o      │ Claude 3.5   │ Gemini Pro   │  Llama 3.1    │
│  GPT-4 Turbo │ Claude 3     │ PaLM 2       │  Llama 3 70B  │
│  DALL-E 3    │              │ Imagen       │               │
├──────────────┼──────────────┼──────────────┼───────────────┤
│   Mistral    │  DeepSeek    │  Cohere      │  Stability AI │
│  Mistral L.  │ DeepSeek V3  │ Command R+   │ SD XL         │
│  Mixtral     │ DeepSeek Coder│ Embed v3     │ SD 3          │
├──────────────┴──────────────┴──────────────┴───────────────┤
│       ... and 40+ more providers. Full list at zmzai.cn     │
└─────────────────────────────────────────────────────────────┘
```

### 📊 Model Coverage

| Category | Models | Highlights |
|----------|--------|------------|
| **👑 LLM / Chat** | 200+ | GPT-4o, Claude 3.5, Gemini Pro, DeepSeek V3, Llama 3.1, Qwen, GLM |
| **🎨 Image Gen** | 80+ | DALL-E 3, Midjourney API, Stable Diffusion, Flux, Imagen |
| **🎬 Video Gen** | 30+ | Runway, Pika, Sora, Kling, CogVideo |
| **🎙️ Audio / TTS** | 60+ | Whisper, ElevenLabs, Bark, CosyVoice |
| **🔢 Embeddings** | 60+ | text-embedding-3, BGE, Cohere Embed |
| **💻 Code / Reasoning** | 50+ | DeepSeek Coder, CodeLlama, CodeGeeX |
| **👁️ Vision / Multimodal** | 40+ | GPT-4V, Gemini Pro Vision, Claude 3 Vision |

---

## 💰 Pricing That Actually Makes Sense

We're **not a VC-burning startup** — we're a real company with sustainable unit economics. Volume discounts + smart routing = prices competitors can't match.

| Model | Official Price (1M tokens) | ZMZ AI | You Save |
|-------|---------------------------|--------|----------|
| **GPT-4o** | $10.00 | **$2.50** | 75% |
| **GPT-4o Mini** | $0.60 | **$0.15** | 75% |
| **Claude 3.5 Sonnet** | $3.00 | **$0.90** | 70% |
| **Claude 3 Opus** | $15.00 | **$4.50** | 70% |
| **Gemini 1.5 Pro** | $1.25 | **$0.35** | 72% |
| **DeepSeek V3** | $1.50 | **$0.30** | 80% |
| **Llama 3.1 70B** | $1.00 | **$0.25** | 75% |
| **Mistral Large** | $4.00 | **$1.20** | 70% |
| **DALL-E 3 (HD)** | $0.080/img | **$0.020/img** | 75% |
| **Midjourney API** | $0.050/img | **$0.010/img** | 80% |

> 🔥 **Volume discounts:** Save an additional 10–30% on monthly plans above $500/mo. [Contact us](https://zmzai.cn) for enterprise pricing.

---

## 🚀 Built for High Concurrency

We run our **own infrastructure** on bare metal, not shared cloud VMs. No throttling. No "rate limit" games.

| Spec | Detail |
|------|--------|
| **Max Concurrent Requests** | 1,000+ per account |
| **Default QPM** | 60,000 requests/min |
| **Auto Scaling** | Dynamic node allocation during peak |
| **Latency P50** | < 300ms (language models) |
| **Latency P99** | < 800ms |
| **Global Edge Nodes** | 15+ regions worldwide |
| **Protocol** | HTTP/2 + SSE streaming |

```python
# Test concurrency yourself — works out of the box
import asyncio
from openai import AsyncOpenAI

client = AsyncOpenAI(
    api_key="your-key",
    base_url="https://api.zmzai.cn/v1"
)

async def send_request(i):
    return await client.chat.completions.create(
        model="gpt-4o",
        messages=[{"role": "user", "content": f"Say {i}"}]
    )

# Fire 500 requests simultaneously — go ahead
results = await asyncio.gather(*[send_request(i) for i in range(500)])
```

---

## 🏗️ Enterprise-Grade Infrastructure

| | |
|---|---|
| 🏢 **Company** | Registered business entity (not an anonymous proxy) |
| 🔒 **Data Privacy** | No log policy. Your data is YOUR data. |
| 🛡️ **Compliance** | GDPR-ready, data processing agreements available |
| ⏱️ **SLA** | 99.9% uptime guarantee |
| 🔄 **Auto Failover** | If one provider goes down, traffic auto-routes to alternatives |
| 📊 **Dashboard** | Real-time monitoring, usage analytics, cost breakdown |
| 👥 **Team Management** | Multi-user access with role-based permissions |
| 💳 **Billing** | Invoice-based billing for enterprises, multiple payment methods |
| 🔑 **API Key Rotation** | Secure key management with automatic rotation |

---

## 🔌 Instant Integration

Fully compatible with the OpenAI SDK format. Zero migration effort.

```bash
# 1. Install OpenAI SDK
pip install openai
```

```python
# 2. Change ONE line — that's it
from openai import OpenAI

client = OpenAI(
    api_key="your-zmzai-key",
    base_url="https://api.zmzai.cn/v1"   # ← Only this changes
)

# 3. Everything else stays exactly the same
stream = client.chat.completions.create(
    model="claude-3-5-sonnet",
    messages=[{"role": "user", "content": "Hello ZMZ AI!"}],
    stream=True
)

for chunk in stream:
    print(chunk.choices[0].delta.content or "", end="")
```

### Works with Everything You Already Use

| SDK / Framework | Compatible? | How |
|----------------|-------------|-----|
| OpenAI Python SDK | ✅ | Change `base_url` |
| OpenAI Node.js SDK | ✅ | Change `baseURL` |
| LangChain | ✅ | Set `openai_api_base` |
| LlamaIndex | ✅ | Set `api_base` |
| Vercel AI SDK | ✅ | Change `baseURL` |
| LiteLLM | ✅ | Set `custom_llm_provider: openai` |
| Anything OpenAI-compatible | ✅ | Change endpoint URL |

### cURL — No SDK Needed

```bash
curl https://api.zmzai.cn/v1/chat/completions \
  -H "Authorization: Bearer YOUR_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "gpt-4o",
    "messages": [{"role": "user", "content": "Write a startup pitch in 3 sentences"}]
  }'
```

---

## 📈 Real Usage. Real Scale.

We serve AI requests for:

- 🏢 **100+ enterprise customers** on commercial contracts
- 👨‍💻 **50,000+ registered developers**
- 📊 **10M+ API calls daily**
- ⚡ **Peak concurrency:** 50,000+ simultaneous requests
- 🌍 **Traffic from:** US, EU, Asia, Middle East, South America

---

## 🤝 Why Trust ZMZ AI Over Others?

| Concern | Other Relays | ZMZ AI |
|---------|-------------|--------|
| Who's running this? | Anonymous Discord admin | **Registered company with legal entity** |
| Will they disappear tomorrow? | Happens all the time | Operating since 2024, growing steadily |
| Data safe? | Questionable | No-logs policy, DPA available |
| Support when things break? | "DM on Telegram" | Ticket system + enterprise SLA |
| Consistent pricing? | Price hikes randomly | Public, transparent pricing |

---

## 🚀 Getting Started

### 1. Sign Up
Visit **[zmzai.cn](https://zmzai.cn)** and create an account in 30 seconds.

### 2. Get Free Credits
New users receive **free credits** to test any model — no credit card required.

### 3. Get Your API Key
Navigate to the dashboard → API Keys → Generate Key.

### 4. Make Your First Call
```python
from openai import OpenAI
client = OpenAI(api_key="YOUR_KEY", base_url="https://api.zmzai.cn/v1")
response = client.chat.completions.create(model="gpt-4o", messages=[{"role": "user", "content": "Hello!"}])
print(response.choices[0].message.content)
```

That's 4 lines of code. You're live. 🚀

---

## 🔗 Links

| Link | Description |
|------|-------------|
| 🌐 **[zmzai.cn](https://zmzai.cn)** | Official website & model playground |
| 📖 **[Docs][(https://zmzai.cn/docs](https://zmzapi.apifox.cn/))** | Full API documentation |
| 💰 **[Pricing](https://zmzai.cn/pricing)** | Transparent pricing for all 500+ models |
| 📊 **[Dashboard](https://zmzai.cn/dashboard)** | Usage analytics & API management |
| 📧 **Enterprise Inquiries** | enterprise@zmzai.cn |

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

### ⚡ Access 500+ AI Models. Save 70–90%. Zero Hassle.

**[Start Building for Free →](https://zmzai.cn)**

*ZMZ AI — Founded 2024. Real company. Real infrastructure. Real savings.*

</div>
