# NetKit Labs website

Static site for the [NetKit Labs](https://github.com/NetKit-Labs) organization, intended for GitHub Pages at:

**https://netkit-labs.github.io/**

## Local preview

```bash
# from this directory
python3 -m http.server 8080
# then open http://localhost:8080
```

## Host on GitHub Pages (org site)

1. Create a public repository named **`NetKit-Labs.github.io`** under the `NetKit-Labs` organization.
2. Push this repository’s contents to the `main` branch of that repo.
3. In the repo **Settings → Pages**, set Source to **Deploy from a branch**, branch **`main`**, folder **`/` (root)**.
4. After a minute or two, the site will be live at `https://netkit-labs.github.io/`.

### First-time push example

```bash
git init
git add .
git commit -m "Add NetKit Labs GitHub Pages site"
git branch -M main
git remote add origin git@github.com:NetKit-Labs/NetKit-Labs.github.io.git
git push -u origin main
```

> Note: GitHub org pages require the exact repo name `NetKit-Labs.github.io` (matching the org login) to publish at the org root URL.
