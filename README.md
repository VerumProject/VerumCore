![image](https://raw.githubusercontent.com/VerumProject/VerumCore/main/src/config/logo-small.png)

### About Verum
```
Verum is a revolutionary, blockchain-based platform designed to promote mental wellness and community support among individuals. The Verum cryptocurrency (VER) serves as a coin for transactions within the platform, allowing users to exchange digital goods and services while also promoting positive interactions.
In addition to facilitating secure transactions, Verum is developing a dating app that connects people who share similar interests and values. The app aims to provide a safe space where individuals can form meaningful relationships and support one another in their mental wellness journeys.
To foster a culture of respect and helpfulness within the community, Verum is also creating a chat system that rewards users with achievements and coins for engaging in respectful and supportive conversations. This system encourages people to connect with others who understand their struggles and share their experiences, promoting a sense of belonging and support.
By leveraging this unique combination of security, anonymity, and social interaction, Verum aims to create a culture of openness and acceptance where people feel comfortable sharing their experiences and connecting with others who understand their struggles.
```

<div style="margin-bottom:4px">
<a href="https://verumcoin.nl">
  <img src="https://img.icons8.com/fluency/48/domain.png" alt="Website" style="width:16px;height:16px;border:none;position:relative;top:2px;"/> Website
</a> |
<a href="https://pool.verumcoin.nl/">
  <img src="https://img.icons8.com/color/48/pickaxe.png" alt="Official Pool" style="width:16px;height:16px;border:none;position:relative;top:2px;"/> Official Pool
</a> |
<a href="https://explorer.verumcoin.nl/">
  <img src="https://img.icons8.com/fluency/48/search.png" alt="Official Block Explorer" style="width:16px;height:16px;border:none;position:relative;top:2px;"/> Official Block Explorer
</a> |
<a href="https://discord.gg/WvV5k4hMny">
  <img src="https://img.icons8.com/fluency/48/discord-logo.png" alt="Discord" style="width:16px;height:16px;border:none;position:relative;top:2px;"/> Discord
</a> |
<a href="https://twitter.com/VerumCore">
  <img src="https://img.icons8.com/fluency/48/twitter.png" alt="Twitter" style="width:16px;height:16px;border:none;position:relative;top:2px;"/> Twitter
</a>
</div><br>

![Download Count](https://img.shields.io/github/downloads/VerumProject/VerumCore/total.svg)
![Open Issue Count](https://img.shields.io/github/issues/VerumProject/VerumCore)
![Version](https://img.shields.io/github/v/release/VerumProject/VerumCore)

**** 

### Coin specifications

| Ticker | Decimals | Maximum Supply | Block Reward | Block Time | P2P Port | RPC Port | Service Port | Algorithm                  |
| ------ | -------- | -------------- | ------------ | ---------- | -------- | -------- | ------------ | -------------------------- |
| VRM    | 8        | 10,100,000 VRM | 3 VRM        | 30 Seconds | 14000    | 14001    | 14002        | Cryptonight Turtle (Pico)  |

****

### Tokenomics

| Block Period          | Est. Period | Project Time | Miner Block Reward    | Staking Block Reward   | Total Supply      |
| --------------------- | ----------- | ------------ | --------------------- | ---------------------- | ----------------- |
| 1*                    |             | 30 seconds   | 100,000 VRM           | \-                     | 100,000 VRM       |
| 2 - 86,400            | 1 Month     | 1 Month      | `[100%]` 3 VRM        | \-                     | 359,200 VRM       |
| 86,400 - 1,051,200    | 11 Months   | 1 Year       | `[66%]` 3 VRM         | `[33%]` 2 VRM          | 4,824,000 VRM     |
| 1,051,200 - 2,102,400 | 1 Year      | 2 Years      | `[33%]` 1 VRM         | `[66%]` 1.5 VRM        | 7,452,000 VRM     |
| 2,102,400 - 3,153,600 | 1 Year      | 3 Years      | `[33%]` 0.5 VRM       | `[66%]` 0.75 VRM       | 8,766,000 VRM     |
| 3,153,600 - 4,204,800 | 1 Year      | 4 Years      | `[33%]` 0.25 VRM      | `[66%]` 0.375 VRM      | 9,423,000 VRM     |
| 4,204,800 - 5,256,000 | 1 Year      | 5 Years      | `[33%]` 0.125 VRM     | `[66%]` 0.1875 VRM     | 9,751,500 VRM     |
| 5,256,000 - 6,307,200 | 1 Year      | 6 Years      | `[33%]` 0.0625 VRM    | `[66%]` 0.09375 VRM    | 9,915,750 VRM     |
| 6,307,200 - 7,358,400 | 1 Year      | 7 Years      | `[33%]` 0.03125 VRM   | `[66%]` 0.046875 VRM   | 9,997,875 VRM     |
| 7,358,400 - 8,409,600 | 1 Year      | 8 Years      | `[33%]` 0.015625 VRM  | `[66%]` 0.0234375 VRM  | 10,038,937.5 VRM  |
| 8,409,600 - 9,460,800 | 1 Year      | 9 Years      | `[33%]` 0.0078125 VRM | `[66%]` 0.01171875 VRM | 10,059,468.75 VRM |

_*This is the premine block_

****

### Installing

You can download the latest binary images from here: https://github.com/VerumProject/VerumCore/releases
To compile the binaries yourself, scroll down to the next section.

****

### Ubuntu 64 bit Compiling

##### Prerequisites

You will need the following packages: boost, cmake (3.8 or higher), make, git and GCC/G++ (GCC-7.0 or higher).

##### Commands

- `sudo apt-get install software-properties-common -y`
- `sudo add-apt-repository ppa:ubuntu-toolchain-r/test -y`
- `sudo apt-get update`
- `sudo apt-get install aptitude -y`
- `sudo aptitude install -y build-essential g++-8 gcc-8 git libboost-all-dev python3-pip`
- `sudo pip3 install cmake`
- `export CC=gcc`
- `export CXX=g++`
- `git clone -b master --single-branch https://github.com/VerumProject/VerumCore`
- `cd VerumCore`
- `mkdir build`
- `cd build`
- `cmake ..`
- `make` *(To compile with a different amount of threads, use `make -j4` and replace the `4` with the your desired thread amount.)*

When the build process is complete. You can find the binary in `VerumCore/build/src`.

- `cd src`
- `./Verumd --version`

****
### Windows 64 bit Compiling

##### Prerequisites
- Install  [Visual Studio 2017 Community Edition](https://github.com/VerumProject/VerumCore/raw/main/downloads/vs_community.exe)
- When installing Visual Studio, it is  **required**  that you install  **Desktop development with C++**
- Install [Boost 1.68](https://sourceforge.net/projects/boost/files/boost-binaries/1.68.0/boost_1_68_0-msvc-14.1-64.exe/download)

##### Commands
- [Download](https://github.com/VerumProject/VerumCore/archive/master.zip) the GitHub repository and extract it somewhere.
- From the start menu, open 'Developer Command Prompt for VS 2017'.
- `cd <your_verum_location>`
- `mkdir build`
- `cd build`
- `set PATH="C:\Program Files (x86)\Microsoft Visual Studio\2017\Community\Common7\IDE\CommonExtensions\Microsoft\CMake\CMake\bin";%PATH%`
- `cmake -G "Visual Studio 15 2017 Win64" .. -DBOOST_ROOT=C:/local/boost_1_68_0`

When it's done creating the cmake files you go ahead and open the `VerumCore/build/Verum.sln` file.
On the top right corner you see `Debug` and `x64` next to the `green play button`. Change `Debug` to `Releases`.  Then click on `Build` on the top menu and hit `Build Solution`. When the build process is complete. You can find the binary in `VerumCore/build/src/Releases`.

****

### OSX/Apple 64 bit Compiling

##### Prerequisites

-   Install XCode and Developer Tools.

##### Commands

-   `which brew || /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
-   `brew install --force cmake boost llvm gcc@8`
-   `export CC=gcc-8`
-   `export CXX=g++-8`
-   `git clone -b master --single-branch https://github.com/VerumProject/VerumCore`
-   `cd VerumCore`
-   `mkdir build`
-   `cd build`
-   `cmake ..`
- `make` *(To compile with a different amount of threads, use `make -j4` and replace the 4 with the your desired thread amount.)*

When the build process is complete. You can find the binary in `VerumCore/build/src`.

- `cd src`
- `./Verumd --version`

****

### Raspberry Pi 3 B+ (AARCH64/ARM64) Compiling
The following images are known to work. Your operation system image  **MUST**  be 64 bit.

##### Known working images

-   [https://github.com/Crazyhead90/pi64/releases](https://github.com/Crazyhead90/pi64/releases)
-   [https://fedoraproject.org/wiki/Architectures/ARM/Raspberry_Pi#aarch64_supported_images_for_Raspberry_Pi_3](https://fedoraproject.org/wiki/Architectures/ARM/Raspberry_Pi#aarch64_supported_images_for_Raspberry_Pi_3)
-   [https://archlinuxarm.org/platforms/armv8/broadcom/raspberry-pi-3](https://archlinuxarm.org/platforms/armv8/broadcom/raspberry-pi-3)

Once you have a 64 bit image installed, setup proceeds the same as any Linux distribution. Ensure you have at least 2GB of ram, or the build is likely to fail. You may need to setup swap space.

##### Commands

-   `git clone -b master --single-branch https://github.com/VerumProject/VerumCore`
-   `cd VerumCore`
-   `mkdir build`
-   `cd build`
-   `cmake ..`
-   `make`

When the build process is complete. You can find the binary in `VerumCore/build/src`.

- `cd src`
- `./Verumd --version`

****

### Thanks to these people to make Verum happen
- Cryptonote Developers
- Bytecoin Developers
- Monero Developers
- Forknote Project
- TurtleCoin Community
- Verum Developers

****
