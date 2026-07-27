# Smart Design Business Operations — New Homepage

This folder contains your updated, premium homepage as a single file: `index.html`.
Everything — fonts, styling, and the animated background — is built into that one file. There is nothing else to install.

## What was checked before delivery

- Every menu link (Home, About, Solutions, Industries, Resources, Case Studies, Contact) was tested and correctly jumps to its section — no broken links.
- No duplicate or missing IDs, no unclosed HTML tags.
- The animated background behind the headline was fixed so it fills the hero area correctly on all screen sizes (it was previously sized to the full browser window, which could make it overflow on tall screens).
- All WhatsApp buttons point to the same number (+27 68 987 1999).
- Added a page description for search engines (Google, etc.).
- Added support for visitors who have "reduce motion" turned on in their device settings — the animation switches off automatically for them, and keyboard users get a visible focus outline when tabbing through links.
- Checked on mobile-width layouts — sections stack correctly.

## How to update your live site on Vercel

You have two options depending on how your current site is set up. If you're not sure which applies to you, Option A (drag-and-drop) always works and takes 2 minutes.

### Option A — Fastest (drag-and-drop, no coding, no account changes)

1. Go to **vercel.com** and log in to your account.
2. Click **Add New → Project**.
3. When asked how to start, choose **"Deploy without Git"** / drag-and-drop upload (Vercel will show a drop zone).
4. Drag the `index.html` file (just this one file) into that drop zone.
5. Click **Deploy**. Vercel gives you a new live URL in about 30 seconds.
6. If you want this to replace your existing `smart-design-live.vercel.app` address: open that project's **Settings → Domains**, and point the domain to this new deployment (or ask your developer to do this step if you don't see that option).

### Option B — If your site is connected to GitHub (recommended long-term)

Use this if your Vercel project auto-deploys whenever you push to a GitHub repository (this is the more common professional setup).

1. Open the GitHub repository connected to your Vercel project.
2. Find the current `index.html` file (it may be inside a folder like `public/` — if your developer built this site with a framework like Next.js or React, **check with them first**, since this file may need to be placed differently in that case).
3. Replace its contents with the new `index.html` provided here (upload/overwrite the file, or edit directly on GitHub and paste in the new content).
4. Commit the change (GitHub will ask for a short message — e.g. "Update homepage design").
5. Vercel will automatically detect the change and redeploy your site within 1–2 minutes. You'll see the new build appear in your Vercel dashboard.

### If you're unsure which option applies

Tell your developer (or send them this file) and ask them to confirm whether the current site is a plain static site or built with a framework (Next.js, React, etc.) — that determines whether Option A or Option B is correct. If it's framework-based, dropping in a raw `index.html` may not work without their help.

## Questions or further changes

If you want any further tweaks (copy changes, color adjustments, new sections), just ask and I'll update this same file.
