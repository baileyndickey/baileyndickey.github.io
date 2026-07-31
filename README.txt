N7 Marketing — GitHub Pages package
=====================================

Upload the ENTIRE contents of this folder (including hidden .nojekyll) to your
repo root, preserving folder structure exactly:

index.html, About.html, Services.html, Testimonials.html, GetStarted.html, Resources.html
_ds/   (design-system CSS + JS — required for all styling)
uploads/  (logos + hero art)
fonts/  (site typefaces)
.nojekyll  (tells GitHub Pages not to ignore the _ds folder)

Best upload method: GitHub Desktop or 'git add . && git commit && git push' from
a local clone — the web drag-and-drop uploader frequently drops nested folders.

Team photos (about-*.jpg) and the case study photo are placeholders — add real
images at those paths in uploads/, or update the <img src> in About.html /
Testimonials.html.

The contact form on GetStarted.html is plain HTML with a client-side "thank you"
message only — connect it to a real form service (Formspree, Netlify Forms, etc.)
to receive submissions on GitHub Pages.
