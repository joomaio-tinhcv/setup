# bash script setup starter

# Getting started
Clone bash script 
```
git clone https://github.com/joomaio-tinhcv/setup.git
cd
```
# Run bash script
```
sudo bash setup.sh -user user-name -fpm fpm-container-name -fpm_path folder_path_in_container
```
with
user-name: permission for starter work, ex: www-data
fpm-container-name: container name run php service. If empty, bash script will run without docker container
folder_path_in_container: is folder source run bash script in container.

When run bash script, you must enter database info:
```
Enter database host: your_db_host
Enter database username: your_db_username
Enter database password: your_password
Enter database name: your_name
Enter database prefix: your_prefix
```
# Install pnote / psol with web app
Step1: acess link: https:\\your_domain\starter?access_key=OPQzxeyQpU
Step2: login in with account in config/starter.php, default: starter \ 4Gr6RlAHPp
Step3: Click button Install

# Install pnote / psol with cli
```
cd ./starter
```

Run command install pnote: 
```
php spt install pnote
```

Or run command install psol:
```
php spt install pnote
```