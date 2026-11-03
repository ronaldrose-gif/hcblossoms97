============================================================
 HOLY CROSS BLOSSOMS — Website (Full Source Code)
 School for Children with Special Needs
 Institute of Rehabilitation Science, Holy Cross College, Trichy
 Vision: Looking Beyond Ability | Since 17 July 1997
============================================================

WHAT IS INSIDE THIS ZIP
-----------------------
  index.html          Home page
  about.html          Our story, vision/mission, objectives, history timeline, team
  programs.html       Stages, curriculum, therapies, vocational unit,
                      integrated education, parent support, ID signs
  achievements.html   Sports, Special Olympics, silambam, awards, celebrations
  gallery.html        Photo gallery (tap to enlarge)
  admissions.html     Admission enquiry form + FAQs
  contact.html        Address, Google Map, contact form
  404.html            Friendly "page not found" page
  assets/css/style.css   All design (mobile-first, responsive)
  assets/js/main.js      Menu, font-size A-/A+, accordion, gallery lightbox, forms
  assets/img/*.jpg       Website illustrations (6 images)
  php/send-enquiry.php   OPTIONAL server form handler (for PHP hosting)
  robots.txt, sitemap.xml  For Google search

HOW TO VIEW (no server needed)
------------------------------
  1. Unzip the file.
  2. Double-click index.html — it opens in your browser.
  Works fully offline except Google Fonts + Google Map (need internet).

HOW TO UPLOAD TO THE COLLEGE WEBSITE (hcctrichy.ac.in/blossoms)
---------------------------------------------------------------
  Option A — cPanel File Manager:
    1. Login to cPanel > File Manager > public_html/blossoms/
    2. Upload this ZIP there and click "Extract".
    3. Make sure index.html is directly inside the blossoms folder.
    4. Open https://hcctrichy.ac.in/blossoms/ to check.
  Option B — FTP (FileZilla):
    1. Connect with the college FTP details.
    2. Upload the unzipped folder CONTENTS into public_html/blossoms/
  NOTE: Take a backup of the old site files before replacing them.

BEFORE PUBLISHING — 3 THINGS THE OFFICE MUST UPDATE
---------------------------------------------------
  1. EMAIL: The enquiry forms currently use a placeholder
     blossoms@hcctrichy.ac.in. Search all .html files for
     "data-mail" and replace with the official school email.
     (Also update $TO_EMAIL in php/send-enquiry.php if used.)
  2. PHONE: Add the official phone number on contact.html
     (search for "Office note") and in the footer if desired.
  3. FORMS ON SERVER (optional, recommended): The forms work
     in "email draft" mode by default. If the college server
     supports PHP mail, set the form action to
     php/send-enquiry.php as explained inside that file,
     so enquiries are emailed automatically.

HOW TO EDIT (common tasks)
--------------------------
  * Text: Open the .html file in Notepad / VS Code, edit the
    words between tags, save, re-upload that one file.
  * New gallery photo: Copy the photo into assets/img/,
    then in gallery.html copy one <figure>...</figure> block,
    change the file name + caption. IMPORTANT: take written
    parental consent before publishing any child's photo.
  * Colours: Edit the variables at the top of assets/css/style.css
    (--pink, --plum, --teal ...). The whole site updates.
  * News/notice line: Edit the text inside <div class="ticker">
    at the top of each page.

MOBILE & ACCESSIBILITY FEATURES
-------------------------------
  * Fully responsive — mobile, tablet, laptop, TV.
  * Mobile sticky bottom bar: Contact | Admission Enquiry | Programmes.
  * Hamburger menu on small screens, big 48px touch buttons.
  * A- / A+ text-size buttons (top bar) for low-vision parents.
  * High-contrast colours, keyboard focus outlines, alt text,
    reduced-motion support, print-friendly CSS.

TECHNICAL
---------
  * Pure HTML5 + CSS3 + vanilla JS. No database, no build step,
    no monthly cost. Works on any hosting (including the
    present PHP server — .html files run as-is).
  * Tested page size: whole site ~1.7 MB (mostly images).

Content prepared from the official school profile of
Holy Cross Blossoms (Head Mistress: Sr. Josephine).
Illustrations are AI-generated for this website — replace
with real campus photos (with parental consent) any time.
