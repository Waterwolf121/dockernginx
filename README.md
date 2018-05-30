# nginx
git clone https://github.com/Waterwolf121/dockernginx.git

cd dockernginx

SUDO BASH docker-install.sh

cd dockernginx

sudo docker image build . -t valami

sudo docker container run –d –p 80:80 (a konténer build számának az első 4 számjegye)
