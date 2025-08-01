# 🧮 Feature Matrix UI — Responsive Comparison Grid
 
> Tech Focus: `CSS Grid`, `position: sticky`, `scroll-snap`, `container queries`, responsive mobile layout

---

## 🔥 Overview

**Feature Matrix UI** is a responsive pricing/feature comparison table designed for modern SaaS and dashboard interfaces.

The layout presents features on the left and multiple plans across columns, with sticky column headers for easy reference.  
On mobile, the matrix becomes **horizontally scrollable** , allowing for intuitive swipe-based comparison.

It strikes a balance between **clarity**, **responsiveness**, and **developer friendliness** — ideal for premium client dashboards or marketing sites.

---

## 🧪 Browser Support

> ✅ Fully supported across modern browsers (Chrome, Firefox, Safari, Edge)  
---

## 🧱 Features

- Sticky top row with `position: sticky` and z-index layering
- Responsive 5-column grid using `grid-template-columns`
- Clear pricing highlight with special styling on `.Price` rows
- Accessible hover states and contrast-tuned typography
- Optional row striping and scroll hint system
- Fully themeable with CSS variables (`--orange-light`, `--text-primary`, etc.)
- Mobile scrollbar hidden using `::-webkit-scrollbar` inside container queries

---

## 🚀 Tech Stack

- HTML5  
- CSS3 (Vanilla, no frameworks)  
- CSS Grid  
- `position: sticky`, `clamp()`  
- CSS Container Queries

---

## 📱 Responsiveness

- Mobile-first design with horizontal scroll
- Column headers remain sticky across viewports
- Uses `min-width`, `cqw`, and `@container` to adapt layout
- Desktop: grid view with sticky headers  
- Mobile: horizontal scroll with snap-to-plan experience

---

## 🌐 Live Demo

🔗 [View Live Project](https://your-project-url.vercel.app)

---

## 🧠 Design Notes

This layout mirrors industry-standard pricing tables used in:

- SaaS product pages  
- Internal admin dashboards  
- Team/enterprise product breakdowns  
- Feature-to-plan audits

It’s functional, responsive, and elegant — ideal for $300–$350 freelance scope.
