FROM node:20-alpine
WORKDIR /app
RUN addgroup -S appgroup && adduser -S appuser -G appgroup
COPY package*.json ./
RUN npm ci --omit=dev
COPY . .
USER appuser
EXPOSE 5001
CMD ["node", "src/index.js"]
