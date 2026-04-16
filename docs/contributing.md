# Contributing Guidelines

## Getting Started

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Write or update tests
5. Submit a pull request

## Code Standards

### Python Style Guide
- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/)
- Use type hints where applicable
- Maximum line length: 100 characters

### Naming Conventions
- Functions and variables: `snake_case`
- Classes: `PascalCase`
- Constants: `UPPER_SNAKE_CASE`
- Private attributes: `_leading_underscore`

## Testing Requirements

- Write tests for all new features
- Maintain test coverage above 80%
- Use `pytest` as test framework
- Place tests in `tests/` directory with `test_*.py` naming

## Security Requirements

1. **Never commit secrets**:
   - No hardcoded passwords or API keys
   - No private credentials in repository
   - Use environment variables for configuration

2. **Use `.env` for local development**:
   - Create `.env.example` with placeholders
   - Add `.env` to `.gitignore`
   - Document all required variables

3. **Dependency Security**:
   - Keep dependencies updated
   - Use `pip audit` to check for vulnerabilities
   - Pin versions in `requirements.txt`

## Commit Messages

Use descriptive commit messages:

```
Short summary (50 chars max)

Detailed explanation of changes if needed.
Explain why, not just what.

- Bullet points for multiple changes
- Use present tense

Fixes #issue-number (if applicable)

Co-authored-by: Your Name <your.email@example.com>
```

## Pull Request Process

1. Update documentation if needed
2. Include issue/feature number in PR title
3. Add description of changes
4. Link related issues
5. Request review from maintainers
6. Address review comments
7. Squash commits if requested

## Documentation

- Update `README.md` for any changes to usage
- Add docstrings to all functions and classes
- Include examples in documentation
- Document configuration options

## Reporting Bugs

When reporting bugs, include:
- Python version and OS
- Steps to reproduce
- Expected behavior
- Actual behavior
- Error messages/logs
- Environment variables used

## License

By contributing, you agree that your contributions will be licensed under the same license as the project.

---

Thank you for contributing!
