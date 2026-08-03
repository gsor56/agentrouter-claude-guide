# 🚀 Supercharge Claude Code CLI with AgentRouter ($200 Free Credits!)

Welcome to the ultimate setup guide for pairing **Claude Code** with **AgentRouter**. 

By following this guide, you will learn how to replace expensive API subscriptions with a single gateway and unlock $200 in free compute credits to use directly in your terminal.

## 🌟 Why Use AgentRouter with Claude Code?
*   **Unified Access:** AgentRouter is a non-profit AI API gateway that provides access to over 30 LLM providers (including Anthropic, OpenAI, and DeepSeek) through a single endpoint.
*   **No Credit Card Required:** You can sign up using just your GitHub account.
*   **Massive Free Tier:** While standard signups receive $100 in credits, using a referral link grants you **$200 in free API credits**.
*   **Drop-In Replacement:** It is fully compatible with the official Claude Code client.

---

## 🛠️ Step 1: Claim Your $200 Free API Credits
To get the maximum free tier, you must use a referral link. 

1.  Click here to register: **[Claim $200 AgentRouter Credits](https://agentrouter.org/register?aff=Hv0y)**
2.  Sign in using your GitHub account (No credit card required).
3.  Once logged in, navigate to `https://agentrouter.org/console/token` to generate your new API Key. Keep this key secret and safe!

## 💻 Step 2: Install Node.js & Claude Code
Claude Code is a powerful command-line interface (CLI) tool created by Anthropic that allows you to interact with AI directly in your coding environment.

1.  **Install Node.js:** Claude Code requires Node.js version 18 or higher. If you don't have it, download it from [nodejs.org](https://nodejs.org).
2.  **Install Claude Code:** Open your terminal or command prompt and run the following command to install the CLI globally:
    ```bash
    npm install -g @anthropic-ai/claude-code
    ```
3.  **Verify Installation:** Check that it installed correctly by running:
    ```bash
    claude --version
    ```

## 🔗 Step 3: Configure the AgentRouter Endpoint
By default, Claude Code tries to connect to Anthropic's official paid API. We need to point it to AgentRouter's free endpoint instead by setting up environment variables.

### For macOS and Linux users:
Add these lines to your `~/.bashrc` or `~/.zshrc` file:
```bash
export ANTHROPIC_BASE_URL=[https://agentrouter.org/](https://agentrouter.org/)
export ANTHROPIC_API_KEY=sk-your-agentrouter-key-here
```
## For Windows (PowerShell) users:
Run these commands in PowerShell as an administrator:
```bash
setx ANTHROPIC_BASE_URL "https://agentrouter.org/"
setx ANTHROPIC_API_KEY "sk-your-agentrouter-key-here"
```
(Note: You will need to restart your terminal for the changes to take effect).

# 🎯 Step 4: Start Coding!
You are all set! Open your terminal, navigate to any of your project folders, and simply type:
```bash
claude
```
You now have a powerful AI coding assistant in your terminal, fully powered by your free AgentRouter credits.

#🤝 Need Help?
If you run into any issues during the setup process, feel free to open an issue on this repository or ask me anything in the comments of my YouTube video. I will try my best to help you out!
