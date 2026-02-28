# Deployment Guide

## GitHub Pages Deployment

### Step 1: Create Repository
1. Go to https://github.com/new
2. Repository name: `bajarangi-constructions`
3. Make it **Public**
4. Click "Create repository"

### Step 2: Push Code
Run these commands:
```bash
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to repository Settings
2. Click "Pages" in sidebar
3. Source: Select "main" branch
4. Click "Save"
5. Wait 2-3 minutes

### Step 4: Your Website URL
```
https://anil-web18.github.io/bajarangi-constructions/
```

## Video Setup (Important!)

The video file is excluded from GitHub (too large).

### Option 1: YouTube (Recommended)
1. Upload video to YouTube
2. Set as "Unlisted" (not public)
3. Copy video ID from URL
4. Replace `YOUR_VIDEO_ID` in index.html line 223

### Option 2: Google Drive
1. Upload video to Google Drive
2. Make it "Anyone with link can view"
3. Get shareable link
4. Use embed code in index.html

### Option 3: Remove Video Section
Comment out or delete the promo video section if not needed.

## Social Media Links

Update footer social media links:
- Facebook: Line 485
- Instagram: Line 486
- LinkedIn: Line 487
- YouTube: Line 488

## Contact Form

The contact form currently shows an alert. To make it functional:
1. Use FormSpree (https://formspree.io)
2. Use EmailJS (https://www.emailjs.com)
3. Or connect to your backend

## Custom Domain (Optional)

To use your own domain:
1. Buy domain from GoDaddy/Namecheap
2. Add CNAME file with your domain
3. Configure DNS settings
4. Update in GitHub Pages settings
