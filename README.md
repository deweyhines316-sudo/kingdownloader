# 👑 KingDownloader — Vercel Deployment Guide

## Folder Structure
```
kingdownloader/
├── api/
│   └── download.py      ← Backend (yt-dlp serverless function)
├── public/
│   └── index.html       ← Frontend website
├── requirements.txt     ← Python dependencies
└── vercel.json          ← Vercel configuration
```

---

## 🚀 Deploy in 5 Minutes (FREE)

### Step 1 — GitHub e upload koro
1. **github.com** e jao → New Repository → Name: `kingdownloader`
2. Shob files upload karo (api/, public/, vercel.json, requirements.txt)
3. Commit karo

### Step 2 — Vercel e deploy koro
1. **vercel.com** e jao → Sign up with GitHub (free)
2. "New Project" click karo
3. Tomar `kingdownloader` repo select karo
4. **Deploy** click karo — 2 minutes e live!

### Step 3 — Done! 🎉
Vercel ekta URL dibe jemon: `https://kingdownloader.vercel.app`

---

## ✅ Supported Platforms (yt-dlp powered)
- YouTube (4K, 1080p, 720p, MP3)
- TikTok (no watermark)
- Instagram (Reels, Stories, Posts)
- Facebook Videos
- Twitter/X Videos
- Reddit Videos
- Vimeo
- 1000+ more sites!

---

## ⚙️ How it works
1. User pastes URL on website
2. Frontend calls `/api/download?url=...`
3. Vercel runs `download.py` (Python serverless)
4. Python runs `yt-dlp` to get direct download links
5. Links returned to browser
6. User clicks SAVE — file downloads directly!

---

## 🆓 Free Tier Limits (Vercel)
- 100GB bandwidth/month
- 100,000 function invocations/month
- Plenty for personal use!

---

## 📝 Notes
- yt-dlp auto-installs via requirements.txt
- No API key needed — yt-dlp is open source
- Supports 1000+ platforms out of the box
