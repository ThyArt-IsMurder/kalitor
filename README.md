# kalitor

Installing the Tor Browser on Kali Linux is a straightforward process. Follow these steps to install it:

### 1. Update your system
First, ensure that your system is up to date:
```bash
sudo apt update
sudo apt upgrade -y
```

### 2. Install the Tor Browser Launcher
The easiest way to install the Tor Browser on Kali Linux is by using the Tor Browser Launcher package. You can install it via the command line:
```bash
sudo apt install torbrowser-launcher
```

### 3. Launch the Tor Browser
After the installation is complete, you can launch the Tor Browser by running:
```bash
torbrowser-launcher
```

The Tor Browser Launcher will handle the download and installation of the latest version of the Tor Browser. Once the download and installation are complete, the Tor Browser will launch automatically.

### 4. (Optional) Verify the Installation
You can verify the installation by checking the version of the Tor Browser:
```bash
tor-browser --version
```

### Alternative Method: Manual Installation

If you prefer to install the Tor Browser manually, you can follow these steps:

#### 1. Download the Tor Browser
Download the latest version of the Tor Browser from the official website:
```bash
wget https://www.torproject.org/dist/torbrowser/12.0.1/tor-browser-linux64-12.0.1_en-US.tar.xz
```

(Note: Check the [Tor Project website](https://www.torproject.org/download/) for the latest version and adjust the URL accordingly.)

#### 2. Extract the Tarball
Extract the downloaded tarball:
```bash
tar -xvf tor-browser-linux64-12.0.1_en-US.tar.xz
```

#### 3. Run the Tor Browser
Navigate to the Tor Browser directory and run the startup script:
```bash
cd tor-browser_en-US/
./start-tor-browser.desktop
```

This will launch the Tor Browser. You can also create a desktop shortcut for easier access in the future.

By following either of these methods, you should be able to successfully install and run the Tor Browser on Kali Linux.
