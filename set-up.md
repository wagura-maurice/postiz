ssh-keygen -f "/home/wagura-maurice/.ssh/known_hosts" -R "207.180.227.85"
ssh root@207.180.227.85
sudo apt install docker-compose -y
mkdir postiz
cd postiz
nano docker-compose.yml

docker compose down
docker-compose up -d
