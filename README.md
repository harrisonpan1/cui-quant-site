# Cui Quantitative Finance Lab — Hexo website

A custom Hexo site inspired by the information architecture and visual rhythm of professional quantitative analytics websites, without copying proprietary assets or text.

## Local preview

```bash
npm install
npm run server
```

Open `http://localhost:4000`.

## Build

```bash
npm run clean
npm run build
```

The static site is generated to `public/`.

## GitHub Pages

1. Create a GitHub repository (for example `cui-quant-site`).
2. Replace `YOUR_GITHUB_USERNAME` in `_config.yml`.
3. Push the project to the `main` branch.
4. In GitHub → Settings → Pages, choose **GitHub Actions** as the source.
5. The included workflow will build and deploy the Hexo site.

If you use a project page instead of `<username>.github.io`, set:

```yaml
url: https://YOUR_GITHUB_USERNAME.github.io/cui-quant-site
root: /cui-quant-site/
```
