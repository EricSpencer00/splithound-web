# FairShare Website

**Live Site**: [https://ericspencer00.github.io/splithound-web](https://ericspencer00.github.io/splithound-web)

## 🎨 What's Been Updated

### 1. Homepage Redesign
The homepage has been completely redesigned with iOS App Store marketing best practices:

- **Hero Section**: Eye-catching gradient header with compelling copy
- **Feature Showcase**: Three main features with screenshot placeholders:
  - 📸 Scan Receipts Instantly
  - ✂️ Break Down Totals Per Person  
  - 🐕 Hound Them for Money!
- **Benefits Grid**: Four-card layout highlighting key selling points
- **Call-to-Action**: Download buttons positioned throughout
- **Modern Design**: Clean, Apple-inspired aesthetic with smooth animations

### 2. Updated CSS
Complete style overhaul featuring:
- iOS-style typography and spacing
- Gradient hero section
- Responsive grid layouts
- Smooth hover effects and transitions
- Mobile-first responsive design
- Apple's SF Pro Display font stack

### 3. Legal Documents

#### Terms of Service ✅
Comprehensive, legally-sound ToS covering:
- User eligibility and responsibilities
- Subscription and payment terms (RevenueCat, App Store)
- Data ownership and privacy
- Third-party integrations (CloudKit, payment services)
- Liability limitations and disclaimers
- Indemnification and dispute resolution
- Termination clauses
- Apple-specific terms
- Illinois jurisdiction

#### Privacy Policy ✅
Thorough privacy policy addressing:
- Data collection practices (local vs cloud)
- Apple CloudKit integration (optional sync)
- RevenueCat subscription management
- On-device OCR processing
- Third-party payment services
- CCPA (California) compliance
- GDPR (European) compliance
- Children's privacy (COPPA)
- Data retention and deletion
- User privacy rights
- International data transfers

### 4. Screenshot Framework
Created `/assets/SCREENSHOT_GUIDE.md` with detailed instructions for:
- Which screens to capture
- How to capture them
- Image specifications (size, format, device)
- Device mockup recommendations
- File naming conventions

## 📸 Screenshots Needed

Place these in `/web/assets/`:

1. **icon.png** - 1024x1024 app icon
2. **hero-phone.png** - Main app view showing receipt with splits
3. **screenshot-scan.png** - Camera/scanning interface
4. **screenshot-split.png** - Item assignment interface
5. **screenshot-payment.png** - Payment summary/links view

See `assets/SCREENSHOT_GUIDE.md` for detailed capture instructions.

## 🚀 How to Use

### Local Development
Open `index.html` in a browser to preview locally:
```bash
cd web
open index.html
```

Or use a local server:
```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Then visit: http://localhost:8000
```

### Adding Screenshots
1. Follow the guide in `assets/SCREENSHOT_GUIDE.md`
2. Capture screenshots from your app
3. Name them exactly as specified
4. Place them in `/web/assets/`
5. Refresh the website to see them

### Deployment
This static site can be deployed to:
- GitHub Pages (currently active)
- Netlify
- Vercel
- Any static hosting service

## 📁 File Structure

```
web/
├── index.html          # Homepage with iOS marketing
├── privacy.html        # Comprehensive privacy policy
├── terms.html          # Legal terms of service
├── css/
│   └── style.css       # All styles (iOS-inspired design)
├── js/
│   └── main.js         # JavaScript utilities
├── assets/
│   └── SCREENSHOT_GUIDE.md   # Screenshot capture guide
│   └── (screenshots go here)
└── README.md          # This file
```

## 🎯 Marketing Copy

The site uses App Store-style marketing language:

**Headline**: "Split Bills Fairly. Every Time."

**Key Messages**:
- Scan receipts instantly with AI
- Break down totals per person automatically
- Hound them for money with payment links

**Tone**: Friendly, confident, solution-focused

## 🔗 Git Submodule

This repo is set up as a git submodule at `/web/` in the main FairShare Xcode project.

To update the submodule in the main repo:
```bash
cd /path/to/FairShare.dev
cd web
git add .
git commit -m "Update website"
git push

# Then in the parent repo
cd ..
git add web
git commit -m "Update website submodule"
git push
```

## ⚖️ Legal Compliance

The Terms of Service and Privacy Policy have been written to:
- Accurately reflect FairShare's actual data practices
- Cover all third-party services (CloudKit, RevenueCat, payment providers)
- Comply with CCPA (California), GDPR (Europe), and COPPA (children's privacy)
- Include proper disclaimers for OCR accuracy and liability
- Meet Apple App Store requirements

**Note**: While these documents are comprehensive, consider having them reviewed by a legal professional before publishing.

## 📧 Contact & Support

Update the support email throughout the site:
- Currently set to: `support@fairshareapp.com`
- Update in: `index.html`, `privacy.html`, `terms.html`

## 🎨 Brand Colors

Current color scheme (in CSS variables):
- Primary: `#007aff` (iOS blue)
- Hero Gradient: Purple to blue gradient
- Background: White/light gray
- Text: Dark gray/black

Easily customizable in `css/style.css` under `:root`.

## 📱 Responsive Design

The site is fully responsive with breakpoints at:
- Desktop: 968px+
- Tablet: 600px - 968px
- Mobile: < 600px

## ✨ Next Steps

1. **Add Screenshots**: Follow `assets/SCREENSHOT_GUIDE.md`
2. **Customize Copy**: Update marketing text to match your voice
3. **Add App Store Link**: Replace `#` with actual App Store URL
4. **Set Up Domain**: Point your domain to the hosted site
5. **Legal Review**: Have a lawyer review the legal documents
6. **Analytics**: Add Google Analytics or similar (optional)
7. **SEO**: Add meta tags, Open Graph tags, and sitemap

## 📄 License

This website is part of the FairShare project.

---

**Built with ❤️ for FairShare users**

