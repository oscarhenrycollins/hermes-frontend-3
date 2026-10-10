---
wizard: 0.2
id: hermes-frontend-3
name: Hermes Frontend 3
type: view
category: interface
version: 0.1.0+1af684e
summary: A Hermes Desktop-style interface in the browser.
icon: icon.png
license: MIT
source: https://github.com/oscarhenrycollins/hermes-frontend-3
runtime:
  kind: runtipi
  config: runtipi/config.json
  compose: runtipi/docker-compose.yml
view:
  path: /
  port: 9120
provides:
- agent-ui
uses:
- hermes-agent
---

# Hermes Frontend 3

A Hermes Desktop-style interface in the browser.
