docker build -t fullstack-session2 .
docker run -d -p 8080:80 fullstack-session2

docker run -d -p 8080:80 -v "D:\fullstack2\Sesion_2\docker-nginx:/usr/share/nginx/html" fullstack-session2