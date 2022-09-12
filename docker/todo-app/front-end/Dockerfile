FROM node:14

WORKDIR /front-end

EXPOSE 3000

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm" ]
CMD [ "start" ]