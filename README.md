# SiriCoin
[SiriCoin](https://siricoin.tech) is a cryptocurrency which can be mined on any device like android phones, Computer's CPU or GPU, AVR devices like arduino, esprissif systems SoC chips like ESP boards, linux devices and many more devices... More info [SiriCoin-Docs](https://docs.siricoin.tech)


# Mainnet
SiriCoin mainnet is the backbone of SiriCoin network, which actually does many stuffs like getting the transaction, giving and accepting jobs from miners, providing informations to the explorer, works as a mainnet for the metamask (siricoin wallet). This was made by [Yanis](https://github.com/ygboucherk) but since he is so busy in his life his repository wasnt maintained. Now the mainnet is maintained by me but he still has access to this repository.


# Installation and Hosting
If you have planned to host a mainnet to support SiriCoin, Thats Great!! follow the guide to host it

* NOTE THAT YOU WILL NEED A STRONG/POWERFUL VPS TO HOST THE MAINNET AS IT SYNCS TO THE NETWORK AND SENDS/RECIEVES DATA ALL THE TIME THERE MIGHT BE EXTRA LOAD IF YOU USE LOW END VPS.

Step 1 -- Update and upgrade your VPS and install git. Follow the below command to do it.

``sudo apt-get update && sudo apt-get upgrade && sudo apt-get install git``

Step 2 -- You will have to clone this repository in order to download the code in your VPS then cd into the directory. Run the below command to clone it.

``git clone https://github.com/Shreyas-ITB/SiriCoin-Mainnet/``

``cd SiriCoin-Mainnet``

Step 3 -- Next in order to run the mainnet you will have to install python and pip (if not installed in your VPS) if it is installed please skip this step.

``sudo apt-get install python3``

``sudo apt-get install python3-pip``

Step 4 -- Now you need to install some dependencies to install it follow the below steps.

``pip install -r requirements.txt``

Step 5 -- Finally Run the mainnet file.

``python3 mainnet-main.py``

* Note that your Python version needs to be atleast 3.9 in order to the mainnet to work. also the mainnet once running will automatically sync to the network by itself.
