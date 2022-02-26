#!/bin/bash
GIT_REPO=https://github.com/Morsmalleo/AhMyth
# Update
# Install AhMyth in Kali Linux 2022
# Source Installation - Linux
# Root Install
npm install -g electron@9.4.1
apt-get install python3* python3-pip*
cd AhMyth/AhMyth-Server
pip3 install -r requirements.txt
npx electron ./app --no-sandbox start


# Install AhMyth in Kali Linux 2021
# sudo npm uninstall -g electron 
# sudo npm uninstall -g electron@9.4.1 
# sudo npm install -g electron@9.4.1 
# cd AhMyth/AhMyth-Server/ 
# npm start
