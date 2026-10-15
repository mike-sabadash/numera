# NUMERA

Static MVP of a personal number ritual: DRAW → METHOD → RITUAL → REVEAL.

No account, analytics, or external data feeds are used. Saved combinations stay in the user's browser.

## Deploy

The included GitHub Actions workflow deploys only this project to `/var/www/numera` and reloads only its dedicated Nginx virtual host. It requires the repository secret `NUMERA_SERVER_SSH_KEY` to be configured with the server key.
