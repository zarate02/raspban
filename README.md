docker 설치

sudo curl -fsSL get.docker.com -o get-docker.sh
sudo ./get-docker.sh
sudo usermod -aG docker pi

우분투 방화벽

sudo apt-get install ufw
sudo ufw enable
sudo ufw allow 21
sudo ufw deny 21/udp