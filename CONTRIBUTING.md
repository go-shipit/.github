# Contributing to GoShip

First off, thank you for considering contributing! 🚀  
These guidelines will help you submit code, report bugs, and request features in a way that keeps the project organized and maintainable.

---

## How to Contribute

### 1. Reporting Bugs

- Please use the [bug report template](.github/ISSUE_TEMPLATE/bug_report.md) when opening issues.
- Include clear steps to reproduce the bug and any relevant error messages.
- Include your environment details (OS, Go version, package version).

### 2. Requesting Features

- Please use the [feature request template](.github/ISSUE_TEMPLATE/feature_request.md).
- Clearly describe the problem you want solved and your proposed solution.

### 3. Pull Requests

1. **Fork the repository and create your branch from `main`:**
   ```bash
   git checkout -b feature/my-feature
   ```
2. **Make your changes and ensure your code follows Go formatting (`gofmt`) and style guidelines.**
3. **Write tests for new functionality or bug fixes.**
4. **Run all tests to ensure nothing breaks:**
   ```bash
   go test ./...
   ```
5. **Submit a pull request using the PR template.**

---

## Code Guidelines

- Use Go modules and follow standard Go project structure.
- Write clean, idiomatic Go code.
- Keep functions small and focused.
- Add comments for exported functions and any complex logic.
- Follow the existing logging, error handling, and testing patterns in the repo.

---

## Commit Messages

- Use clear, concise commit messages.
- Include the type of change: `feat`, `fix`, `chore`, `docs`, etc.

**Examples:**
```
feat(logger): add structured JSON logging
fix(parser): handle empty input without panic
```

---

## Code Reviews

- Every PR will be reviewed before merging.
- Maintain good test coverage and clear commit history.
- Respond promptly to review comments.

---

## Additional Resources

- [Go Official Documentation](https://golang.org/doc/)
- [Effective Go](https://golang.org/doc/effective_go.html)
- [GitHub Flow Guide](https://guides.github.com/introduction/flow/)

---

Thank you for contributing! 💛 Together, we make GoShip better for everyone.
