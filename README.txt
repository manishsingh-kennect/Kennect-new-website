KENNECT 2.0 — SOLUTIONS (deployable bundle)
===========================================
Static site. No build step. Upload this folder to any static host
(Netlify, Vercel, S3/CloudFront, Nginx, GitHub Pages) and it works.
Entry point: index.html (redirects to kennect-solutions.html).

PAGES (12)
  index.html ................ entry / redirect
  kennect-solutions.html .... hub: nav splits into By team + By industry
  team-leadership.html ...... \
  team-reps.html ............  |
  team-finance.html .........  } 5 team pages (each in its accent colour)
  team-operations.html ......  |
  team-hr.html .............. /
  industry-pharma.html ...... \
  industry-insurance.html ...  } 4 industry pages (unified slate)
  industry-bfsi.html ........  |
  industry-fmcg.html ........ /
  kennect-contact.html ...... Book-a-demo form + real contact details

NAV: "Solutions" is a mega-menu (By team | By industry). Works on
desktop (hover/click) and mobile (burger -> accordion).

TO FINISH WIRING
  - Logo + footer brand currently point to index.html. Repoint to the
    real homepage when this is merged into the full Kennect 2.0 site.
  - Top-nav Platform / Pricing / Resources / About are "#" placeholders
    (out of scope for this bundle).
  - The contact form posts nowhere — connect action="" to your CRM /
    HubSpot / form endpoint. Email + phone fallbacks are live.
  - Industry logos are text chips; swap for image logos when available.
  - FMCG names no clients (our FMCG contacts are prospects, not customers).
