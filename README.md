# 🎯 Goal2Govt

**Goal2Govt – Your Goal. Your Government Job.**

Goal2Govt is a single-page website that helps students and job seekers explore government job opportunities in India, organized by qualification level — **10th pass**, **12th pass**, and **Graduate** — with eligibility details, exam stages, a step-by-step preparation road map, and a practice quiz for each post.

🌐 **Website:** goal2govt.com

---

## 🚀 About Goal2Govt

Finding the right government job notification shouldn't be difficult.

Goal2Govt organizes 28+ major government job categories (SSC, UPSC, Railways, Banking, Defence, Police, Postal, PSU and more) into three simple entry routes based on qualification, so aspirants can quickly find posts they're eligible for and understand exactly what preparing for them looks like.

---

## ✨ Features

- 🎓 Qualification-based job search (After 10th / After 12th / After Graduation)
- 🏛️ 28 government job profiles across SSC, UPSC, Railways, Banking, Defence, Police, Postal and PSU
- 📋 Per-job **Overview**, **Eligibility** (age & education), **Exam Stages**, **Road Map**, and **Official Links** tabs
- 🧠 Built-in **practice quiz** (10 random questions per job, tier-appropriate) with navigation, scoring, and a "new set" shuffle
- 📱 Responsive, mobile-friendly design
- ✏️ Editable welcome banner section for custom text/images
- 📊 Simple per-browser visit counter
- ⚠️ Built-in disclaimer reminding users to verify details on official recruiting-body websites

---

## 🏛️ Job Categories Covered

- SSC (MTS, CHSL, CGL, GD Constable, CPO)
- UPSC (Civil Services, CDS/CAPF, NDA)
- Railway / RRB (Group D, NTPC)
- Banking (Bank PO)
- Defence (Army Agniveer, Navy SSR, Air Force Agniveer)
- Police (State Police Constable)
- Postal (India Post GDS, Postal/Sorting Assistant)
- PSU Apprenticeships
- State PSC (Group 1/2, LDC/Junior Assistant)
- Forest Department & other state jobs
- EPFO, Income Tax Inspector, and other Group A/B posts

---

## 🛠️ Technologies

Built with:

- HTML5
- CSS3 (custom design system, no framework)
- Vanilla JavaScript (no build step, no dependencies)

Everything lives in a single `index.html` file — open it directly in a browser or deploy it to any static host (GitHub Pages, Netlify, etc.).

---

## 📁 Project Structure

```
goal2govt/
└── index.html   # entire site: markup, styles, job data, and interactivity
```

- **Home section** — hero copy, editable banner, three qualification cards, "why/tips" info strips
- **Category pages** — filtered job lists per qualification tier
- **Detail overlay** — tabbed view (Overview / Eligibility / Exam Stages / Road Map / Quiz / Official Links) for each job, opened without leaving the page
- All job data, road maps, and quiz question pools are stored in JS objects/arrays near the bottom of the file, making it straightforward to add or edit a job entry

---

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/Build-exe/goal2govt.git
   ```
2. Open `index.html` in your browser — no build tools or server required.
3. To deploy, upload `index.html` to any static hosting provider (GitHub Pages, Netlify, Vercel, etc.).

### Adding or editing a job

Find the `jobs` array in the `<script>` section and add an object with the same shape (`id`, `tier`, `code`, `name`, `body`, `overview`, `age`, `edu`, `salary`, `stages`, `roadmapType`, `resources`). It will automatically appear in its tier's category page and detail overlay.

---

## 🎯 Our Mission

> **Make government job information easy to find, easy to understand, and accessible to every aspirant.**

Goal2Govt focuses on providing useful information without unnecessary complexity.

---

## ⚠️ Disclaimer

Goal2Govt is an **independent informational platform** and is **not affiliated with, endorsed by, or associated with any government organization or department**.

Job notifications, exam information, dates, eligibility criteria, salary figures, and other details are collected and presented for informational purposes only. Ages, salaries, vacancy numbers, and exam patterns change with every official notification — **always verify current details on the recruiting body's own website before applying.**

Goal2Govt is not responsible for changes, errors, or decisions made by official recruiting organizations.

---

## 🔐 Privacy

Goal2Govt respects user privacy. The site currently stores only a local, per-browser visit count (via `localStorage`) and does not send data to any server. Please refer to the website's Privacy Policy for complete information.

---

## 📌 Project Status

🚧 **Goal2Govt is currently under active development.**

New features, job categories, and improvements will continue to be added.

---

## ❤️ Support Goal2Govt

If Goal2Govt helps you, consider sharing the platform with other government job aspirants.

**One Goal. One Platform. Goal2Govt. 🎯**

---

© 2026 Goal2Govt. All Rights Reserved.
