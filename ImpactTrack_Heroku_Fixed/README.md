
# ImpactTrack Portal & Middleware

## 📦 Contents:
- `impacttrack_portal.html`: Front-end customer portal
- `impacttrack_middleware.js`: Node.js server for backend connections
- `Dockerfile`: Containerize the middleware
- `README.md`: Instructions

## 🚀 Quick Start

### 1. Local Dev
```bash
npm install
node impacttrack_middleware.js
```

### 2. Front-End
Open `impacttrack_portal.html` in a browser. Hook fetch/XHR to `/api/`.

### 3. Docker Run
```bash
docker build -t impacttrack .
docker run -p 4000:4000 impacttrack
```
