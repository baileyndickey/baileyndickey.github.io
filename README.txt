N7 Marketing — Static Export for WordPress
===========================================

Each page is a self-contained static HTML file (Home.html, About.html, Services.html,
Testimonials.html, GetStarted.html, Resources.html) with the _ds, uploads, and fonts
folders it depends on.

How to use in WordPress:
1. Easiest: install a plugin like "Insert Headers and Footers" or use a Custom HTML /
   Code block per page, and paste the contents of the <body> section into a new Page.
   Upload the _ds, uploads, and fonts folders to your theme or child-theme directory
   and update the relative paths (./uploads/..., ./_ds/..., ./fonts/...) to match.
2. For full fidelity (fonts, layout classes, hover states), keep the <style> block from
   the page's <head> — it can go in Appearance > Customize > Additional CSS, or a
   custom page template.
3. The team photos and case-study photo are placeholders (they'll show as empty gray
   boxes) — swap in real images at ./uploads/about-megan.jpg, about-jennifer.jpg,
   about-maria.jpg, case-study-photo.jpg, or update the src attributes.
4. The contact form on GetStarted.html is a plain HTML form with a client-side-only
   "thank you" message — wire it to your WordPress form plugin (e.g. Contact Form 7,
   WPForms, Gravity Forms) to actually receive submissions.
