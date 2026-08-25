# Contributing to Ignition 2026 🔥

Thank you for your interest in contributing! Follow these steps carefully.

## Getting Started

1. **Fork** this repository by clicking the Fork button on GitHub.
2. **Clone** your forked copy:
   ```bash
   git clone https://github.com/<your-username>/ignition-2026.git
   ```
3. **Navigate** into the project:
   ```bash
   cd ignition-2026
   ```

## Making Your Contribution

### Create a Branch

Always work on a new branch. Name it after yourself:

```bash
git checkout -b add-<your-name>
```

### Add Your File

Create a markdown file in the `doc/` folder with your name:

```bash
touch doc/<your-name>.md
```

Use this template inside your file:

```markdown
# Your Full Name

- **GitHub:** [username](https://github.com/username)
- **About:** Brief introduction
- **Skills:** Your technical skills
- **Fun Fact:** Something cool about you
```

### Commit Your Changes

```bash
git add doc/<your-name>.md
git commit -m "docs: add <your-name>.md"
```

### Push to Your Fork

```bash
git push origin add-<your-name>
```

### Open a Pull Request

1. Go to the original repository on GitHub
2. Click **"Compare & pull request"**
3. Select your branch
4. Fill in the PR title: `docs: add <your-name>`
5. Submit!

## ⚡ Auto-Merge

Your PR will be **automatically merged** if it meets these criteria:

| Rule | Description |
|------|-------------|
| ✅ Single file | Only **one** file should be changed |
| ✅ In `doc/` folder | File must be inside the `doc/` directory |
| ✅ Markdown only | File must have `.md` extension |
| ✅ New file | Only add new files, don't modify/delete existing ones |
| ✅ Not `example.md` | Don't modify the sample file |

If your PR doesn't meet these rules, the CI will comment with what needs to be fixed.

## ⚠️ Important Rules

- **DO NOT** push directly to `main`
- **DO NOT** modify other contributors' files
- **ONE** file per contributor in the `doc/` folder
- Follow the file naming convention: `<your-name>.md` (lowercase, hyphens for spaces)

---

Happy contributing! 🚀
