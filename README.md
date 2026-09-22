# ad-intelligence-assets

Public static asset host for the [ad-intelligence](https://github.com/yeunjaee/ad-intelligence)
pipeline. Contains only image files - no code, no secrets, no business logic.

This repo is public so kie.ai's image generation API can fetch product
reference images by URL (kie.ai has no way to authenticate against a
private repo). Files are referenced from ad-intelligence's scripts as:

```
https://raw.githubusercontent.com/yeunjaee/ad-intelligence-assets/main/assets/products/<filename>
```

## assets/products/

Drop product reference images here (JPG/PNG). Each one becomes a public
URL immediately on push - no build step.
