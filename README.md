# AI BrainBox

AI BrainBox is a cutting-edge web application built with Next.js, React, and TypeScript, providing an interactive, AI-powered coding environment. It integrates the Ollama AI model for chat-based assistance, code analysis, and automated code review—offering features similar to CodeSandbox, but powered by modern AI.

## Features

- **Interactive Chatbox:** Get instant answers, explanations, and discussions about your code with Ollama AI.
- **Code Analyzer:** Review and analyze code for bugs, improvements, and best practices.
- **Automated Code Review:** AI-driven suggestions and feedback to help you write better code.
- **Live Coding Playground:** Prototype and experiment with code in a browser-based IDE.
- **Dashboard:** Manage your coding sessions and projects with a centralized dashboard.
- **Authentication:** Secure login and access management.
- **Modular Architecture:** Easily extend features via well-organized modules.
- **Seamless AI Integration:** All AI features are powered by Ollama, ensuring fast and reliable responses.

## Project Structure

Here's an overview of the main directories and their purpose:

```
AI BRAINBOX/
│
├── .next/                  # Next.js build output
├── app/                    # Main app source
│   ├── (auth)/             # Authentication routes and logic
│   ├── (root)/             # Root-level configuration
│   ├── api/                # API routes
│   ├── dashboard/          # Dashboard UI
│   ├── playground/         # Coding playground
│   ├── favicon.ico         # Favicon
│   ├── globals.css         # Global styles
│   └── layout.tsx          # App layout
│
├── components/             # React components
│   ├── providers/          # Context providers
│   ├── ui/                 # UI elements
│   └── hooks/              # Custom React hooks
│
├── lib/                    # Utility libraries
├── modules/                # Modular features
│   ├── ai-chat/            # AI-based chat system
│   └── auth/               # Authentication module
│   ├── dashboard/          # Dashboard implementation
│   ├── home/               # Home page
│   ├── playground/         # Playground implementation
│   ├── webcontainers/      # Webcontainers for running code in-browser
│
├── node_modules/           # npm packages
├── output/                 # Build/output files
├── prisma/                 # Prisma ORM files (if using a database)
├── public/                 # Static assets
├── vibecode-starters/      # Starter templates for coding
│
├── .env                    # Environment variables
```

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm or yarn
- [Ollama AI](https://ollama.com/) installed and running locally or accessible via API

### Installation

```bash
git clone https://github.com/<your-username>/ai-brainbox.git
cd ai-brainbox
npm install
```

### Running the App

```bash
npm run dev
```

The app will be available at [http://localhost:3000](http://localhost:3000).

### Ollama Integration

Make sure your Ollama AI server is running and accessible. Configure the Ollama API endpoint in your environment variables or project settings as needed.

## Usage

- **Chatbox:** Enter questions or code snippets in the chatbox to receive AI-powered answers and code reviews.
- **Code Editor / Playground:** Write and edit your code in the browser. Use the "Analyze" and "Review" buttons to get instant feedback from Ollama AI.
- **Dashboard:** Organize your coding sessions, manage files, and track your work.
- **Save & Share:** Save your projects and share links with collaborators.

## Technologies Used

- Next.js
- React
- TypeScript
- Ollama AI (Chat, Code Analysis, Review)
- Prisma (optional, for database integration)
- CSS/Styled Components

## Contributing

Contributions are welcome! Please open issues or pull requests for any features, bug fixes, or suggestions.

## License

This project is licensed under the MIT License.

---

*AI BrainBox: Your AI-powered coding companion!*
