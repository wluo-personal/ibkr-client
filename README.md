# ibkr-client
This project is to maintain docker containers to launch ibkr client

# build
sudo docker build -t ibkrself .

# run
sudo docker run -it -p 5000:5000 --name ibtest ibkrself 
bin/run.sh root/conf.yam

https://192.168.50.138:5000/demo/