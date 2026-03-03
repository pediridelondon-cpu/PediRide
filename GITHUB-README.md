# PediRide GitHub Website Suite

Complete web presence for PediRide built for GitHub Pages deployment. All data sourced from official business plan submitted to Grow London Local.

---

## 📦 What's Included

### 1. **index.html** - Interactive Business Plan Mapper
Comprehensive visualization of PediRide's business model, roadmap, and market opportunity.

**Audience:** Investors, Grow London Local, general stakeholders

**Key Sections:**
- Overview with Hierarchy of Needs strategy
- Tri-Hybrid Revenue Model (SaaS + Transactions + Advertising)
- 5-Year Implementation Roadmap
- Market Opportunity & TfL Consultation Data
- Platform Suite (PediRide OS, Pay, Ad Network)

### 2. **tfl-website.html** - B2B Regulatory Website
Professional compliance partner presentation specifically for TfL and Westminster Council.

**Audience:** Transport for London, Westminster Council, regulators

**Key Sections:**
- The Enforcement Challenge (consultation data)
- Digital Compliance Infrastructure
- Real-Time Dashboard & Reporting
- Westminster Geofencing
- Partnership Benefits & Timeline

---

## 🚀 GitHub Pages Setup

### Quick Deploy (5 Minutes)

1. **Create Repository**
   ```
   Repository name: pediride
   Public repository
   ✓ Add README
   ```

2. **Upload Files**
   - Upload `index.html`
   - Upload `tfl-website.html`
   - Commit changes

3. **Enable GitHub Pages**
   - Settings → Pages
   - Source: Deploy from branch
   - Branch: main
   - Folder: / (root)
   - Save

4. **Access Your Sites**
   - Business Plan: `https://yourusername.github.io/pediride/`
   - TfL Site: `https://yourusername.github.io/pediride/tfl-website.html`

---

## 📊 Corrected Data (from Official Business Plan)

### Key Metrics
- **Funding:** £95,000 SEIS-eligible
- **Break-Even:** Month 9 at 48 vehicles
- **Market Size:** 400 active pedicabs
- **Market Value:** £12M annual revenue (100% cash currently)

### Revenue Model - "Tri-Hybrid"
1. **SaaS:** £35/vehicle/month (£420/year)
2. **Transactions:** 8% commission on digital fares
3. **Advertising:** £500/vehicle per 4-week campaign (Year 2+)

### Financial Projections

| Metric | Year 1 | Year 2 | Year 3 |
|--------|--------|--------|--------|
| **Vehicles** | 50 (12.5%) | 150 (37.5%) | 250 (62.5%) |
| **Digital Adoption** | 40% | 55% | 70% |
| **Total Rides** | 50,000 | 206,250 | 437,500 |
| **GMV** | £600K | £2.48M | £5.25M |
| **SaaS Revenue** | £10,500 | £63,000 | £105,000 |
| **Transaction Fees** | £34,560 | £198,000 | £420,000 |
| **Advertising** | £0 | £50,000 | £200,000 |
| **TOTAL REVENUE** | £45,060 | £311,000 | £725,000 |
| **Net Profit** | (£17,540) | £190,825 | £525,450 |
| **Net Margin** | -39% | 61% | 72% |

### TfL Consultation Data (March 2025)
- **85%** of passengers report overcharging
- **75%** feel unsafe using pedicabs
- **92-97%** public support for licensing controls
- **60%** of users are tourists
- **1,000,000** annual rides currently
- **Zero organized opposition:** Only 18 operators (0.3%) opposed regulation

---

## 🎯 Usage Guide

### For Different Audiences

**Investors / Grow London Local:**
- Use `index.html` (Business Plan Mapper)
- Walk through: Overview → Tri-Hybrid Model → Market → Roadmap
- Highlight: 11.2x SEIS-enhanced return, 6.1x base case

**TfL / Westminster Council:**
- Use `tfl-website.html`
- Focus on: Compliance Dashboard, Automated Reporting, Geofencing
- Emphasize: Zero cost to TfL, operator-funded infrastructure

**Pedicab Operators:**
- Use `index.html`
- Focus on: Platform features, compliance benefits
- Messaging: "Avoid vehicle seizure - automate TfL compliance"

