# spot-grlib
Boston dynamics SPOT control using [grlib](https://github.com/mikhail-vlasenko/grlib)


## install
sudo pip install -r requirements.txt  

## Create data
set lable name in creat_data.py, then run:  
sudo python create_data.py  
Shoot training images of specific gestures with space bar

## Run Main script
export BOSDYN_CLIENT_USERNAME=<user>  
export BOSDYN_CLIENT_PASSWORD=<password>  
python main.py  
