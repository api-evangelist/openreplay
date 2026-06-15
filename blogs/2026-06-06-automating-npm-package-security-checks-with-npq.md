---
title: "Automating npm Package Security Checks with npq"
url: "https://blog.openreplay.com/npm-package-security-checks-npq/"
date: "2026-06-06"
author: "OpenReplay Team"
feed_url: "https://blog.openreplay.com"
---
npq audits an npm package before it installs by intercepting the installation request to examine package metadata, age, scripts, and known CVEs before any code reaches node_modules — unlike npm audit which only reports vulnerabilities after the fact. This guide demonstrates how to integrate npq into terminal workflows and pre-commit hooks for automatic dependency security auditing.
