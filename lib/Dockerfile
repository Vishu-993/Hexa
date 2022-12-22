FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Vishu-993/Hexa-Md /root/Vihanga
WORKDIR /root/Vihanga/
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
