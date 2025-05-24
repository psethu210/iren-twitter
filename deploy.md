# Quick Deployment Guide

## Option 1: GitHub Pages (Recommended - FREE)

### Why GitHub Pages?
- ✅ Completely FREE hosting
- ✅ Global CDN for fast loading
- ✅ HTTPS by default
- ✅ Easy custom domain setup
- ✅ Automatic deployments
- ✅ Great for SEO indexing

### Steps:

1. **Create GitHub Account** (if you don't have one)
   - Go to github.com
   - Sign up for free

2. **Create New Repository**
   - Click "New repository"
   - Name: `iren-stock-influencers`
   - Make it Public (required for free GitHub Pages)
   - Initialize with README: ❌ (we have our own files)

3. **Upload Your Files**
   - Upload `index.html`, `README.md`, `robots.txt`, `sitemap.xml`
   - Or use git commands from the README

4. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Source: "Deploy from a branch"
   - Branch: "main"
   - Folder: "/ (root)"
   - Click Save

5. **Your Site is Live!**
   - URL: `https://yourusername.github.io/iren-stock-influencers/`
   - Takes 5-10 minutes to go live

## Option 2: Alternative Free Hosts

### Netlify (Also Great)
1. Sign up at netlify.com
2. Drag and drop your files
3. Get instant deployment
4. Custom domain support

### Vercel
1. Sign up at vercel.com
2. Import from GitHub
3. Automatic deployments
4. Excellent performance

### Cloudflare Pages
1. Sign up at pages.cloudflare.com
2. Connect GitHub repository
3. Super fast global CDN
4. Advanced optimization features

## Custom Domain Setup (Optional)

### If you want a custom domain like `irenstockinfluencers.com`:

1. **Buy a domain** from:
   - Namecheap ($8-12/year)
   - GoDaddy ($10-15/year)
   - Cloudflare ($8-10/year)

2. **Configure DNS**:
   - Add CNAME record: `www` → `yourusername.github.io`
   - Add A records for apex domain:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```

3. **Update GitHub Pages Settings**:
   - Add your custom domain
   - Enable "Enforce HTTPS"

## SEO Submission

### Submit to Search Engines:

1. **Google Search Console**
   - Add property: your-domain.com
   - Verify ownership
   - Submit sitemap: `your-domain.com/sitemap.xml`

2. **Bing Webmaster Tools**
   - Add site
   - Submit sitemap

### Expected Indexing Time:
- Google: 1-7 days
- Bing: 1-14 days
- Other search engines: 2-30 days

## AdSense Setup

1. **Apply for AdSense**
   - Need 10-20 daily visitors first
   - Original, valuable content
   - Privacy policy (add to footer)

2. **Replace Ad Placeholders**
   - Update the `.ad-space` divs in index.html
   - Add your AdSense publisher ID

## Performance Monitoring

### Tools to Track:
- Google PageSpeed Insights
- GTmetrix
- Google Analytics
- Google Search Console

### Expected Metrics:
- Page Load: < 500ms
- Core Web Vitals: All green
- Mobile Usability: Perfect score

---

**Total Setup Time**: 15-30 minutes
**Total Cost**: $0 (or $8-15/year for custom domain)
**Maintenance**: 5 minutes/month 