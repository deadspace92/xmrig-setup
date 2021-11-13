# xmrig-setup
How to setup your Raspberry pi easily with bash script.

First you want to do these commands.

sudo apt-get install git

git clone https://github.com/deadspace92/xmrig-setup.git

cd xmrig-setup

chmod +x xmrig-setup.sh

./xmrig-setup.sh

chmod +x xmrig-start.sh

Now you want to replace the (your wallet) with your crypto wallet and the (mining pool) with the mining pool you want.

Next do this.

./xmrig-start.sh

Then your good to go!

PS. Your going to need the arm64 version of raspbian (aka raspberry pi os).
  
You can Download it at https://downloads.raspberrypi.org/raspios_lite_arm64/images/

I suggest this mining pool: gulf.moneroocean.stream:10128
