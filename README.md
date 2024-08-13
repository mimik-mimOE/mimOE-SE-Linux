
# mimOE-SE-Linux v3.12.0

**mimOE (mim Operating Environment)**, mimOE-SE-Linux Standard Edition for Ubuntu Linux, supports the following platforms and architectures:

1. **mimOE for Linux** on Intel and AMD64 for Ubuntu 20.04 and above releases.
2. **mimOE for Linux-ARM64** for Ubuntu 22.04.2 LTS and above releases on Raspberry Pi or NVIDIA Jetson, including Jetson Orin Nano/AGX.
3. **mimOE for Linux-ARM CUDA** for Ubuntu 22.04.2 LTS and above releases on NVIDIA Jetson (with CUDA support), including Jetson Orin Nano/AGX.

   **Note:** The CUDA-enabled edition `mimOE-SE-linux-developer-arm64-CUDA` binary is significantly larger in size due to the inclusion of NVIDIA CUDA components (`.nv_fatbin`).

## Before You Start

- [Explore developer resources & documentation](https://developer.mimik.com)
- [Sign up and create a mimik developer console account](https://developer.mimik.com/console/create_account)

## Installation Guide

1. Download the latest release of mimOE-SE-Linux [here](https://github.com/mimik-mimOE/mimOE-SE-Linux/releases).
2. Create a new directory.
3. Move the downloaded package to the newly created directory.
4. Open a terminal and navigate to the directory containing the downloaded `.tar` file.
5. Untar the package using the following command, replacing `<downloaded mimOE tar file>` with the actual filename. For example, for X86-64 (AMD64) Linux Ubuntu:

   ```
   tar xvf mimOE-SE-linux-developer-amd64-v3.12.0.tar
   ```

6. Run the start script to launch mimOE:

   ```
   ./start.sh
   ```

7. Visit the [Developer Console](https://developer.mimik.com/console/create_account) to create an account and get started with your projects.

## Notes:

- After extracting, a directory may be created. Navigate into this directory to find the `start.sh` script.
- Do not close the terminal window where mimOE is running. Closing this window will terminate the mimOE process.
- To stop mimOE, close the terminal or use the keyboard shortcut `CTRL + C` in the terminal where it is running.
