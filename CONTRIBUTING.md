---
# 🤝 Contributing to Bulk File Organizer

Hey there, fellow builder!
Thanks for your interest in contributing to **Bulk File Organizer** — the neat freak of the digital world 💫
---

## 🧑‍💻 Setting Up Your Dev Environment

1. **Fork** this repository
2. **Clone** your fork locally

   ```bash
   git clone https://github.com/YOUR-USERNAME/bulk-file-organizer.git
   cd bulk-file-organizer

   ```

3. **Create a virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # macOS/Linux
   venv\Scripts\activate     # Windows
   ```

4. **Install dependencies**

   ```bash
   pip install -e .[dev]
   ```

---

## 🧩 Code Structure

| File           | Purpose                                        |
| -------------- | ---------------------------------------------- |
| `cli.py`       | Command-line interface logic                   |
| `scanner.py`   | Scans directories and yields files             |
| `mapper.py`    | Maps file extensions to folder categories      |
| `organizer.py` | Handles moving or simulating file organization |

---

## 🌈 Coding Style

- Follow **PEP8** guidelines
- Use **Rich** for CLI output (keep it colorful but consistent)
- Avoid hardcoding — use constants or configs
- Write docstrings and meaningful commit messages
- Run tests before pushing:

  ```bash
  pytest
  ```

---

## 🧪 Submitting Changes

1. Create a new branch for your feature/fix:

   ```bash
   git checkout -b feat/amazing-idea
   ```

2. Commit your changes:

   ```bash
   git commit -m "✨ Added amazing idea to improve CLI"
   ```

3. Push to your fork and open a pull request:

   ```bash
   git push origin feat/amazing-idea
   ```

---

## 🪄 Need Help?

Feel free to open a discussion or issue on GitHub.
We believe every contribution — even a typo fix — adds value 💪

---

> Let’s keep it tidy 🧹
> — Team Bulk File Organizer

---
