# Sardar Abdul Moiz Khan — Portfolio

A responsive, single-page portfolio built with plain HTML and CSS. It has no build step, package manager, JavaScript framework, or external assets. The visual direction uses an atmospheric dark hero, restrained green accents, large editorial typography, and direct navigation, inspired by the current [micro1 website](https://www.micro1.ai/) while using original portfolio content and styling.

## Files

- `index.html` — the complete site, styles included.
- `CV_Sardar Abdul Moiz Khan.pdf` — résumé linked from the page.
- `main.tex` — LaTeX source for the résumé.

## Included content

Profile, experience, education, skills, achievement, certifications, projects, and links were sourced from `main.tex`. Project ownership labels follow the owner's clarification: Reiseagent, Argus PM, and Armour Security MDM are client work; the OCR scraper and DentAI are personal projects. The project cards link to the live Reiseagent and Armour sites, the Argus contact path, and the personal project source/notebook links listed in the résumé.

## Preview and edit

Open `index.html` in a browser. To personalize it, edit the text and links in that file. The résumé link expects the PDF to stay beside `index.html`; URL-encode spaces as `%20` in the link path. The Argus card currently offers contact for details because no public URL was listed in the LaTeX source. If you have an approved public live URL, replace the `mailto:` URL in that card with it.

Before publishing, confirm contact details and client descriptions are still current and approved for public display.

## Publish with GitHub Pages

1. Create a public repository named `YOUR-USERNAME.github.io`.
2. Upload `index.html`, `CV_Sardar Abdul Moiz Khan.pdf`, and this README to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
4. The site will publish at `https://YOUR-USERNAME.github.io`.

To use your Namecheap `.me` domain, claim the current one-year Namecheap offer through the [GitHub Student Developer Pack](https://education.github.com/pack?sort=az&tag=Domains) and check its renewal terms. Then add the domain under **Settings → Pages → Custom domain** and follow [GitHub's custom domain guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site) to set DNS records, verify the domain, and enable HTTPS. GitHub Pages remains the host; the `.me` domain is the public address.
