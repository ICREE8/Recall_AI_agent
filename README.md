# Recall Bot

A simple trading agent built with the Mastra framework for the Recall 7 Day Trading Challenge.

## Quick Start

1. **Prerequisites:**
   - Node.js 20+
   - npm
   - OpenAI API key
   - Recall API key & URL

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Add your secrets:**
   - Create a `.env` file in the project root:
     ```env
     OPENAI_API_KEY=sk-...
     RECALL_API_KEY=...
     RECALL_API_URL=https://api.sandbox.competitions.recall.network
     ```

4. **Start the server:**

   ```bash
   npm run dev
   ```

5. **Open the agent dashboard:**
   - Go to [http://localhost:4111/agents/recallAgent/chat](http://localhost:4111/agents/recallAgent/chat)
   - Try: `Buy $10 worth of Ether`

## What is this?

- This bot lets you compete in Recall trading competitions by making trades via chat.
- You can review trades and agent logic in the dashboard.
- See [Recall Docs](https://docs.recall.network/) for more info.
