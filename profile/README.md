<div align="center">
  <img src="/api/placeholder/120/120" alt="FatDuck AI Logo" width="120" height="120"/>
  
  # FatDuck AI
  
  _Build intelligent AI agents with personality_

  [![Twitter Follow](https://img.shields.io/twitter/follow/fatduckai?style=social)](https://twitter.com/fatduckai)
  [![Discord](https://img.shields.io/discord/1234567890?label=discord&logo=discord&style=flat-square)](https://discord.gg/fatduckai)
</div>

## 🚀 Quick Start

```bash
# Create a new AI agent project
npx create-fatduckai-app my-agent

# Or install individual packages
npm install @fatduckai/ai @fatduckai/brain
```

## 📦 Core Packages

| Package | Description | Version |
|---------|------------|---------|
| [@fatduckai/core](https://github.com/fatduckai/ai-templates) | Core utilities and types for building AI agents | [![npm version](https://img.shields.io/npm/v/@fatduckai/core.svg)](https://www.npmjs.com/package/@fatduckai/core) |
| [@fatduckai/prompt-utils](https://github.com/fatduckai/prompt-utils) | Prompt builder and LLM integration tools | [![npm version](https://img.shields.io/npm/v/@fatduckai/prompt-utils.svg)](https://www.npmjs.com/package/@fatduckai/ai) |
| [@fatduckai/ai](https://github.com/fatduckai/ai) | Engine for creating agents | [![npm version](https://img.shields.io/npm/v/@fatduckai/ai.svg)](https://www.npmjs.com/package/@fatduckai/brain) |
| [@fatduckai/cli](https://github.com/fatduckai/ai-templates) | CLI tools for managing FatDuck AI projects | [![npm version](https://img.shields.io/npm/v/@fatduckai/cli.svg)](https://www.npmjs.com/package/@fatduckai/cli) |

## 🛠️ Tools & Templates

| Repository | Description |
|------------|-------------|
| [create-fatduckai-app](https://github.com/fatduckai/create-fatduckai-app) | Create AI agents with zero configuration |
| [fatduckai-templates](https://github.com/fatduckai/templates) | Official templates for different agent types |
| [fatduckai-examples](https://github.com/fatduckai/examples) | Example projects and implementations |

## 🌟 Features

- **Modular Architecture**: Use only what you need
- **Personality Engine**: Create agents with distinct personalities and behaviors
- **Platform Agnostic**: Deploy to Telegram, Twitter, Discord, or custom platforms
- **Token Efficient**: Smart token management and caching
- **Developer Friendly**: Strong TypeScript support and comprehensive documentation

## 📚 Documentation

Visit our [documentation](https://docs.fatduckai.com) to learn more about:
- Getting Started
- Core Concepts
- API Reference
- Examples & Tutorials
- Best Practices

## 🔧 Example Usage

```typescript
// Simple prompt building
import { PromptBuilder } from '@fatduckai/prompt-utils';

const prompt = new PromptBuilder(template)
  .withContext({ tone: 'friendly' })
  .build();

// Full agent with personality
import { CharacterEngine } from '@fatduckai/brain';
import { TelegramClient } from '@fatduckai/telegram';

const engine = new CharacterEngine({
  name: "HelperBot",
  personality: ["helpful", "friendly"],
  goals: ["assist_users"]
});

const agent = new TelegramClient({ engine });
```

## 🤝 Contributing

We love our contributors! Check out our [contribution guidelines](CONTRIBUTING.md) to get started.

Each repository has its own contribution requirements, but generally:

1. **Core Packages**: PRs welcome for bug fixes and features
2. **Templates**: Share your agent templates
3. **Examples**: Show off your implementations
4. **Documentation**: Help improve our docs

## 🏗️ Project Structure

```
fatduckai/
├── Core
│   ├── core/           # Base utilities and types
│   ├── prompt-utils/   # Prompt building and LLM tools
│   ├── ai/          # AI engine
│   └── cli/            # CLI tools
│
├── Tools
│   ├── create-fatduckai-app/  # Project scaffolding
│   ├── templates/             # Official templates
│   └── examples/              # Example projects
│
└── Community
    ├── community-templates/   # User-created templates
    └── awesome-fatduckai/     # Community resources
```

## 📜 License

All FatDuck AI packages are [MIT licensed](LICENSE).

## 💬 Community

- [Discord](https://discord.gg/fatduckai)
- [Twitter](https://twitter.com/fatduckai)
- [Blog](https://blog.fatduckai.com)

## 🙋 Getting Help

- 📚 [Documentation](https://docs.fatduckai.com)
- 💭 [Discord Community](https://discord.gg/fatduckai)
- 🐛 [Issue Tracker](https://github.com/fatduckai/core/issues)
- 📧 [Email Support](mailto:support@fatduckai.com)

---

<div align="center">
  <sub>Built with ❤️ by the FatDuck AI team and contributors</sub>
</div>
