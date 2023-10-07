# Library-Raspberry-Pi4
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install python3
sudo apt-get install build-essential python-dev
sudo python3 setup.py install

#Grove seeed
curl -sL https://github.com/Seeed-Studio/grove.py/raw/master/install.sh | sudo bash -s -
sudo pip3 install seeed-python-dht
#MQTT
sudo pip install paho-mqtt
#Supervisor
sudo apt-get install supervisor
#Newest
sudo raspi-config -> 5 interfacing options -> P2 SSH
