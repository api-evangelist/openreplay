---
title: "How to Dockerize a Bun Application"
url: "https://blog.openreplay.com/dockerize-bun-application/"
date: "2026-06-18"
author: "OpenReplay Team"
feed_url: "https://blog.openreplay.com"
---
A guide to containerizing Bun applications with production-ready configurations, emphasizing pinning the oven/bun:1 base image, running as non-root, binding to 0.0.0.0 instead of localhost, and adding SIGTERM handlers for graceful shutdown via server.stop(). It covers caching dependency layers, migrating from binary bun.lockb to text-based bun.lock (default since Bun 1.2), copying tsconfig.json for path aliases, multi-stage compiled-binary builds, and a Docker Compose setup with PostgreSQL.
