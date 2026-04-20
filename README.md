# 🌍 Catalyze Camp Website

This repository contains the source code for the **Catalyze Camp** websites, an annual mission camp for high school graduates across Eastern Africa.

The project includes:

* The main Eastern Africa website
* Country-specific versions (e.g., Kenya)

---

## 🌐 Live Sites

* Main Site: https://catalyzecamp.com
* Kenya Site: https://ke.catalyzecamp.com

---

## 🧱 Project Structure

```id="s6x3y2"
catalyze-camp/
│
├── catalyzecamp.com/                # Eastern Africa main website
│   ├── index.html
│   ├── assets/
│   ├── styles/
│   └── scripts/
│
├── ke.catalyzecamp.com/                  # Kenya-specific website
│   ├── index.html
│   ├── assets/
│   ├── styles/
│   └── scripts/
│
└── README.md
```

---

## ⚙️ Tech Stack

* HTML
* CSS
* JavaScript
* Vercel (Hosting)

---

## 📦 Getting Started

### Clone the Repository

```bash id="c6l8qn"
git clone https://github.com/your-org/catalyze-camp.git
cd catalyze-camp
```

### Run Locally (VS Code Live Server)

1. Open the project in VS Code
2. Install the **Live Server** extension (if not already installed)
3. Navigate to either:

   * `catalyzecamp.com/index.html`
   * `ke.catalyzecamp.com/index.html`
4. Right-click the file and select **"Open with Live Server"**

---

## 🚀 Deployment

Each site is deployed separately using Vercel:

* `catalyzecamp.com` → catalyzecamp.com
* `ke.catalyzecamp.com` → ke.catalyzecamp.com

Deployment is connected to the `main` branch.

---

## 🤝 Contribution Guidelines

This is an internal codebase. Contributions are limited to approved team members.

### Workflow

1. Create a new branch from `main`:

   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Make your changes

3. Commit your work:

   ```bash
   git commit -m "feat: short description"
   ```

4. Push your branch:

   ```bash
   git push origin feature/your-feature-name
   ```

5. Open a Pull Request for review

---

### Branch Naming Convention

* `feature/feature-name`
* `fix/bug-name`
* `chore/task-name`
* `refactor/component-name`

---

### Code Guidelines

* Keep HTML clean and semantic
* Maintain consistent styling across pages
* Avoid duplication where possible
* Keep country-specific content isolated within its folder
* Use clear and consistent naming for files and folders

---

### Commit Message Format

```id="p3g7kf"
type: short description
```

Examples:

* `feat: add kenya hero section`
* `fix: resolve mobile navbar issue`
* `refactor: clean up scripts`

---

### Pull Request Checklist

* Code runs without errors
* Follows project structure
* Clear and meaningful commits
* UI changes include screenshots (if applicable)

---

## 🔒 Access & Security

* This repository is private and for internal use only
* Do not share access without authorization
* Do not commit sensitive information (API keys, tokens)

---

## 📄 License

Internal Use Only — All Rights Reserved