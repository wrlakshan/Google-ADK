# Google-ADK

A Python project built with [Google Agent Development Kit (ADK)](https://google.github.io/adk-docs/) for building AI agents powered by Google's Gemini models.

## Prerequisites

- Python 3.9+
- A Google AI API key ([Get one here](https://aistudio.google.com/app/apikey))

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/wrlakshan/Google-ADK.git
cd Google-ADK
```

### 2. Create and activate a virtual environment

```bash
python -m venv venv
```

**Windows:**

```bash
source venv/Scripts/activate
```

**macOS / Linux:**

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment variables

Create a `.env` file in the project root and add your API key:

```env
GOOGLE_API_KEY=your_api_key_here
```

## Development

### Install a new package and save it

```bash
pip install <package-name>
pip freeze > requirements.txt
```

### Deactivate the virtual environment

```bash
deactivate
```

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file.
