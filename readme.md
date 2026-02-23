<div align="center">

# 📈 Lucknow Trading House — Official Website

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
![Hostinger](https://img.shields.io/badge/Hostinger-673DE6?style=for-the-badge&logo=hostinger&logoColor=white)
![GoDaddy](https://img.shields.io/badge/GoDaddy-1BDBDB?style=for-the-badge&logo=godaddy&logoColor=white)

A professional, fully responsive website built for **Lucknow Trading House** — a premier stock market and trading education institute based in Lucknow, India.

🌐 **Live Website:** [lucknowtradinghouse.com](https://lucknowtradinghouse.com)

</div>

---

## 📌 About the Project

This project was developed during my **internship at Lucknow Trading House**. The goal was to design and build a modern, SEO-optimized, and visually compelling website to establish the institute's online presence, showcase their trading courses, and attract prospective students.

> **Note:** This repository contains only the **production build (dist/static export)** of the Next.js application — not the source code.

---

## 🏢 About the Client

**Lucknow Trading House** is a trading education institute founded by **Mr. Akshay Gupta**. Their mission is to provide comprehensive, hands-on trading education covering Indian equities, crypto, forex, and commodities markets. They focus on practical learning through live trading sessions, real-time market analysis, and professional mentorship.

**Location:** Sector 13, near Munshipulia Metro Station, Indira Nagar, Lucknow, India

---

## 🛠️ Tech Stack

| Category         | Technology                                                    |
| ---------------- | ------------------------------------------------------------- |
| **Framework**    | Next.js (React) with Static Export                            |
| **Styling**      | Tailwind CSS v4                                               |
| **Typography**   | Geist Sans & Geist Mono (Custom Web Fonts)                    |
| **Animations**   | AOS (Animate on Scroll), Custom CSS Animations, Spotlight FX  |
| **Media**        | Cloudinary (Image & Video CDN)                                |
| **Widgets**      | TradingView Stock Ticker Widget                               |
| **SEO**          | Open Graph, Twitter Cards, Structured Meta Tags               |
| **Domain**       | GoDaddy                                                       |
| **Hosting**      | Hostinger                                                     |

---

## 📄 Pages & Sections

| Page             | Route           | Description                                                       |
| ---------------- | --------------- | ----------------------------------------------------------------- |
| **Home**         | `/`             | Hero with video background, About section, Features scroll, Testimonials, Events, Head Mentor spotlight |
| **About**        | `/about`        | Detailed institute overview and team information                  |
| **Courses**      | `/courses`      | Three structured course offerings (P.T.P., U.P.T.P., F.T.T.P.)  |
| **Contact**      | `/contact`      | Contact form and institute location details                       |
| **Masterclass**  | `/masterclass`  | Free masterclass registration page                                |
| **Login**        | `/login`        | Student login portal                                              |

### 📚 Course Programs

| Program                           | Duration   | Level        | Highlights                                                         |
| --------------------------------- | ---------- | ------------ | ------------------------------------------------------------------ |
| **P.T.P.** (Primary Trading Program)   | 1 Month  | Beginner     | Basics, 5 strategies, IPO, Smart Investment, Commodities, Psychology |
| **U.P.T.P.** (Ultimate Pro Trading Program) | 3 Months | Intermediate | Indian/Crypto/Forex markets, Options & Derivatives, Live Trading, 15 Strategies (FTR, SMC, MSS) |
| **F.T.T.P.** (Full-Time Trading Program) | 6 Months | Advanced     | All markets, up to 10 trade ideas/day, Advanced strategies, Placement assistance, Certifications |

---

## ✨ Key Features

- **Fully Responsive Design** — Optimized for mobile, tablet, and desktop viewports
- **Dark Theme UI** — Sleek, modern dark interface with cyan/blue accents (`#31b4ed`)
- **Animated Hero Section** — Spotlight effect with looping background video
- **Interactive Navigation** — Desktop navbar + animated mobile slide-out drawer
- **Testimonials Carousel** — Auto-scrolling infinite marquee of student reviews
- **Scroll Animations** — Smooth fade-in effects powered by AOS library
- **TradingView Widget** — Real-time stock market ticker on the homepage
- **Content Sections** — Scrollytelling feature showcase with sticky image
- **Canvas Particle Effect** — Dynamic background animation on the mentor section
- **SEO Optimized** — Comprehensive meta tags, Open Graph, Twitter Cards, structured keywords
- **Social Integration** — Instagram, WhatsApp, Facebook, LinkedIn, YouTube links
- **Cloudinary CDN** — All images and videos served via Cloudinary for optimal performance

---

## 📁 Repository Structure

This repository contains the **static export (dist build)** of the Next.js application:

```
Lucknow-Trading-House/
├── index.html              # Homepage
├── about.html              # About page
├── courses.html            # Courses page
├── contact.html            # Contact page
├── masterclass.html        # Masterclass page
├── login.html              # Login page
├── 404.html                # Custom 404 page
├── _not-found.html         # Next.js not-found page
├── _next/                  # Next.js build assets
│   ├── static/
│   │   ├── chunks/         # JS bundles & CSS files
│   │   ├── media/          # Fonts (Geist Sans & Mono)
│   │   └── dk90zjPwJ7.../  # Build manifest files
│   └── dk90zjPwJ7.../      # Build ID directory
├── about/                  # About route RSC payloads
├── contact/                # Contact route RSC payloads
├── courses/                # Courses route RSC payloads
├── login/                  # Login route RSC payloads
├── masterclass/            # Masterclass route RSC payloads
└── readme.md               # This file
```

> The `.txt` files (e.g., `index.txt`, `__next._full.txt`) are **React Server Component (RSC) payloads** used by Next.js for client-side navigation and hydration.

---

## 🚀 Deployment

The website was deployed using the following infrastructure:

1. **Domain Registration** — Purchased via **GoDaddy** (`lucknowtradinghouse.com`)
2. **Web Hosting** — Deployed on **Hostinger** (static file hosting)
3. **DNS Configuration** — GoDaddy DNS pointed to Hostinger nameservers
4. **Media Delivery** — All images and videos hosted on **Cloudinary CDN**

### Deployment Steps (Reproduction)

```bash
# 1. Build the Next.js project (from source code)
npm run build

# 2. The static export generates the 'out' directory

# 3. Upload the contents of the 'out' directory to Hostinger via File Manager or FTP

# 4. Configure domain DNS on GoDaddy to point to Hostinger
```

---

## 📱 Connect with Lucknow Trading House

| Platform      | Link                                                                 |
| ------------- | -------------------------------------------------------------------- |
| 🌐 Website    | [lucknowtradinghouse.com](https://lucknowtradinghouse.com)           |
| 📸 Instagram  | [@lucknowtradinghouse](https://www.instagram.com/lucknowtradinghouse) |
| 📘 Facebook   | [Lucknow Trading House](https://www.facebook.com/profile.php?id=61573830659280) |
| 💼 LinkedIn   | [Lucknow Trading House](https://www.linkedin.com/in/lucknow-trading-house/) |
| 🎥 YouTube    | [@LucknowTradingHouse](https://www.youtube.com/@LucknowTradingHouse) |
| 💬 WhatsApp   | [Chat Now](https://wa.me/+919005981007)                              |
| 📞 Phone      | +91 9569318082                                                       |
| 📧 Email      | info.lucknowtradinghouse@gmail.com                                   |

---

## 👨‍💻 Developer

**Chandan Chaudhary**
- Role: Web Developer (Intern)
- Internship Period: 2025–2026
- Responsibilities: Full website design, development, and deployment

---

## 📜 License

This project was developed as part of a professional internship engagement. All content, branding, and assets belong to **Lucknow Trading House**. The build artifacts in this repository are shared for portfolio and reference purposes only.

---

<div align="center">

**Built with ❤️ during my internship at Lucknow Trading House**

</div>