Andrew Grau -- personal site

  index.html     the page (70 KB)
  assets/        57 photos, videos and models it references (26 MB)

Keep them together. index.html points at assets/ using relative paths,
so the folder must stay beside it.

------------------------------------------------------------------
RUN IT LOCALLY
------------------------------------------------------------------
Open a terminal, cd into this folder, and run:

    python3 -m http.server 8000

Then open http://localhost:8000 in your browser. Ctrl+C to stop.

Do not just double-click index.html. Photos and video will work, but
browsers block fetch() on file:// URLs, so 3D models will not load.

------------------------------------------------------------------
PUT IT ONLINE
------------------------------------------------------------------
GitHub Pages:
    create a repo, upload index.html and assets/ to the root,
    then Settings -> Pages -> Source: main branch, / (root)

Netlify or Cloudflare Pages:
    drag this whole folder onto their deploy page. No build step.

------------------------------------------------------------------
EDIT IT
------------------------------------------------------------------
Click Edit (bottom right). Every piece of text is editable in place.
Drop photos or video onto the image wells and drop zones. Click Done.

Then click Export to download content.json and send it to me. New
files arrive as base64 inside that file; I convert and compress them
into assets/ and hand back an updated folder.

Anything you drop lives in memory only -- media is too large for
browser storage -- so export before you close the tab.

Videos must be MP4 (H.264). iPhone .MOV and .HEIC will not play or
display in any browser; send me the originals and I will convert them.
