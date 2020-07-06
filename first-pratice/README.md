docker-compose -f .\traefik.yml up -d
docker-compose -f .\whoami.yml down

docker-compose -f .\whoami.yml up -d
docker-compose -f .\traefik.yml down