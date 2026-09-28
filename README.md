# Face Mesh Explorer

A browser-based face-mesh visualization app rendering facial landmark meshes in real time.

**Live demo:** https://munkys.dev/face-mesh

> Requires camera access (getUserMedia); served over HTTPS.

## Run locally
```bash
docker build -t face-mesh-explorer .
docker run --rm -p 8080:80 face-mesh-explorer
```

Then open http://localhost:8080

## Deployment
Deployed as a lightweight Nginx container behind Caddy on munkys.dev under `/face-mesh`.
