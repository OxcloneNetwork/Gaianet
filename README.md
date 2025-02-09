# Gaia-Node Installation Guide

# Hardware Requirements
# ✅ CPU: 4 vCPU
# ✅ RAM: 8GB

# Commands to Install

## Install Dependencies
```console
sudo apt update && sudo apt upgrade -y
sudo apt install -y build-essential libssl-dev libffi-dev python3-dev python3-pip pip
```
## Install Gaia repository
```console
sudo apt update && sudo apt upgrade -y
sudo apt install -y build-essential libssl-dev libffi-dev python3-dev python3-pip pip
```
```console
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2-0.5b-instruct/config.json
```
Wait until the installation is complete.

## Now, start the node
```console
gaianet start
```

## Check Node Information
```console
gaianet info
```

## Joining a Domain
(There is only one domain that supports the lowest hardware requirements.)
```console
gaianet stop
gaianet config --domain gaia.domains
gaianet init
gaianet start
```
Now, go to node settings.
Click the three dots in the UI and select "Join Domain."

In the domain field, type "pengu" and add the domain.


# Boosting Node Score
Using this bot instead of ChatGPT will increase your node score.

To keep the node running even when not in use, install an auto-text bot.

1. Switch to the Base network and redeem your EXP points.
2. Convert Credits to Consumed.
3. Create an API key and save it.
   
## Run the bot:
```console
curl -L -o gaiabot.py https://github.com/enzifiri/gaia-node/raw/main/gaiabot.py
screen -S gaia
python3 gaiabot.py
```
To detach from the screen session:
## Press CTRL + A, then D

The "Consumed" credits will increase every time you refresh.

## Adding Multiple Nodes
You can add as many nodes as you want to your account.

⚠ Don’t forget that your token will run out! EXP points are important.

Your node score will increase in 24 hours. 🚀

