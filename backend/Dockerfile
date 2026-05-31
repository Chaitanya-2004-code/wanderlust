# Base image from backend 
FROM	node:21

#Set the working directory inside the container
WORKDIR	/app

# Copy Package,json and package-lock.json to the working directory 
COPY	package*.json ./

RUN	npm install

COPY	..
COPY	.env.sample .env

EXPOSE 	5000

CMD	["npm","start"]
