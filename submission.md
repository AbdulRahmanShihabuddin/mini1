# Submission: Docker & App Verification

Repository: https://github.com/AbdulRahmanShihabuddin/mini1

---

## 1) Docker containers (output of `docker ps`)

```
$(docker ps output captured below)

NAMES              IMAGE            STATUS          PORTS
mini1-frontend-1   mini1-frontend   Up 4 minutes    0.0.0.0:3000->3000/tcp, [::]:3000->3000/tcp
mini1-backend-1    mini1-backend    Up 4 minutes    0.0.0.0:5001->5000/tcp, [::]:5001->5000/tcp
mini1-db-1         postgres:13      Up 11 minutes   5432/tcp
```

## 2) Backend API response (GET /api)

```
Hello from Express + Postgres! Server time: (example response)
Hello from Express + Postgres! Server time: Wed Nov 26 2025 08:28:25 GMT+0000 (Coordinated Universal Time)
```

## 3) Frontend served HTML (top of `http://localhost:3000`)

```
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>React + Express + Postgres App</title>
  <script defer src="/static/js/bundle.js"></script></head>
  <body>
    <noscript>You need to enable JavaScript to run this app.</noscript>
    <div id="root"></div>
  </body>
</html>
```

---

## Notes

- I committed and pushed the Dockerfiles and compose setup with message: "Added Dockerfiles and docker-compose setup".
- You can view the full code on GitHub: https://github.com/AbdulRahmanShihabuddin/mini1

If you need actual image screenshots instead of the textual outputs above, please tell me and I can:

- capture terminal output as PNG images and embed them in a PDF, or
- walk you through taking browser screenshots and I will assemble the final PDF/DOC.
