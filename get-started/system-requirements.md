---
layout: default
title: 12. System Requirements
description: Official TinyMCE browser support.
keywords: browser compatibility explorer ie safari firefox chrome edge
---

## Browser Compatibility

TinyMCE uses advanced JavaScript and tries to be as smart as possible when it comes to different browsers. The main focus is on Chrome, Firefox, Internet Explorer and Safari.

If a browser is not listed on this page it doesn't mean TinyMCE won't work, but it does mean that TinyMCE may not have been fully tested on that browser. To determine compatibility with an unlisted browser, try out the examples on our website.

Since TinyMCE version 4.6.0 Internet Explorer 8-10 is no longer supported, if you still need legacy browser support the 4.5.X branch will be maintained with critical fixes.

Please use the [issues tracker on GitHub](https://github.com/tinymce/tinymce/issues) to submit bugs on the listed browsers only.

|Browser | Windows | Mac | GNU/Linux |
|:------:|:-------:|:---:|:---------:|
|Chrome  | YES      | YES  | YES |
|Firefox | YES      | YES  | YES |
|Edge    | YES      | N/A | N/A |
|IE 11   | YES      | N/A | N/A |
|IE 10   | NO      | N/A | N/A |
|IE 9    | NO      | N/A | N/A |
|IE 8    | NO      | N/A | N/A |
|Safari  | N/A     | YES  | N/A |

TinyMCE fully supports the most recent version of all supported browsers listed above.  If vendors offer an Extended Support Release (e.g. Firefox) we also officially support the latest ESR from each vendor.  As each browser vendor releases new major versions (e.g. Chrome 61 vs Chrome 62) we will provide support for the prior major version for 60 days after the prior release is superseded.

{% assign_page next_page = "/get-started/get-support/index.html" %}
{% include next-step.html next=next_page %}
