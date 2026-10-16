# Vaseem Anwar — Senior Software Engineer Portfolio (Fixed Release)

## What Was Fixed
1. **Resolved All 8 Broken Images (Zero-404 Guarantee)**:
   - Embedded high-resolution, optimized Base64 data URIs directly inside `index.html` AND bundled the standalone image files inside `img/` for:
     - Top Navbar Avatar & Hero Profile Portrait (`img/profile-avatar.jpg`)
     - Project 1: Enterprise Loan Origination System (`img/project-los.jpg`)
     - Project 2: ABCD — Aditya Birla Capital Super-App (`img/project-abcd.jpg`)
     - Project 3: My Wallet — Personal Finance & Analytics (`img/project-mywallet.jpg`)
     - Project 4: FlutterGram — Developer Community & Feed (`img/project-fluttergram.jpg`)
     - Project 5: Netflix Media App & Eazy Video Meetings (`img/project-netflix-eazy.jpg`)
     - Project 6: Zomato Calicut, Hyundai Kona & YouTube Web Interfaces (`img/project-webclones.jpg`)
     - Endorsements 1–5 (`img/testimonial-fayis.png`, `img/testimonial-nasikh.png`, `img/testimonial-thajul.png`, `img/testimonial-rayan.png`, `img/testimonial-jasir.png`)
2. **Fixed Sticky Navbar Overlap on Anchor Jumps**:
   - Added `scroll-padding-top: 5.5rem` on `html` and `scroll-margin-top: 5.5rem` on all `section[id]` elements so jumping to `#overview`, `#architecture`, `#experience`, `#projects`, `#education`, `#endorsements`, or `#contact` never obscures section headings.
3. **Upgraded Contact Form to Asynchronous AJAX Submission**:
   - Connected form submission to `https://formsubmit.co/ajax/vaseemanwarafi@gmail.com` with client-side validation and in-page confirmation banners so visitors aren't redirected away from your portfolio.
4. **Accessible Quick Jump (`⌘K` / `Ctrl+K`), Interactive Case Study Modals & Theme Toggle**:
   - Added `aria-haspopup="dialog"`, `Escape` key handling, mobile navigation drawer, and WCAG-compliant Light/Dark mode variables.

## Quick Deploy to GitHub & Netlify (`vaseemanwar.netlify.app`)
Replace `index.html` in your repository (`github.com/vaseemva/Personalwebsite`) and push:

```bash
git add index.html img/
git commit -m "fix: embed all portfolio images and resolve scroll/form issues"
git push origin main
```
