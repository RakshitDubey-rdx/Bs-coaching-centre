# BS Coaching Centre 🎓

A modern, high-performance landing page for **BS Coaching Centre** (Nangloi, New Delhi) featuring an interactive frame-by-frame canvas scroll animation, floating glassmorphic navigation bar, interactive course catalogs, student testimonials, and instant demo pass booking.

---

## 🚀 Features

- **Apple-Style Scroll Scrubbing Animation**: 240 high-resolution frames loaded smoothly onto an HTML5 `<canvas>` that scrub fluidly in sync with page scroll.
- **Glassmorphic Floating Navigation**: Small, rounded floating pill navbar with frosted glass (`backdrop-filter: blur()`), drop shadows, quick links, and a mobile drawer.
- **Interactive Course Hub**: Dynamic tab switcher for **Government Exam Preparation** (SSC, Banking, Defence, Railway, CTET) and **Computer & Skill Development** (ADCA, Digital Marketing, Graphic Design, Tally Prime).
- **Live Counter Benchmark Metrics**: Dynamic scroll-triggered number counting for selections, students trained, and ratings.
- **Trustindex & Google Reviews**: Verified testimonials from past students.
- **Lead Generation & Demo Pass**: Interactive registration modal with immediate feedback.
- **Vercel-Ready**: Zero-configuration static deployment with immutable edge caching configured in `vercel.json`.

---

## 📦 Project Structure

```
├── frames/                 # 240 sequence frames (ezgif-frame-001.jpg - 240.jpg)
├── index.html              # Main application page
├── vercel.json             # Vercel CDN headers and caching configuration
├── package.json            # Scripts & project metadata
├── .gitignore              # Ignored files
└── README.md               # Documentation
```

---

## ⚡ Deployment to Vercel

### Option 1: Import via Vercel Dashboard (Recommended)
1. Go to [vercel.com/new](https://vercel.com/new).
2. Connect your GitHub account and import **`RakshitDubey-rdx/Bs-coaching-centre`**.
3. Leave all build settings as default (Framework Preset: **Other**; Root Directory: `./`).
4. Click **Deploy**. Vercel will deploy it in seconds with global edge CDN caching!

### Option 2: Deploy using Vercel CLI
```bash
npm i -g vercel
vercel
```

---

## 💻 Local Development

You can run the project locally using Python or Node:

### Using Python:
```bash
python -m http.server 8080
```
Then visit [http://localhost:8080](http://localhost:8080).

### Using Node / npx:
```bash
npx serve .
```

---

## 📄 License
MIT License.
