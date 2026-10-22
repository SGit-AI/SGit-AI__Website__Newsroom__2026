# SGit-AI__Website__Newsroom__2026

repo for 2026.newsroom.sgit.ai

A hub site of the SGit Newsroom: `data/site.json` rendered by `admin/build/build.py` into the repository root, deployed by GitHub Pages from `dev`. `admin/build/validate.py` is the gate; `admin/build/release.sh "<what changed>"` bumps the version (patch by default: every push is a version), builds, validates, pushes to dev and verifies live. Every page has a markdown twin; `llms.txt` lists them.

Up: https://newsroom.sgit.ai/. Down: https://oct.2026.newsroom.sgit.ai/ · https://php.oct.2026.newsroom.sgit.ai/.

Content CC BY 4.0, code Apache-2.0.
