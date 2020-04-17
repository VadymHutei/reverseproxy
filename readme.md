docker build -t reverseproxy .

docker-compose -f /home/hutei/projects/proxy/start.yml up -d
docker-compose -f /home/hutei/projects/proxy/start.yml down
