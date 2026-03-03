# Love Amongst the Hovels

> *The better parts of Crime and Punishment, less crime more punishment. An entirely historically accurate, preachy, psychological thriller, with reasonable literary significance.*

**Authors:** Eden Lyman & Emily Lyman

A humorous book about Russia in the early 1900s — dry satirical parody, literary pastiche, and deadpan historical comedy.

## Website

The official website is a static site deployable via **GitHub Pages** or **AWS S3 + CloudFront**.

### Pages

| File | Description |
|------|-------------|
| `index.html` | Landing page — book description, humor analysis, navigation |
| `audiobook.html` | Stream/download the audiobook recording |
| `authors.html` | Authors overview |
| `emily.html` | Emily Lyman author profile |
| `eden.html` | Eden Lyman author profile |
| `style.css` | Imperial Russian-inspired stylesheet |

### Deploy to GitHub Pages

1. Go to **Settings → Pages** in this repository.
2. Under *Source*, select **GitHub Actions**.
3. Push to `main` — the workflow in `.github/workflows/deploy.yml` deploys automatically.

### Deploy to AWS (S3 + CloudFront)

1. Create an S3 bucket with static website hosting enabled.
2. Upload all files (HTML, CSS, audio) to the bucket.
3. Create a CloudFront distribution pointing to the S3 bucket.
4. (Optional) Attach a custom domain via Route 53.

## Audiobook File

`Love among the hovels!🫥.m4a` — the complete audiobook recording (~14 MB, M4A format).

## Roadmap

- [x] Landing page with book description and humor analysis
- [x] Audiobook player and download page
- [x] Authors overview page
- [x] Emily Lyman profile page
- [x] Eden Lyman profile page
- [x] GitHub Pages deployment workflow
- [ ] Author photographs (pending — add as `eden-photo.jpg` / `emily-photo.jpg` and update HTML)
- [ ] Custom domain configuration
- [ ] AWS S3/CloudFront deployment instructions (optional alternative to GitHub Pages)
