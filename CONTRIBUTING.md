# Contributing to Compliment My Pet

Thank you for your interest in contributing! This document provides guidelines for contributing to this Copilot Studio agent project.

## 🎯 Ways to Contribute

### 1. Improving the Agent
- Enhance conversation topics
- Add new compliment variations
- Improve response quality
- Add support for more pet types

### 2. Documentation
- Add more screenshots
- Improve installation instructions
- Create video tutorials
- Translate documentation

### 3. Bug Fixes
- Report issues with import/export
- Fix conversation flow problems
- Address edge cases

## 📝 Contribution Workflow

1. **Fork the Repository**
   ```bash
   # Click 'Fork' on GitHub, then clone your fork
   git clone https://github.com/YOUR-USERNAME/compliment-my-pet.git
   cd compliment-my-pet
   ```

2. **Create a Branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-fix-name
   ```

3. **Make Your Changes**
   - Update the Copilot Studio agent
   - Export the new version
   - Update documentation
   - Add screenshots if needed

4. **Export Updated Agent**
   - Follow the export instructions in `export/README.md`
   - Name the file with version number
   - Update the version history

5. **Test Your Changes**
   - Import the agent in a test environment
   - Verify all conversation flows work
   - Test with various pet types
   - Ensure no errors occur

6. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "feat: Add support for exotic pets"
   # or
   git commit -m "fix: Correct conversation flow for birds"
   ```

7. **Push and Create Pull Request**
   ```bash
   git push origin feature/your-feature-name
   ```
   Then open a Pull Request on GitHub

## 💬 Commit Message Guidelines

Use clear, descriptive commit messages:

- `feat:` - New features
- `fix:` - Bug fixes
- `docs:` - Documentation changes
- `style:` - Formatting, missing semicolons, etc.
- `refactor:` - Code restructuring
- `test:` - Adding tests
- `chore:` - Maintenance tasks

Examples:
- `feat: Add reptile-specific compliments`
- `fix: Resolve image upload issue`
- `docs: Add video tutorial link`

## 📸 Screenshot Guidelines

When adding screenshots:
- Use high resolution (at least 1080p)
- Save as PNG for UI, JPG for photos
- Remove personal information
- Optimize file size
- Add descriptive filenames
- Update README.md references

## 🧪 Testing Checklist

Before submitting a PR, verify:
- [ ] Agent imports successfully from the export file
- [ ] All conversation topics work as expected
- [ ] No errors in Copilot Studio
- [ ] Documentation is updated
- [ ] Screenshots are current
- [ ] No sensitive data in export
- [ ] Version number updated

## 🤝 Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- Help others learn and grow
- Keep discussions focused and professional

## 📋 Pull Request Template

When creating a PR, include:

```markdown
## Description
Brief description of changes

## Type of Change
- [ ] New feature
- [ ] Bug fix
- [ ] Documentation update
- [ ] Agent enhancement

## Changes Made
- List specific changes
- Include any new topics or flows

## Testing
- Describe how you tested the changes
- Include test scenarios

## Screenshots
- Add any relevant screenshots

## Checklist
- [ ] Code follows project style
- [ ] Documentation updated
- [ ] Export file updated
- [ ] Screenshots added/updated
- [ ] Tested in Copilot Studio
```

## ❓ Questions?

If you have questions:
- Open an issue for discussion
- Check existing issues and PRs
- Review the main README.md

## 🌟 Recognition

Contributors will be recognized in the project. Thank you for making pet compliments better! 🐾

