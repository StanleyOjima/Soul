# SOUL website — private preview

A test build so the founders can review the site on desktop and phone. It is not the launch site.

## What's in it
- `index.html` — homepage
- `about.html` — About
- `venture-development.html` — Venture Development
- `contact.html` — Let's talk (the form is a preview: it sends and stores nothing)
- `404.html` — shown for any page that isn't uploaded yet (Partnerships, Work, the three case studies) and for mistyped links
- `assets/` — images and the three case-study videos

## Page names the site already links to
| Page | File name |
|---|---|
| Partnerships | `partnerships.html` |
| Work | `work.html` |
| QuickFleet case study | `case-quickfleet.html` |
| Pantech Dynamics case study | `case-pantech.html` |
| Rhanamerzy case study | `case-rhanamerzy.html` |

## Put it online with GitHub Pages
1. Use a separate repository (for example `soul-preview`), not `soul-website`.
2. Upload everything in this folder to the root, keeping the `assets` folder. Commit.
3. Settings → Pages → "Deploy from a branch" → `main`, `/ (root)` → Save.
4. The site appears at `https://<your-username>.github.io/<repo>/` within a couple of minutes.

To update, upload the changed files and commit.

## Worth knowing
- Every page asks search engines not to index it, but anyone with the link can open it, and a free-plan repository is public.
- Client work (QuickFleet, Pantech Dynamics, Rhanamerzy) is shown before every client has given permission, so share the link only with the founders.

## Link previews (OG cover)
`assets/og-cover.png` (1200×630) is the image shown when the link is shared on WhatsApp, X, LinkedIn or Slack. Most apps need its full web address, so once the site has its address, change `assets/og-cover.png` in the `og:image` and `twitter:image` lines at the top of each page to the full address, for example `https://<your-username>.github.io/<repo>/assets/og-cover.png`.
