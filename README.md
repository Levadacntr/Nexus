docker pull nexusxyz/nexus-cli:latest
sudo apt install screen -y && screen -Rd nexus
docker run -it --init --name nexus nexusxyz/nexus-cli:latest start --node-id YOUR_NODE_ID
