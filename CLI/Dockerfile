FROM node:12

WORKDIR /zenn

ADD package.json /zenn/package.json
RUN npm install

EXPOSE 8000

ENTRYPOINT [ "npx", "zenn" ]
CMD [ "preview" ]
