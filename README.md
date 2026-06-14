# 🤖 Autonomous Tech News Research AI Agent

An automated, node-based AI research workflow built using **n8n** that autonomously discovers, analyzes, and distributes technology news updates to reduce manual reading overhead.

## 🚀 Features
* **Automated Collection:** Automatically triggers daily to pull the latest headlines via various RSS feeds.
* **AI-Powered Analysis:** Leverages an LLM (GPT-4o-mini/Claude-3) to instantly categorize articles and generate concise 2-sentence summaries.
* **Automated Reporting:** Aggregates and formats multiple news items into a single, clean markdown newsletter.
* **Instant Delivery:** Delivers the structured brief directly to google spreadsheet (Google sheets).

## 🛠️ Architecture & Tech Stack
* **Workflow Automation:** n8n
* **AI Integration:** Advanced AI (LangChain wrapper) + OpenAI/Anthropic Chat Models
* **Data Sources:** RSS Feed Parsers
* **Final Data** Google Sheets

## 📦 How to Import & Use This Project
1. Copy the raw contents of the `n8n_news_agent_workflow.json` file in this repository.
2. Open your **n8n instance** and create a blank canvas.
3. Press `Ctrl + V` (or `Cmd + V` on Mac) to paste and auto-generate the workflow structure.
4. Supply your own **LLM API Credentials** in the AI Agent Model node.
5. Add appropriate user login to google sheet to access the news on it.
6. Toggle the workflow to **Active**.
