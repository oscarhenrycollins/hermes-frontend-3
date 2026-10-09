---
wizard: 0.2
id: hermes-frontend-3
name: Hermes Frontend 3
type: view
version: 0.1.0+1af684e
summary: Desktop-style browser UI for your existing Hermes Agent.
license: MIT
source: https://github.com/minhyeong112/hermes-frontend-3
runtime:
  kind: runtipi
  config: runtipi/config.json
  compose: runtipi/docker-compose.yml
view:
  path: /
  port: 9120
provides: [agent-ui]
---

# Hermes Frontend 3

Desktop-style browser UI for your existing Hermes Agent.
