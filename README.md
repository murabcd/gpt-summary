<p align="center">
  <img alt="GPT Summary" src="./preview/public/gpt-suite.png">
  <h1 align="center">GPT Summary</h1>
</p>

<p align="center">
  A powerful Chrome extension that uses OpenAI to generate summaries of webpages.
</p>

<p align="center">
  <a href="#features"><strong>Features</strong></a> ·
  <a href="#model-provider"><strong>Model provider</strong></a> ·
  <a href="#deploy-your-own"><strong>Deploy your own</strong></a> ·
  <a href="#running-locally"><strong>Running locally</strong></a>
</p>
<br/>

## Features

- [OpenAI](https://ai-sdk.dev/)
  - Advanced AI integration for content analysis and podcast generation
  - Real-time web page content processing and summarization

## Model Provider

This extension uses [OpenAI](https://openai.com/) as the default model provider.

- `gpt-4o`: Advanced GPT-4o model for accurate and efficient content summarization
- `gpt-4o-mini`: Lightweight GPT-4o variant optimized for faster processing and concise summaries

## Deploy your own

1. Clone this repository:

```bash
git clone https://github.com/muradpm/chat-gpt3-summary.git
```

2. Configure the extension:
   - Add your OpenAI API key to extension settings: `OPENAI_API_KEY=your_key_here`

3. Load in Chrome:
   - Open Chrome Extensions page (`chrome://extensions/`)
   - Enable "Developer mode"
   - Click "Load unpacked"
   - Select the cloned repository folder

## Running locally

1. Click the extension icon in your Chrome toolbar
2. Navigate to any webpage you want to summarize
3. Click the "Summarize" button
4. View your generated summary with key facts and insights