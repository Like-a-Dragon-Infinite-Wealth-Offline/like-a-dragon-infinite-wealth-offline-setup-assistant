# Contributing to Like a Dragon: Infinite Wealth Offline Setup Assistant

🎮 Thank you for your interest in contributing to our project! We welcome all types of contributions that help make offline gaming more accessible to everyone.

## 🤝 Ways to Contribute

### 🐛 Bug Reports
Found an issue? Help us improve by reporting bugs:
- Check existing [Issues](https://github.com/Like-a-Dragon-Infinite-Wealth-Offline/like-a-dragon-infinite-wealth-offline-setup-assistant/issues) first
- Use our [Bug Report Template](.github/ISSUE_TEMPLATE/bug_report.md)
- Include system information, error messages, and steps to reproduce
- Attach screenshots or video recordings when possible

### 💡 Feature Requests
Have ideas for new features or improvements?
- Use our [Feature Request Template](.github/ISSUE_TEMPLATE/feature_request.md)
- Explain the problem your feature would solve
- Describe your proposed solution
- Consider alternative approaches

### 🔧 Code Contributions
Ready to dive into the code?
- Fork the repository
- Create a feature branch (`git checkout -b feature/amazing-feature`)
- Make your changes with clear, descriptive commits
- Follow our coding standards (see below)
- Test your changes thoroughly
- Submit a Pull Request using our template

### 🌍 Translations
Help make the setup assistant accessible in more languages:
- Check existing translation files in `/locales/`
- Create or update translation files
- Ensure translations are culturally appropriate
- Test the interface with your translations

### 📝 Documentation
Improve our guides and documentation:
- Fix typos or unclear instructions
- Add missing information
- Create tutorials or examples
- Improve code comments

## 🏗️ Development Setup

### Prerequisites
- Node.js 16+ or Python 3.8+
- Git
- Code editor with linting support

### Getting Started
```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/like-a-dragon-infinite-wealth-offline-setup-assistant.git
cd like-a-dragon-infinite-wealth-offline-setup-assistant

# Install dependencies
npm install
# or
pip install -r requirements.txt

# Run development setup
npm run dev
# or
python setup.py develop
```

### Running Tests
```bash
# Run all tests
npm test
# or
python -m pytest

# Run specific test suite
npm run test:unit
npm run test:integration

# Run tests with coverage
npm run test:coverage
```

## 📋 Coding Standards

### Code Style
- Use consistent indentation (2 spaces for JS/HTML, 4 for Python)
- Follow language-specific conventions (ESLint for JS, PEP8 for Python)
- Write descriptive variable and function names
- Add comments for complex logic

### Commit Messages
Follow the conventional commit format:
```
type(scope): description

[optional body]

[optional footer]
```

Types:
- `feat`: New features
- `fix`: Bug fixes
- `docs`: Documentation changes
- `style`: Code style changes
- `refactor`: Code refactoring
- `test`: Test additions/modifications
- `chore`: Maintenance tasks

Examples:
- `feat(installer): add support for custom installation paths`
- `fix(ui): resolve display issues on high-DPI screens`
- `docs(readme): update installation instructions`

### Pull Request Guidelines
- Use our [Pull Request Template](.github/PULL_REQUEST_TEMPLATE.md)
- Link related issues using keywords (fixes #123, closes #456)
- Include screenshots for UI changes
- Write clear descriptions of changes and their impact
- Ensure all tests pass
- Keep PRs focused and atomic

## 🎯 Project Priorities

### Current Focus Areas
1. **Cross-Platform Compatibility**: Ensuring the setup assistant works on all platforms
2. **User Experience**: Making installation as simple as possible
3. **Performance**: Optimizing setup speed and resource usage
4. **Documentation**: Clear guides for all user types
5. **Localization**: Supporting multiple languages

### Areas Needing Help
- [ ] macOS and Linux testing
- [ ] UI/UX improvements
- [ ] Additional language translations
- [ ] Performance optimization
- [ ] Automated testing coverage

## 🚀 Release Process

### Version Numbering
We follow [Semantic Versioning](https://semver.org/):
- `MAJOR.MINOR.PATCH` (e.g., 1.2.3)
- Major: Breaking changes
- Minor: New features (backward compatible)
- Patch: Bug fixes (backward compatible)

### Release Branches
- `main`: Stable releases
- `develop`: Integration branch for new features
- `feature/*`: Individual feature development
- `hotfix/*`: Critical bug fixes

## 🎖️ Recognition

### Contributors
All contributors are recognized in:
- GitHub contributors list
- Release notes
- Special mentions for significant contributions

### Maintainer Guidelines
For project maintainers:
- Review PRs promptly and constructively
- Provide helpful feedback
- Merge when ready (all checks pass, approved)
- Update project documentation
- Communicate changes clearly

## 📞 Getting Help

### Community Support
- 💬 [Discord Community](https://discord.gg/dragon-infinite-wealth)
- 📧 Email: contributors@like-a-dragon-offline.com
- 🐛 [GitHub Issues](https://github.com/Like-a-Dragon-Infinite-Wealth-Offline/like-a-dragon-infinite-wealth-offline-setup-assistant/issues)

### Mentorship
New to open source? We're here to help!
- Look for issues labeled `good first issue`
- Join our Discord for real-time help
- Don't hesitate to ask questions

## 📜 Code of Conduct

This project follows our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold these standards and help create a welcoming environment for everyone.

## 🎮 Gaming Community Values

As a gaming-focused project, we especially value:
- **Inclusivity**: Gaming is for everyone, regardless of background
- **Accessibility**: Making games playable for users with different needs
- **Preservation**: Keeping gaming history and culture alive
- **Freedom**: Supporting user choice in how they play games
- **Community**: Building connections through shared gaming experiences

---

Thank you for contributing to making offline gaming more accessible! Every contribution, no matter how small, helps improve the experience for gamers everywhere. 🎮✨ 