# KS-Portfolio

Public one-page portfolio for Kire Stojanov. The page is static HTML and CSS. There is no build step.

## Local preview

From the repo root:

```
python3 -m http.server
```

Open the address the server prints.

## Cloudflare Pages

The site is not deployed. In the Cloudflare dashboard, connect the GitHub repo noWie2k/KS-Portfolio and use these settings:

- Production branch: main
- Framework preset: None
- Build command: empty
- Build output directory: /

## Archive

`archive/old_docs_reference/` is the retired 2024 page. That copy has a `noindex` robots meta tag and is not linked from the new page.
