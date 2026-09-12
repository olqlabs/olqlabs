OLQ LABS — YOUR WEBSITE, READY TO USE
=========================================

Everything is in this folder, already working with placeholder
content. You can host it as-is today, and replace pieces with
your real content whenever you're ready — nothing needs to be
"finished" before it works.

WHAT'S INSIDE
-------------
  index.html          <- the whole website (this is the file browsers load)
  content/             <- pictures, WAT words, SRT situations (see below)
  games/pabt.html       <- placeholder page for PABT games
  games/gto.html        <- placeholder page for GTO tasks

HOW TO PUT IT ONLINE
----------------------
Upload this ENTIRE folder (keeping index.html, content/, and
games/ all in the same place, in this same arrangement) to any
web hosting:

  - Already have hosting? Use its File Manager or FTP and upload
    everything into the main web folder (often called
    "public_html" or "www").
  - No hosting yet? The fastest way to test with a real, live
    web address is Netlify Drop — go to netlify.com/drop in a
    browser and drag this whole folder onto the page. It gives
    you a working link in seconds, no account needed to try it.

You can also just open index.html directly by double-clicking it
on your computer to preview — the pictures will all work fine
that way. WAT and SRT custom word lists specifically need real
hosting to load (explained below) — until then they quietly use
built-in defaults, so nothing breaks either way.

======================================================
1. PICTURES — content/tat/ and content/ppdt/
======================================================
Both folders already contain placeholder pictures for all 6
candidate categories, so TAT and PPDT work right now, out of
the box. Replace them whenever you have real pictures:

  content/tat/<category>/
      01.jpg, 02.jpg, ... 11.jpg, blank.jpg
      (up to 100 supported — number them with no gaps,
       e.g. 01, 02, 03... the site picks a random, non-repeating
       set from however many are there each time someone
       practices)

  content/ppdt/<category>/
      01.jpg, 02.jpg, 03.jpg...
      Upload CLEAR pictures — the website blurs them
      automatically and un-blurs them again when comparing.

The 6 category folder names (used exactly as-is, don't rename):
  male_10plus2   male_graduate   male_service
  female_10plus2 female_graduate female_service

Just drop a new 01.jpg into a folder to replace the placeholder
there — no other changes needed, the website picks it up
automatically.

======================================================
2. WAT WORDS & SRT SITUATIONS — content/wat/ and content/srt/
======================================================
Both folders already contain real, working word/situation lists
(the same list used across the site) for all 6 categories, named:

  male_10plus2.txt   male_graduate.txt   male_service.txt
  female_10plus2.txt female_graduate.txt female_service.txt

To use your own: open the relevant .txt file in Notepad (or any
plain text editor), and replace the contents —
  - WAT files: one word per line
  - SRT files: one situation per line

You can have as many lines as you like; the site uses a random,
non-repeating subset each time, sized to whatever the practice
session is set to.

IMPORTANT: these .txt files only load once the site is actually
hosted online (see "How To Put It Online" above) — not when
just double-clicking index.html on your computer. That's a
standard browser security rule. Until it's hosted, the site
automatically falls back to its built-in list, so nothing looks
broken either way.

======================================================
3. PABT GAMES & GTO TASKS — games/pabt.html and games/gto.html
======================================================
The homepage's "PABT Practice" and "GTO Tasks" tiles already
link to these two files. Right now they're simple placeholder
pages. When your PABT games and GTO content are ready:

  - Replace games/pabt.html with your real PABT games file
  - Replace games/gto.html with your real GTO tasks file

Keep the filenames exactly as they are (pabt.html, gto.html) and
keep them inside the games/ folder — the homepage tiles will
then take people straight to your real content, with no other
changes needed anywhere else on the site.

======================================================
QUESTIONS
======================================================
If anything doesn't load as expected once it's hosted, the most
common causes are: a typo in a filename/folder name, or a folder
placed in the wrong spot relative to index.html. Everything is
case-sensitive on most web hosts, so keep names exactly as shown
above.
