FROM Ajser4/Sana-Mwol:latest

RUN git clone https://github.com/Ajser4/Sana-Mwol /root/sana
WORKDIR /root/sana/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Ajser4/sana-media

CMD ["node", "bot.js"]
