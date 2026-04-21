# GitHub Review

AI-powered code review system for GitHub using GitHub Actions.

## Quick Start

### 1. Copy to your project

```bash
cp -r .github/ /path/to/your/project/
```

### 2. Add API Key (Optional - for advanced AI)

For better AI reviews, add OpenAI API key:
```bash
gh secret set OPENAI_API_KEY
```

### 3. That's it!

Every PR will automatically get an AI review.

## Features

- Automatic code review on PRs
- Supports multiple languages
- Security vulnerability detection
- Code quality suggestions
- Free to use (no API key needed for basic review)

## Configuration

Edit `.github/workflows/ai-review.yml` to customize:
- Trigger on push/PR
- Review depth (files to review)
- AI model (if using API)
