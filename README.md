# NovaBoards

A one-page site for NovaBoards electric skateboards. Hosted on GitHub Pages, edited with [Pages CMS](https://pagescms.org).

## What's where

| File / folder | What it is |
|---|---|
| `index.html` | The whole page: layout, styles and animations |
| `content/site.json` | The editable content: boards, prices, reviews, gallery, contact details |
| `images/` | Photos (uploads from Pages CMS land here too) |
| `.pages.yml` | Pages CMS settings: which fields can be edited |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Editing content

Log in at <https://app.pagescms.org>, open this repository and choose **NovaBoards content**. Saving commits the change to GitHub; the live site updates about a minute later.

Keep uploaded photos reasonably small (ideally under ~500 KB, 1600 px wide or less) so the site stays fast.

## Previewing on your computer

Opening `index.html` by double-clicking shows the built-in copy of the content, not `content/site.json`, because browsers block local files from loading each other. To preview with the real content, run this in the project folder:

```
python3 -m http.server 8000
```

then open <http://localhost:8000>.
