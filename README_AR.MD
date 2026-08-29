# 🚀 تشغيل Claude Code باستخدام API خارجي

**🇺🇸 [English — اضغط هنا](README.md)**

تشغل Claude Code باستخدام API من خدمات خارجية في كام خطوة بسيطة جدًا.

**مفيش اختراق.
مفيش Crack.
مفيش تعديل على Claude.
مفيش إعدادات معقدة.**

الفكرة ببساطة:

**تسجل حساب → تاخد API Key → تحط الـURL والـKey → تشغل Claude Code.**

---

# ⭐ أفضل اختيارين

## 1. AgentRouter

👉 **[التسجيل من هنا](https://agentrouter.org/register?aff=tWcX)**

## 2. JustWoker

👉 **[التسجيل من هنا](https://api.justwoker.icu/register?aff=gTPs)**

دول أهم اختيارين في الدليل.

> **Referral:** الروابط دي Referral Links، وممكن أحصل على مكافأة لو سجلت من خلالها.

---

# 💻 Claude Code — Terminal

## 1. تثبيت Claude Code

### Windows

افتح PowerShell واكتب:

```powershell
irm https://claude.ai/install.ps1 | iex
```

### macOS / Linux

```bash
curl -fsSL https://claude.ai/install.sh | bash
```

---

# 2. هات الـAPI Key

سجل في أي Provider من اللي فوق.

بعد التسجيل هات الـ:

```text
API Key
```

---

# 3. اربط Claude Code

### Windows PowerShell

```powershell
$env:ANTHROPIC_BASE_URL="YOUR_API_URL"
$env:ANTHROPIC_AUTH_TOKEN="YOUR_API_KEY"
$env:ANTHROPIC_API_KEY=""
```

بدل:

```text
YOUR_API_URL
YOUR_API_KEY
```

بالـURL والـAPI Key بتوع الخدمة اللي سجلت فيها.

### macOS / Linux

```bash
export ANTHROPIC_BASE_URL="YOUR_API_URL"
export ANTHROPIC_AUTH_TOKEN="YOUR_API_KEY"
export ANTHROPIC_API_KEY=""
```

---

# 4. شغل Claude

```bash
claude
```

🎉 **خلصت!**

لو Claude كان معمول له Login قبل كده:

```text
/logout
```

وبعدها شغل Claude تاني.

---

# 🖥️ Claude Desktop

تقدر تعمل نفس الفكرة من Claude Desktop.

## 1. فعل Developer Mode

افتح Claude Desktop وروح إلى:

**Help → Troubleshooting → Enable Developer Mode**

اعمل Restart للبرنامج.

---

## 2. افتح إعدادات الـAPI

روح إلى:

**Developer → Configure Third-Party Inference**

اختار:

**Gateway**

---

## 3. حط البيانات

```text
Gateway Base URL: YOUR_API_URL
API Key: YOUR_API_KEY
Auth Scheme: Bearer
```

وبعدين:

**Apply locally**

🎉 **خلصت.**

---

# 🔄 عايز تستخدم Provider تاني؟

نفس الفكرة تقريبًا.

بتغير بس:

```text
API URL
API KEY
```

لازم الخدمة تكون داعمة لـ:

**Anthropic Messages API / Claude Code**

---

# 🌐 خدمات تانية

لو عايز تجرب خدمات إضافية:

* **HelpCoder:** https://helpcoder.cc/register?aff=5yLk
* **TokenBOM:** https://tokenbom.com/login?mode=register&invite=SS-C5882AE6
* **BluesMinds:** https://api.bluesminds.com/sign-up?aff=QlJ3
* **VSLMM:** https://vsllm.com/register?aff=4pUb

---

# 🔐 هل ده اختراق؟

**لا.**

أنت مش بتخترق Claude ولا بتعدل البرنامج.

أنت فقط بتستخدم:

**Claude Code + Third-Party API**

يعني بتسجل حساب في خدمة خارجية، تاخد API Key، وتخلي Claude Code يستخدم الـAPI الخاص بالخدمة.

Claude Code نفسه يتيح الاتصال بـLLM gateways التي توفر Anthropic Messages API.

### ⚠️ مهم جدًا

الـAPI Key بتاعك **سري**.

متحطوش في:

* GitHub
* Reddit
* Discord
* Screenshots
* Public Code

ومتبعتش كلمات سر أو Private Keys أو بيانات حساسة لخدمة خارجية إلا بعد ما تراجع سياسة الخصوصية والأمان الخاصة بها.

---

# ⚡ المختصر

```text
سجل حساب
    ↓
هات API Key
    ↓
حط API URL
    ↓
حط API Key
    ↓
claude
    ↓
🚀 اشتغل
```

---

**🇺🇸 [English — اضغط هنا](README.md)**

⭐ لو الدليل أفادك، اعمل Star للـRepository.
