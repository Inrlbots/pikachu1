FROM ameer-kallumthodi/pikachu:test

RUN git clone https://github.com/ameer-kallumthodi/pikachu/ /skl/pikachu
WORKDIR /skl/pikachu 
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "pikachu.js"]
