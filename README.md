# SOUL website — private preview

A test build so the founders can review the site on desktop and phone. It is not the launch site.

## What's in it
- `index.html` — homepage
- `about.html` — About
- `404.html` — shown for any page that isn't uploaded yet:
  - Venture Development, Partnerships, Work and Let's talk → "<Page> · Coming soon"
  - each case study (QuickFleet, Pantech Dynamics, Rhanamerzy) → "Case study coming soon", with a link back to the work
  - a mistyped link → "Page not found"
- `assets/` — images and the three case-study videos

## Page names the site already links to
When a page is ready, upload it under exactly this name and the existing links will open it instead of the 404:

| Page | File name |
|---|---|
| Venture Development | `venture-development.html` |
| Partnerships | `partnerships.html` |
| Work | `work.html` |
| Let's talk | `contact.html` |
| QuickFleet case study | `case-quickfleet.html` |
| Pantech Dynamics case study | `case-pantech.html` |
| Rhanamerzy case study | `case-rhanamerzy.html` |

## Put it online with GitHub Pages
1. Create a **new** repository (for example `soul-preview`). Don't use the existing `soul-website` repo.
2. Upload everything in this folder to the root of the repo (Add file → Upload files), keeping the `assets` folder. Commit.
3. Go to Settings → Pages. Under Source, choose "Deploy from a branch", then `main` and `/ (root)`. Save.
4. After a minute or two the site appears at `https://<your-username>.github.io/soul-preview/`.

To update the site, upload the changed files again and commit. Pages rebuilds automatically.

## Worth knowing
- Every page tells search engines not to index it. Even so, anyone with the link can open it, and on a free GitHub plan the repository itself has to be public.
- The homepage case studies show QuickFleet, Pantech Dynamics and Rhanamerzy. Client permission is still pending, so share the link only with the founders.
