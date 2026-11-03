# ⚡ Trozan Blaze – Official Web Platform

> **Autonomous Intelligence • Adelaide Hub • Digital Wealth • AI Content Creation**  
> Official repository for [Trozan Blaze](https://trozanblaze.wordpress.com/).

---

## 🌟 Overview & Key Features

This repository contains the standalone, high-performance web platform for **Trozan Blaze**, completely migrated and updated from WordPress with modern responsive architecture, dark cyber/fintech aesthetics, and dynamic client-side engines.

### 1. Updated Branding & Header
- **Brand Title**: Clean, modern typography — `Trozan Blaze` (replacing legacy stylized casing).
- **Tagline**: `AI Content Creator` (replacing legacy "Gaming Content Creator").
- **Header Spacing**: Top whitespace tightly trimmed to **less than 1 cm** (~12px padding) with a sticky backdrop blur effect.
- **Header Menu**: Top-right corner interactive **Menu** dropdown featuring:
  - 📰 **AI News** (`ai-news.html`)
  - ⚡ **Products** (`products.html` - placed before Contact for upcoming digital products)
  - ✉️ **Contact** (`contact.html` / `#contact`)

### 2. Live Wire Continuous Marquee Ticker
- Hardware-accelerated continuous right-to-left marquee running seamlessly on an infinite loop (`transform: translate3d`).
- Automatically pauses on hover for comfortable reading.
- Includes dynamic daily date badge (Adelaide ACDT) and dynamic rotating bulletin headlines.
- Featured alert:
  > `🔴 Live Wire 🔒 [VIP INSIDER] Raiz 3-Year DCA Audit: Eliminating 37% Australian ETF Overlap | 🔒 [VIP PROMPT] 15 Production AI Prompts That Make Life 10x Easier | 🔒 [ADELAIDE AFL] Crows & Port Adelaide Pre-Season Tactical Breakdown`

### 3. Updated Social Dock
- **Instagram**: [https://www.instagram.com/trozanblaze/](https://www.instagram.com/trozanblaze/)
- **Facebook**: [https://www.facebook.com/TrozanTalHa](https://www.facebook.com/TrozanTalHa)
- **Telegram**: [@BeastgravityBot](https://t.me/BeastgravityBot)
- **TikTok**: Completely removed per instruction.

### 4. Interactive Compounding Sliding Bar & Table
- **Sliding Bar**: An interactive slider allowing visitors to adjust their daily micro-investment from **\$1.00/day to \$50.00/day** (default \$5.00/day).
- **Time Horizon Slider**: 1 to 20 years.
- **Dynamic Math Engine**: Calculates daily compound interest at **9.1% CAGR**:
  $$FV = P \times \frac{(1 + r)^{n} - 1}{r}$$
- **Real-Time Recalculation**: Animates total deposits, future portfolio value, and free compound profit live, automatically syncing with the 1Y, 3Y, 5Y, and 10Y comparison table rows!

### 5. Centered Contact Us Section
- Located cleanly in the **center** of the layout / viewport.
- **Physical address completely removed**.
- **Email display text removed** from visible view.
- **Working Form Backend**: Submits inquiries directly to `trozanblaze@gmail.com` via FormSubmit AJAX endpoint without page reload, featuring spam honeypot filtering and instant confirmation feedback.

### 6. Digital Products Showcase (`products.html`)
- Dedicated digital product listings for future releases:
  - **15 Production AI Prompts Vault** (Markdown / Notion prompt vault)
  - **Autonomous Agent Blueprints** (Headless 24/7 Python daemons)
  - **Micro-DCA Compounding Model** (Australian ETF overlap elimination spreadsheet)
- Early access notification card with confetti celebration.

### 7. Bottom Newsletter Box with Confetti Explosion
- Tightened bottom spacing with zero excess whitespace.
- High-performance, zero-dependency HTML5 Canvas Confetti Engine (`launchConfetti()`).
- On subscription submission, bursts 180+ vibrant particle flakes across the screen with gravity and wobble physics.

---

## 📁 Repository Structure

```text
├── index.html                   # Main intelligence hub & homepage
├── ai-news.html                 # AI News archive with all 5 full articles
├── products.html                # Digital products catalog & VIP waitlist
├── contact.html                 # Centered dedicated contact page
├── css/
│   └── style.css                # Master stylesheet (dark theme, variables, typography)
├── js/
│   └── main.js                  # Compounding calculator, ticker, menu, confetti & AJAX
├── assets/
│   ├── logo.jpg                 # Trozan Blaze official logo
│   └── posts/                   # Localized images for all published articles
├── wordpress-export/
│   ├── updated-homepage-block.html # Ready-to-paste Gutenberg Custom HTML block
│   └── WORDPRESS_INSTRUCTIONS.md   # Step-by-step WordPress dashboard guide
├── posts.json                   # Structured JSON archive of all blog posts
├── .gitignore                   # Standard ignore rules
└── README.md                    # Project documentation
```

---

## 🚀 Running Locally & Deployment

### Run Locally
Open `index.html` directly in any web browser, or launch a simple local HTTP server:
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

### Deploying to GitHub Pages
1. Push this repository to GitHub under `SyedTalha561/TrozanBlaze`.
2. Go to **Settings** → **Pages** on your GitHub repository.
3. Under **Branch**, select `main` and `/ (root)`.
4. Click **Save**. Your site will be live instantly with a free SSL certificate!

---

## 📬 Contact & Support
- **Inquiries**: `trozanblaze@gmail.com`
- **Instagram**: [@trozanblaze](https://www.instagram.com/trozanblaze/)
- **Facebook**: [TrozanTalHa](https://www.facebook.com/TrozanTalHa)
- **Telegram**: [@BeastgravityBot](https://t.me/BeastgravityBot)

© 2026 Trozan Blaze. Powered by Beastgravity Autonomous Intelligence.