**Media / PR:**
- Use `index.html` for industry transformation narrative
- Stats: 85% overcharging → transparent digital pricing
- Angle: "Fixing London's pedicab crisis"

---

## 🔧 Customization

### Updating Revenue Data

In `index.html`, find the JavaScript section:

```javascript
const revenueData = {
    1: { 
        saas: '£10,500', 
        transactions: '£34,560', 
        advertising: '£0', 
        total: '£45,060',
        // Update values here
    }
}
```

### Changing Contact Information

In `tfl-website.html`, update:

```html
<a href="mailto:pediridelondon@gmail.com">pediridelondon@gmail.com</a>
<a href="tel:07496181387">07496 181 387</a>
```

### Brand Colors

Both sites use consistent color scheme:
- **Primary Blue:** #3B82F6 (trust, regulatory)
- **Emerald Green:** #10B981 (growth, compliance)
- **Cyan:** #00B8D9 (innovation, data)
- **Purple:** #8B5CF6 (premium, advertising)

---

## 📱 Mobile Responsive

Both websites are fully responsive:
- Desktop: Full multi-column layouts
- Tablet: Adaptive grid systems
- Mobile: Stacked single-column, collapsible navigation

Test on:
- Chrome DevTools (F12 → Device toolbar)
- Real devices before sharing with stakeholders

---

## 🖨️ PDF Export

Both sites support print-to-PDF:

1. Open website
2. Click "Export PDF" or "Download Brief" button
3. Browser print dialog opens
4. Select "Save as PDF"
5. Share offline

**Print optimized:**
- Hides navigation buttons
- Single-column layout
- High-contrast colors
- Page breaks at logical sections

---

## 🔐 Security & Privacy

### No Sensitive Data
- No API keys in code
- No database connections
- Pure static HTML/CSS/JS
- Safe to make repository public

### GDPR Compliance
- No cookies or tracking
- No analytics (add Google Analytics later if needed)
- No user data collection
- Privacy-first design

---

## 🎨 Design Philosophy

### Business Plan Site (`index.html`)
- **Aesthetic:** Modern, data-driven, trustworthy
- **Typography:** Outfit (body) + Space Grotesk (headers)
- **Purpose:** Visualize complex financial model clearly
- **Tone:** Confident but accessible

### TfL Site (`tfl-website.html`)
- **Aesthetic:** Professional, gov-tech, institutional
- **Typography:** IBM Plex Sans + IBM Plex Mono
- **Purpose:** Compliance partner positioning
- **Tone:** Regulatory, data-focused, partnership-oriented

---

## 🚢 Deployment Checklist

Before going live:

- [ ] Test both sites on mobile devices
- [ ] Verify all data matches business plan
- [ ] Check all links work correctly
- [ ] Test PDF export functionality
- [ ] Confirm contact info is correct
- [ ] Review for typos/errors
- [ ] Test on multiple browsers (Chrome, Firefox, Safari)
- [ ] Get feedback from 1-2 trusted advisors

---

## 📈 SEO & Discoverability

### Meta Tags (Optional Enhancement)

Add to `<head>` section of both files:

```html
<meta name="description" content="PediRide - Compliance operating system for London's pedicab industry. SEIS-eligible £95K investment opportunity.">
<meta name="keywords" content="pedicab, London transport, TfL, compliance, SEIS investment">
<meta property="og:title" content="PediRide - Pedicab Compliance Platform">
<meta property="og:description" content="Digital infrastructure for London's newly regulated pedicab sector">
```

### Custom Domain (Optional)

Purchase `pediride.co.uk`:

1. Buy domain from Namecheap/Google Domains (~£10/year)
2. In GitHub Settings → Pages → Custom domain
3. Enter: `www.pediride.co.uk`
4. Configure DNS at registrar:
   ```
   CNAME: www → yourusername.github.io
   ```
5. GitHub provides free HTTPS automatically

---

## 🔄 Version Control

### Making Updates

1. Edit files locally or in GitHub
2. Commit changes with clear message:
   ```
   "Updated Year 2 revenue projections"
   "Added new TfL partnership section"
   ```
3. Push to main branch
4. GitHub Pages auto-deploys (1-2 minutes)

### Rollback if Needed

