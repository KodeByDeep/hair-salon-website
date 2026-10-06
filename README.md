# 💇 Stylish Salon — Luxury Hair Salon Website
## Concept website built as a portfolio project. Business name, team and pricing are fictional.

<div align="center">

![Stylish Salon](https://images.unsplash.com/photo-1560066984-138dadb4c035?w=1200&q=80)

**🌐 Live Site: [https://salon.veloraweb.co.uk](https://salon.veloraweb.co.uk)**

[![Next.js](https://img.shields.io/badge/Next.js-14-black?style=flat-square&logo=next.js)](https://nextjs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=flat-square&logo=typescript)](https://typescriptlang.org)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-10-purple?style=flat-square)](https://framer.com/motion)
[![Deployed on Hostinger](https://img.shields.io/badge/Hosted-Hostinger-orange?style=flat-square)](https://hostinger.com)

</div>

---

## 🔗 Live Demo

**[https://salon.veloraweb.co.uk](https://salon.veloraweb.co.uk)**

A fully responsive, SEO-optimised luxury hair salon website built with Next.js 14, TypeScript, and Framer Motion. Designed to a professional industry standard, inspired by top London salons like Gielly Green and Salon 64.

---

## ✨ Features

### Animations & Effects
- **Typewriter hero** — text cycles through phrases with blinking gold cursor
- **Parallax scrolling** — background image moves slower than content on scroll
- **Scroll reveal** — every section fades and slides in as you scroll down
- **Infinite auto-scroll gallery** — images scroll left continuously, pauses on hover
- **Counting stats** — numbers animate from 0 to target when scrolled into view
- **Auto-sliding testimonials** — reviews change every 5 seconds with smooth transitions
- **Hover bio reveal** — stylist cards reveal full bio on hover
- **Animated gold dividers** — lines scale in on scroll

### Design
- Dark luxury theme — charcoal black `#0A0A0A` + gold `#C9A84C`
- Georgia serif headings, Arial sans-serif body text
- Transparent navbar that becomes solid on scroll
- Mobile hamburger menu with smooth open/close animation
- Gold underline on active nav link

### Technical
- **6 separate pages** — each with unique SEO metadata
- **Fully responsive** — mobile, tablet, desktop
- **Static export** — no server needed, works on any host
- **SEO ready** — sitemap.xml, robots.txt, Open Graph tags
- **Fast** — all pages prerendered as static HTML

---

## 📄 Pages

| Page | URL | Content |
|------|-----|---------|
| **Home** | `/` | Hero, services preview, about strip, stats, team preview, gallery strip, testimonials, CTA, brands |
| **Services** | `/services` | 5 service categories with full pricing, alternating image/text layout, FAQs |
| **Our Team** | `/team` | 6 stylist full bios, experience, specialities, quotes, careers section |
| **Gallery** | `/gallery` | 18 images filterable by category — Colour, Cuts, Balayage, Styling, Salon |
| **About** | `/about` | Salon story, timeline, values, awards, product brands |
| **Contact** | `/contact` | Booking form with stylist selection, salon info, getting here, policy cards |

---

## 🛠 Tech Stack

| Tool | Version | Purpose |
|------|---------|---------|
| [Next.js](https://nextjs.org) | 14 | Full-stack React framework, static export |
| [TypeScript](https://typescriptlang.org) | 5 | Type safety — catches bugs before runtime |
| [Framer Motion](https://framer.com/motion) | 10 | All animations — scroll reveal, parallax, transitions |
| [Tailwind CSS](https://tailwindcss.com) | 4 | Responsive CSS class helpers |
| [Lucide React](https://lucide.dev) | latest | Icon library |

---

## 📁 Project Structure

```
salon-app/
│
├── app/                          # Next.js App Router
│   ├── page.tsx                  # Homepage (/)
│   ├── services/
│   │   └── page.tsx              # Services page (/services)
│   ├── team/
│   │   └── page.tsx              # Team page (/team)
│   ├── gallery/
│   │   └── page.tsx              # Gallery page (/gallery)
│   ├── about/
│   │   └── page.tsx              # About page (/about)
│   ├── contact/
│   │   └── page.tsx              # Contact page (/contact)
│   ├── layout.tsx                # Root layout — SEO metadata, fonts
│   └── globals.css               # Global styles, buttons, animations, responsive
│
├── components/
│   ├── pages/                    # Full page content components
│   │   ├── HomePage.tsx          # All homepage sections
│   │   ├── ServicesPage.tsx      # Full services with pricing + FAQs
│   │   ├── TeamPage.tsx          # 6 stylist bios
│   │   ├── GalleryPage.tsx       # Filterable image grid
│   │   ├── AboutPage.tsx         # Story, timeline, values, awards
│   │   └── ContactPage.tsx       # Booking form + info
│   │
│   ├── Navbar.tsx                # Responsive navbar — transparent/solid on scroll
│   ├── Hero.tsx                  # Fullscreen hero — parallax + typewriter
│   ├── Stats.tsx                 # Animated counting numbers
│   ├── Testimonials.tsx          # Auto-sliding client reviews
│   ├── Footer.tsx                # 4-column footer with links, hours, socials
│   ├── HomepageTeam.tsx          # Team preview with overlapping images
│   └── FadeIn.tsx                # Reusable scroll-reveal animation wrapper
│
├── public/
│   ├── robots.txt                # SEO — allows all crawlers
│   └── sitemap.xml               # SEO — all 6 page URLs
│
├── out/                          # Static export output (generated, not committed)
├── next.config.ts                # Static export configuration
├── tsconfig.json                 # TypeScript configuration
├── package.json                  # Dependencies and scripts
└── README.md                     # This file
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18 or higher
- npm

### 1. Clone the repository

```bash
git clone https://github.com/KodeByDeep/hair-salon-website.git
cd hair-salon-website
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### 4. Build for production

```bash
npm run build
```

This generates the `out/` folder with static HTML/CSS/JS files.

---

## 🌍 Deployment — Hostinger

This site is deployed on Hostinger shared hosting at [salon.veloraweb.co.uk](https://salon.veloraweb.co.uk).

### Steps to deploy

```bash
# 1. Build the static files
npm run build

# 2. The 'out' folder contains everything needed
# 3. Zip the contents of the 'out' folder
# 4. Upload zip to Hostinger File Manager → public_html
# 5. Extract the zip inside public_html
# 6. Confirm index.html is directly in public_html
```

No Node.js server required — pure static files.

---

## 🎨 Design System

### Colours

| Name | Hex | Usage |
|------|-----|-------|
| Gold | `#C9A84C` | Buttons, accents, highlights, dividers |
| Dark | `#0A0A0A` | Primary background |
| Dark 2 | `#111111` | Secondary background (alternating sections) |
| White | `#FFFFFF` | Headings |
| Muted | `rgba(255,255,255,0.4)` | Body text, descriptions |
| Muted Light | `rgba(255,255,255,0.65)` | Subtitles |

### Typography

| Use | Font | Style |
|-----|------|-------|
| Headings | Georgia | Serif, weight 400 |
| Body text | Arial | Sans-serif |
| Labels | Arial | Uppercase, letter-spacing 0.18em |
| Quotes | Georgia | Italic |

### Spacing
- Section padding: `120px 0` desktop, `72px 0` tablet
- Container max-width: `1280px`
- Container padding: `0 40px` desktop, `0 24px` mobile

---

## 📱 Responsive Breakpoints

| Breakpoint | Width | Changes |
|-----------|-------|---------|
| Desktop | > 900px | Full layout, 2-4 column grids |
| Tablet | ≤ 900px | 2 column grids, hamburger menu |
| Mobile | ≤ 480px | Single column, smaller buttons |

---

## 🔍 SEO

Each page has unique:
- `<title>` — e.g. "Hair Services & Pricing | Stylish Salon London"
- `<meta name="description">` — unique per page
- `<meta name="keywords">` — targeted keywords
- Open Graph tags for social sharing

Site-wide:
- `sitemap.xml` — all 6 pages with priorities
- `robots.txt` — allows all search engine crawlers

---

## 📦 Services Listed

| Category | Services |
|----------|---------|
| Cut & Finish | Women's Cut, Men's Cut, Children's Cut, Dry Cut, Fringe Trim |
| Colour | Full Colour, Root Colour, Toner/Gloss, Colour Correction |
| Balayage & Highlights | Full Highlights, Half Head, Balayage, Baby Lights, Ombré |
| Styling | Blow Dry, Updo, Bridal Hair, Hair Up Lesson |
| Treatments | Olaplex, Deep Conditioning, Keratin, Scalp Treatment, Glossing |

---

## 👥 Team

| Name | Role |
|------|------|
| Sophie Laurent | Creative Director & Master Stylist |
| Marcus Reid | Senior Colour Technician |
| Aisha Patel | Senior Stylist |
| James Thornton | Men's Grooming Specialist |
| Lucia Fernandez | Colour Specialist |
| Tom Ashworth | Junior Stylist |

---

## 📝 Scripts

```bash
npm run dev        # Start development server at localhost:3000
npm run build      # Build static export to /out folder
npm run start      # Start production server (not needed for static)
npm run lint       # Run ESLint
```

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch — `git checkout -b feature/your-feature`
3. Commit your changes — `git commit -m "Add your feature"`
4. Push to the branch — `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

MIT License — free to use, modify and distribute.

---

## 🙏 Credits

- Photography — [Unsplash](https://unsplash.com) (free to use)
- Animations — [Framer Motion](https://framer.com/motion)
- Framework — [Next.js](https://nextjs.org)
- Built with — [Kiro](https://kiro.dev) AI development environment

---

<div align="center">

**🌐 Live at [https://salon.veloraweb.co.uk](https://salon.veloraweb.co.uk)**

Made with ❤️ for Stylish Salon

</div>


