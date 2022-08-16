FROM node:16

WORKDIR /usr/drivenops/

COPY . .

EXPOSE 5000

RUN npm i && npx prisma generate && npm run build

CMD ["npm", "run", "start"]