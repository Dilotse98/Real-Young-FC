# Real Young FC — Sponsorship Proposal Website

A single-page, mobile-friendly website version of the Real Young FC sponsorship proposal — built to be shared as a link and turned into a QR code for sponsor packs, matchday, and print materials.

## What's in this folder
```
site/
├── index.html                    ← the whole website (self-contained)
├── assets/
│   ├── logo-transparent.png      ← club crest with background removed, used in header/badge
│   └── logo-watermark.png        ← large, low-opacity gold crest used as the hero background texture
└── README.md                     ← this file
```

## Before you publish — 3 things to check

1. **Contact details** — The Contact section now lists two emails and two phone numbers: your original (Kgengwethapelo77@gmail.com / 064 040 3904) and the new ones you added (tebohondwene07@gmail.com / 071 164 0981). Confirm this is how you want both shown, or let me know if one should be labelled (e.g. "Club Manager") to avoid confusion for sponsors.
2. **Logo quality** — Replaced with your newer, sharper crest photo. It's been cleaned up (background removed) for the header badge, and turned into a subtle gold watermark for the hero section background using the club's navy/red/gold colours.
3. **QR code placeholder** — The Contact section still has a dashed placeholder box where a real QR code will go. You can only generate the real QR code *after* your site is live (see Step 3 below).

---

## Step 1: Put it on GitHub (free)

1. Go to [github.com](https://github.com) and log in (or create a free account).
2. Click the **+** icon top-right → **New repository**.
3. Name it something like `real-young-fc-proposal`. Keep it **Public**. Click **Create repository**.
4. On the new repo page, click **uploading an existing file**.
5. Drag in `index.html` and the whole `assets` folder (drag the folder — GitHub will keep the structure).
6. Scroll down, click **Commit changes**.

## Step 2: Turn on GitHub Pages (makes it a live website)

1. In your repo, click **Settings** (top tab).
2. In the left sidebar, click **Pages**.
3. Under "Build and deployment" → Source, choose **Deploy from a branch**.
4. Branch: select **main**, folder: **/ (root)** → **Save**.
5. Wait about 1 minute, then refresh the page. GitHub will show you your live URL — it looks like:
   ```
   https://YOUR-USERNAME.github.io/real-young-fc-proposal/
   ```
6. Open that link — your proposal site is now live for anyone, anywhere.

**Alternative — Netlify (also free, sometimes even simpler):**
1. Go to [netlify.com](https://netlify.com) → sign up free.
2. On your dashboard, drag your whole `site` folder straight onto the page where it says "Drag and drop your site folder here."
3. Netlify gives you a live URL in seconds (e.g. `real-young-fc.netlify.app`). You can rename it for free under **Site settings → Change site name**.

Either option works well — GitHub Pages is great if you want it tied to a GitHub account you control long-term; Netlify is the fastest if you just want a link today.

## Step 3: Generate your real QR code

Once you have your live URL from Step 1 or 2:

1. Go to a free QR generator like [qr-code-generator.com](https://www.qr-code-generator.com) or [qrcode-monkey.com](https://www.qrcode-monkey.com).
2. Paste in your live site URL.
3. Download the QR code as a PNG.
4. Use that QR image directly in your sponsorship PDF, printed materials, or matchday posters — it'll take anyone straight to this website.

*(Optional: if you want the QR code embedded on the website itself, in the "dashed box" placeholder, send me the final URL and I'll generate it and drop it into the page for you.)*

## Step 4 (optional): Get a custom domain

If you want something like `realyoungfc.co.za` instead of a github.io/netlify.app address:
- Domains cost roughly R150–R300/year from providers like Domains.co.za, Afrihost, or Namecheap.
- Once purchased, both GitHub Pages and Netlify let you connect a custom domain for free under their settings — just ask if you want help with this step later.

---

## Making edits later

Everything is in one file — `index.html`. You (or I, in a future chat) can open it in any text editor and change text directly. If you re-upload the edited file to GitHub or re-drag it to Netlify, the live site updates automatically.
