# DiskLens Website Structure

## Current Pages
- `index.htm` - Landing page with hero, features, and download CTAs

## Folder Structure
```
disklens-site/
├── index.htm              # Main landing page
├── downloads/             # Installer files (.dmg, .exe)
│   ├── README.md
│   └── checksums.txt      # SHA-256 checksums
├── screenshots/           # App screenshots for website/press
│   ├── hero-dark.png
│   ├── hero-light.png
│   ├── sunburst-view.png
│   ├── top50-view.png
│   └── types-view.png
├── docs/                  # Documentation
│   ├── getting-started.html
│   ├── faq.html
│   └── keyboard-shortcuts.html
└── assets/                # Future: CSS, JS, images
    ├── css/
    ├── js/
    └── img/
```

## Future Pages to Add

### Priority 1 (Essential)
| Page | File | Description |
|------|------|-------------|
| Privacy Policy | `privacy.html` | Required for app stores |
| Terms of Service | `terms.html` | Legal terms |
| Changelog | `changelog.html` | Release notes by version |

### Priority 2 (Nice to Have)
| Page | File | Description |
|------|------|-------------|
| FAQ | `docs/faq.html` | Common questions |
| Screenshots | `screenshots.html` | Gallery of app views |
| Support | `support.html` | Contact & help resources |
| Press Kit | `press.html` | Logos, screenshots for press |

### Priority 3 (Future Growth)
| Page | File | Description |
|------|------|-------------|
| Blog | `blog/` | Updates, tips, tutorials |
| Documentation | `docs/` | Full user guide |
| Roadmap | `roadmap.html` | Upcoming features |
| Compare | `compare.html` | vs WinDirStat, TreeSize, etc. |

## Suggested Improvements to index.htm

### 1. Update Download Buttons with Real Links
```html
<a href="downloads/DiskLens-1.0.18-win-x64.exe" download>
    Download for Windows
</a>
<a href="downloads/DiskLens-1.0.18-mac-arm64.dmg" download>
    Download for Mac
</a>
```

### 2. Add Version Badge
Display current version dynamically or update manually.

### 3. Add Screenshot Gallery
Replace abstract UI with real app screenshots.

### 4. Add Testimonials Section
Social proof from users.

### 5. Add Comparison Table
Show advantages over alternatives.

### 6. Fix Typo
"DiskLense" → "DiskLens" (consistent spelling)

## SEO Checklist
- [ ] Add Open Graph meta tags
- [ ] Add Twitter card meta tags
- [ ] Add favicon
- [ ] Add sitemap.xml
- [ ] Add robots.txt
- [ ] Optimize images
- [ ] Add structured data (JSON-LD)

## Analytics
Consider adding:
- Google Analytics or Plausible
- Download tracking
