# Contributing to Browser Startpage

First off, thank you for considering contributing to Browser Startpage! It's people like you that make this project better for everyone.

## Code of Conduct

This project and everyone participating in it is governed by our commitment to providing a welcoming and inspiring community for all. Please be respectful and constructive in your interactions.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the existing issues to avoid duplicates. When you create a bug report, include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples** to demonstrate the steps
- **Describe the behavior you observed** and what you expected to see
- **Include screenshots or GIFs** if applicable
- **Specify your browser and OS version**

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion:

- **Use a clear and descriptive title**
- **Provide a detailed description** of the suggested enhancement
- **Explain why this enhancement would be useful** to most users
- **Include mockups or examples** if applicable

### Pull Requests

1. **Fork the repository** and create your branch from `main`
2. **Make your changes** with clear, concise commits
3. **Test thoroughly** across different browsers
4. **Update documentation** if needed
5. **Follow the coding style** of the project
6. **Submit a pull request**

## Development Guidelines

### Code Style

- Use **2 spaces** for indentation
- Use **semantic HTML5** elements
- Keep **functions small and focused**
- Add **comments** for complex logic
- Use **meaningful variable names**

### JavaScript Guidelines

```javascript
// Good
function createCircularButtons() {
  if (buttonsCreated) return;
  // Implementation...
}

// Bad
function crtBtn() {
  if(bc)return
  // Implementation...
}
```

### CSS Guidelines

- Use **CSS custom properties** for theming
- Follow **mobile-first** approach
- Use **rem/em** for sizing (not px)
- Group related **properties together**

```css
/* Good */
.button {
  /* Layout */
  display: flex;
  align-items: center;

  /* Sizing */
  padding: 12px 24px;
  border-radius: 8px;

  /* Visual */
  background: var(--button-bg);
  color: var(--button-text);

  /* Animation */
  transition: all 0.3s ease;
}
```

### Commit Messages

Write clear, concise commit messages:

- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Documentation changes
- **style**: Code style changes (formatting, etc.)
- **refactor**: Code refactoring
- **test**: Adding tests
- **chore**: Maintenance tasks

Examples:
```
feat: add bookmark folder support
fix: modal not closing on mobile
docs: update installation instructions
style: improve button hover states
```

## Testing Checklist

Before submitting a PR, please verify:

- [ ] Code works in Chrome/Edge
- [ ] Code works in Firefox
- [ ] Code works in Safari (if possible)
- [ ] Responsive design works on mobile
- [ ] Light and dark modes both work
- [ ] localStorage persists correctly
- [ ] No console errors
- [ ] Code is properly formatted

## Project Structure

```
browser-startpage/
├── index.html          # Main application (HTML, CSS, JS all in one)
├── README.md           # Project documentation
├── LICENSE             # MIT License
├── CONTRIBUTING.md     # This file
└── assets/             # Screenshots and assets
```

## Questions?

Feel free to open an issue with the `question` label if you have any questions about contributing.

## Recognition

Contributors will be recognized in the README.md file. Thank you for your contributions!

---

**Happy coding!** 🚀
