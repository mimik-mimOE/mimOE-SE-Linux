# mimOE-SE-Linux

mimOE-SE-Linux Standard Edition for Ubuntu Linux supports the following platforms and architectures.
1. mimOE for generic Linux X86_64 on Intel and AMD64 for Ubuntu 20.04 and above releases.
2. mimOE for Linux-ARM aarch64 for Ubuntu 20.04.2 LTS and above releases on Raspberry Pi 4.
3. mimOE for Linux-ARM aarch64 for Ubuntu 20.04.2 LTS and above releases on NVIDIA Jetson including Jetson Orin Nano.

## Before you start


 [explore the developer resources & documentation](https://developer.mimik.com)
 
 [sign up and create a mimik developer console account](https://developer.mimik.com/console/create_account)


## Installation Guide
1. Download the latest desired release for mimOE-SE-Linux  [HERE](https://github.com/mimik-mimOE/mimOE-SE-Linux/releases)
2. Create a new directory.
3. Move the package to the newly created directory.
4. Open a terminal and navigate to the newly created directory with the downloaded .tar file.
5. *Untar package (ex:)
   Use the command say 'tar xvf <dowloaded mimOE tar file for the desired platform>'
   As an example for X86-64(AMD64) Linux Ubuntu, run the following command.

```
tar xvf mimOE-SE-linux-developer-amd64-v3.12.0.tar
```

6. Run the start script to start mimOE
```
./start.sh
```
7. Please visit [Developer Console](https://developer.mimik.com/console/create_account) to create an account and get started with your projects


## Notes:
* A directory may be made after untaring. Navigate into that directory to find the `start.sh` script.
- Do not close the terminal window where mimOE is running. Closing this window will terminate the mimOE process.
- To stop mimOE, in the terminal where it is running, either close the terminal or use the keyboard shortcut CTRL + C.
