# ==== CONFIGURE =====
FROM debian:sid
RUN apt update && apt upgrade -y && apt auto-remove -y
RUN apt install curl tree -y
RUN curl -fsSL https://deb.nodesource.com/setup_18.x | bash -
RUN apt install nodejs golang-go -y
RUN npm i -g pnpm