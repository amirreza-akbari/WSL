# Common Commands for WSL

Here are some common commands you might find useful when working with WSL.

## Basic Linux Commands

- List files and directories:
  ```bash
  ls
  ```
- Change directory:
  ```bash
  cd /path/to/directory
  ```
- Copy files:
  ```bash
  cp source_file destination
  ```
- Move files:
  ```bash
  mv source_file destination
  ```
- Remove files or directories:
  ```bash
  rm file_name
  rm -r directory_name
  ```

## WSL Specific Commands

- List installed distributions:
  ```bash
  wsl --list --verbose
  ```
- Set default distribution:
  ```bash
  wsl --set-default <DistributionName>
  ```
- Open a new WSL session:
  ```bash
  wsl
  ```

## Network Commands

- Display network configuration:
  ```bash
  ifconfig
  ```
- Ping a host:
  ```bash
  ping hostname
  ```

Feel free to add more commands as needed!
