# WordPress Configuration Notes

- Create MySQL database: `CREATE DATABASE wordpress;`
- Create MySQL user: `CREATE USER 'wpuser'@'localhost' IDENTIFIED BY 'password';`
- Grant privileges: `GRANT ALL PRIVILEGES ON wordpress.* TO 'wpuser'@'localhost';`
- Edit `wp-config.php`:
