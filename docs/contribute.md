# Contributing to LUG-Mino

Thank you for your interest in contributing to the LUG-Mino repository.

This project aims to document Linux User Group (LUG) sessions held in MinoDasht by collecting and maintaining high-quality educational content, such as LaTeX-based PDFs, code examples, terminal instructions, and more.

This guide explains how to contribute effectively and in a structured, consistent way — even if you’re new to Git, GitHub, or contributing to open-source projects.

---

## 📌 Who Can Contribute?

Anyone. You do **not** need to be an expert in Linux, Git, or LaTeX. You’re welcome to:
- Fix typos or grammar
- Improve explanations
- Add examples or illustrations
- Suggest changes to structure or flow
- Add entirely new sessions or sections (with discussion)

All contributions are appreciated!

## 🛠 How to Contribute

1. **Fork this repository.**  
   Create your own copy using the "Fork" button on GitHub.

2. **Clone your fork locally.**
   ```bash
   git clone https://github.com/YOUR_USERNAME/LUG-Mino.git
   cd LUG-Mino
   ```

3. **Create a new branch for your changes.**

   ```bash
   git checkout -b fix-typos-session-01
   ```

4. **Make your changes.**

   * Follow the folder structure.
   * Keep LaTeX formatting consistent (`UTF-8`, no hard tabs, use `\section`, `\subsection`, etc.).
   * For code: keep it minimal, documented, and relevant to session topic.
   * If you add images, use `.png` or `.svg` and place them in the correct `assets/` folder.

5. **Use semantic commit messages.** See below.

6. **Push to your fork.**

   ```bash
   git push origin fix-typos-session-01
   ```

7. **Open a Pull Request.**

   * Go to your fork on GitHub.
   * Click “Compare & pull request”.
   * Describe what you changed and why.

---

## Semantic Commit Messages

We use **semantic commit messages** to keep history clean and meaningful. This means your commit messages should follow this structure:

```
<type>(scope): short summary
```

### Examples:

* `docs(session-01): fix typo in section title`
* `feat(session-02): add example script for user management`
* `refactor(template): clean up LaTeX spacing and comments`

### Allowed types:

| Type       | Meaning                                    |
| ---------- | ------------------------------------------ |
| `feat`     | New content or functionality               |
| `fix`      | Bugfix or error correction                 |
| `docs`     | Documentation or text updates              |
| `style`    | Formatting changes (no content change)     |
| `refactor` | Internal restructuring                     |
| `test`     | Add or modify examples/test cases          |
| `chore`    | Other tasks (e.g., file renaming, cleanup) |

> ⚠️ Try to keep commits small and focused. One commit = one logical change.

---

## LaTeX Guidelines

* Use `UTF-8` encoding.
* Stick to standard LaTeX commands (`\section`, `\subsection`, etc.).
* Use `lmodern` or `cmr` fonts unless session needs a specific style.
* If using external packages, add them to the session's `.tex` header with clear comments.
* If you add diagrams using TikZ or similar tools, document them well.

---

## Review Process

All pull requests will be reviewed by the repository maintainer. The review may include:

* Suggestions for rewording or clarity
* Requests to split large changes into smaller commits
* Formatting corrections

We aim to keep the tone consistent and the quality high, especially for educational content.

---

## License

All contributions are licensed under the repository's main license:

* **Content:** [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)
* **Code snippets:** [MIT License](https://opensource.org/licenses/MIT)

By contributing, you agree that your changes will be published under these licenses.

---

## Thank You

Your time and effort help grow this open educational project. Whether it’s a typo fix or a whole new section, your contribution is valuable.

If you have any questions before contributing, feel free to open an issue or reach out directly.