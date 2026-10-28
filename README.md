# AMP Sandbox

A single-page AMP experiment connecting a select input, automatic form submission, and analytics triggers.

## Explore locally

```sh
python3 -m http.server 8000
```

Open [localhost:8000](http://localhost:8000). No package install or build step is needed. The AMP runtime and component scripts load from the AMP CDN.

## What's in the example

- `amp-form` handles the select-driven form submission.
- `amp-analytics` defines click and form-submit requests.
- The analytics configuration demonstrates passing the selected form value into a request URL.

This is a historical learning sandbox. The canonical URL, article metadata, and analytics destinations are example placeholders; the repository contains only the example HTML and no backend. Replace those values and validate the AMP document before using it as a published page.
