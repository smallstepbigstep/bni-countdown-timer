# BNI Countdown Timer - GitHub Pages Deployment

## Quick Setup Instructions

### Step 1: Create GitHub Repository
1. Go to [GitHub.com](https://github.com) and sign in
2. Click the "+" icon → "New repository"
3. Repository name: `bni-countdown-timer`
4. Make it **Public** (required for GitHub Pages)
5. Check "Add a README file"
6. Click "Create repository"

### Step 2: Upload Files
1. In your new repository, click "uploading an existing file"
2. Drag and drop ALL files from this folder:
   - `index.html` (main timer)
   - `widget.html` (compact version)
   - `embed.html` (oEmbed version)
   - `minimal.html` (ultra-minimal)
   - `player.html` (video-player style)
   - `oembed.json` (embedding metadata)
3. Commit message: "Add BNI countdown timer files"
4. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. Go to repository "Settings" tab
2. Scroll down to "Pages" section
3. Source: "Deploy from a branch"
4. Branch: "main" (or "master")
5. Folder: "/ (root)"
6. Click "Save"

### Step 4: Get Your URLs
After 2-3 minutes, your timer will be available at:

**Main Timer:** `https://[your-username].github.io/bni-countdown-timer/index.html`
**Widget:** `https://[your-username].github.io/bni-countdown-timer/widget.html`
**Embed:** `https://[your-username].github.io/bni-countdown-timer/embed.html`
**Minimal:** `https://[your-username].github.io/bni-countdown-timer/minimal.html`
**Player:** `https://[your-username].github.io/bni-countdown-timer/player.html`

Replace `[your-username]` with your actual GitHub username.

## Testing in Pitch.com

Try each URL in Pitch.com's "Embed any link" feature:
1. Open your Pitch presentation
2. Click "Embed" → "Any link"
3. Paste one of the URLs above
4. Click "Add"

## Features Included

✅ **60-second countdown** (customizable via settings)
✅ **BNI red branding** (#C8102E)
✅ **Audio alerts** (ding at 10s, alarm at 0s)
✅ **Visual feedback** (wiggle at 10s, flash at 0s)
✅ **Auto-hide controls** (appear on hover, hide after 2s)
✅ **Mobile compatible** (works on iPhone Safari)
✅ **Settings panel** (30s, 60s, 90s, 2min presets + custom)

## Troubleshooting

- **No audio on mobile?** Tap the audio prompt when it appears
- **Controls not hiding?** Move mouse away from timer for 2+ seconds
- **Timer not embedding?** Try different URL versions above
- **Need different duration?** Click settings gear icon (red cog)

## Support

If you need modifications or have issues, the timer is fully self-contained in each HTML file.
