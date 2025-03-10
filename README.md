# LLMChecker

<!-- ![LLMChecker Banner](https://via.placeholder.com/800x200?text=LLMChecker) -->

> **Can I Run This LLM?** - Find out if your computer can run popular Large Language Models locally

## 🚀 Overview

LLMChecker is an open-source tool that helps you determine whether your hardware is capable of running various Large Language Models locally. Simply input your system specifications, select an LLM model, and get an instant compatibility check along with alternative model suggestions.

## ✨ Features

- **Hardware Compatibility Check**: Check if your system meets the RAM and VRAM requirements for specific LLM models
- **Alternative Suggestions**: Get recommendations for similar models that will run on your hardware
- **Comprehensive Model Database**: Contains specifications for popular open-source LLMs
- **User-friendly Interface**: Simple and intuitive UI for easy compatibility checking

## 🖥️ Demo

<!-- ![LLMChecker Demo](https://via.placeholder.com/800x450?text=LLMChecker+Demo) -->

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/prodigyRahul/LLMChecker.git
cd LLMChecker

# Install dependencies
pnpm install

# Set up environment variables
cp .env.example .env
# Edit .env with your specific configuration

# Start the development server
pnpm run dev
```

## 📋 Usage

1. Select your computer type (Mac/PC)
2. Enter your GPU model (e.g., NVIDIA RTX 4090)
3. Specify your available RAM (e.g., 32GB)
4. Choose an LLM model to check compatibility
5. View the results and alternative model suggestions

## 🔧 Development

### Project Structure

```
LLMChecker/
├── src/                 # Source code
├── public/              # Static assets
├── components/          # Reusable UI components
├── data/                # LLM specifications database
├── tests/               # Test files
└── ...
```

### Commands

```bash
# Install dependencies
pnpm install

# Start development server
pnpm run dev

# Build for production
pnpm run build

# Run tests
pnpm test

# Format code
pnpm run pretty
```

## 🏗️ Built With

<p align="center">
  <a href="https://nextjs.org/">
    <img src="https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  </a>
  <a href="https://reactjs.org/">
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  </a>
  <a href="https://www.prisma.io/">
    <img src="https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white" alt="Prisma" />
  </a>
  <a href="https://www.postgresql.org/">
    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  </a>
  <a href="https://tailwindcss.com/">
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  </a>
  <a href="https://ui.shadcn.com/">
    <img src="https://img.shields.io/badge/shadcn/ui-000000?style=for-the-badge&logo=shadcnui&logoColor=white" alt="shadcn/ui" />
  </a>
  <a href="https://www.docker.com/">
    <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  </a>
</p>

## 🤝 Contributing

We welcome contributions to LLMChecker! Here's how to contribute:

### Git Commit Conventions

All commit messages should follow this format:
```
<type>: <description>
```

Where `<type>` is one of:
- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Documentation changes
- **style**: Code style changes (formatting, missing semi-colons, etc)
- **refactor**: Code changes that neither fix a bug nor add a feature
- **perf**: Code changes that improve performance
- **test**: Adding or modifying tests
- **chore**: Changes to the build process or auxiliary tools

Examples:
```
feat: add support for apple silicon gpus
fix: correct ram calculation for windows systems
docs: update installation instructions
chore: update dependency versions
```

All commit messages should be lowercase and concise (ideally under 50 characters).

### Pull Request Process

1. Fork the repository
2. Create a new branch from the `development` branch:
   ```bash
   git checkout development
   git pull origin development
   git checkout -b feature/your-feature-name
   ```
3. Make your changes
4. Format the code:
   ```bash
   pnpm run pretty
   ```
5. Build the project to ensure everything works:
   ```bash
   pnpm run build
   ```
6. Commit your changes with a descriptive message following our commit conventions
7. Push your branch and create a Pull Request to the `development` branch
8. Wait for review and address any feedback

### Code Style

- Follow the existing code style
- Write clear commit messages
- Add tests for new features
- Update documentation as needed

## 🐛 Issues

Found a bug or have a feature request? We'd love to hear from you!

1. Check if the issue already exists in the [Issues](https://github.com/prodigyRahul/LLMChecker/issues) section
2. If not, [create a new issue](https://github.com/prodigyRahul/LLMChecker/issues/new)
3. Clearly describe the issue/feature with a descriptive title
4. For bugs, include steps to reproduce, expected behavior, and actual behavior
5. For feature requests, explain why this feature would be useful

## ⭐ Support

If you find this project useful, please consider giving it a star on GitHub! This helps others discover the project and motivates us to continue improving it.

[![Star this repo](https://img.shields.io/github/stars/prodigyRahul/LLMChecker?style=social)](https://github.com/prodigyRahul/LLMChecker)

## 👥 Contributors

<a href="https://github.com/prodigyRahul/LLMChecker/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=prodigyRahul/LLMChecker" />
</a>

## 📊 Project Roadmap

- [ ] Add more LLM models to the database
- [ ] Implement detailed hardware requirement breakdowns
- [ ] Add performance benchmark estimates
- [ ] Create model comparison features
- [ ] Support for mobile device compatibility checks

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Thanks to all the open-source LLM projects for their amazing work
- Special thanks to the contributors who have helped grow this project
- Inspired by "Can I Run It" tools for gaming

## 📬 Contact

- GitHub: [prodigyRahul](https://github.com/prodigyRahul)
- Twitter: [@_rahulimstry](https://x.com/_rahulmistry)

---

<p align="center">Made with ❤️ for the AI community</p> 