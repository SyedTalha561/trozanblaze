# WordPress Live Site Update Guide

If you wish to apply these updates to your live WordPress site at **trozanblaze.wordpress.com**, here is the step-by-step checklist:

---

### 1. Site Title & Tagline (Requirement 2)
1. Go to your WordPress Dashboard: `https://wordpress.com/settings/general/trozanblaze.wordpress.com`
2. Update **Site Title** to: `Trozan Blaze`
3. Update **Site Tagline** to: `AI Content Creator`
4. Click **Save Settings**.

---

### 2. Header Menu with Products (Requirements 3 & 6)
1. In your dashboard, go to **Appearance** → **Menus** (or **Editor** → **Navigation**).
2. Under the primary navigation menu, arrange the items in this order:
   - **AI News** (`https://trozanblaze.wordpress.com/category/ai-news/`)
   - **Products** (Create a new Page called *Products* or custom link)
   - **Contact** (`https://trozanblaze.wordpress.com/contact/`)
3. Save the menu.

---

### 3. Header White Space (Requirement 3)
In **Appearance** → **Customize** → **Additional CSS** (if available on your plan), you can add:
```css
.site-header {
  padding-top: 12px !important;
  padding-bottom: 12px !important;
  margin-top: 0 !important;
}
.entry-header {
  margin-top: 8px !important;
  margin-bottom: 8px !important;
}
```

---

### 4. Updating the Homepage with Live Ticker & Sliding Bar (Requirements 5, 7, 8)
1. Edit your homepage in the WordPress Block Editor: `https://wordpress.com/page/trozanblaze.wordpress.com`
2. Open the **Custom HTML** block containing the automation card.
3. Replace its entire contents with the updated code in `wordpress-export/updated-homepage-block.html`.
4. Click **Update / Publish**.
5. The live page will immediately feature:
   - Updated title and tagline.
   - Smooth running **Live Wire** ticker marquee moving right to left.
   - Updated Instagram (`https://www.instagram.com/trozanblaze/`) and Facebook (`https://www.facebook.com/TrozanTalHa`), with TikTok removed.
   - Restored **Interactive Compounding Sliding Bar** allowing visitors to adjust daily spend from \$1 to \$50 and see live table recalculations!

---

### 5. Contact Page (Requirement 4)
1. Edit your Contact Page (`https://wordpress.com/page/trozanblaze.wordpress.com/contact`).
2. Remove the street address (`73, Augustine Street, Mawson Lakes...`).
3. Remove the email address text (`trozanblaze@gmail.com`).
4. In the Contact Form block settings:
   - Set the recipient email to: `trozanblaze@gmail.com`
   - Center-align the form column.
5. Save changes.
