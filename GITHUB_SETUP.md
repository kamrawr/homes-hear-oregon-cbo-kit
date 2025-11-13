# GitHub Setup Instructions

This repository is ready to push to GitHub. Follow these steps:

## 1. Create a New GitHub Repository

1. Go to https://github.com/new
2. Repository name: `homes-hear-oregon-cbo-kit`
3. Description: `Documentation kit for Community-Based Organizations administering Oregon's HOMES and HEAR energy rebate programs`
4. Choose **Public** (to help other CBOs) or **Private** (if you prefer)
5. **Do NOT** initialize with README, .gitignore, or license (already included)
6. Click "Create repository"

## 2. Push Your Local Repository

After creating the GitHub repository, run these commands:

```powershell
cd "$env:USERPROFILE\OneDrive\Development\homes-hear-oregon-cbo-kit"

# Add the remote repository (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/homes-hear-oregon-cbo-kit.git

# Rename branch to main (if needed)
git branch -M main

# Push to GitHub
git push -u origin main
```

## 3. Enable GitHub Pages

Enable the website for your repository:

1. Go to repository **Settings**
2. Navigate to **Pages** (in left sidebar)
3. Under **Source**, select "Deploy from a branch"
4. Choose branch: **main** (or **master**)
5. Choose folder: **/docs**
6. Click **Save**

Your website will be available at:
```
https://YOUR_USERNAME.github.io/homes-hear-oregon-cbo-kit/
```

(Replace YOUR_USERNAME with your actual GitHub username)

## 4. Configure Repository Settings (Optional)

On GitHub, go to your repository settings:

### Topics
Add topics to help others find your repo:
- `energy-efficiency`
- `oregon`
- `community-organizations`
- `homes-program`
- `hear-program`
- `documentation`

### About
Add the description:
> Documentation kit for Community-Based Organizations administering Oregon's HOMES and HEAR energy rebate programs

### Website
Add your GitHub Pages URL:
```
https://YOUR_USERNAME.github.io/homes-hear-oregon-cbo-kit/
```

## 4. Next Steps

- Review and customize the documentation for your organization's needs
- Consider adding your CBO's specific procedures in `cbo-operations/`
- Keep `links/master-link-index.csv` updated as guidance changes
- Share with other CBOs who might benefit

## Current Repository Structure

```
homes-hear-oregon-cbo-kit/
├── .gitignore                    # Protects sensitive data
├── LICENSE                       # MIT License
├── README.md                     # Main documentation
├── CONTRIBUTING.md               # Contribution guidelines
├── GITHUB_SETUP.md              # This file
├── cbo-operations/              # CBO operational guides
│   ├── README.md
│   ├── intake-eligibility.md
│   └── data-privacy-reporting.md
├── federal-guidance/            # Federal program guidance
│   └── federal-core-docs.md
├── oregon-implementation/       # Oregon-specific implementation
│   └── oregon-core-docs.md
├── links/                       # Master link index
│   └── master-link-index.csv
├── resources/                   # Additional resources
│   └── additional-resources.md
└── templates/                   # Blank templates for CBO use
    └── README.md
```

## Maintenance

As you maintain this repository:

1. **Update links regularly** - Federal and state guidance changes frequently
2. **Add templates** - Share useful forms and workflows (remove PII first)
3. **Document lessons learned** - Help other CBOs avoid common pitfalls
4. **Review pull requests** - Accept contributions from other CBOs

---

**Repository Owner:** Community Consulting Partners LLC  
**Maintainer:** Isaiah Kamrar
