Andrew Grau -- personal site

  index.html          THE PUBLIC SITE -- upload this one
  index-editor.html   private editing build, do NOT upload
  assets/             58 files -- photos, videos, and your CV PDF

------------------------------------------------------------------
WHICH FILE GOES ONLINE
------------------------------------------------------------------
Upload index.html and assets/ only.

index.html is read-only: no Edit button, no drop zones, no export,
nothing writes to the browser. All content is baked in.

index-editor.html is the version with editing. Keep it on your
machine. If you upload it, visitors get an Edit button.

------------------------------------------------------------------
RUN IT LOCALLY
------------------------------------------------------------------
    cd this-folder
    python3 -m http.server 8000

Then open http://localhost:8000  (Ctrl+C to stop).
Use http://localhost:8000/index-editor.html to edit.

Do not just double-click the file -- browsers block fetch() on
file:// URLs, so 3D models will not load.

------------------------------------------------------------------
PUT IT ONLINE (GitHub Pages)
------------------------------------------------------------------
Upload index.html and the assets folder to the REPO ROOT --
drag the contents of this folder, not the folder itself.
Settings -> Pages -> Deploy from a branch -> main -> / (root)

------------------------------------------------------------------
CHANGING CONTENT LATER
------------------------------------------------------------------
Open index-editor.html locally, click Edit, make changes, click
Export. Send me the content.json and I will rebuild both files.

Anything you drop in lives in memory only, so export before you
close the tab. Videos must be MP4 (H.264); .MOV and .HEIC will not
work in any browser -- send me the originals and I will convert.
