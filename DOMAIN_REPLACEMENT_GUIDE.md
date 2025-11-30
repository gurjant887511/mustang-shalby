# 🔧 DOMAIN REPLACEMENT GUIDE

**Important:** Follow these exact steps to complete your SEO setup!

---

## ⚠️ CRITICAL: Replace Your Domain

All instances of `https://your-domain.com` must be replaced with your actual domain.

### Step 1: Gather Your Information
- Your domain: ____________________________________________
- Your email: _____________________________________________
- Your phone: _____________________________________________

Example (if your domain is `mustang-shelby-cars.com`):
- Replace: `https://your-domain.com`
- With: `https://mustang-shelby-cars.com`

---

## 📝 Files That Need Updating

### File 1: `index.html`
**Find and replace 7 occurrences:**

| Line # | Search For | Replace With |
|--------|-----------|-------------|
| 1 | `https://your-domain.com` | YOUR_DOMAIN |
| 2 | `https://your-domain.com` | YOUR_DOMAIN |
| 3 | `https://your-domain.com` | YOUR_DOMAIN |
| 4 | `https://your-domain.com` | YOUR_DOMAIN |
| 5 | `https://your-domain.com` | YOUR_DOMAIN |
| 6 | `https://your-domain.com` | YOUR_DOMAIN |
| 7 | `https://your-domain.com` | YOUR_DOMAIN |

**Quick Replace Method (VS Code):**
1. Open `index.html`
2. Press `Ctrl+H` (Find & Replace)
3. Find: `https://your-domain.com`
4. Replace: `https://your-domain.com` (your actual domain)
5. Click "Replace All"

---

### File 2: `about.html`
**Find and replace 4 occurrences:**
- Line: `<meta property="og:url" content="https://your-domain.com/about.html">`
- Line: `<link rel="canonical" href="https://your-domain.com/about.html">`
- Line: `"url": "https://your-domain.com"`
- Line: In Organization schema

---

### File 3: `gt500-details.html`
**Find and replace 3 occurrences:**
- Line: `<meta property="og:url" content="https://your-domain.com/gt500-details.html">`
- Line: `<link rel="canonical" href="https://your-domain.com/gt500-details.html">`
- Line: In Product schema

---

### File 4: `gt350-details.html`
**Find and replace 3 occurrences:**
- Line: `<meta property="og:url" content="https://your-domain.com/gt350-details.html">`
- Line: `<link rel="canonical" href="https://your-domain.com/gt350-details.html">`
- Line: In Product schema

---

### File 5: `engine-details.html`
**Find and replace 2 occurrences:**
- Line: `<meta property="og:url" content="https://your-domain.com/engine-details.html">`
- Line: `<link rel="canonical" href="https://your-domain.com/engine-details.html">`

---

### File 6: `dct-details.html`
**Find and replace 2 occurrences:**
- Line: `<meta property="og:url" content="https://your-domain.com/dct-details.html">`
- Line: `<link rel="canonical" href="https://your-domain.com/dct-details.html">`

---

### File 7: `aerodynamics-details.html`
**Find and replace 2 occurrences:**
- Line: `<meta property="og:url" content="https://your-domain.com/aerodynamics-details.html">`
- Line: `<link rel="canonical" href="https://your-domain.com/aerodynamics-details.html">`

---

### File 8: `faq.html`
**Find and replace 3 occurrences:**
- Line: `<meta property="og:url" content="https://your-domain.com/faq.html">`
- Line: `<link rel="canonical" href="https://your-domain.com/faq.html">`
- Line: In FAQPage schema (if present)

---

### File 9: `sitemap.xml`
**Find and replace ALL occurrences:**

```xml
BEFORE:
<loc>https://your-domain.com</loc>
<loc>https://your-domain.com/gt500-details.html</loc>
<loc>https://your-domain.com/about.html</loc>
etc.

AFTER:
<loc>https://YOUR-ACTUAL-DOMAIN.COM</loc>
<loc>https://YOUR-ACTUAL-DOMAIN.COM/gt500-details.html</loc>
<loc>https://YOUR-ACTUAL-DOMAIN.COM/about.html</loc>
etc.
```

**Count:** 8 URLs × 1 = 8 replacements

---

### File 10: `robots.txt`
**Find and replace 1 occurrence:**

```
BEFORE:
Sitemap: https://your-domain.com/sitemap.xml

AFTER:
Sitemap: https://YOUR-ACTUAL-DOMAIN.COM/sitemap.xml
```

---

## ✅ EASY METHOD: Find & Replace All

### In Visual Studio Code:

1. **Open Project Folder** (File → Open Folder → Select mustang-shallby)

2. **Open Find & Replace**
   - Press: `Ctrl+Shift+H` (Windows/Linux)
   - Or: `Cmd+Shift+H` (Mac)

3. **Configure Search**
   - Find: `https://your-domain.com`
   - Replace: `https://YOUR-ACTUAL-DOMAIN.COM` (your domain)

4. **Search Scope**
   - Click on "Find in files" icon
   - OR use `.` to search current folder
   - Make sure ABC icon is OFF (case-sensitive search)

