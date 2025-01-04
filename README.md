## AI Meeting Preparation Agent
This Streamlit application leverages multiple AI agents to create comprehensive meeting preparation materials. It uses OpenAI's GPT-4, Anthropic's Claude, and the Serper API for web searches to generate context analysis, industry insights, meeting strategies, and executive briefings.

### Features

- Multi-agent AI system for thorough meeting preparation
- Utilizes OpenAI's GPT-4 models.
- Web search capability using Serper API
- Generates detailed context analysis, industry insights, meeting strategies, and executive briefings


### Agents used
- context_analyzer
- industry_insights_generator
- strategy_formulator 
- executive_briefing_creator
- 
### How to get Started?

1. Clone the GitHub repository

```bash
git clone https://github.com/NageshMashette/meeting_agent_crewai.git
```
2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Get your SerpAPI Key

- Sign up for an [Serper API account](https://serper.dev/) and obtain your API key.

4. Get your OpenAI API Key

- Sign up for an [OpenAI account](https://platform.openai.com/) (or the LLM provider of your choice) and obtain your API key.

5. Run the Streamlit App
```bash
streamlit run meeting_agent.py
```