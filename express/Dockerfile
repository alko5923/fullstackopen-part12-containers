FROM node:16
  
WORKDIR /usr/src/app

COPY --chown=node:node . .
RUN npm ci 

ENV DEBUG=part-12-containers-applications:*

USER node
CMD npm start