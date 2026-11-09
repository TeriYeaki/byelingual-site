# Byelingual policy site

This repository contains the local, static website for Byelingual’s privacy policy and support information. It uses plain HTML5 and one stylesheet. It has no JavaScript, analytics, tracking, cookies, forms or third-party assets.

## Preview

From the repository root, run:

```sh
python3 -m http.server -d . 8090
```

Then open `http://localhost:8090/` in a browser.

## Publish checklist

Before publishing:

- replace every visible placeholder marked with `class="gap"`;
- resolve and remove every publication note marked with `class="gap-note"`;
- remove `<meta name="robots" content="noindex">` from every HTML page;
- recheck all relative links and external provider-policy links; and
- verify that the published policy matches the release app, store disclosures and production service settings.

The first version took effect on 9 November 2026. It describes the TestFlight beta as built at Byelingual `develop` 7c4bcecd: TestFlight only, cards on the test server, no purchases, testers 16 or over who live outside the EU, EEA and UK, and support mail to support@byelingual.app forwarded by Cloudflare Email Routing to Gmail.

Before the App Store: check it again against the release build and the production server, and add purchases if they exist by then.
