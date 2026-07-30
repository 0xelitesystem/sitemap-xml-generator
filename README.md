# Sitemap XML Generator

This tool turns a list of page URLs into a valid sitemap.xml, with lastmod, changefreq, and priority on every entry. Paste one URL per line, set the defaults, and copy or download the file.

**Live demo:** https://0xelitesystem.github.io/sitemap-xml-generator/

## What it does

Paste your page URLs one per line. Set a default change frequency, a priority, and a last-modified date, with an option to use today's date automatically. The tool generates a standards-compliant sitemap.xml with a url entry for each valid URL, and offers copy and download.

Lines that are not http or https URLs are skipped. Place the file at your site root and reference it from robots.txt so crawlers can find it.

## Aesthetic

A transit map: a colored route bar down the side, station-dot legends, and condensed display type, with the generated XML in a dark panel.

## Privacy

Everything runs in your browser. Nothing you type is sent anywhere, stored, or saved. Closing the tab clears it.

## Use it

Open `index.html` in any modern browser, or host it as a static page. No build step, no dependencies, no network calls.

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## License

MIT. Copyright (c) 2026 0xelitesystem.
