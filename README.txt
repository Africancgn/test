CLEAN-ROOM SCAFFOLD (no copied content)
---------------------------------------
Generated: September 13, 2025

What this is:
- A starter front-end that mimics the general structure of a professional NGO site.
- All text and media are placeholders. Replace them with your original content and brand assets.

Files:
- index.html, about.html, programs.html, events.html, news.html, article.html, partners.html, contact.html
- /assets for your images, logos, and icons

How to customize:
1) Replace the logo box (header) with your official logo PNG and update the site name.
2) Edit copy on each page with your organization's text.
3) Place partner logos inside /assets and fill the Partners page.
4) If you own the rights to afcgn.com content, you can migrate it here manually.

Optional real mirror (if you own the rights):
- Use HTTrack or wget from your own machine to download your site and then move the legal assets/text into this scaffold.
  Example (Linux/macOS):
    httrack https://afcgn.com/ -O ./mirror-afcgn --update
  or
    wget --mirror --convert-links --page-requisites --adjust-extension https://afcgn.com/

  After downloading, copy ONLY the content you legally control into this scaffold.

Notes:
- TailwindCSS is loaded via CDN for simplicity.
- No frameworks required; works on shared hosting.
- For forms, wire the contact form to your backend (PHP/mail service) as needed.
