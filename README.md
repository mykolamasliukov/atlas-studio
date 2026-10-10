# ATLAS Studio — public pages

Static pages for the publishing section of ATLAS Studio (a self-hosted, single-user video studio):

- `index.html` — what the app is;
- `privacy.html`, `terms.html`, `data-deletion.html` — the policies Meta and TikTok ask for;
- `connect/` — the sign-in return page: it only forwards the sign-in code to the studio on the same computer
  (`http://127.0.0.1:<port>/callback/`), stores nothing and sends nothing anywhere else.

Served by GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root.
