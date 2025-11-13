# Oregon HOMES/HEAR CBO Guide - Website

This folder contains the GitHub Pages website for the Oregon HOMES & HEAR CBO Documentation Kit.

## Website Structure

- **index.html** - Homepage with program overview and CBO roles
- **programs.html** - Detailed program information for HOMES and HEAR
- **eligibility.html** - Income, housing, and documentation requirements
- **operations.html** - CBO operations guide (intake, referrals, data privacy)
- **resources.html** - Comprehensive links to all federal and Oregon documentation
- **styles.css** - Responsive styling for the website
- **_config.yml** - GitHub Pages configuration

## Features

### Comprehensive Program Details
- Full HOMES and HEAR program specifications
- Rebate amounts by income tier
- Measure-by-measure requirements for HEAR
- Retroactivity rules and timelines

### Verified Links
All links from `../links/master-link-index.csv` are included with working URLs to:
- Federal DOE program requirements
- Oregon ODOE documents and FAQs
- Energy Trust and Earth Advantage resources
- Implementation guidance from Energy Innovation, RMI, ENERGY STAR
- Legislative materials and contractor resources

### CBO-Focused Content
- Intake screening questions and workflows
- Referral pathways to implementers
- Data privacy and protection guidance
- Tracking and reporting templates
- Partnership building strategies

## Enabling GitHub Pages

After pushing to GitHub:

1. Go to your repository settings
2. Navigate to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Choose branch: `main` (or `master`)
5. Choose folder: `/docs`
6. Click "Save"

Your site will be available at: `https://YOUR_USERNAME.github.io/homes-hear-oregon-cbo-kit/`

## Local Development

To preview locally, you can use any local web server:

```bash
# Python 3
cd docs
python -m http.server 8000

# Then visit http://localhost:8000
```

Or use VS Code's Live Server extension, or any other local server tool.

## Updating Content

To update program information:

1. Edit the relevant HTML file (`programs.html`, `eligibility.html`, etc.)
2. Commit changes to git
3. Push to GitHub
4. GitHub Pages will automatically rebuild (takes 1-2 minutes)

## Customization

- **Colors**: Edit CSS variables in `styles.css` (`:root` section)
- **Links**: Update footer GitHub links to your username
- **Content**: All pages are standard HTML - no build process required

## Mobile Responsive

The site is fully responsive and works on:
- Desktop browsers
- Tablets
- Mobile phones

## Accessibility

- Semantic HTML structure
- Clear navigation
- Readable font sizes
- Sufficient color contrast
- Descriptive link text

---

**Maintained by:** Community Consulting Partners LLC  
**License:** MIT
