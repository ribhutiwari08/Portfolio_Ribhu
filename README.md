# Ribhu Bhushan Tiwari: Portfolio

A one-page portfolio site. Everything (HTML, CSS, JavaScript, photo and certificate images) lives in a single `index.html`, so there is no build step.

## Run locally

Open `index.html` in a browser.

## Publish with GitHub Pages

1. In this repository, go to Settings, then Pages.
2. Under Build and deployment, choose "Deploy from a branch".
3. Select the `main` branch and the `/ (root)` folder, then save.

The site will be available at `https://ribhutiwari08.github.io/Portfolio_Ribhu/`.

## Customize

- Text, projects and links are plain HTML in `index.html`.
- Colors come from one hue variable (`--hue`) at the top of the stylesheet.
- Visitors can switch theme, accent color and motion effects from the Customize button in the header.

## Resume download

The "Get resume" button opens a form that checks the name, email and Indian mobile number before the PDF downloads. The PDF is `Ribhu_Bhushan_Tiwari_Resume.pdf` in the repository root, so replace that file to update the resume.

To receive the submitted details, set `RESUME_ENDPOINT` in the script at the bottom of `index.html` to a form-backend URL (Formspree or a Google Apps Script web app). It is empty by default, so nothing is sent anywhere.
