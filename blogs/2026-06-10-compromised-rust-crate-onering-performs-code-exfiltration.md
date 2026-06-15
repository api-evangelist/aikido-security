---
title: "Compromised Rust crate onering performs code exfiltration"
url: "https://www.aikido.dev/blog/compromised-rust-crate-onering-performs-code-exfiltration"
date: "2026-06-10"
feed_url: "https://www.aikido.dev/blog/rss.xml"
---
The compromised onering Rust crate v1.4.1 on crates.io shipped a malicious build.rs that exfiltrates the diff of your latest commit to a hosted Sentry endpoint every time you build. Category: Vulnerabilities & Threats
