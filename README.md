# dot.net

Create Dot net CI\CD server 

##	Method deploy to GCP appengin 

    wget -q https://packages.microsoft.com/config/ubuntu/17.10/packages-microsoft-prod.deb
    sudo dpkg -i packages-microsoft-prod.deb

    sudo apt-get install apt-transport-https
    sudo apt-get update
    sudo apt-get install dotnet-sdk-2.1

    sudo curl -L https://github.com/docker/compose/releases/download/1.21.2/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose
    sudo chmod +x /usr/local/bin/docker-compose
    docker-compose --version


## COMMAND STACK

sudo docker-compose -f docker-compose.yml up 

docker stack deploy --compose-file docker-compose.yml 