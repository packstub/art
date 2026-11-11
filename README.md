# Packstub art

Published images for Packstub plugins, one folder per plugin. Link them raw:

```
https://raw.githubusercontent.com/packstub/art/main/<slug>/banner.jpg
https://raw.githubusercontent.com/packstub/art/main/<slug>/docs/<shot>.png
```

- `<slug>/banner.jpg`, `thumbnail.jpg`, `preview.png`, `mock.png`, `og.png`:
  rendered in packstub/store (`public/images/plugins/<slug>/`) and published by
  its `publish-art.yml` workflow.
- `<slug>/docs/`: the plugin's screenshots, pushed from its own `docs/images/` by
  its `docs-sync.yml` workflow.

Nothing is deleted on publish, so links from older releases keep working. Do not
edit here: change the image at its source and push.
