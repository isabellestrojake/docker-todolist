FROM node:14-alpine AS todobackend

EXPOSE 3001

ADD node_modules.tar.gz /dk-be

COPY . /dk-be

ENTRYPOINT ["npm", "start"]