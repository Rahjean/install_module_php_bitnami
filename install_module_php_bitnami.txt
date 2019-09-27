Activation module php:
	1)micreer fichier d'information ho anilay site ary asina ilay code eo ambany :
		ex: info.php
			﻿<?php phpinfo();?>
	2)lancena ilay fichier info.php rehefa voafindra tay anaty serveur ary jerena oe ef ao v aloa ilay module:
		ex:eufonie.fr/info.php
	3)raha tsy ao ilay module dia manao apt-gat install any amilay serveur
	4)madea /opt/bitnami/php/etc ary alaina modifiena ilay fichier php.ini,tedavina ao ilay module ary activena(esorina ilay point virgule eo aloany ex: extension=imagick.so)
	5)averina alefa am serveur ary manao ireto commande ireto:
	   - sudo /opt/bitnami/ctlscript.sh restart apache
	   - sudo /opt/bitnami/ctlscript.sh restart php-fpm
	6)jerena ilay eufonie.fr/info.php ary tokony ho ita ao ilay module rehefa niactivena
