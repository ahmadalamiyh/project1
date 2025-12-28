# QuizMate

A simple login page for QuizMate application.

## Custom Domain Setup

This repository is configured to use the custom domain: **ahmadalamiyh.me**

### DNS Configuration Required

To complete the custom domain setup, configure the following DNS records with your domain registrar:

#### Option 1: Using A Records (Apex Domain)
Add the following A records:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

#### Option 2: Using CNAME (if using www subdomain)
If you want to use `www.ahmadalamiyh.me`, add a CNAME record:
```
CNAME: www -> ahmadalamiyh.github.io
```

### GitHub Pages Settings

1. Go to repository Settings → Pages
2. Verify that "Custom domain" is set to `ahmadalamiyh.me`
3. Enable "Enforce HTTPS" (recommended, wait for DNS propagation first)

### Verification

After DNS configuration:
1. Wait for DNS propagation (can take up to 48 hours, usually much faster)
2. Visit https://ahmadalamiyh.me to verify the site is accessible
3. GitHub will automatically provision an SSL certificate once DNS is properly configured

## Files

- `index.html` - Main login page
- `procss.css` - Stylesheet
- `logo.png` - QuizMate logo
- `CNAME` - Custom domain configuration for GitHub Pages
