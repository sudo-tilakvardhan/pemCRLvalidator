# pemCRLvalidator
A nodejs snippet which takes PEM encoded public key, decode the CRL CDP endpoint and checks if the provided certificate is revoked by the the Issuer. 

sudo yum install -y yum-utils
sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
sudo yum install docker-ce docker-ce-cli containerd.io docker-compose-plugin
sudo systemctl start docker
