# kʷátɬp — static site

Single-page HTML/CSS for the **tmixw** repo. Deploy with GitHub Pages from this `site/` folder.

## GitHub Pages

**Option A — publish `/site` on `main`**

1. In the **tmixw** repo on GitHub: **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch** (or GitHub’s folder option if available).
3. If your host offers “folder” deployment, choose **`/site`** so `index.html` is served from `https://<user>.github.io/tmixw/` (exact URL depends on user/org pages vs project pages).

**Option B — `gh-pages` branch**

1. Put **only** the contents of `site/` at the **root** of the `gh-pages` branch (so `index.html` is at the branch root).
2. In **Settings → Pages**, set the branch to **`gh-pages`** and **/ (root)**.

Use whichever matches how you want the **tmixw** repo organized; both are valid.

## Assets

Copy your background art into this folder:

- From repo art (if present): `art/backgroundimage.jpg` → **`site/assets/background.jpg`**

Until that file exists, the page still loads with a dark fallback behind the overlay.

## Waitlist (Buttondown)

- Public page: [buttondown.com/kwatlp](https://buttondown.com/kwatlp)
- The signup form in `index.html` posts to `https://buttondown.com/api/emails/embed-subscribe/kwatlp`. To use a different newsletter slug, change **`kwatlp`** in both the form `action` and any links you add.

## Footer links (wired)

- itch.io: [kwatlp.itch.io](https://kwatlp.itch.io/)
- tmíxʷ source repo: [github.com/kwatlp/tmixw](https://github.com/kwatlp/tmixw)

## Contact

Studio email: **kwatlpstudio@gmail.com** (add to the page or metadata if you want it public).
