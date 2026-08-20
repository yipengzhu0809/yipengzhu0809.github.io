# Yipeng Zhu — Personal Homepage

Static academic homepage for GitHub Pages. No build step is required.

## Preview locally

Open `index.html` directly in a browser, or run a temporary static server:

```bash
cd /home/yipeng/yipengzhu0809.github.io
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a public GitHub repository named exactly `yipengzhu0809.github.io`.
2. Push this directory to the repository's `main` branch.
3. In GitHub, open **Settings → Pages** and select **Deploy from a branch**, `main`, `/ (root)` if it is not enabled automatically.
4. Visit `https://yipengzhu0809.github.io/` after deployment completes.

From this prepared local directory, connect the empty repository and push:

```bash
cd /home/yipeng/yipengzhu0809.github.io
git remote add origin git@github.com:yipengzhu0809/yipengzhu0809.github.io.git
git push -u origin main
```

Edit `index.html` to update biography, publications, and links. Replace files in `assets/` to update the portrait.

Profile icons are sourced from Simple Icons (CC0), Lucide (ISC), and Bootstrap Icons (MIT).
