# Consign — Freight in Motion

A modern logistics control platform for real-time freight tracking, warehouse operations, and customs management.

## 🚀 Features

- **Live Fleet Tracking** — GPS positions refresh every 15 seconds across road, rail, and ocean legs
- **Warehouse Operations** — Barcode-verified accuracy with real-time manifest logging
- **Customs & Documents** — Auto-generate manifests, invoices, and customs declarations
- **Route Optimization** — Automatic re-routing based on live traffic, weather, and port data
- **Control Tower Dashboard** — Single map view of all active shipments with live status

## 📊 Current Metrics

- **98.4%** on-time delivery rate
- **12,406** shipments in transit
- **340** fleet vehicles connected
- **47** active ports & hubs

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (custom design system)
- **Animation:** Native CSS animations + Intersection Observer API
- **Typography:** Space Grotesk, Inter, JetBrains Mono
- **Responsive:** Mobile-first design (320px–1920px)
- **Accessibility:** WCAG 2.1 compliant (focus states, keyboard navigation, reduced-motion support)

## 🚀 Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/siyandamyeni46-dot/consign.git
   cd consign
   ```

2. Open in browser:
   ```bash
   # Option A: Using Python
   python -m http.server 8000
   
   # Option B: Using Node.js
   npx http-server
   
   # Option C: Direct open
   open index.html
   ```

3. Visit: `http://localhost:8000`

### GitHub Pages Deployment

The site is configured for automatic deployment via GitHub Pages:

1. Go to **Settings → Pages**
2. Set **Source** to `main` branch
3. Your site will be live at: `https://siyandamyeni46-dot.github.io/consign/`

## 🎨 Design System

### Color Palette

```
--bg:        #0B0F14  (Deep Navy)
--bg-alt:    #10161D  (Dark Slate)
--panel:     #131A21  (Panel Dark)
--amber:     #FF7A1A  (Primary Action)
--steel:     #3E5C76  (Secondary)
--teal:      #2F8F73  (Accent)
--text:      #EDEFEF  (Primary Text)
--text-dim:  #8B95A1  (Secondary Text)
--line:      #232B33  (Borders)
```

### Typography

- **Display:** Space Grotesk (headings)
- **Body:** Inter (body text)
- **Mono:** JetBrains Mono (labels, code)

## ✨ Key Interactions

- Smooth scroll behavior with anchor links
- Reveal animations on scroll (Intersection Observer)
- Pulsing hero eyebrow indicator
- Animated route spine with traveling gradient
- Form validation with visual feedback
- Hover states on all interactive elements
- Focus-visible outlines for keyboard navigation

## 🔜 Roadmap

- [ ] React component library
- [ ] Next.js full-stack version with API
- [ ] Real-time WebSocket integration
- [ ] Dark/Light theme toggle
- [ ] Multi-language support (i18n)
- [ ] Analytics dashboard
- [ ] Mobile app (React Native)
- [ ] Docker containerization
- [ ] CI/CD pipeline (GitHub Actions)

## 📄 License

MIT License — feel free to use this project for personal or commercial purposes.

---

**Made with ❤️ for modern logistics.**