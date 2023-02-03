npm init -y

npm i express

node index.js

docker build -t chandrashekharchoudha/nodejs-app:0.0.1.RELEASE .

docker container run -p 3000:3000 -d chandrashekharchoudha/nodejs-app:0.0.1.RELEASE

docker push chandrashekharchoudha/nodejs-app:0.0.1.RELEASE
