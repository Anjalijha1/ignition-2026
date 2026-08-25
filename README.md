# 🔥 Ignition 2026

Welcome to **Ignition 2026** — the starting point for collaborative open-source contributions!

## 🚀 What is this?

This is a practice repository designed for contributors to learn the **fork → clone → branch → PR** workflow. Everyone adds their own `name.md` file to the `doc/` folder and raises a Pull Request.

> **✨ Bonus:** PRs that follow the rules are **automatically merged** via our CI pipeline!

---

## 📋 How to Contribute

### Step 1: Fork this Repository
Click the **Fork** button at the top-right of this page to create your own copy.

### Step 2: Clone your Fork
```bash
git clone https://github.com/<your-username>/ignition-2026.git
cd ignition-2026
```

### Step 3: Create a New Branch
Create a branch with your name:
```bash
git checkout -b add-<your-name>
```
> Example: `git checkout -b add-rahul`

### Step 4: Add Your File
Create a new file inside the `doc/` folder named `<your-name>.md`:

```bash
# Create your file
touch doc/<your-name>.md
```

Then edit the file and add the following content:

```markdown
# Your Name

- **GitHub:** [your-username](https://github.com/your-username)
- **About:** A short intro about yourself
- **Skills:** Your tech skills
- **Fun Fact:** Something interesting about you!
```

### Step 5: Commit and Push
```bash
git add .
git commit -m "docs: add <your-name>.md"
git push origin add-<your-name>
```

### Step 6: Create a Pull Request
1. Go to your forked repository on GitHub
2. Click **"Compare & pull request"**
3. Set the base branch to `main`
4. Add a meaningful title and description
5. Submit the PR! 🎉

> ✅ If your PR only adds a `.md` file in the `doc/` folder, it will be **automatically merged**!

---

## 📁 Project Structure

```
ignition-2026/
├── .github/
│   └── workflows/
│       └── auto-merge.yml    ← CI pipeline for auto-merge
├── README.md
├── CONTRIBUTING.md
├── LICENSE
└── doc/
    └── example.md            ← sample file for reference
```

---

## 📜 Rules

1. **One file per person** — Add only your own `name.md` file in the `doc/` folder
2. **Use your own branch** — Never push directly to `main`
3. **Follow the template** — Use the format shown above
4. **Only `.md` files** — The CI will reject non-markdown files
5. **Only in `doc/` folder** — Don't modify files outside `doc/`
6. **Be respectful** — This is a collaborative space

---

## ⚙️ CI Pipeline

This repo uses **GitHub Actions** to automatically:
- ✅ Validate that the PR only adds `.md` files inside `doc/`
- ✅ Auto-approve valid PRs
- ✅ Auto-merge valid PRs into `main`

If your PR modifies files outside `doc/` or adds non-markdown files, it will be **rejected with a comment**.

---

## 🤝 Contributors

Thanks to everyone who has contributed! Your name will appear here once your PR is merged.

<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

**Made with ❤️ for learning Git & GitHub collaboration**
