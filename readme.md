* Instalar o apache *
	sudo apt-get update
	apt-get install apache2

* Habilitar o novo site(sites-avalible) *
	a2nensite [nome do arquivo .conf]

* Para o Apache processar o php *

sudo apt-get install php libapache2-mod-php
sudo a2enmod mpm_prefork && sudo a2enmod php7.0
sudo service apache2 restart