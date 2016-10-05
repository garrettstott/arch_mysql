# Install MySQL Arch

`sudo pacman -S mariadb`

`sudo mysql_install_db --user=mysql --basedir=/usr --datadir=/var/lib/mysql`

`sudo systemctl start mysqld`

`sudo systemctl enable mysqld`

### If you have extra configs
`sudo vim /etc/mysql/my.cnf`

### Login to MySQL
`sudo mysql -u root -p`
