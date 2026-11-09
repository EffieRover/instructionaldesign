# Loy's MD2BSP

Turn markdown, Word copy, or web copy into a clean, accessible, Brightspace-ready HTML page.

**Use it here:** https://effierover.github.io/instructionaldesign/md2bsp.html

## What it does

You paste your content, decide how each piece should look, and download a finished page built on the GCC Brightspace template. It handles the fiddly parts for you: callouts, accordions, video wrappers, accessible links, time estimates, a "Last published" line, and the standard footer.

It runs entirely in your browser. Nothing is uploaded or stored on a server.

## How to use it

1. **Paste or upload.** Drop in markdown, Word copy, or a copied web page.
2. **Page extras.** Add the page title, the unit/module/week, and the top-of-page list (time, before you start, materials, key terms, learning outcome). Enter the course info so the banner path is right.
3. **Content.** Each chunk of text becomes a box. Pick how it should look: paragraph, heading, list, callout, accordion, video, or link. Suggestions are marked, but you make the call.
4. **Preview and download.** Check the student view, then download the HTML and upload it to Brightspace.

## Good to know

- The preview is a close simulation. The downloaded file uses the real template styles, so it looks right once it's in Brightspace.
- Video lengths are typed in, not read from the link. The tool will try to fetch YouTube and Vimeo titles.
- For linked readings, the tool tries to estimate reading time from the page. Many sites block that, and library links need a login, so you may need to type the minutes.
- Word (.docx) file upload isn't built yet. Pasting Word copy works.

## Status

Tested mostly with markdown. Word and web-page pastes are lightly tested. Output hasn't been checked across every Brightspace setup, so give your first page a once-over.

## License

[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). Use it, change it, share it, just credit Loy Gross.

Icons are from [Font Awesome Free](https://fontawesome.com), licensed [CC BY 4.0](https://fontawesome.com/license/free).
