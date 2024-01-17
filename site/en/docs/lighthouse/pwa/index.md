---
layout: 'layouts/project-landing.njk'
title: 'PWA Audits'
description: 'These checks validate the aspects of a Progressive Web App.'
project_key: lighthouse/pwa
---

{% block css %}
{% InlineCss '/css/single-post.css' %}
{% endblock %}

{% Aside 'caution' %}
PWA testing in Lighthouse is deprecated. For more information on its deprecation see [Chrome’s updated Installability Criteria](https://developer.chrome.com/blog/update-install-criteria). For guidance on testing, refer to the [PWA documentation](https://developer.chrome.com/docs/devtools/progressive-web-apps/).
{% endAside %}
