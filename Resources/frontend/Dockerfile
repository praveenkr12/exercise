FROM node
WORKDIR /client
COPY Package*.json /client/
RUN npm install
COPY . /client/
EXPOSE 3999
CMD ["npm","start"]
