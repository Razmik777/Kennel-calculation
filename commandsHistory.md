# Task 1

cat > home_animals.txt

собака  

кошка 

хомяк

cat > pack_animals.txt

Лошадь 

Осел

Верблюд


cat home_animals.txt pack_animals.txt > all_animals.txt

cat all_animals.txt

mv all_animals.txt human_friends.txt

ls -l


# Task 2

mkdir animals

mv human_friends.txt animals/

ls -l animals


# Task 3

sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb

sudo apt update

sudo apt install mysql-server

sudo apt install mysql-server mysql-client


# Task 4

sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13\~3-0\~ubuntu-jammy_amd64.deb

sudo dpkg -i docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb

sudo dpkg -r docker-ce-cli
