# Contributing to Student IoT Showcase

Thank you for your interest in sharing your IoT project! This guide explains how any **BSU Malvar student** can add their project to the showcase.

---

## Prerequisites

- A [GitHub account](https://github.com/join)
- An IoT project hosted in a **public** GitHub repository
- Basic knowledge of Git (fork, commit, pull request)

---

## Step-by-Step Guide

### 1. Fork the Repository

Click the **Fork** button at the top-right of this repository's GitHub page. This creates your own copy of the showcase under your GitHub account.

### 2. Clone Your Fork

```bash
git clone https://github.com/<your-username>/Student-IoT-Showcase.git
cd Student-IoT-Showcase
```

### 3. Create a Branch

Create a descriptive branch for your addition:

```bash
git checkout -b add-<your-project-name>
```

### 4. Add Your Project to the Table

Open `README.md` and find the **Project Showcase** table:

```markdown
| # | Project Name | Author | Description | GitHub Link |
|---|--------------|--------|-------------|-------------|
```

Add a new row at the **bottom** of the table following this format:

```markdown
| <next number> | Your Project Name | Your Full Name | A short one-line description of your project | [View on GitHub](https://github.com/your-username/your-repo) |
```

**Example:**

```markdown
| 2 | Smart Plant Watering System | Juan dela Cruz | Automatically waters plants based on soil moisture sensor readings using an ESP32. | [View on GitHub](https://github.com/jdelacruz/smart-plant-watering) |
```

**Guidelines:**

- Keep the description to **one sentence** (≤ 120 characters).
- Make sure your project repository is **public** so others can view it.
- Use your **real full name** as the author.
- Do **not** edit other students' rows.

### 5. Commit Your Changes

```bash
git add README.md
git commit -m "Add <Your Project Name> by <Your Name>"
```

### 6. Push Your Branch

```bash
git push origin add-<your-project-name>
```

### 7. Open a Pull Request

1. Go to your fork on GitHub.
2. Click **Compare & pull request**.
3. Fill in the PR title: `Add <Your Project Name> by <Your Name>`.
4. Optionally add a short description in the body.
5. Click **Create pull request**.

A maintainer will review your submission. If everything looks good, it will be merged into the main showcase!

---

## Code of Conduct

- Be respectful and supportive of your fellow students.
- Only submit projects you own or have explicit permission to showcase.
- Do not submit projects that contain harmful, offensive, or plagiarized content.

---

## License

By contributing to this repository, you agree that your contributions will be licensed under the **GNU General Public License v3.0 (GPLv3)**. See [LICENSE](LICENSE) for details.
