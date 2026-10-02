# Strategic Parking Consultancy website

A lightweight, static website for Strategic Parking Consultancy. It is ready to be committed to GitHub and deployed with Cloudflare Pages.

## Files

- `index.html` — website homepage
- `assets/logo.png` — company logo

## Deploy with Cloudflare Pages

1. Create a new GitHub repository and upload the contents of this folder (keep `index.html` at the repository root).
2. In Cloudflare, open **Workers & Pages** and create a Pages project connected to that GitHub repository.
3. Choose **Framework preset: None**.
4. Set **Build command** to blank / none.
5. Set **Build output directory** to `/` (the repository root).
6. Deploy. Cloudflare will publish the static site and provide a `*.pages.dev` address.

For subsequent updates, commit and push changes to the connected GitHub branch; Cloudflare Pages will automatically build and deploy them.

## Local preview

Open `index.html` in a browser. No build tools or dependencies are required.

## Before publishing

The contact button currently uses a placeholder email address (`hello@strategicparking.co.uk`). Replace it in `index.html` with the correct business email address before launch.
