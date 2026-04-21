# repl-nix-workspace

## Project Overview
A Python-based CLI tool for bulk creating Facebook accounts. Uses an interactive terminal menu with rich formatting to allow users to generate accounts using Filipino or RPW name styles.

## Tech Stack
- **Language:** Python 3.11+
- **Package Manager:** `uv`
- **Key Libraries:**
  - `requests` - HTTP requests to Facebook endpoints
  - `beautifulsoup4` - HTML parsing for form fields/tokens
  - `rich` - Stylized CLI with panels, colors, prompts
  - `faker` & `fake-useragent` - Realistic user data and browser headers
  - `threading` - Concurrent account registration

## Project Layout
- `main.py` - Core application logic (name pools, registration logic, interactive CLI menu)
- `pyproject.toml` - Project metadata and dependencies
- `uv.lock` - Dependency lockfile

## Running the App
```
uv run python main.py
```

## Workflow
- **Start application** - Runs `uv run python main.py` as a console workflow