5. **Replace All**
   - Click "Replace All" button (right side of Replace field)
   - Should replace ~28 occurrences

6. **Verify**
   - Press `Ctrl+Shift+F` to open Find
   - Search: `your-domain.com`
   - Should find 0 results

---

## 🔍 VERIFICATION CHECKLIST

After replacement, verify each file:

### Check index.html:
```html
✓ <meta property="og:url" content="https://YOUR-DOMAIN.COM">
✓ <link rel="canonical" href="https://YOUR-DOMAIN.COM">
✓ "url": "https://YOUR-DOMAIN.COM"
✓ In all schema blocks
```

### Check about.html:
```html
✓ <meta property="og:url" content="https://YOUR-DOMAIN.COM/about.html">
✓ <link rel="canonical" href="https://YOUR-DOMAIN.COM/about.html">
```

### Check gt500-details.html:
```html
✓ <meta property="og:url" content="https://YOUR-DOMAIN.COM/gt500-details.html">
✓ <link rel="canonical" href="https://YOUR-DOMAIN.COM/gt500-details.html">
```

### Check sitemap.xml:
```xml
✓ <loc>https://YOUR-DOMAIN.COM</loc>
✓ <loc>https://YOUR-DOMAIN.COM/gt500-details.html</loc>
✓ (8 total URLs)
```

### Check robots.txt:
```
✓ Sitemap: https://YOUR-DOMAIN.COM/sitemap.xml
```

---

## 🎯 SEARCH STRINGS

For your convenience, here are all search strings:

```
https://your-domain.com
https://your-domain.com/
https://your-domain.com/about.html
https://your-domain.com/gt500-details.html
https://your-domain.com/gt350-details.html
https://your-domain.com/engine-details.html
https://your-domain.com/dct-details.html
https://your-domain.com/aerodynamics-details.html
https://your-domain.com/faq.html
```

---

## 📊 REPLACEMENT SUMMARY

| File | Occurrences | Type |
|------|-------------|------|
| index.html | 7 | META, CANONICAL, SCHEMA |
| about.html | 4 | META, CANONICAL |
| gt500-details.html | 3 | META, CANONICAL, SCHEMA |
| gt350-details.html | 3 | META, CANONICAL, SCHEMA |
| engine-details.html | 2 | META, CANONICAL |
| dct-details.html | 2 | META, CANONICAL |
| aerodynamics-details.html | 2 | META, CANONICAL |
| faq.html | 3 | META, CANONICAL, SCHEMA |
| sitemap.xml | 8 | URLs |
| robots.txt | 1 | SITEMAP |
| **TOTAL** | **35** | **Replacements** |

---

## ⚡ QUICK STEPS

1. Open your project in VS Code
2. Press `Ctrl+Shift+H`
3. Find: `https://your-domain.com`
4. Replace: `https://your-domain-name.com` (YOUR DOMAIN)
5. Click "Replace All"
6. Save all files (`Ctrl+K, Ctrl+S`)
7. Verify no more instances of "your-domain.com"

---

## 🚀 AFTER REPLACEMENT

### Next Actions:

1. **Upload to Hosting**
   - Upload all files to your web server
   - Ensure HTTPS/SSL is enabled

2. **Verify in Google Search Console**
   - Go to: https://search.google.com/search-console
   - Add property with your domain
   - Verify ownership
   - Submit sitemap.xml
   - Request indexing

3. **Test Pages**
   - Visit: https://your-domain.com
   - Visit: https://your-domain.com/about.html
   - Visit: https://your-domain.com/faq.html
   - Verify all pages load correctly

4. **Monitor Analytics**
   - Set up Google Analytics 4
   - Monitor organic traffic
   - Track keyword rankings

---

## ⚠️ IMPORTANT NOTES

- **Don't forget HTTPS:** Must be `https://` NOT `http://`
- **No trailing slash:** Use `https://domain.com` not `https://domain.com/`
- **Consistent format:** Use same format throughout (with or without www)
- **Case sensitivity:** Domain names are case-insensitive but keep consistent
- **Save files:** After replacement, save all files
- **Test thoroughly:** Check all links work after replacement

---

## 🆘 TROUBLESHOOTING

**Problem:** Still seeing "your-domain.com" in page
- Solution: Check browser cache, do hard refresh (Ctrl+Shift+Delete)

**Problem:** Links showing wrong domain
- Solution: Verify all files saved, check for typos in replacement

**Problem:** Google Search Console says "Verify domain"
- Solution: Use HTML file method or DNS record method provided by GSC

**Problem:** Pages not showing in search
- Solution: Wait 5-7 days, submit to GSC, check sitemap submitted

---

## 📞 SUPPORT

If you need help:
1. Check exact domain format (www vs non-www)
2. Verify HTTPS is working
3. Contact your hosting provider for certificate setup
4. Review Google Search Console help docs
5. Test with https://validator.schema.org

---

**Good luck! Your SEO optimization is almost complete!**

Just one more step: Replace the domain and you're ready to rank! 🚀
