# dot.net

Create Dot net CI\CD server 

##	Method deploy to GCP appengin 

    wget -q https://packages.microsoft.com/config/ubuntu/17.10/packages-microsoft-prod.deb
    sudo dpkg -i packages-microsoft-prod.deb

    sudo apt-get install apt-transport-https
    sudo apt-get update
    sudo apt-get install dotnet-sdk-2.1


## COMMAND STACK

docker stack deploy --compose-file docker-compose.yml