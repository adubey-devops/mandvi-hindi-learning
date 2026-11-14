Mandvi Dubey Hindi teaching website

Open index.html in a browser to preview the site. The portrait is stored locally as mandvi-dubey.jpg, so keep both files together.

Before publishing:
- Replace each student review placeholder with approved, accurate feedback.
- Add specific board exam results only when verified and approved for sharing.
- Add Mandvi's preferred email/contact link in the contact section.
- Confirm the preferred lesson formats, location wording, and any availability details.

The page is a standalone responsive HTML file. It uses Google Fonts when an internet connection is available and falls back to system fonts otherwise.

The contact form is marked up for Netlify Forms. It will collect submissions after the site is deployed to Netlify and form handling is enabled there. If you host on AWS or another platform, connect the form to that provider's submission endpoint (for AWS, typically an API Gateway/Lambda workflow with email delivery) before launch.

The contact form is marked up for Netlify Forms. It will collect submissions after the site is deployed to Netlify and form handling is enabled there. If you host on AWS or another platform, connect the form to that provider's submission endpoint (for AWS, typically an API Gateway/Lambda workflow with email delivery) before launch.

The reviews section includes a separate `review` form. Netlify stores submissions privately in the site dashboard; they do not publish automatically. Enable form detection and redeploy after connecting the repository. Review and approve the wording and attribution before adding a testimonial to the public page.
