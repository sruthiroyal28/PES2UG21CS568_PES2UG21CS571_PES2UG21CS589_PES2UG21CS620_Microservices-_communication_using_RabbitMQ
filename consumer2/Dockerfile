FROM node:14  
WORKDIR /app/consumer2
COPY ..

RUN npm install express
RUN npm install amqplib
RUN npm install mysql2

#COPY PES2UG21CS568_571_589_620_Microservices_communication_using_RabbitMQ/consumer2/!node_modules ./

EXPOSE 3009

CMD ["node", "index.js"]