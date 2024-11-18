# Docker installation for Debian12

### Requirements

Have sudo installed and add a user in the sudo group
```apt install sudo
adduser <user> sudo
```

### Run the script with one command (Recommanded)

```
sudo bash -c "$(wget -qLO - https://raw.githubusercontent.com/Aiioonairr/docker_install/refs/heads/main/install_docker.sh)"
```

### Run the script manually

You must to download the script in a dir :

```
wget -qLO - https://raw.githubusercontent.com/Aiioonairr/docker_install/refs/heads/main/install_docker.sh
```

Now, you can run the script with command 'sudo'
```
sudo bash install_docker.sh
```
or
```
sudo ./install_docker.sh
```
