
# Dockerfile for ImpactTrack Middleware
FROM node:18
WORKDIR /app
COPY impacttrack_middleware.js .
RUN npm init -y && npm install express axios
CMD ["node", "impacttrack_middleware.js"]
EXPOSE 4000
