
# MoneyBand

 - **Leave a star ⭐ if you like this project 🙂 thank you.**

![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/bardiotmarin/MultyBand/release-on-tag.yml?style=flat-square&link=https%3A%2F%2Fgithub.com%2Fbardiotmarin%2FMultyBand)

  

**|Easy automatic multi-app passive income project with Web Dashboard, Auto Updater, and Proxy Support :dollar::satisfied:|**

  

## Quick Overview 🚀

**MultyBand** leverages unused internet bandwidth, allowing you to make money with something you have and would otherwise be wasted. It utilizes containerized versions of apps like EarnApp, Honeygain, IPRoyal Pawns, PacketStream, Peer2Profit, Repocket, Earnfm, Proxyrack, Proxylite, Bitping, Grass, Packetshare, Gradient and more. It's also safer than installing and using these native apps on your host system.

  

✨ **Key Features:**

-  **Multiplatform** and lightweight Docker stack.

-  **Automatic Updates** to keep your applications up-to-date.

-  **Web Dashboard** for easy monitoring.

-  **Proxy Support** for enhanced flexibility.

  

🌐 For a detailed overview and FAQ, visit the [Wiki](https://github.com/bardiotmarin/MULTYBAND/wiki) ( soon) .

  

## Getting Started 🚥

  

### Prerequisites 

- Ensure that you have a 64-bit operating system, virtualization functions are enabled, and Docker is installed and able to auto-start on system boot.

- (Optional) For ARM devices like Raspberry Pi, installing an emulation layer for non-ARM native Docker images is recommended. Even though the script can assist with the installation, we recommend users install an emulation layer by themselves following the [Wiki](https://github.com/bardiotmarin/MULTYBAND/wiki) guide.

- (Optional) On Windows, ensure the Virtualization Platform and Windows Subsystem for Linux are active as Docker requires these features. Even though the script can assist with the installation, we recommend users enable these Windows functions by themselves following the [Wiki](https://github.com/bardiotmarin/MULTYBAND/wiki) guide.

  

### Quick Setup Guide 🧑‍💻

  

#### Preferred Method: Using Release Artifacts 📦

  

1.  **Download** the latest release of MultyBand for your operating system from the [Releases Page](https://github.com/bardiotmarin/MULTYBAND/releases).

	-  **Windows Users:**

		- Download the `MultyBand-windows-latest-x64-<version>.zip` file.

		- Extract the ZIP file to a folder of your choice.

		- Navigate to the extracted folder and run `MultyBand.exe`.

		-  **Note:** If Windows SmartScreen appears, click on **More info** and then select **Run anyway** to proceed.

	-  **Linux Users:**

		- Download the `MultyBand-ubuntu-latest-x64-<version>.tar.gz` file.

		- Extract the tar.gz file:```tar -xvzf MultyBand-ubuntu-latest-x64-<version>.tar.gz```

		- Navigate to the extracted folder and run the script:```./MultyBand``` 
		- **Note:** You can make sure it is executable on your OS with ```chmod +x MultyBand```

	-  **macOS Users:**

		- Download the `MultyBand-macos-latest-x64-<version>.tar.gz` file.

		- Extract the tar.gz file:```tar -xvzf MultyBand-macos-latest-x64-<version>.tar.gz```

		- Navigate to the extracted folder and run the script:```./MultyBand``` 
		- **Note:** You can make sure it is executable on your OS with ```chmod +x MultyBand```

	-  **ARM Devices (e.g., Raspberry Pi):**

		- Download the appropriate ARM release from the [Releases Page](https://github.com/bardiotmarin/MULTYBAND/releases) (e.g., `arm64` or `armv7`).

		- Follow the same steps as Linux users.

  

2.  **Register** accounts on the application websites. [Here's a list of available apps](#app-compatibility-and-sign-up-links-).

  

3.  **Run** the guided setup through the MultyBand application:

	- Follow the on-screen instructions to configure and start the services.

  

4.  **Start Earning** passively and monitor your performance through the web dashboard.

  

#### Alternative Method (any OS): Cloning the Repository / running from source code 🔀

  

If you prefer to clone the repository (or contribute to the project):

  

1.  **Clone** the project:```git clone https://github.com/bardiotmarin/MULTYBAND.git && cd MultyBand```

	-  **OR** download the ZIP and extract it using one of the options below:
		- ```wget https://github.com/bardiotmarin/MULTYBAND/archive/refs/heads/main.zip && unzip main.zip && cd MultyBand-main```
		- ```Invoke-WebRequest -Uri https://github.com/bardiotmarin/MULTYBAND/archive/refs/heads/main.zip -OutFile main.zip; Expand-Archive -Path main.zip -DestinationPath .\ ; cd MultyBand*```
2.  **Run** the project from source code:```pip install -r requirements.txt && python3 main.py```
	- Feel free to create a virtual environment first if you want to keep your OS Python installation cleaner: `python3 -m venv venvm4b`
 	- Remember to activate the virtual environment by using:
	  - (Linux/Mac):  ```source venvm4b/bin/activate```
	  - (Windows): ```venvm4b\.Scripts\activate```

  
  
  

#### M4B v3 legacy Setup Guide 🧓

1.  **Download** the latest version of MultyBand from the [Releases](https://github.com/bardiotmarin/MULTYBAND/releases) or git clone the project.
2.  **Register** accounts on the application websites. [Here's a list of availabe apps](#app-compatibility-and-sign-up-links-)
3.  **Access the MultyBand v3 Folder**: The legacy code of M4B v3 is included with the new releases and is located in a subfolder. To run the old M4B v3 bash or PowerShell scripts, navigate to this subfolder and use one of the following options:
	- **(Linux/Mac):** ```sudo chmod +x runme.sh && ./runme.sh```
	- **(Windows):**```Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Bypass -Force; .\runme.ps1```


4.  **Follow the remaining standard steps until completion** 

  

## App Compatibility and Sign Up Links 📋

Register an account on the app's sites clicking each apps' names in the following compatibility matrix

  

- :moneybag: Registering trough these links on the apps' sites, you should also receive a welcome bonus and at the same time you will effortlessly show that you appreciate my work, thank you so much :slightly_smiling_face:.

  

- :key: If you are using login with google, remember to set also a password for your app account!

  

| App Name & Link | Residential/Home/Mobile IP or equivalent Proxy's IP | VPS/Datacenter/Hosting/Cloud IP or equivalent Proxy's IP | Max devices per Account | Max Devices per IP |
| :---: | :---: | :---: | :---: | :---: |
| Go to [Earnapp](https://earnapp.com/i/8zp7aub) | :white_check_mark: | :x: | 15|1|
| Go to [HoneyGain](https://r.honeygain.me/BARDICEAC7) | :white_check_mark: | :x: |10|1|
| Go to [IPROYAL](https://pawns.app/?r=740309) | :white_check_mark: | :x: |Unlimited|1|
| Go to [PEER2PROFIT](https://t.me/peer2profit_app_bot?start=165478003262a1f0801ea04) | :white_check_mark: | :white_check_mark: | Unlimited|Unlimited|
| Go to [PACKETSTREAM](https://packetstream.io/?psr=3zSD) | :white_check_mark: | :x: |Unlimited|1|
| Go to [TRAFFMONETIZER](https://traffmonetizer.com/?aff=280746) | :white_check_mark: | :white_check_mark: |Unlimited|Unlimited|
| Go to [REPOCKET](https://link.repocket.com/TPiy) | :white_check_mark: | :white_check_mark: |Unlimited|2|
| Go to [EARNFM](https://earn.fm/ref/MATTTAV6) | :white_check_mark: | :x: |Unlimited|1|
| Go to [PROXYRACK](https://peer.proxyrack.com/ref/myoas6qttvhuvkzh8ffx90ns1ouhwgilfgamo5ex) | :white_check_mark: | :white_check_mark: |500|1|
| Go to [PROXYLITE](https://proxylite.ru/?r=O1QRU93Q) | :white_check_mark: | :white_check_mark: |Unlimited|1|
| Go to [BITPING](https://app.bitping.com?r=qm7mIuX3) | :white_check_mark: | :white_check_mark: |Unlimited|1|
| Go to [SPEEDSHARE](https://speedshare.app/?ref=mindlessnerd) | :white_check_mark: | :x: | Unlimited | 1 |
| Go to [GRASS](https://app.getgrass.io/register/?referralCode=ra6C9seOytc9eY0) | :white_check_mark: | :x: | Unlimited | 1 |
| Go to [PACKETSHARE](https://packetstream.io/?psr=vPS) | :white_check_mark: | :x: | Unlimited | 1 |
| Go to [GRADIENT](https://app.gradient.network/signup?code=DD5SE8) | :white_check_mark: | :x: | Unlimited | 1 |
| Go to [MYSTNODE](https://mystnodes.co/?referral_code=eY6cj1t8sUv4bwgMbWqZSBNyzhB3jXITPrmR5HXC) | :white_check_mark: | :white_check_mark: |Unlimited|Unlimited|

  

## Scale Up with Multi-Proxy Support 🌐

  

**MultyBand** has the ability to create multiple instances also using a proxy list, ideal for scaling up your setup. Quickly set up numerous instances each linked to a different proxy with ease.

  

### Getting Started with Multi-Proxy

1.  **Prepare Proxies**: Create a `proxies.txt` file in the root folder of M4B, listing each proxy on a separate line and ending with a new line.
	- Proxy entries can be formatted in one of the following ways:
 		- **With Authentication:** `protocol://proxyUsername:proxyPassword@proxy_url:proxy_port`
   		-  **Without Authentication:** `protocol://proxy_url:proxy_port`
2. **Start M4B and do the Setup**: During the setup MultyBand will ask you if you want to setup mutiplroxy, reply yes and follow the steps.

### Getting Started with Multi-Proxy (Legacy M4B v3)
1.  **Initial Setup**: First, set up the main instance using `runme.sh` with a proxy.
2.   **Prepare Proxies**: Create a `proxies.txt` in the root folder, listing each remaning proxy on a separate line and ending with a new line.
3.   **Run the multiproxy instances**: Use the "Setup and manage multiproxy instances by list" in the M4B menu or execute `runmproxies` script in the terminal. 

>  **Notice:** While using multiple proxies, be aware that only certain apps permit proxy usage per their Terms of Service. We recommend using personal, private proxies with IPs not flagged as proxies and always respecting the ToS of each app.

> **Notice:** Proxy entries can be formatted in one of the following ways:
>	- **With Authentication:** `protocol://proxyUsername:proxyPassword@proxy_url:proxy_port`
> 	-  **Without Authentication:** `protocol://proxy_url:proxy_port`

## Compatibility and tested environments

This Docker Stack should work on anything that may have docker installed. In particular, it has been tested on:

| | Windows 11 x86_64\amd64 | Linux Ubuntu x86_64\amd64 | Raspbian OS arm64 | MacOS Intel x86_64 | MacOS silicon arm64 |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Tested | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle:|
| on device | Desktop/Laptop PC | Desktop/Laptop PC | Raspberry Pi3/Pi4 | MacBook Pro | MacBook Air |

  

:green_circle:: All functions supported, Auto/manual setup supported

:yellow_circle:: All functions supported but not tested, Auto/manual setup supported

  

## Need Help or Found an Issue? ❓

- For discussions, info, and feature requests, use the [Discussion tab](https://github.com/bardiotmarin/MULTYBAND/discussions)

- F.A.Q., Alternatve Manual Setup, How To Update, other useful guides and more details inside the [Wiki](https://github.com/bardiotmarin/MULTYBAND/wiki)

  

- For issues and bug reporting, use the [Issue tab](https://github.com/bardiotmarin/MULTYBAND/issues).



  

## Support the Projects 🫶

  

Your contributions are vital in helping to sustain the development of open-source projects and tools made freely available to everyone. If you find value in my work and wish to show your support, kindly consider making a donation:

  

### Cryptocurrency Wallets

  

-  **Bitcoin (BTC):**  `bc1q2rhag5upk2wa9nkjm5tw0rp6ulhrf7ccm8zk4t`

-  **Ethereum (ETH):**  `0xE65c32004b968cd1b4084bC3484C0dA051eeD3ee`

-  **Polygon (MATIC):**  `0x488EC95186f66ED42E9b9c04CadD8D5feaA6A9fE`

-  **BNB (Binance Smart Chain):**  `0x488ec95186f66ed42e9b9c04cadd8d5feaa6a9fe`

  

Your support, no matter how small, is enormously appreciated and directly fuels ongoing and future developments. Thank you for your generosity! 🙏

  

---

### :warning: Disclaimer


Always check that the laws of your country and the contractual terms of your internet plan allow the use of such applications. In any case, I do not take any responsibility for any consequences deriving from the use of such apps. This stack proposed by me simply brings these apps together, allows easy configuration even for the less experienced, and updates the apps' images automatically.

This project and its artifacts are provided "as is" and without warranty of any kind.

The author makes no warranties, express or implied, that this script is free of errors, defects, or suitable for any particular purpose.

The author shall not be held liable for any damages suffered by any user of this script, whether direct, indirect, incidental, consequential, or special, arising from the use of or inability to use this script or its documentation, even if the author has been advised of the possibility of such damages.

  

## :hash: License

[GPL 3.0](https://www.gnu.org/licenses/gpl-3.0.html)
