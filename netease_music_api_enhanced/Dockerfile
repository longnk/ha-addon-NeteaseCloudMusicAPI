FROM node:18-alpine

WORKDIR /app

COPY build/NeteaseCloudMusicApiEnhanced /app

RUN npm install

COPY run.sh /run.sh
RUN chmod +x /run.sh

CMD [ "/run.sh" ]
