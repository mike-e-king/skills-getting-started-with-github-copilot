# Getting Started with GitHub Copilot 🤖

<div align="center">
  <img src="https://github.com/user-attachments/assets/4d22496d-850b-4785-aafe-11cba03cd5f2" alt="GitHub Copilot Logo" width="200"/>
</div>

## 📖 Overview

This repository is a **GitHub Skills** hands-on training exercise designed to help developers learn and practice using **GitHub Copilot**, an AI-powered coding assistant. Through interactive exercises, you'll learn how to leverage Copilot to write code faster, increase productivity, and focus more on problem-solving.

## 🎯 What You'll Learn

This exercise teaches you how to use various GitHub Copilot features:

- **⚡ Inline Suggestions**: Get AI-powered code completions as you type
- **💬 Ask Mode**: Ask questions about your codebase and coding concepts
- **✏️ Edit Mode**: Make code edits across multiple files with AI assistance
- **🤖 Agent Mode**: Perform autonomous edits across your project
- **💭 Inline Chat**: Get targeted help on specific code blocks

## 🏫 The Sample Application

The training uses a **Mergington High School Management System** - a FastAPI web application that allows students to:
- View available extracurricular activities (Chess Club, Programming Class, Sports Teams, Drama Club, etc.)
- Sign up for activities
- Unregister from activities

This realistic application provides a practical context for learning Copilot features through bug fixes, feature additions, and code improvements.

## 🚀 Getting Started

### Prerequisites
- GitHub account with GitHub Copilot access
- Basic familiarity with Python

### Quick Start

1. **Start a Codespace**: Open this repository in a GitHub Codespace with a pre-configured development environment
2. **Follow the Exercises**: Complete the step-by-step activities guided by automated feedback
3. **Practice with Copilot**: Use different Copilot modes to fix bugs, add features, and generate code

### Running the Application

```bash
# Install dependencies
pip install -r requirements.txt

# Run the application
uvicorn src.app:app --reload --port 8000

# Run tests
pytest
```

Visit `http://localhost:8000` to see the application in action.

## 📚 Exercise Structure

The training includes multiple hands-on activities:

1. **Hello Copilot**: Get familiar with the project and run it
2. **Fix Bugs**: Use Copilot to identify and fix registration bugs
3. **Generate Data**: Let Copilot create sample test data
4. **Code Navigation**: Use Copilot to explore and understand codebases
5. **Advanced Features**: Learn Edit Mode, Agent Mode, and more

## 🛠️ Tech Stack

- **Backend**: FastAPI (Python)
- **Testing**: pytest
- **Development**: GitHub Codespaces, VS Code
- **AI Assistant**: GitHub Copilot

## 📁 Repository Structure

```
.
├── src/
│   ├── app.py          # Main FastAPI application
│   └── static/         # Frontend assets
├── tests/
│   └── test_app.py     # Application tests
├── .github/
│   ├── workflows/      # Automated exercise workflows
│   └── steps/          # Exercise instructions
└── requirements.txt    # Python dependencies
```

## 🎓 Learning Resources

- [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- [GitHub Copilot Features](https://docs.github.com/en/copilot/about-github-copilot/github-copilot-features)
- [More GitHub Skills Courses](https://learn.github.com/skills)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

### 🌟 Complete the Exercise 🌟

Ready to accelerate your development with AI? Start the interactive training now!

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/mike-e-king/skills-getting-started-with-github-copilot?quickstart=1)

*Part of [GitHub Skills](https://learn.github.com/skills) - Learn by doing*

</div>

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

