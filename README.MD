# 🚀 AgentRouter — Free AI Coding Credits for Claude Code, Codex & More

> A practical community guide for using AgentRouter with AI coding tools such as Claude Code, Codex, Gemini CLI, OpenCode, and more.

[![AgentRouter](https://img.shields.io/badge/AgentRouter-AI%20Coding-blue)](https://agentrouter.org/)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-supported-purple)](https://docs.anthropic.com/en/docs/claude-code)
[![Codex](https://img.shields.io/badge/OpenAI%20Codex-supported-green)](https://github.com/openai/codex)

---

## 🎁 Get Free AI Coding Credits

If you're looking for a way to try AI coding tools without immediately paying for another API subscription, AgentRouter currently offers promotional/free credits for developers.

### 👉 [Create an AgentRouter Account](https://agentrouter.org/register?aff=tWcX)

**Referral disclosure:** This is a referral link. If you sign up through it, you may receive the promotional benefit offered by AgentRouter, and I may receive a referral reward.

> Promotional offers, credit amounts, eligibility requirements, and referral terms can change. Check the registration page for the current offer before signing up.

---

## 🤖 What is AgentRouter?

AgentRouter is an AI coding gateway that lets developers connect coding agents to supported AI models through a unified service.

It can be used with popular AI coding tools including:

* Claude Code
* OpenAI Codex
* Gemini CLI
* OpenCode
* Cline
* Roo Code
* Kilo Code
* Qwen Code
* and other supported tools

The official AgentRouter documentation currently lists support for multiple CLI, IDE, and coding-agent tools.

---

# ⚡ Quick Start

## 1. Create Your Account

Start here:

### 👉 [Register for AgentRouter](https://agentrouter.org/register?aff=tWcX)

Create your account and follow the instructions shown on the official website.

After registration, open your AgentRouter dashboard and create/copy your API key.

---

# 🧠 Claude Code

If you're using Claude Code, AgentRouter can be configured as the API endpoint.

### Install Claude Code

```bash
npm install -g @anthropic-ai/claude-code
```

### Configure the API

#### Windows PowerShell

```powershell
$env:ANTHROPIC_BASE_URL="https://agentrouter.org/"
$env:ANTHROPIC_AUTH_TOKEN="YOUR_AGENTROUTER_API_KEY"
$env:ANTHROPIC_API_KEY="YOUR_AGENTROUTER_API_KEY"
```

#### macOS / Linux

```bash
export ANTHROPIC_BASE_URL="https://agentrouter.org/"
export ANTHROPIC_AUTH_TOKEN="YOUR_AGENTROUTER_API_KEY"
export ANTHROPIC_API_KEY="YOUR_AGENTROUTER_API_KEY"
```

Then start Claude Code:

```bash
claude
```

> Always check the current AgentRouter documentation for the latest endpoint and authentication configuration.

---

# 💻 OpenAI Codex

AgentRouter can also be used with Codex.

### Install Codex

```bash
npm install -g @openai/codex
```

Then configure Codex according to the current AgentRouter Codex documentation.

Typical configuration involves:

* AgentRouter API endpoint
* AgentRouter API token
* Model configuration

For the latest Codex configuration:

👉 **[AgentRouter Codex Documentation](https://docs.agentrouter.org/)**

---

# 🟢 OpenCode

If you use OpenCode, you can configure AgentRouter as a model/API provider.

The exact configuration may change as AgentRouter and OpenCode evolve, so use the current AgentRouter documentation when configuring your account.

---

# 🧩 Supported Coding Tools

AgentRouter currently documents support for multiple AI coding tools.

| Tool        | Supported |
| ----------- | --------: |
| Claude Code |         ✅ |
| Codex       |         ✅ |
| Gemini CLI  |         ✅ |
| OpenCode    |         ✅ |
| Cline       |         ✅ |
| Roo Code    |         ✅ |
| Kilo Code   |         ✅ |
| Qwen Code   |         ✅ |
| Trae        |         ✅ |

Support and available models can change over time.

---

# 🔑 Where Do I Get an API Key?

After creating your AgentRouter account:

1. Sign in to your dashboard.
2. Open the API key/token section.
3. Create or copy your API key.
4. Add it to the coding tool you're using.
5. Start your coding agent.

### ⚠️ Never publish your API key

Do NOT put your API key directly inside:

* GitHub repositories
* README files
* screenshots
* public Discord messages
* Reddit posts
* `.env` files committed to Git

Use environment variables instead.

---

# 🛠️ Example Environment Variables

Create your environment variables locally:

```bash
ANTHROPIC_BASE_URL=https://agentrouter.org/
ANTHROPIC_AUTH_TOKEN=YOUR_AGENTROUTER_API_KEY
ANTHROPIC_API_KEY=YOUR_AGENTROUTER_API_KEY
```

Replace:

```text
YOUR_AGENTROUTER_API_KEY
```

with your own key.

---

# ❓ FAQ

## Is AgentRouter free?

AgentRouter currently provides free/promotional credits for developers, but the exact amount and eligibility can change.

Check the registration page for the current offer.

## Do I need a credit card?

Requirements can change depending on the current promotion and account eligibility.

Check the registration flow for the latest requirements.

## Can I use AgentRouter with Claude Code?

Yes. Claude Code is listed among the supported tools.

## Can I use AgentRouter with Codex?

Yes. AgentRouter provides documentation for using it with Codex.

## Can I use it with other coding agents?

Yes. The official documentation currently lists several supported coding tools.

## Is this an official AgentRouter repository?

No.

This is an independent community-created guide.

The official AgentRouter website and documentation should always be considered the source of truth for current pricing, limits, supported models, and promotional offers.

---

# 🔒 Security

Never share your AgentRouter API key publicly.

If you accidentally expose your key:

1. Revoke it immediately.
2. Generate a new key.
3. Remove the exposed key from your repository history.
4. Update your local environment variables.

---

# 📚 Official Resources

* [AgentRouter](https://agentrouter.org/)
* [AgentRouter Documentation](https://docs.agentrouter.org/)
* [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code)
* [OpenAI Codex](https://github.com/openai/codex)

---

# ⭐ Support This Guide

If this guide helped you:

* ⭐ Star this repository
* 🐛 Open an issue if you find an outdated instruction
* 🔧 Submit a pull request with improvements
* 📢 Share the guide with other developers

---

## 🎁 Ready to Try It?

### 👉 [Create Your AgentRouter Account](https://agentrouter.org/register?aff=tWcX)

**Referral disclosure:** This is a referral link. You may receive a promotional benefit from AgentRouter, and I may receive a referral reward.

Always verify the current promotion and eligibility requirements on AgentRouter before signing up.

---

## Disclaimer

This repository is an independent community guide and is not affiliated with, endorsed by, or operated by AgentRouter.

AgentRouter's pricing, credits, models, supported tools, terms, and referral programs may change at any time.

Always verify current information on the official AgentRouter website.
