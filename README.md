# Caroline Dunne: portfolio

A single-page bilingual (EN/FR) portfolio made of three files: `index.html`, `photo.jpg` and `Caroline_Dunne_CV.pdf`. There's nothing to build or install.

## Put it online with GitHub Pages

1. Create a free account at github.com if you don't have one.
2. Click **New repository**. Name it `<your-username>.github.io` to get the address `https://<your-username>.github.io`, or use any other name (e.g. `portfolio`) to get `https://<your-username>.github.io/portfolio`. Set it to **Public**, which is required for GitHub Pages on a free account.
3. On the repository page, click **Add file → Upload files**, drag in **all three files** (`index.html`, `photo.jpg`, `Caroline_Dunne_CV.pdf`), then click **Commit changes**. They must sit side by side, or the photo and the CV button won't work.
4. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, select `main` and `/ (root)`, then click **Save**.
5. After a minute or two, the site address appears at the top of that page.

## Useful details

- **Language:** visitors get French or English depending on their browser, and can switch with the EN/FR button. To send someone a specific version, use `?lang=fr` or `?lang=en` at the end of the link.
- **Search engines:** the page currently asks search engines not to index it, so it's only seen by people you send the link to. When you're ready to be found, delete the line `<meta name="robots" content="noindex, nofollow">`.
- **Link preview:** once you know your site address, open `index.html`, search for `YOUR-SITE-ADDRESS` (it appears twice) and replace it with your address, e.g. `https://cdunne.github.io`. LinkedIn and email will then show your photo and tagline when you share the link.
- **CV:** to update the CV, upload a new PDF with exactly the same name, `Caroline_Dunne_CV.pdf`.
- **Custom domain (optional):** buy a domain (about €10–15 a year), then add it under **Settings → Pages → Custom domain**.
- **Editing:** on GitHub, open `index.html` and click the pencil icon. Each piece of text appears twice, once with `lang="en"` and once with `lang="fr"`, so remember to update both.
