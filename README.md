# Simple Cloud Drive 3.1.0 — KOMBajn

Debian self-hosted file manager.

## Install

```bash
npm ci
cp .env.example .env
nano .env
chmod +x start.sh
./start.sh
```

Set a strong `ADMIN_PASSWORD` and unique `SESSION_SECRET` before starting. Default port: `1213`. User data is stored outside the repository in `/home/magic/simple-cloud-drive-data`. Never commit `.env`, user files, metadata, temporary uploads or `node_modules`.
