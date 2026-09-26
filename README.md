# rayscarfe-assets

Figure images for the blog **RaysCarfe** — https://rayscarfe.blogspot.com/

Each folder is one post (named after the post's manuscript slug). The files are
diagrams drawn for that post and exported from PowerPoint originals.

Files are named `fig-N.<sha8>.png`, where `<sha8>` is the first 8 hex digits of
the file's SHA-256. The name therefore changes whenever the picture changes, so
a given URL always returns the same image and CDN caches never go stale.

They are served to the blog through jsDelivr:

```
https://cdn.jsdelivr.net/gh/kyungik/rayscarfe-assets@main/<post-slug>/<file>
```

This repository holds images only. It exists because the Blogger API has no
image upload, and because embedding pictures in the post body as `data:` URIs
made each post large enough that Blogger's index pages (home, label, search,
archive) would list only one post at a time.

The diagrams are the author's own work and are published here so the blog can
display them. Photographs reused from Wikimedia Commons are not stored here —
those are linked from Commons directly, with the licence named in each caption.
