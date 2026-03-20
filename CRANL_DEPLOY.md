# CranL deploy

Required environment variables:

- DATABASE_URL=postgresql://khatatak:oaR8bIrjHdH53VEDQW5ffjcNGk9INIV4@149.104.71.203:40012/1celecDB
- PORT=3000
- NODE_ENV=production
- BASE_PATH=/
- FRONTEND_URL=https://<your-cranl-domain>

This package is prepared so production build only includes:
- @workspace/khtat-sairak
- @workspace/api-server

Start command is routed through root package.json and railpack.toml.
