# GitHub profile README setup

This folder is meant to become the repo **`janhaviprof-bot/janhaviprof-bot`** (same name as your GitHub username).

## 1. Create the repo on GitHub

1. Go to [github.com/new](https://github.com/new)
2. Repository name: **`janhaviprof-bot`** (must match username exactly)
3. Public
4. Add a README (optional — you will replace it)
5. Create repository

## 2. Push this folder

From PowerShell (adjust path if needed):

```powershell
cd "c:\Work\Job\PortfolioRepo\Portfolio.github.io\profile-readme"

git init
git add README.md .github/workflows/snake.yml
git commit -m "Add profile README and contribution snake workflow"
git branch -M main
git remote add origin https://github.com/janhaviprof-bot/janhaviprof-bot.git
git push -u origin main
```

If the repo already exists with a README, pull first:

```powershell
git pull origin main --rebase
git push -u origin main
```

## 3. Enable the snake animation

1. Open the repo on GitHub → **Actions** tab
2. Enable workflows if prompted
3. Run **Generate Snake** manually once (Actions → Generate Snake → Run workflow)
4. After it completes, refresh [github.com/janhaviprof-bot](https://github.com/janhaviprof-bot) — the snake appears at the bottom of the README

## 4. Update your GitHub profile settings

[github.com/settings/profile](https://github.com/settings/profile)

| Field | Suggested value |
|-------|-----------------|
| Name | Janhavi Gaikwad |
| Bio | Systems Engineer @ Cornell · MBSE · Controls · Agentic AI · ASEP |
| URL | `https://janhaviprof-bot.github.io/Portfolio.github.io/` |
| LinkedIn | your profile URL |

## 5. Pin repositories (recommended order)

1. Portfolio.github.io
2. SupplyMindAI
3. SystemsArchitecture
4. DS-AIforSystemsEng-Project
5. DS-AIforSystemsEng
6. AIforSystemsEng

## Notes

- Private repos (`UAM-Routing`, `SystemAnalysis-BehaviourOptimization`) are intentionally omitted from the public README.
- Stats cards use [github-readme-stats](https://github.com/anuraghazra/github-readme-stats); they may take a minute to load on first visit.
- Edit `README.md` anytime — changes show on your profile within seconds.
