# Ringer Vault config

Settings the Ringer Vault app and browser extension read. Each file is signed
with Ringer Vault's Ed25519 key; the app and the extension check the
signature and refuse anything changed, unsigned or older than what they
already have. Signed, not secret.

| File | What it says |
|---|---|
| `free-limit.json` | How many logins the free plan holds (never fewer than 20) |
