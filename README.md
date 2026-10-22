# Wade Zinkand - Personal Website

A responsive personal portfolio for Wade Zinkand, an Information Systems student at the University of Maryland's Robert H. Smith School of Business.

## Features

- Work Experience, Education, Programs, and Activities tabs
- Keyboard navigation using the arrow, Home, and End keys
- Direct links to each tab, such as `#education`
- Downloadable resume, professional email, and LinkedIn links
- Responsive layouts and reduced-motion support

## Files

- `index.html`: page content, styles, and tab behavior
- `wade-zinkand-resume.pdf`: reviewed web resume without a phone number or document metadata
- `.nojekyll`: serve the files directly on GitHub Pages
- `.gitignore`: excludes credentials, environment files, private documents, caches, and local hosting configuration

## Preview

Open `index.html` in a browser. No build step, package installation, API keys, or server is required.

Google Fonts provides the optional DM Sans and Manrope fonts; the page uses fallback fonts if the network is unavailable.

## Deploy with GitHub Pages

1. Upload these files to the repository root, including `.gitignore` and `.nojekyll`.
2. In the repository, open **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch containing these files and **/ (root)**, then save.
5. GitHub displays the published URL after deployment finishes.

Documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Privacy and future changes

This project intentionally includes a professional email address, LinkedIn profile, and resume history. The original resume, phone number, local paths, Sites configuration, and previous repository history are excluded from this copy.

A `.gitignore` prevents accidental additions of matching untracked files; it does not remove secrets already committed. Review every staged change before pushing. Do not add credentials or private documents, and do not store secrets in HTML or client-side JavaScript.
