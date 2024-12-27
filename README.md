<p align="center">
  <a href="https://platform.straico.com/signup?fpr=awesomestraico"><img src="straico-logo.png" alt="Straico Logo" style="display: block; margin: 0 auto; margin-bottom: 30px;"></a>
</p>

# Awesome Straico [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Straico resources, tools, articles and more. [Straico](https://platform.straico.com/signup?fpr=awesomestraico)^† is a unified AI workspace that provides seamless access to multiple generative AI models for text, images, and audio. It enables parallel conversations with different LLMs, supports multimedia context integration, and offers powerful API access for developers.

^†_Community insights ahead._

> **Community Note**: Building this awesome list takes time and passion. Our friends at Straico have been incredibly supportive, offering a little something special for folks who discover Straico through our community.
> 
> [10% off your subscription and 1,000 free coins to explore](https://platform.straico.com/signup?fpr=awesomestraico) 🎁 – helping makers build awesome things.
> 
> **Note:** Links to Straico's platform and some other resources may contain affiliate links that support the time spent on keeping this list updated and relevant.

Key Features:
- 30+ Language Models for diverse AI interactions
- Parallel chat capabilities with up to 4 LLMs simultaneously
- Template library for workflow optimization
- Multimedia context support (PDFs, images, audio, video)
- RAG (Retrieval-Augmented Generation) capabilities 🚧
- AI Agents support 🚧
- Comprehensive API access
- Rich integration ecosystem

## Contents

- [Official Resources](#official-resources)
- [Community](#community)
- [Integrations](#integrations)
- [API Wrappers](#api-wrappers)
- [Tools](#tools)
- [Articles](#articles)
- [Media & Learning](#media--learning)
- [Templates & Prompts](#templates--prompts)
- [Model Recommendations](#model-recommendations)
- [RAG](#rag)
- [Agents](#agents)
- [Contributing](#contributing)

## Official Resources

- [Straico Website](https://straico.com) - Official website
- [API Reference (Swagger)](https://documenter.getpostman.com/view/5900072/2s9YyzddrR) - Complete API reference documentation
- [Public Roadmap](https://trello.com/b/f6tsuMaE/straicos-board-roadmap) - Track upcoming features and development progress
- [Desktop App](https://straico.com/desktop-app/) - Native Windows, macOS and Linux application
- [Model Selection Guide](https://straico.com/multimodel/) - Comprehensive guide for choosing the right LLM model
- [YouTube Channel](https://www.youtube.com/channel/UC7_fJIbV6QPbuPjwHwm--rw) - Official tutorials, guides, and updates

## Community

- [Discord](https://discord.gg/straico-community-1118690015443161130) [![Discord](https://img.shields.io/discord/1118690015443161130?color=7289da&logo=discord&logoColor=white)](https://discord.gg/straico-community-1118690015443161130)

## Integrations

*Tools and platforms that integrate with Straico.*

- [Aahsheet](https://www.aahsheet.com/) - Spreadsheet automation platform with Straico integration for AI workflows
  - Free tools available at [aahsheet.com/free](https://www.aahsheet.com/free) including Google Sheets integration with Straico AI Function (`=ai("prompt")`) and template
- [Activepieces](https://github.com/activepieces/activepieces) - Low-code business automation tool with Straico integration
- [Albato](https://albato.com/apps/straico) - Workflow automation platform supporting Straico API integration
- [AlterHQ](https://alterhq.com/) - Native macOS AI assistant with AppSense technology for contextual awareness across applications
- [BizReply](https://bizreply.co) - AI-powered social media engagement tool that identifies relevant posts and generates contextual responses using your brand voice
- [Enconvo](https://github.com/Enconvo/straico) - Native macOS AI assistant integration enabling seamless communication with Straico's chat, RAG, and agents through the Enconvo platform (requires Enconvo v1.8.8+)
- [Flowmattic](https://flowmattic.com/integration/straico/) - Workflow automation for WordPress with Straico integration
- [LiteLLM](https://gist.github.com/jayrinaldime/3f53d3621618eadfaa7a5942d538324a) - Unified LLM Gateway for managing authentication and load balancing across 100+ LLMs in OpenAI format
- [Make.com](https://www.make.com) - Advanced integration platform with Straico capabilities
- [Olly](https://www.youtube.com/watch?v=y5XrgBrsaIo) - AI automation platform with Straico integration
- [Pabbly](https://www.pabbly.com/connect/integrations/straico/) - Business process automation with Straico support
- [Robomotion](https://robomotion.io) - RPA platform for building data extraction bots and automating web/desktop applications
- [Snippety](https://youtu.be/qUF6GwnO5lM) - AI-powered smart placeholders and template generation tool
- [StraicoForWP](https://github.com/RoboRiley/StraicoForWP) - WordPress plugin for AI-powered post and page creation
- [TaskMagic](https://www.taskmagic.com/) - Convert walkthrough videos into automated web tasks, eliminating repetitive manual work
- [TubeOnAI](https://tubeonai.com//?via=IvoPer) - All-in-one AI summarizer for videos, podcasts, PDFs, and web articles, enabling quick content consumption and repurposing for enhanced productivity
- [ViinyxAI](https://www.viinyx.com/) - All-in-one AI assistant supporting multiple models including GPT-4, GPT-4o, Gemini 1.5, Claude 3+, with custom API key connections
- [ZeroWork](https://www.zerowork.io/) - No-code automation platform for web scraping and task automation, with Straico integration via HTTP requests ([Community Template](https://discord.com/channels/945706937020973097/1255869783510093864) available in [ZeroWork Discord](https://discord.gg/JkkCNmVBeg))

## API Wrappers

*Libraries and packages for interacting with Straico API.*

- [aio-straico](https://github.com/jayrinaldime/aio-straico) - Python async client library for Straico API
- [clsStraico](https://github.com/roelfrenkema/clsStraico) - PHP class for Straico API integration with Fizz (Fizz is a PHP framework for building RESTful APIs)
- [ollama-straico-apiproxy](https://github.com/jayrinaldime/ollama-straico-apiproxy) - API proxy that implements Ollama/LM Studio endpoints but redirects requests to Straico API Server
- [straico-client](https://github.com/ricardokl/straico-client) - Rust client library for Straico API

## Tools

*Tools and utilities related to Straico.*

- [Aider](https://aider.chat/docs/llms/ollama.html) - AI coding assistant that can connect to Straico through ollama-straico-apiproxy integration
- [Ollama](https://ollama.com) - Run LLMs locally, compatible with Straico through ollama-straico-apiproxy
- [Straico Assistant](https://chromewebstore.google.com/detail/straico-assistant/pjnabmgggljaohlghgocippfdnfnepmo) - Chrome extension with side panel for easy API interaction and message history
- [YouTube Scraper](https://github.com/therealJMT/Straico/tree/main/Youtube-Scraper) - Straico YouTube scraper boilerplate (currently non-functional, but useful as development reference)

## Articles

*Articles and blog posts about Straico.*

## Media & Learning

### Content Creators
*YouTube channels and content creators focused on Straico tutorials and implementations*

- [CodingMenace](https://www.youtube.com/@codingmenace) - Channel featuring Straico integrations and automation tutorials
- [Softreviewed](https://www.youtube.com/@softreviewed) - Channel featuring AI tools and software automation reviews

### Tutorials & Guides
*Step-by-step guides and educational content about Straico.*

- 🇺🇸 [AI-Powered PDF Invoice Manager](https://www.youtube.com/watch?v=hlO_oLSPLAk) - Building an invoice management system with Straico in Robomotion
- 🇺🇸 [Building an AI Research Agent](https://www.youtube.com/watch?v=3hozFgV3xjc) - Step-by-step guide on creating a research agent using ActivePieces and Perplexity AI
- 🇺🇸 [Custom Template Creation Guide](https://straico.com/how-to-create-a-custom-template-in-straico-a-step-by-step-guide/) - Learn how to create and customize templates in Straico
- 🇺🇸 [Features Overview](https://youtu.be/gjuRtOfWH3o) ![Official](https://img.shields.io/badge/official-blue) - Quick introduction to Smart Mode, image generation with Flux 1.1 Pro and DALL-E 3, and Side By Side Mode features
- 🇺🇸 [Generate Visuals with Straico](https://youtu.be/175NkEnODCo) ![Official](https://img.shields.io/badge/official-blue) - Quick tutorial on using sample images to generate visuals with Straico's image generation capabilities
- 🇺🇸 [Multi-API Integration with BizReply](https://youtu.be/6KIfC6WQOUc) - Tutorial on connecting OpenAI, Straico, and Gemini APIs with BizReply's BYOK feature
- 🇺🇸 [Personal Experience with Straico](https://youtu.be/A2tvOQxs9Og) - Comprehensive review by Selena Tramayne on using Straico for workflow optimization, comparing AI models, and organizing prompts
- 🇪🇸 [Todos los modelos de A.I. en un único lugar](https://www.youtube.com/watch?v=pej6FPL8XeU) - Overview of Straico's AI model integration capabilities

### Integration Examples
*Real-world examples and implementation showcases.*

### Talks & Presentations
*Conference talks, webinars, and presentations featuring Straico.*

## Templates & Prompts

*Curated list of useful Straico templates and prompting guidelines.*

- [The Power of Template Prompts: Boost Your Productivity with Straico](https://straico.com/the-power-of-template-prompts-boost-your-productivity-with-straico/) ![Official](https://img.shields.io/badge/official-blue) - Guide on using Straico's template prompts to enhance productivity by streamlining AI interactions and reducing repetitive tasks.

## Model Recommendations

### Recommended Models by Use Case
*Best performing models for specific tasks based on community feedback and testing. Costs are in coins per 100 words as of December 2024.*

#### Content Creation & SEO
- **OpenAI: GPT-4o mini** (0.4 coins) - Best for SEO-optimized content with web awareness
- **NVIDIA: Llama 3.1 Nemotron 70B** (0.5 coins) - Excellent for creative writing and content generation
- **Meta: Llama 3.1 70B** (0.7 coins) - Great for long-form content and storytelling

#### Research & Analysis
- **Perplexity: Llama 3.1 Sonar 405B** (2.7 coins) - Superior for research with real-time web search
- **OpenAI: GPT-4o** (3.0 coins) - Excellent for complex analysis with web browsing
- **Google: Gemini Pro 1.5** (3.7 coins) - Strong analytical capabilities with image understanding

#### Code Generation & Technical Writing
- **Qwen2.5 Coder 32B** (0.5 coins) - Specialized for coding tasks
- **Mistral: Codestral Mamba** (0.2 coins) - Efficient for code documentation
- **Anthropic: Claude 3.5 Sonnet** (4.8 coins) - Excellent for technical documentation with image context

#### Summarization & Data Processing
- **Cohere: Command R** (0.2 coins) - Cost-effective for basic summarization
- **Qwen2.5 72B** (0.2 coins) - Efficient for document processing
- **Meta: Llama 3.1 405B** (1.6 coins) - Great for complex document understanding

#### Creative & Marketing Copy
- **Anthropic: Claude 3 Haiku** (1.0 coins) - Excellent for concise, creative content
- **Mistral: Large** (3.0 coins) - Strong for marketing copy
- **OpenAI: GPT-4o mini** (0.4 coins) - Great for brand voice consistency

#### Multilingual Content
- **Google: Gemini Pro 1.5** (3.7 coins) - Superior multilingual capabilities
- **NVIDIA: Nemotron 70B** (0.5 coins) - Strong in multiple languages
- **Meta: Llama 3.1 405B** (1.6 coins) - Excellent for translation and localization

> **Note**: Costs and capabilities are subject to change. Always check the [official pricing](https://straico.com/multimodel/) for the most current rates.

## RAG 🚧

*Resources and examples for Retrieval-Augmented Generation with Straico.*

### Tutorials
- [Introduction to Straico’s latest RAG API upgrade](https://straico.com/rag-intro-api) ![Official](https://img.shields.io/badge/official-blue) - Guide on using Straico's API for Retrieval-Augmented Generation (RAG) to enhance AI responses with external data.
- [Multiple Files Upload Guide](https://www.youtube.com/watch?v=aKAPY03ciI4) - Comprehensive tutorial on uploading multiple files to Straico RAG
- [RAG Tutorial with Make.com](https://www.youtube.com/watch?v=OEi7DX6hB5M) - Complete guide on connecting Straico AI with Make.com API integration

## Agents 🚧

*Resources and examples for working with Straico AI Agents.*

### Tutorials
- [AI Agents in Make.com](https://www.youtube.com/watch?v=lgttnHbiOlc) - Step-by-step tutorial on building AI agents with Straico in Make.com

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
