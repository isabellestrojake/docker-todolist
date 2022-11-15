FROM node:14-alpine AS todofrontend

EXPOSE 3000

ADD node_modules.tar.gz /dk-fe

COPY . /dk-fe

ENTRYPOINT ["npm", "start"]