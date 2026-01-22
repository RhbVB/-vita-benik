# VITA BENIK Website

Private Investment Office landing page.

## Quick Deploy to Vercel

### Option 1: Using Vercel CLI (Recommended)

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Navigate to this folder:
```bash
cd vita-benik
```

3. Deploy:
```bash
vercel
```

4. Follow the prompts. Your site will be live!

### Option 2: Using Vercel Dashboard

1. Go to [vercel.com](https://vercel.com) and sign in
2. Click "Add New Project"
3. Drag and drop this entire folder, OR connect your GitHub repo
4. Click "Deploy"

## Adding Your Logo

Replace the text logo with your image:

1. Add your logo file to this folder (e.g., `logo.png`)
2. In `index.html`, find this line:
```html
<a href="#" class="logo">VITA BENIK</a>
```
3. Replace with:
```html
<a href="#" class="logo"><img src="logo.png" alt="VITA BENIK" height="30"></a>
```

## Connecting the Form

The form currently shows an alert on submission. To connect to a real backend:

### Option A: Formspree (Easy)
1. Sign up at [formspree.io](https://formspree.io)
2. Create a form and get your endpoint
3. Add `action` and `method` to the form tag:
```html
<form class="contact-form" action="https://formspree.io/f/YOUR_ID" method="POST">
```

### Option B: Airtable Integration
Use Airtable's form feature or webhook to capture leads directly into your CRM.

## Customization

- Colors: Edit CSS variables in `:root` section
- Fonts: Change Google Fonts link and font-family values
- Content: Edit text directly in the HTML

## Files

- `index.html` - Main website (all-in-one)
- `vercel.json` - Vercel deployment config
- `package.json` - Project metadata

---

© 2026 Benik Global Connections LLC
