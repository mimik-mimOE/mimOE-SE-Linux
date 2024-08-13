# mimOE-SE-Linux

mimOE(mim Operating Environment), mimOE-SE-Linux Standard Edition for Ubuntu Linux supports the following platforms and architectures.
1. mimOE for generic Linux X86_64 on Intel and AMD64 for Ubuntu 20.04 and above releases.
2. mimOE for Linux-ARM aarch64 for Ubuntu 20.04.2 LTS and above releases on Raspberry Pi 4.
3. mimOE for Linux-ARM aarch64 for Ubuntu 22.04.2 LTS and above releases on NVIDIA Jetson including Jetson Orin Nano.
4. mimOE arm64-CUDA for Ubuntu 22.04.2 LTS and above releases on NVIDIA Jetson (with CUDA support), including Jetson Orin Nano.
   <br /> **NOTE:** CUDA enabled edition minOE-SE-linux-developer-arm64-CUDA **binary is very larger in size** due to NVIDIA CUDA component (**.nv_fatbin**)

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
- To stop mimOE, close the terminal or use the keyboard shortcut CTRL + C in the terminal where it is running.
