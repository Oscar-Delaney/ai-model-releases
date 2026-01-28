# Frontier AI Model Releases

A dashboard tracking model releases from leading AI companies, with timeline visualization and rough next-release predictions based on historical cadence.

**Live site:** [oscar-delaney.github.io/ai-model-releases](https://oscar-delaney.github.io/ai-model-releases/)

## Companies tracked

OpenAI, Anthropic, Google DeepMind, Meta, xAI, DeepSeek, Alibaba (Qwen)

## Features

- Cards showing days since last major release, average cadence, and predicted next release
- Swimlane timeline with major vs minor release dots
- "Today" line and dashed predicted-next-release markers
- Single `index.html` file, no dependencies

## Data

Release dates are hardcoded in `index.html` and sourced from official blogs, Wikipedia, and tech news. The distinction between "major" and "minor" releases is subjective. Contributions and corrections welcome via issues or PRs.
