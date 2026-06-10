# BizzaOS App Template

This template helps you create new apps for BizzaOS.

## Structure

- app.json → metadata
- pod.yaml → container definition
- .env.example → configuration

## Steps

1. Copy this folder
2. Rename to your app name
3. Update app.json
4. Replace IMAGE
5. Adjust ports and volumes

## Rules

- Always use ENV variables (no hardcoding)
- Keep DATA_DIR inside ~/.bizzaos/data/
- Avoid privileged containers unless necessary