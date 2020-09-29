# docker-mysql8

docker file mysql8 & phpMyAdmin - résoudre le probleme entre php 7.2 et mysql 8 - authentication method unknown to the client

mysql:
  image: mysql:8
  command: ['--character-set-server=utf8mb4', '--collation-server=utf8mb4_unicode_ci','--default-authentication-plugin=mysql_native_password']
