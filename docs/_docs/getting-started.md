---
docid: getting-started
title: Getting Started
layout: docs-getting-started
permalink: /docs/getting-started
---

{% capture gradle %}{% include_relative getting-started/gradle.md %}{% endcapture %}
{% capture gradle-kt %}{% include_relative getting-started/gradle-kt.md %}{% endcapture %}
{% capture buck %}{% include_relative getting-started/buck.md %}{% endcapture %}
{% capture testing %}{% include_relative getting-started/testing.md %}{% endcapture %}

{{gradle | markdownify }}
{{gradle-kt | markdownify }}
{{buck | markdownify }}
{{testing | markdownify }}
