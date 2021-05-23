# Nextcloud stack

This docker stack deploy a Nextcloud using the following docker images and resources:

### Images 
  + percona:8
  + adminer:latest
  + redis:latest
  + nextcloud-fpm-alpine
  + nginx-stable-alpine


### Resources
* Config
  + nextcloud_conf
* Secret
  + cloud_localdomain_crt
  + cloud_localdomain_key
  + mysql_password
  + mysql_root_password
  + nextcloud_admin_password