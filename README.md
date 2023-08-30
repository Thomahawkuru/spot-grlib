# spot-grlib
Boston dynamics SPOT control using grlib.


## install
sudo pip install -r requirements.txt
sudo python main.py -m 192.168.80.3
## Create data
set lable name in creat_data.py, then run:
sudo python create_data.py

## Run Main script
export BOSDYN_CLIENT_USERNAME=<user>
export BOSDYN_CLIENT_PASSWORD=<password> 
sudo python main.py -m 192.168.80.3