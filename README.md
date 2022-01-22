# Setting up the environment

### The Hardware

Macbook Air M1 (2020)
___


### The OS

Kali Linux 2021.3 ARM64
___

### The Goal

Install Kali on M1 with a fully functional Juice-Shop environment and the latest Burp Community Edition

#### Step 1:

Istall Kali using Parallels Pro

#### Step 2: 

Run update and upgrade
```
sudo apt-get update && upgrade
```

#### Step 3:

Install Juice Shop
1. Follow the docker installation from [this](https://www.techpanther.in/2020/05/install-owasp-juice-shop-on-kali-linux.html) tutorial.
2. Follow [this](https://hub.docker.com/r/santosomar/juice-shop-arm64) tutorial for installing ARM64 Juice Shop.

#### Step 4: 

Install Burp
1. Install Java version for Burp using [this](https://foojay.io/today/java-17-on-the-raspberry-pi/) tutorial.
2. Download .jar Burp file from portswigger.

#### Step 5: 

Install Foxy Proxy
1. Setup foxy proxy using [this](https://null-byte.wonderhowto.com/how-to/use-burp-foxyproxy-easily-switch-between-proxy-settings-0196630/) tutorial.

#### Step 6:

Run your Juice Shop server, start having fun.
