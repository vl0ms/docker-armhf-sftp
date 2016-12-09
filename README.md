# Description
Docker container with SFTP server for ARM

# Customization
Enter your username and password in start.sh (2 and 4 lines)

# Build
docker build -t vl0ms/armhf-sftp

# Run
docker run -d --restart=always -v /your/data/folder:/data/incoming -p your_port:22 vl0ms/armhf-sftp
