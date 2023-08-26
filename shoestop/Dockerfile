FROM node:14-alpine
WORKDIR /app
RUN apk update && apk add git
RUN git clone https://github.com/oooTUXED0ooo/Hackathon-Application.git .
WORKDIR /app/shoestop
RUN npm install
EXPOSE 5000
CMD ["npm", "start"]
