---
layout: 'layouts/doc-post.njk'
title: Each page has a URL
description: |
  Learn about the Lighthouse "Each page has a URL" audit.
date: 2019-05-04
updated: 2019-09-19
---

{% Aside 'caution' %}
PWA testing in Lighthouse is deprecated. For more information on its deprecation see [Chrome’s updated Installability Criteria](https://developer.chrome.com/blog/update-install-criteria). For guidance on testing, refer to the [PWA documentation](https://developer.chrome.com/docs/devtools/progressive-web-apps/).
{% endAside %}

Ensure individual pages and views in your
[Progressive Web App (PWA)](https://web.dev/explore/progressive-web-apps#make-it-installable)
are deep linkable via URL and that each URL is unique
to make them easily shareable on social media.

## Recommendations

- Test that individual pages and views can be opened and
  directly accessed via new browser windows.
- If building a single-page app,
  make sure the client-side router can reconstruct the app state from a given URL.

{% Partial 'lighthouse-pwa/scoring.njk' %}

## Resources

[Source code for **Each page has a URL** audit](https://github.com/GoogleChrome/lighthouse/blob/main/core/audits/manual/pwa-each-page-has-url.js)
