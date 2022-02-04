FROM fusuf/whatsasena:latest

RUN git clone https://github.com/BOSSMODZ/BOSS-MODZZ /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
