# Smart Design Business Operations — Flagship Website

A premium, single-file website built from the full flagship blueprint — Home, About, Solutions, Industries, Resources, Case Studies, and Contact, all in one `index.html` you can open directly in your browser.

**Status:** Phase 1 — Marketing website. No backend, database, or authentication yet (see *Before This Goes Live* below).

---

## How this file works

Everything — every page, all styling, all interactivity — lives inside the one `index.html` file. There's nothing else to install and nothing else to open.

- Double-click `index.html` and the whole site loads, starting on the Home page.
- The navigation menu (Home, About, Solutions, Industries, Resources, Case Studies, Contact) switches between sections instantly — no page reloads, no extra files.
- Buttons like "Book a Consultation" and "Request a Demo" jump straight to the right section of the Contact page.

## Uploading to GitHub

1. Create a new repository on GitHub.
2. Upload `index.html` to the root of that repository (this is the only file you need).
3. Commit / push.

## Deploying to Vercel

1. Go to vercel.com/new and import the GitHub repository.
2. Vercel will detect it as a static site automatically — no build command or output folder needed.
3. Click **Deploy**. You'll get a live link immediately, and it will redeploy automatically every time you update the file on GitHub.

That's it — one file in, one live website out.

---

## Before this goes live — a few honest flags

1. **Contact details are placeholders.** The phone number (+27 00 000 0000) and email (hello@smartdesignoperations.com) shown in the footer and Contact page need to be replaced with your real business details. Use your browser's Find & Replace on the file, or search for those two strings.
2. **The consultation form doesn't send anywhere yet.** Submitting it shows an on-screen "Thank you" message, but there's no backend on a plain HTML file to actually deliver the enquiry to your inbox. The easiest fixes, in order of simplicity:
   - **Formspree** or **Basin** (free tier) — point the form at their endpoint, no code needed.
   - **EmailJS** — sends form submissions straight to your inbox from the page itself.
   - A real backend and database — the long-term option once you're tracking enquiries, stages, and history.
3. **Privacy Policy and Terms sections are placeholders** and should be reviewed by a legal advisor before launch, especially for POPIA compliance.
4. **Case studies are clearly labelled "Illustrative Example"** until real client results are available — replace them as projects are completed.
5. **The social media link in the footer is a placeholder** (#) — add your real profile link.

## What's next

This build covers the full marketing website from the blueprint. Later phases described in the blueprint — a client login portal, CRM-backed enquiry tracking, a content-managed Knowledge Centre, and full database architecture — depend on a real backend and aren't part of this static file. When you're ready for that stage, just let me know.
