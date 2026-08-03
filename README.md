<p align="center">
  <img src="assets/banner.svg" alt="Claude Code + AgentRouter banner" width="800"/>
</p>

<p align="center">
  <em>Set up Claude Code CLI with AgentRouter and claim $200 in free credits.</em>
</p>

---

> **Disclosure:** The signup link below is my referral link — I receive a benefit when you use it. Standard signups get $100 in credits; the referral link is what unlocks $200.
>
> **Security note:** Once you set `ANTHROPIC_API_KEY` / `ANTHROPIC_BASE_URL` to a third-party gateway, that provider can see and log every request you send through Claude Code. Don't reuse a key tied to sensitive projects, and review AgentRouter's terms and privacy practices yourself before proceeding.

## 🌟 Why Use AgentRouter with Claude Code?

* **Unified Access:** AgentRouter is an API gateway providing access to 30+ LLM providers (Anthropic, OpenAI, DeepSeek, and others) through a single endpoint.
* **No Credit Card Required:** Sign up using just your GitHub account.
* **Free Tier:** Standard signups receive $100 in credits; using the referral link below grants **$200**.
* **Drop-In Replacement:** Compatible with the official Claude Code client via environment variables.

---

## <img src="assets/step1.svg" width="28" valign="middle"/> Step 1: Claim Your Free API Credits

1. Register here: **[Claim $200 AgentRouter Credits](https://agentrouter.org/register?aff=Hv0y)**
2. Sign in with your GitHub account (no credit card required).
3. Generate an API key at `https://agentrouter.org/console/token`. Treat this key like a password — keep it secret.

## <img src="assets/step2.svg" width="28" valign="middle"/> Step 2: Install Node.js & Claude Code

Claude Code is Anthropic's official command-line coding assistant.

1. **Install Node.js 18+** from [nodejs.org](https://nodejs.org) if you don't already have it.
2. **Install Claude Code:**
   ```bash
   npm install -g @anthropic-ai/claude-code
   ```
3. **Verify:**
   ```bash
   claude --version
   ```

## <img src="assets/step3.svg" width="28" valign="middle"/> Step 3: Point Claude Code at AgentRouter

By default, Claude Code talks to Anthropic's official API. To route through AgentRouter instead, set two environment variables.

**macOS / Linux** — add to `~/.bashrc` or `~/.zshrc`:
```bash
export ANTHROPIC_BASE_URL="https://agentrouter.org/"
export ANTHROPIC_API_KEY="sk-your-agentrouter-key-here"
```

**Windows (PowerShell, as administrator):**
```powershell
setx ANTHROPIC_BASE_URL "https://agentrouter.org/"
setx ANTHROPIC_API_KEY "sk-your-agentrouter-key-here"
```

Restart your terminal for changes to take effect.

## <img src="assets/step4.svg" width="28" valign="middle"/> Step 4: Start Coding

```bash
claude
```

You're set — Claude Code is now running against your AgentRouter credits.

---

## 🤝 Need Help?

Open an issue on this repo, or leave a comment on my YouTube video — I'll do my best to help.