1. Go to repository → Commits
2. Find last working version
3. Click "..." → "Revert this commit"

---

## 📧 Sharing Links

### Email Templates

**For Investors:**
```
Subject: PediRide Business Plan - SEIS-Eligible £95K Opportunity

Hi [Name],

I'm seeking £95K SEIS investment for PediRide, the compliance platform for 
London's newly regulated pedicab industry.

Interactive business plan: https://yourusername.github.io/pediride/

Key metrics:
• Break-even: Month 9 (48 vehicles)
• Year 3: £725K revenue, 72% margin
• SEIS-enhanced return: 11.2x

Happy to discuss further.

Best,
Tuoyo
```

**For TfL:**
```
Subject: Partnership Proposal - Pedicab Compliance Infrastructure

Dear [TfL Contact],

Following recent pedicab regulation developments, I'd like to propose PediRide 
as your compliance data partner.

Regulatory solution overview: https://yourusername.github.io/pediride/tfl-website.html

We provide zero-cost-to-TfL compliance dashboards, automated Act 2024 reporting, 
and Westminster geofencing support.

Could we schedule a 30-minute discussion?

Best regards,
Tuoyo Sakpere
```

---

## 🐛 Troubleshooting

### Site Not Loading
- Wait 2-3 minutes after enabling Pages
- Clear browser cache (Ctrl+Shift+R)
- Check Settings → Pages shows "Your site is published"
- Verify files are named exactly `index.html` (case-sensitive)

### Styles Not Working
- Tailwind CDN might be blocked - try different network
- Check browser console (F12) for errors
- Verify `<script src="https://cdn.tailwindcss.com"></script>` is present

### Icons Missing
- Lucide CDN issue - check internet connection
- Look for: `<script src="https://unpkg.com/lucide@latest"></script>`
- Alternative: Replace with emoji (🔒 instead of lock icon)

### Mobile Layout Broken
- Test in Chrome DevTools device emulator first
- Check for horizontal scroll (viewport width issue)
- Verify responsive classes: `md:grid-cols-2` etc.

---

## 📞 Support & Feedback

### For Technical Issues
- Check this README first
- Review browser console errors
- Test in incognito mode (rules out extensions)

### For Content Updates
Edit business plan data in JavaScript sections:
- `revenueData` object
- `roadmapData` array
- Static text in HTML

---

## 🎓 Learning Resources

### GitHub Pages
- Official docs: https://pages.github.com
- Custom domains: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

### Tailwind CSS
- Quick reference: https://tailwindcss.com/docs
- For color changes, utility classes

### Lucide Icons
- Icon library: https://lucide.dev
- Search icons, copy component code

---

## 📄 License & Usage

**Created for:** PediRide Limited  
**Founder:** Tuoyo Sakpere  
**Purpose:** Investor presentations, regulatory engagement

**Permitted Use:**
- ✅ Share with investors and stakeholders
- ✅ Present to TfL and Westminster Council
- ✅ Include in pitch decks
- ✅ Modify data as business evolves
- ✅ Use in PR and media outreach

**Keep Confidential:**
- Financial projections
- Funding requirements
- Strategic roadmap details

---

## 🔮 Future Enhancements

Consider adding:
- [ ] Live chat widget (Intercom/Drift)
- [ ] Email capture form for updates
- [ ] Video embed explaining the platform
- [ ] Investor FAQ section
- [ ] Case study from pilot operator
- [ ] Interactive financial calculator
- [ ] Google Analytics for traffic tracking
- [ ] Contact form integration (Formspree/Netlify Forms)

---

## ✅ Final Checklist

Before sharing widely:

- [ ] Both sites load correctly on your GitHub Pages URL
- [ ] All data matches your official business plan
- [ ] Contact information is correct
- [ ] Mobile display works properly
- [ ] PDF export generates clean documents
- [ ] No spelling or grammatical errors
- [ ] Links open in new tabs where appropriate
- [ ] Tested on at least 2 different browsers
- [ ] Shared with 1-2 advisors for feedback
- [ ] Ready to send to investors and TfL!

---

**Version:** 2.0 (Corrected Data)  
**Last Updated:** March 2026  
**Data Source:** PediRide Business Plan 2026 - Grow London Local Submission

**Questions?** Email pediridelondon@gmail.com
