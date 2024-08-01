# Installing Kali Nethunter on Android without Root

This script allows you to install Kali Nethunter on an Android device without requiring root access. It is provided by **trhacknon**.

## Prerequisites

- An Android device with Termux installed.
- An active internet connection.

## Instructions

### Step 1: Download the Script

Download the script by running the following commands in Termux:

```bash
pkg install wget -y
wget -O install_kali.sh https://haste-server-me13.onrender.com/raw/iroceholar
chmod +x install_kali.sh
```

### Step 2: Run the Script

Run the downloaded script:

```bash
./install_kali.sh
```

### Script Details

The script performs the following actions:

1. **Configure storage for Termux**:
    - Command: `termux-setup-storage`
    - Description: Configures storage permissions for Termux.

2. **Install wget**:
    - Command: `pkg install wget -y`
    - Description: Installs the wget tool to download files.

3. **Download the installation script**:
    - Command: `wget -O install-nethunter-termux https://haste-server-me13.onrender.com/raw/ogixuzodeh`
    - Description: Downloads the Kali Nethunter installation script.

4. **Make the installation script executable**:
    - Command: `chmod +x install-nethunter-termux`
    - Description: Modifies the script's permissions to make it executable.

5. **Run the installation script**:
    - Command: `bash install-nethunter-termux`
    - Description: Executes the downloaded installation script.

### Warnings

- Ensure that your Android device is compatible with Termux and Kali Nethunter.
- This script is provided as-is, with no warranty. Use it at your own risk.

### Support

For any questions or assistance, please contact **trhacknon** via [contact link].

---

**Note**: This README uses simple formatting for better readability. For advanced visual effects, you can explore extended Markdown features and GitHub plugins.
