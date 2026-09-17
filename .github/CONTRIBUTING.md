# Contributing Guidelines

Thank you for your interest in contributing! Whether you are reporting a bug, proposing a new feature, or submitting a pull request, your contributions help keep our open-source tools reliable, performant, and clean.

Please review the following guidelines before submitting code.

---

## 🧭 Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md) in all community interactions.

---

## 💡 Ways to Contribute

1. **Reporting Bugs**: Check existing issues first. If new, submit a detailed report using the bug report template with a minimal reproduction.
2. **Feature Proposals**: Open an issue or discussion outlining the use case, motivation, and proposed API / design.
3. **Documentation**: Improving explanations, fixing typos, and providing clear examples are always appreciated.
4. **Code Submissions**: Fixing bugs, refactoring, or implementing agreed-upon features.

---

## 🛠️ Development & Contribution Workflow

### 1. Fork and Clone
Fork the repository to your own GitHub account, then clone it locally:
```bash
git clone [https://github.com/](https://github.com/)<your-username>/<repository-name>.git
cd <repository-name>
```

### 2. Branch Naming
Create a focused branch from the default branch (`main`):
```bash
# Format: <type>/<short-description>
git checkout -b fix/memory-leak
git checkout -b feat/add-dark-mode
git checkout -b docs/update-readme
```

### 3. Code Standards & Quality
- **Language Idioms**: Follow the official style guides, formatting, and lint rules standard for the project's language and framework.
- **Clean Architecture**: Keep functions focused, avoid unnecessary external dependencies, and ensure proper resource cleanup and lifecycle management.
- **Safety**: Write defensive code, handle errors and edge cases explicitly, and maintain thread safety where concurrency applies.

### 4. Testing
All changes altering logic or resolving bugs should be accompanied by tests:
- Execute existing unit and integration test suites.
- Ensure all tests pass without regressions before submitting.

### 5. Commit Standards
Follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:
```text
feat: add streaming support
fix: resolve null pointer exception during teardown
docs: clarify configuration parameters in readme
refactor: simplify event dispatcher logic
test: add regression test for concurrent requests
```

---

## 🚀 Submitting a Pull Request

1. Push your branch to your fork.
2. Open a Pull Request targeting the `main` branch.
3. Complete the PR template checklist.
4. Verify that all automated CI checks and workflows pass.

---

## ⚖️ License
By contributing, you agree that your contributions will be licensed under the project's [LICENSE](LICENSE).
