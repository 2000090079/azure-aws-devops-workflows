<p align="center">
  <img src="https://avatars.githubusercontent.com/u/2000090079?s=100" />
</p>

# My Starter Workflows

This repository contains a collection of reusable GitHub Actions workflows for CI/CD, automation, linting, DevOps tasks, and basic project setup.  
These workflows can be used as templates to quickly set up automation for any project.

---

## 📂 Repository Structure

- **ci/** – Continuous Integration workflows (build, test, lint, format)
- **automation/** – Automated tasks (labeling, greetings, stale issues, auto-assign)
- **deployments/** – Workflows for building or publishing artifacts
- **code-scanning/** – Templates for CodeQL and security scanning
- **pages/** – Workflows for GitHub Pages deployments
- **icons/** – SVG icons used in workflow templates

Each workflow has:
- A `.yml` workflow file
- A matching `.properties.json` file containing metadata shown in the GitHub UI

Example:

---

## 🛠 How to Use These Workflows

1. Go to any GitHub repository  
2. Open the **Actions** tab  
3. Select **New workflow**  
4. Choose a workflow from this collection  
5. Customize the file as needed and commit

---

## 🧰 Variables You Can Use

These placeholders are automatically replaced by GitHub:

- **`$default-branch`** → your repo’s default branch (e.g., `main`)
- **`$protected-branches`** → branches that are protected
- **`$cron-daily`** → a random valid time for daily jobs

---

## 📝 Categories Used in Metadata

- continuous-integration  
- deployment  
- testing  
- code-quality  
- dependency-management  
- automation  
- monitoring  
- utilities  

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to submit improvements, fixes, or new workflow templates.

---

## 🔐 Security

If you find a security issue related to a workflow, please open an issue in this repository.

---

## 📄 License

This project is licensed under the MIT License.  
See the `LICENSE` file for details.
