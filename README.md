<p align="center"><img src="https://raw.githubusercontent.com/cilegordev/cilegordev/refs/heads/main/assets/WSL.png" height="128px" weight="128px" alt="WSL"></p>

<h1 align="center">Azure Linux Desktop Experience.</h1>

<p align="center">Enable DE/WM like Xfce or Hyprland</p>

<hr>

## How to install?

1. **Install extended repo**
    ```
   sudo dnf install azurelinux-repos-extended
    ```

2. **Get this repo**
    ```
   sudo wget -P /etc/yum.repos.d https://raw.githubusercontent.com/cilegordev/azurelinux-repos-env/refs/heads/Extended/azurelinux-env.repo
    ```

## Or you can install prebuild iso

1. **Get the iso**
   ```
   https://github.com/cilegordev/azurelinux-repos-env/releases/tag/6.6.85.1-4-23062025
   ```

2. **You can install on a vm or baremetal**