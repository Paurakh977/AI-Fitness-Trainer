# AI Fitness Trainer

An intelligent personal fitness tool that provides customized fitness and nutrition guidance using AI. This application helps users manage their fitness goals, track personal metrics, and receive AI-powered recommendations.

## Features

- 🏃 Personal profile management (age, weight, height, gender, activity level)
- 🎯 Customizable fitness goals (Muscle Gain, Fat Loss, Stay Active)
- 🍎 AI-generated macro calculations
- 📝 Note-taking functionality
- 🤖 AI-powered fitness and nutrition advice
- 💾 Data persistence using Astra DB

## Prerequisites

- Python 3.8 or higher
- [uv](https://github.com/astral-sh/uv) package installer
- Astra DB account
- Langflow account

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/AI-Fitness-Trainer.git
cd AI-Fitness-Trainer
```

2. Create and activate a virtual environment using uv:
```bash
uv venv
source .venv/bin/activate  # On Unix/macOS
# OR
.venv\Scripts\activate  # On Windows
```

3. Install dependencies using uv:
```bash
uv pip install .        # Install regular dependencies
# OR
uv pip install ".[dev]" # Install with development dependencies
```

## Environment Setup

Create a `sample.env` file in the project root and add the following configurations:
```env
ASTRA_ENDPOINT=your_astra_endpoint
ASTRA_DB_APPLICATION_TOKEN=your_astra_token
LANGFLOW_TOKEN=your_langflow_token
```

Rename `sample.env` to `.env` and replace the placeholder values with your actual credentials.

## Project Structure
