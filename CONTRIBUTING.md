# Contributing Guide

Thanks for being part of the AI/ML team's yearly programme! Here's exactly how to submit your monthly work.

## One-time setup

1. Fork this repository (button top-right of the GitHub page).
2. Clone your fork locally:
   ```bash
   git clone https://github.com/<your-username>/GDGOnCampus_AI-ML_Team_Members_Comasts_Attock_Campus.git
   cd aiml-activity-plan-2026
   ```
3. Add the main repo as "upstream" so you can pull the latest folders/updates later:
   ```bash
   git remote add upstream https://github.com/rasheed89034/GDGOnCampus_AI-ML_Team_Members_Comasts_Attock_Campus.git
   ```

## Every month

1. Sync your fork with the latest main repo:
   ```bash
   git checkout main
   git fetch upstream
   git merge upstream/main
   git push origin main
   ```
2. Create a new branch named `month-XX-focus-area/your-name`:
   ```bash
   git checkout -b month-03-ml-fundamentals/your-name
   ```
3. Add your work inside `month-XX.../members/your-name/`:
   - Code / notebooks for the hands-on challenge
   - `ARTICLES.md` with links to your 2 published articles
4. Commit with a clear message:
   ```bash
   git add .
   git commit -m "Month 3: Kaggle challenge submission - your-name"
   ```
5. Push to your fork:
   ```bash
   git push origin month-03-ml-fundamentals/your-name
   ```
6. Open a Pull Request into `main` on the original repo. Fill out the PR template.
7. Respond to any review comments from the team lead, then it gets merged.

## Folder naming rules

- Use your GitHub username as your folder name — keeps things unique and easy to find.
- Don't edit other members' folders.
- Don't rename or delete the month folders themselves.

## Getting help

Stuck on Git? Open an issue, or ask in the team channel — Month 1 covers Git/GitHub basics for exactly this reason.
