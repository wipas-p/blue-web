# blue-web

docker run -d -p 8080:80 --name blue-web wipasp/blue-web
docker build -t wipasp/blue-web .

docker push wipasp/blue-web
