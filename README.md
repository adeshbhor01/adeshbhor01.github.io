# Adesh Bhor Portfolio Website

This is a simple static portfolio website for GitHub Pages and the custom domain `www.adeshbhor.com`.

## Files

- `index.html` - the full one-page portfolio
- `styles.css` - all styling
- `script.js` - mobile menu, project filters, scroll reveal, active nav
- `CNAME` - tells GitHub Pages to use `www.adeshbhor.com`
- `assets/img/` - SVG project visuals
- `assets/docs/Adesh_Bhor_Resume.pdf` - resume PDF used by the Download Resume button
- `robots.txt` and `sitemap.xml` - basic SEO files

## Edit these first

1. Open `index.html`.
2. Search for `your-github-username` if you add a GitHub link later.
3. Replace or remove any project text you do not want public.
4. Replace `assets/docs/Adesh_Bhor_Resume.pdf` with your preferred public resume PDF if needed.
5. Keep private/confidential company files, internal schematics, customer board files, and restricted photos out of the public website.

## Publish with GitHub Pages

1. Create a GitHub account.
2. Create a public repository named `YOUR-GITHUB-USERNAME.github.io`.
3. Upload all files in this folder to the root of that repository.
4. Go to repository Settings > Pages.
5. Set Source to "Deploy from a branch".
6. Select branch `main` and folder `/root`.
7. Save.
8. Confirm your temporary site works at `https://YOUR-GITHUB-USERNAME.github.io`.
9. In Settings > Pages, set the custom domain to `www.adeshbhor.com`.

## Namecheap DNS records

In Namecheap > Domain List > Manage > Advanced DNS > Host Records, use:

A Record      @      185.199.108.153      Automatic
A Record      @      185.199.109.153      Automatic
A Record      @      185.199.110.153      Automatic
A Record      @      185.199.111.153      Automatic
CNAME Record  www    YOUR-GITHUB-USERNAME.github.io  Automatic

Replace `YOUR-GITHUB-USERNAME` with your real GitHub username.

After DNS works, go back to GitHub Settings > Pages and enable "Enforce HTTPS".
