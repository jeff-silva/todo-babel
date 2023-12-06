FROM node:21

# WORKDIR /usr/src/app

RUN npm install -g @nestjs/cli

# COPY package.json .
# COPY yarn.lock .

RUN yarn install

# COPY . .

# EXPOSE 3000

# Comando para iniciar a aplicação
CMD ["yarn", "start:dev"]