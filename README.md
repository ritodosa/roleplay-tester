# Roleplay Testing with Promptfoo

## Running Tests
```bash
export ANTHROPIC_API_KEY=your_key
export GEMINI_API_KEY=your_key
export OPENAI_API_KEY=your_key
export OPENROUTER_API_KEY=your_key

promptfoo cache clear
promptfoo eval -c promptfoo_config.yaml --no-cache
promptfoo view
```
