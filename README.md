# Vely Privacy Policy & Legal Pages

This repository hosts the privacy policy, terms of service, and support pages for the **Vely** mobile application.

## 🌐 Live Site

The pages are hosted on GitHub Pages at: `https://[your-username].github.io/vely-privacy-policy/`

## 📄 Pages Included

| Page | Description | URL Path |
|------|-------------|----------|
| **Privacy Policy** | How we collect, use, and protect user data | `/` or `/index.html` |
| **Terms of Service** | Rules and guidelines for using Vely | `/terms.html` |
| **Support** | FAQ and contact information | `/support.html` |
| **Delete Account** | Instructions for account deletion | `/delete-account.html` |

## 🚀 Deployment to GitHub Pages

### Option 1: Using GitHub UI

1. Create a new repository on GitHub named `vely-privacy-policy`
2. Push this code to the repository
3. Go to **Settings** > **Pages**
4. Under "Source", select **Deploy from a branch**
5. Select `main` branch and `/ (root)` folder
6. Click **Save**
7. Wait a few minutes for deployment

### Option 2: Using Git Commands

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit - Privacy policy and legal pages"

# Add your GitHub repository as remote
git remote add origin https://github.com/[your-username]/vely-privacy-policy.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## 📱 Usage in Google Play Console

Use these URLs in your Google Play Console listing:

- **Privacy Policy URL**: `https://[your-username].github.io/vely-privacy-policy/`
- **Terms of Service URL**: `https://[your-username].github.io/vely-privacy-policy/terms.html`

## 🎨 Customization

### Colors
The pages use the Vely brand colors defined in CSS variables:

```css
--primary: #7C3AED;       /* Purple */
--primary-dark: #6D28D9;  /* Dark Purple */
--background: #0F0F1E;    /* Dark Background */
--surface: #1A1A2E;       /* Card Background */
--gold: #F59E0B;          /* Accent Gold */
```

### Contact Emails
Update these email addresses in all HTML files:
- `support@vely.app` - General support
- `privacy@vely.app` - Privacy concerns
- `safety@vely.app` - Safety reports
- `billing@vely.app` - Payment issues
- `legal@vely.app` - Legal matters

### Company Information
Update the company name and address in the footer sections:
```
MettaAi
Pune, Maharashtra, India
```

## 📋 Checklist for Google Play

- [x] Privacy Policy with data collection details
- [x] Terms of Service
- [x] Account deletion instructions and link
- [x] Support/Contact information
- [x] Age restrictions (18+)
- [x] Data security information
- [x] Third-party service disclosures (Supabase, Stripe, Razorpay)

## 🔧 Local Development

To preview the pages locally:

1. Open the folder in VS Code
2. Install "Live Server" extension
3. Right-click `index.html` and select "Open with Live Server"

Or use Python:
```bash
python -m http.server 8000
```

## 📝 Updates

When updating these pages:
1. Update the "Last Updated" date in the header
2. Commit and push changes
3. GitHub Pages will automatically redeploy

## 📄 License

© 2025 Vely / MettaAi. All rights reserved.

---

Made with ❤️ for couples
