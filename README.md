# Commands used

1. touch package.json
2. npm install
3. touch .dockerignore
4. touch app.js
5. touch Dockerfile
6. docker build . -t node-js-app
7. docker run -dp 3000:80 --memory=10m --cpus=0.1 node-js-app
8. curl -i localhost:3000
9. docker tag node-js-app melkye/docker-training
10. docker push melkye/docker-training