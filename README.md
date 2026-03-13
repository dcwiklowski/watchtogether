# 🎬 WatchTogether — Couples Watchlist App

A beautiful, single-file web app to track TV shows and movies for two people across all your streaming platforms.

## ✨ Features

- **All your platforms** — PBS Passport, Peacock, Disney+, Hulu, Sling TV, Over the Air (St. Louis), HBO Max, Apple TV+
- **Two viewer profiles** — Each partner can mark what they want to watch
- **Priority ratings** — 1–5 stars so you always know what to watch first
- **Filter by platform, type, or search** — Find anything instantly
- **Mark as watched** — Keep a history of everything you've seen
- **Export to CSV** — Back up or share your list
- **100% local** — All data saved in your browser, no account needed
- **Works on mobile** — Great on the couch!

## 🚀 Hosting on GitHub Pages (Free!)

1. **Create a new GitHub repository** (e.g., `watchtogether`)
2. **Upload `index.html`** to the root of the repo
3. Go to **Settings → Pages**
4. Under "Source", select **Deploy from a branch → main → / (root)**
5. Click **Save** — your app will be live at:
   `https://yourusername.github.io/watchtogether`

> Both you and your partner can use the same URL from any device!

## 📱 Sharing Between Partners

Since this is a static app, each person's list is saved locally in their browser. To sync with your partner:
- **Option A:** Both use the same shared computer/browser
- **Option B:** Use the **Export** button to share your CSV list
- **Option C:** For real-time sync, you can upgrade to use a free [JSONBin](https://jsonbin.io) or [Supabase](https://supabase.com) backend (see below)

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `N` | Add a new title |
| `Esc` | Close modal |

## 🛠 Optional: Real-Time Sync Between Partners

To sync both partners' lists in real time, open `index.html` and replace the `STORAGE_KEY` localStorage logic with a free API. Instructions in `SYNC.md` (coming soon).

## 📋 Platforms Included

| Platform | Color |
|----------|-------|
| PBS Passport | Green |
| Peacock | Purple |
| Disney+ | Blue |
| Hulu | Teal |
| Sling TV | Orange |
| Over the Air (St. Louis) | Gold |
| HBO Max | Purple |
| Apple TV+ | Gray |

## 🔧 Customization

Edit the `PLATFORMS` array in the `<script>` section to add, remove, or rename platforms. Each platform has a `name` and `color`.

---

Made with ❤️ for two people and one remote.
