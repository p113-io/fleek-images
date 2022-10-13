# ==== CONFIGURE =====
FROM debian:sid
RUN apk update && apk add --no-cache curl tree 
RUN curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
RUN apk install nodejs
RUN npm i -g serve
RUN npm i -g pnpm