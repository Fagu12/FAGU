FROM quay.io/hermit/hermit-ser:latest

RUN git clone https://github.com/Fagu12/FAGU-MD /root/FAGU-MD
WORKDIR /root/FAGU-MD/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js", "--max_old_space_size=2560"]
