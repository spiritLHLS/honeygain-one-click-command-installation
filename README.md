# honeygain-one-click-command-installation

## Language

[English](README.md) | [中文文档](README_zh.md)

## **Introduction**

The honeygain is an option that allows users to earn money by sharing your traffic.

You'll receive $0.10 for the 1G traffic you share, and this script supports data center network or home bandwidth.

It has below features:

1. Automatically install docker based on the system, and if docker are already installed, it will not installed again.

2. Automatically select and build the pulled docker image according to the architecture, without the need for you to manually modify the official case.

3. Use Watchtower for automatic mirror update without manual update and re-entry of parameters.

(Watchtower is a utility that automates the updating of Docker images and containers. It monitors all running containers and related images, and automatically pulls the latest image and uses parameters when initially deployed to restart the corresponding container.)

## Notes

- Verified on AMD64 and ARM
- Try it if you are interested via my --> [referrals](https://r.honeygain.me/SPIRICF6DB) <--, you will get 5 dollar.

## Install

### Interactive installation

```shell
curl -L https://raw.githubusercontent.com/spiritLHLS/honeygain-one-click-command-installation/main/hg.sh -o hg.sh && chmod +x hg.sh && bash hg.sh
```

After the registration link is registered, remember the email and password, run this script, paste the email and password, and press Enter to start the installation.

### One command installation

```shell
curl -L https://raw.githubusercontent.com/spiritLHLS/honeygain-one-click-command-installation/main/hg.sh -o hg.sh && chmod +x hg.sh && bash hg.sh -m youremail -p yourpassword
```

Change to your the email and password of this command

## Uninstall

```shell
bash hg.sh -u
```

uninstall service

## Experience

The platform does not allow data center traffic, so it can only be shared using home bandwidth or similar.

## Disclaimer

This program is for learning purposes only, not for profit, please delete it within 24 hours after downloading, not for any commercial use. The text, data and images are copyrighted, if reproduced, please indicate the source.

Use of this program is subject to the deployment disclaimer. Use of this program is subject to the laws and regulations of the country where the server is deployed, the country where it is located, and the country where the user is located, and the author of the program is not responsible for any misconduct of the user.
