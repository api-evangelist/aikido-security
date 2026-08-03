---
title: "Unauthenticated RCE in WordPress core (wp2shell), via SQL injection"
url: "https://www.aikido.dev/blog/unauthenticated-rce-in-wordpress-wp2shell"
date: "2026-07-17"
feed_url: "https://www.aikido.dev/blog/rss.xml"
---
WordPress core has an unauthenticated RCE (wp2shell), confirmed as SQL injection. Update to 7.0.2 or 6.9.5 now, with mitigations if you can't patch yet. Block the attack class at runtime with Aikido Zen.
