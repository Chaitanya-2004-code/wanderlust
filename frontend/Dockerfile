FROM	node:21
WORKDIR	/frontend
COPY	package*.json ./
RUN	npm i
COPY	. .
COPY	.env.sample .env.local
EXPOSE	3000
cmd	["npm","run","dev","--","--host"]

