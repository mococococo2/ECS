# EcoClear Solutions — Website

DFW's #1 valet trash service website. Redesigned with a bold editorial aesthetic — deep forest green, crisp white, and electric lime accents.

## 📁 File Structure

```
/
├── index.html              # Home page (hero, services, ROI calculator, sustainability)
├── services.html           # Full service catalog (8 services + coming soon)
├── property-managers.html  # For property managers (pain points, tech, ROI)
├── residents.html          # For residents (how it works, rules, FAQ)
├── about.html              # About (story, P.R.I.D.E. values, timeline)
├── careers.html            # Careers (open roles, hiring process, apply form)
└── contact.html            # Contact (channels, quote form, location)
```

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository
2. Upload all 7 HTML files to the root
3. Go to **Settings → Pages**
4. Under **Source**, select `main` branch and `/ (root)`
5. Save — your site goes live at `https://yourusername.github.io/repo-name/`

For a custom domain (e.g., `ecoclearsolutions.net`), add a `CNAME` file with just your domain on one line and update your DNS.

## 🎨 Design System

- **Colors**: Forest green (`#0E3B22`) + electric lime (`#C8F542`) + cream (`#F5F2EA`)
- **Fonts**: Fraunces (serif headlines) + Outfit (sans-serif body) — loaded from Google Fonts
- **Animations**: IntersectionObserver-based scroll reveals on every page
- **Responsive**: Mobile breakpoint at 900px

## ✨ Features

- **ROI Calculator** (home page): 4 interactive sliders with live revenue/profit calculations
- **Interactive FAQ** (residents page): Click to expand
- **Live Dashboard Mockup** (property managers page): Simulated real-time service dashboard
- **Animated Timeline** (about page): Company history with visual progression
- **Job Listings** (careers page): 6 open roles with pay ranges and apply flow
- **Quote Forms** (contact + home): Multi-field forms with validation styling

## 🔧 Customization Quick Tips

- **Change colors**: Edit the `:root` CSS variables at the top of each file's `<style>` block
- **Update phone number**: Search/replace `(214)-909-1824` and `2149091824`
- **Update email**: Search/replace `support@ecoclearsolutions.net`
- **Connect forms**: Replace the `onclick="alert(...)"` handlers with your actual form submission logic (Formspree, Netlify Forms, or custom backend)

## 📱 Browser Support

Modern browsers (Chrome, Firefox, Safari, Edge). Uses CSS Grid, Flexbox, and IntersectionObserver.

---

Copyright © 2026 EcoClear Solutions LLC
