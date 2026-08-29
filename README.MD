# 🚀 Claude Code + Third-Party API

**🇸🇦 [العربي — اضغط هنا](README_AR.md)**

Use Claude Code with a third-party API provider in a few simple steps.

No cracking.
No modified Claude.
No bypassing Claude.
No complicated setup.

You simply:

**Create an account → Get an API Key → Add the API URL → Start Claude Code.**

---

# ⭐ Recommended Providers

## 1. AgentRouter

👉 **[Register AgentRouter](https://agentrouter.org/register?aff=tWcX)**

## 2. JustWoker

👉 **[Register JustWoker](https://api.justwoker.icu/register?aff=gTPs)**

These are the two recommended options in this guide.

> Referral links: I may receive a referral reward if you register through these links.

---

# 💻 Claude Code — Terminal

## 1. Install Claude Code

### Windows PowerShell

```powershell
irm https://claude.ai/install.ps1 | iex
```

### macOS / Linux

```bash
curl -fsSL https://claude.ai/install.sh | bash
```

---

## 2. Get Your API Key

Create an account with one of the providers above and get your API key.

---

## 3. Connect Claude Code

### Windows PowerShell

```powershell
$env:ANTHROPIC_BASE_URL="YOUR_API_URL"
$env:ANTHROPIC_AUTH_TOKEN="YOUR_API_KEY"
$env:ANTHROPIC_API_KEY=""
```

Replace:

```text
YOUR_API_URL
YOUR_API_KEY
```

with the values from your provider.

### macOS / Linux

```bash
export ANTHROPIC_BASE_URL="YOUR_API_URL"
export ANTHROPIC_AUTH_TOKEN="YOUR_API_KEY"
export ANTHROPIC_API_KEY=""
```

---

## 4. Start Claude Code

```bash
claude
```

That's it. 🎉

If Claude Code was already logged into Anthropic:

```text
/logout
```

Then start Claude again.

---

# 🖥️ Claude Desktop

You can also use a compatible third-party API with Claude Desktop.

### 1. Enable Developer Mode

Open Claude Desktop:

**Help → Troubleshooting → Enable Developer Mode**

Restart Claude Desktop.

### 2. Open API Settings

Go to:

**Developer → Configure Third-Party Inference**

Choose:

**Gateway**

### 3. Enter your API

```text
Gateway Base URL: YOUR_API_URL
API Key: YOUR_API_KEY
Auth Scheme: Bearer
```

Then click:

**Apply locally**

Done. ✅

---

# 🔄 Using Another Provider?

The setup is usually the same.

You only change:

```text
API URL
API KEY
```

The provider must support the **Anthropic Messages API / Claude Code**.

---

# 🌐 More Providers

If you want to try other services:

* **HelpCoder:** https://helpcoder.cc/register?aff=5yLk
* **TokenBOM:** https://tokenbom.com/login?mode=register&invite=SS-C5882AE6
* **BluesMinds:** https://api.bluesminds.com/sign-up?aff=QlJ3
* **VSLMM:** https://vsllm.com/register?aff=4pUb

---

# 🔐 Is This Hacking?

**No.**

This setup does not hack Claude or modify the Claude application.

You are simply using a **third-party API provider** and connecting Claude Code to its API endpoint.

You still use the normal Claude Code application.

### ⚠️ Important

Your API key is private.

Never share it on:

* GitHub
* Reddit
* Discord
* Screenshots
* Public code

Also avoid sending passwords, private keys, or sensitive company data through a third-party provider unless you have reviewed its privacy/security terms.

---

# ⚡ Super Simple

```text
Create Account
      ↓
Get API Key
      ↓
Set API URL
      ↓
Set API Key
      ↓
claude
      ↓
🚀 Done
```

---

**🇸🇦 [العربي — اضغط هنا](README_AR.md)**

⭐ If this guide helped you, consider starring the repository.
