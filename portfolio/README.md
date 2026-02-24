# Michaela Angela E. Cailing Portfolio

Minimal, static portfolio site built with HTML, CSS, and JavaScript.

## Customize content

1. Update text in `index.html`.
2. Add your UI/UX images in an `assets` folder (create it if needed).
3. Replace the placeholder snapshot cards with `<img>` tags pointing to your images.

## Deploy for free with GitHub Pages

### Option A: GitHub Pages (recommended)

1. Create a new GitHub repository named `cailingmicha.com` (public).
2. In this project folder, initialize git and push to that repo.
3. In GitHub, go to **Settings** > **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then **Save**.
6. Wait for the green success message and URL to appear.

### Connect your custom domain (cailingmicha.com)

1. Buy the domain (any registrar is fine). Keep your DNS control panel open.
2. In GitHub repo **Settings** > **Pages**, set **Custom domain** to `cailingmicha.com` and save.
3. Add these DNS records at your domain registrar:
   - Type: `A`
     Name: `@`
     Value: `185.199.108.153`
   - Type: `A`
     Name: `@`
     Value: `185.199.109.153`
   - Type: `A`
     Name: `@`
     Value: `185.199.110.153`
   - Type: `A`
     Name: `@`
     Value: `185.199.111.153`
   - Type: `CNAME`
     Name: `www`
     Value: `cailingmicha.com`
4. Wait for DNS to propagate (can take up to 24 hours).
5. In GitHub Pages settings, enable **Enforce HTTPS** once available.

## Optional: add a favicon

1. Add `favicon.ico` in the project root.
2. Add this line in `index.html` inside `<head>`:
   `<link rel="icon" href="favicon.ico" />`
