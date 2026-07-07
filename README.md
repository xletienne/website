# Xiaoli Etienne — academic website

Simple multi-page site. Plain HTML + one stylesheet. No build step, no dependencies.

## Files
- index.html          Home (about, education)
- research.html       Research overview
- research-prices.html / research-futures.html / research-energy.html / research-food.html
- publications.html   All 62 peer-reviewed articles + papers under review
- teaching.html
- extension.html      Extension, service, media
- students.html       Full advising record
- news.html           Recent updates
- style.css           Shared styling for every page

## To finish setup
1. Add `headshot.jpg` (your photo) to this folder.
2. Add `CV_Etienne.pdf` to this folder.
3. (Done) Profile links — Google Scholar, ORCID, LinkedIn, and VERSO are wired in.

## How to update
- **New publication**: in publications.html, copy the top `<li>` inside the
  numbered list, paste it above, and edit the text. The list numbers itself
  (it uses `<ol reversed start="62">` — bump `start` to 63). Also consider
  adding it to the relevant research-*.html page and a line in news.html.
- **News item**: in news.html, copy a `news-item` div and edit date + text.
  Newest goes on top.
- **New student**: in students.html, copy a `student` div and edit.

## Hosting (GitHub Pages)
Upload all files in this folder to a public GitHub repository, enable Pages
(Settings → Pages → deploy from branch → main, root), then add the custom
domain and DNS records per GitHub's instructions.
