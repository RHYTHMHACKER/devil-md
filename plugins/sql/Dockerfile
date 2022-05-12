FROM fusuf/whatsasena:latest

RUN git clone https://github.com/RHYTHMHACKER/devil-md
WORKDIR /skl/Raganork
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN npm install
CMD ["node", "index.js"]
