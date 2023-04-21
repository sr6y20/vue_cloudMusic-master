FROM node:12

ARG REGISTRY=https://registry.npm.taobao.org

WORKDIR /opt/cloud-music

COPY . /opt/cloud-music

EXPOSE 8080

RUN npm i --registry ${REGISTRY}

CMD ["npm", "run", "serve"]
