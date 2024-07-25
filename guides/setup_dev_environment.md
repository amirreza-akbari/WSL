# Setting Up Development Environment in WSL

Follow these steps to set up a development environment in WSL.

## Step 1: Install Essential Packages

1. Open your WSL terminal.
2. Install Git:
   ```bash
   sudo apt install git
   ```
3. Install other essential packages:
   ```bash
   sudo apt install build-essential curl wget
   ```

## Step 2: Set Up a Code Editor

1. Install Visual Studio Code:
   - Download and install [Visual Studio Code](https://code.visualstudio.com/) on your Windows machine.
   - Install the "Remote - WSL" extension from the Extensions view.

## Step 3: Clone a Repository

1. Navigate to your working directory:
   ```bash
   cd ~
   ```
2. Clone a repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```

Your development environment is now ready!
