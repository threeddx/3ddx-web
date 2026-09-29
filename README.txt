3DDX new pages - HOSTED version of v3 (2026-09-29): put this folder on a web server

This copy is meant to be served from a web address (https://...). There the YouTube
videos play inside the page, like on the WordPress site. (Opened straight from the
folder they still work, but YouTube videos then open on YouTube.)

HOW TO PUT IT ONLINE
  Netlify (easiest, free):
    1. Go to https://app.netlify.com/drop and sign in (or create a free account).
    2. Drag this whole folder (3ddx-html-pages-v3-hosted) onto the page.
    3. Netlify gives you a link like https://something.netlify.app - share that link.
       index.html opens the home page. You can rename the site in Site settings.
  GitHub Pages:
    1. Create a repository, upload the contents of this folder (keep media/ next to home.html).
    2. Settings > Pages > Deploy from branch > main / root. Share the https://<user>.github.io/<repo>/ link.
  Any web server: copy the folder to the server's web root.

  home.html                      New home page (standalone mockup design)
  magnetix-guided-surgery.html   MagnetiX Guided Surgery
  photogrammetry.html            Photogrammetry
  temporary-restorations.html    Temporary Restorations
  final-restorations.html        Final Restorations
  chairside-assistance.html      Chairside Assistance
  all-on-x.html                  All-on-X Solutions hub
  media/                         Home page hero video (keep it next to home.html)

Every page is one self-contained file: images, fonts, styles and the site's scripts
(animations, menus, carousels, accordions) are embedded.

New since version 1:
  - Home page rebuilt from the standalone mockup (styles, assets, animations), with
    the mockup's footer on phones, stacked testimonials on tablets/phones, testimonial
    arrows white (blue on hover), and the contact button no longer blocking them.
  - Mega menu (Solutions) matches the Figma "Header - Option 3". Its links open the
    other pages in this folder.
  - Photogrammetry: Clinical Flexibility panel has the Figma dotted-wave background.
  - Chairside Assistance: dark glossy header over the hero; the service photo zooms in
    place on hover.
  - Comparison cards (MagnetiX, Temporary Restorations): the card button is centred
    and turns orange on hover.
  - Plus the other fixes made on the site since version 1.

New in version 3 (HTML only):
  - All-on-X: the first service card no longer shows its hover state by default.
  - Header: no light/dark icon at any width. Phones/tablets (below 1100px): no My account button;
    My account is now at the bottom of the burger menu.
  - Mega menu: new Featured Product photo; "Temp. restoration" renamed "Temporary Restorations".
  - Home: the hero video is embedded in home.html (plays even if the file is opened on its
    own) and plays with reduced motion too; "Read all testimonials" link label.
  - Final Restorations: in "Why Clinicians Choose 3DDX" no card is highlighted by default;
    each card gets the blue gradient on hover.

The pages link to each other. Links to pages that are not built yet go to "#".
Send the whole folder (zip it) so the home video keeps working.
