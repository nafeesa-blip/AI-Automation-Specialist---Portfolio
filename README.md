# Nafeesa | AI Automation Portfolio

A multi-page static portfolio. No build step, no dependencies.

## Run locally
Open `index.html` in any browser.

## Publish on GitHub Pages
1. Create a new repository and upload `index.html`, the `images` folder and `README.md`.
2. Go to Settings > Pages.
3. Under Source, pick the `main` branch and the `/ (root)` folder, then Save.
4. Your site appears at `https://<your-username>.github.io/<repo-name>/`.

## Customize
- The contact form sends to the email in the `mailto:` link inside `index.html`; change it there if needed.
- Add GitHub, LinkedIn or Upwork links next to the Email button.

## Hero illustration
The first screen shows an animated workflow illustration (inline SVG inside `index.html`, no image file needed). Theme colours are set as CSS variables at the top of the `<style>` block (`--accent`, `--navy`, etc.).

## Pages
Every project has its own page, so you can send a client the link to just that project:

| Page | File |
|---|---|
| Home | `index.html` |
| Data annotation (AI training data) | `data-annotation.html` |
| AI lead intelligence & CRM automation | `projects/ai-lead-intelligence-crm-automation.html` |
| AI recruiter outreach agent | `projects/ai-recruiter-outreach-agent.html` |
| Business research & strategic analysis | `projects/business-research-strategic-analysis.html` |
| AI spot the difference dataset | `projects/ai-spot-the-difference-dataset.html` |
| Windows invoice generator | `projects/windows-invoice-generator.html` |
| Payroll automation (freee HR) | `projects/payroll-automation-freee-hr.html` |
| CRM lead scoring & follow-up | `projects/crm-lead-scoring-follow-up.html` |
| Webinar lead automation | `projects/webinar-lead-automation.html` |

Each page has a **Copy page link** button. All pages share one stylesheet: `assets/style.css`.

Example photos on the data annotation page come from Wikimedia Commons (credits are listed at the bottom of that page).
