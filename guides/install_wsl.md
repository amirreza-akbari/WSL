# Installing WSL

Follow these steps to install Windows Subsystem for Linux (WSL) on your Windows machine.

## Step 1: Enable WSL

1. Open PowerShell as Administrator.
2. Run the following command:
   ```powershell
   dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
   ```

## Step 2: Install a Linux Distribution

1. Open Microsoft Store.
2. Search for "Linux".
3. Choose your preferred Linux distribution (e.g., Ubuntu) and click "Install".

## Step 3: Set Up Your Linux Distribution

1. Open the installed Linux distribution from the Start menu.
2. Set up your username and password.
3. Update your package lists:
   ```bash
   sudo apt update
   sudo apt upgrade
   ```

Congratulations! You have successfully installed WSL on your Windows machine.
