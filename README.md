# AdMediaPixeel LLC — Website

Static website for AdMediaPixeel LLC, hosted on GitHub Pages.

## Pages

| File | URL |
|------|-----|
| `index.html` | Home |
| `about.html` | About Us |
| `support.html` | Support / FAQ |
| `contact.html` | Contact |
| `privacy.html` | Privacy Policy |
| `terms.html` | Terms of Service |

## Files

```
admediapixeel/
├── index.html
├── about.html
├── support.html
├── contact.html
├── privacy.html
├── terms.html
├── style.css
├── script.js
└── README.md
```

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `admediapixeel-website`)
2. Upload all files to the repository root
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Choose `main` branch and `/ (root)` folder
6. Click **Save**

Your site will be live at `https://<your-username>.github.io/<repo-name>/`

### Custom Domain (optional)

To use `admediapixel.com`:
1. Add a `CNAME` file to the repo root containing: `admediapixel.com`
2. In your DNS provider, add a CNAME record pointing `www` → `<your-username>.github.io`
3. Add an A record for the apex domain pointing to GitHub's IPs:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
4. In GitHub Pages settings, enter your custom domain and enable **Enforce HTTPS**

## Contact

support@admediapixel.com
