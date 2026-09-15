# Freecash Landing Page

Responsive Freecash landing page configured for static zero-build hosting and deployment on Vercel.

## Affiliate Link Configuration
- Target CTA URL: `https://linkthem.net/aff_c?offer_id=3531&aff_id=181327`
- Dynamic parameters (`sub1` for campaign, `sub2` for click ID / ttclid) are automatically passed through on click.

## File Structure
- `index.html`: Complete standalone landing page with CTA routing, notification toasts, and modal dialog.
- `vercel.json`: Clean URL routing and security headers for Vercel deployment.
- `.github/workflows/deploy.yml`: GitHub Actions automated deployment workflow to Vercel on push to `main`.

## Deploying to Vercel
1. Import this repository directly into [Vercel](https://vercel.com/new).
2. Or configure GitHub Actions by adding the following repository secrets under **Settings > Secrets and variables > Actions**:
   - `VERCEL_TOKEN`
   - `VERCEL_ORG_ID`
   - `VERCEL_PROJECT_ID`
