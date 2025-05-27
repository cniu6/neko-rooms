# Community Installation Scripts

This directory contains community-maintained installation scripts for various operating systems and configurations. While these scripts are not officially supported, they can be helpful for setting up neko-rooms on different platforms.

## Available Scripts

### AWS Linux
For Amazon Linux 2 or higher:
```bash
apt install -y sudo curl wget unzip git
wget -O neko-rooms-aws.sh https://raw.githubusercontent.com/cniu6/neko-rooms/refs/heads/pause_api/community/scripts/ubuntu-debian.sh
sudo bash neko-rooms-aws.sh
```

### Ubuntu/Debian with Nginx
For Ubuntu 20.04 or higher, or Debian 10 or higher:
```bash
apt install -y sudo curl wget unzip git
wget -O neko-rooms.sh https://raw.githubusercontent.com/cniu6/neko-rooms/refs/heads/pause_api/community/scripts/ubuntu-debian.sh
sudo bash neko-rooms.sh
```
