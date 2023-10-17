---
title: Hugo module for error messages
---

Nothing to see here.

Warning and error messages appear in the console. Error messages let the build fail, get logged, and appear also in the browser instead of the site.

Here, the partial "md-error-msg" is **not** called from a template processing Markdown as it is supposed to.  
It’s called directly in the template "index.html" for testing.
