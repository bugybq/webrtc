sudo apt update
sudo apt upgrade


---
sudo apt install npm
---
#upgrade npm
sudo npm install -g npm
curl -sL https://deb.nodesource.com/setup_13.x | sudo -E bash -
sudo apt install nodejs


#upgrade node
sudo npm cache clean -f
sudo npm install -g n
sudo n latest
PATH="$PATH"

