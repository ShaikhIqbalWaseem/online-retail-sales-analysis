<h1>📄 CONTRIBUTING.md</h1>

<h2>👋 Welcome</h2>

Thank you for contributing to online-retail-sales-analysis. This project follows a structured Git workflow to ensure clean collaboration, reproducibility, and zero merge conflicts.

Please read these guidelines before making changes.

## 🧪 Environments (Branches)

### 🔹 DEV (`dev`)
- All development happens here  
- You may push directly  
- Trial files and experiments are allowed  
- Create feature branches from here

### 🔹 UAT (`uat`)
- Protected branch  
- No direct pushes  
- Only PRs allowed  
- Used for testing and validation

### 🔹 PRD (`main`)
- Fully protected  
- No direct pushes  
- Only approved PRs from UAT may merge


---

## 🔀 Branching Workflow

1. Pull latest `dev`
2. Create a feature branch
3. Do your work  
4. Commit and push  
5. Open a PR → `dev`  
6. After testing, maintainers will promote:

<h2>🧱 Project Workflow Overview</h2>

All contributors must:
1. Work on a separate branch
2. Commit changes with clear messages
3. Push to their branch
4. Submit a Pull Request (PR)
5. Wait for review and approval before merging
6. No one pushes directly to main.

<h2>🌿 Branching Strategy</h2>

Create branches using this format:

1. feature/<short-description>
2. bugfix/<short-description>
3. analysis/<notebook-name>
4. dashboard/<component-name>

Examples:
1. feature/data-cleaning
2. analysis/customer-segmentation
3. dashboard/sales-trends-plotly

<h2>📝 Commit Message Guidelines</h2>

Use clear, descriptive commit messages.

Format:

<type_of_commit>: <short_description>

Types:

1. feat — new feature
2. fix — bug fix
3. clean — data cleaning
4. viz — visualization updates
5. refactor — code restructuring
6. docs — documentation updates

Examples:

1. clean: handled missing values in customer_id
2. viz: added monthly sales plot using plotly
3. feat: created Dash layout for dashboard


---

## 📁 Data Rules

### ❌ Do NOT commit:
- Raw data  
- Cleaned data  
- Aggregated data  
- Large files  
- Secrets or credentials  

### ✔️ Allowed:
- `.gitkeep` files  
- Scripts  
- Notebooks  
- Documentation  

---

## 🧼 Code Quality Rules
- Use relative paths (`data/bronze/...`)
- Clean notebooks before committing
- Use meaningful commit messages
- Keep functions modular and reusable
- Follow PEP8 where possible

---

## 📝 Pull Request Requirements
Every PR must include:
- Clear title  
- Summary of changes  
- Screenshots (if visualization changes)  
- Confirmation that code runs  
- No trial files or temporary notebooks  

PRs into UAT or PRD require approval.

---

## 🧹 Trial Files
Trial files are allowed **only in DEV**.  
They must be removed before PRs into UAT or PRD.

Maintainers will reject PRs containing:
- `test.ipynb`
- `temp.py`
- `random_experiment.ipynb`
- Any non‑project files

<h2>🔄 Pull Request Process</h2>

Before submitting a PR:

1. Ensure your branch is up to date with main
2. Run your notebook/script to confirm it executes without errors
3. Add comments explaining complex logic
4. Ensure large files are not committed (use .gitignore)

PR Requirements

1. Every PR must include:

   a. A clear title<br>
   b. A short description of changes<br>
   c. Screenshots (if visualization-related)

2. A checklist confirming:

   a. Code runs without errors<br>
   b. No large files added<br>
   c. Notebook outputs cleaned (optional but recommended)

<h2>🧪 Code Style Guidelines</h2>

1. Use pandas, numpy, scipy, matplotlib, seaborn, plotly, and dash consistently
2. Use meaningful variable names
3. Avoid hard‑coding file paths
4. Keep notebooks clean and organized
5. Move reusable logic into /scripts

---

## 🙌 Thank You
Following these rules keeps the project clean, professional, and easy for everyone to collaborate.

