# Milo Glance Dashboard

Self‑hosted Glance with a default **Home** page and a **Homelab** tab.

## Quick start

1) Copy `.env.example` to `.env` and fill in your URLs + secrets.  
2) `docker compose up -d`  
3) Visit http://localhost:8080 (or your mapped port).

> Uses the official image and Glance’s config-in-`/app/config` pattern.
