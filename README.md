# Lotto

Multiplayer Lotto game built with React, Vite, Express, and Socket.IO.

## Deploy on Render

1. Create a new **Blueprint** on Render and connect this repository.
2. Render reads `render.yaml` and creates the web service.
3. Open the service URL when its first deploy finishes.

The free Render plan may spin down after inactivity. Room state is kept in
server memory, so active games are lost when the service restarts or spins down.

## Run locally

```sh
npm ci
npm run build
npm start
```
