# Update Package Index:
sudo apt Update

# Install Docker:
sudo apt install -y apt-transport-https ca-certificates curl software-properties-common

# Then add the Docker GPG key:
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

# Add the Docker repository to your system:
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"

# Finally, install Docker:
sudo apt update
sudo apt install docker-ce

# Start Docker Service:
sudo systemctl start docker
sudo systemctl enable docker

# Verify Installation:
sudo docker --version

# Manage Docker as a Non-Root User (Optional):
sudo usermod -aG docker $USER

### Log out and log back for the change to take effect ###

# Test docker service:
docker pull hello-world
docker run hello-world
