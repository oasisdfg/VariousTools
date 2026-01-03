![screenshot 1430](https://github.com/user-attachments/assets/a41c7356-bf51-4e0c-9ce9-ee67c404ef58)

# A Program which allows users who want quick access to common system tweaks and resolution changes
## Features
### NVIDIA Service Toggle - Quickly enable/disable the NVDisplay. ContainerLocalSystem service
### Monitor Toggle - Enable/disable monitor devices via Device Manager
### Win32PrioritySeparation - Adjust CPU priority allocation between foreground and background processes
### InterruptSteeringFlags - Configure hardware interrupt distribution across CPU cores
### Resolution Changer - Switch between available display resolutions (all displayed at 250Hz)
### Quick Cleanup - Remove temporary files, caches, logs, and non-present devices
### Smart Static IP - Auto-detects current network config and selects the fastest DNS (Google vs Cloudflare) via ping test
### Restart Explorer - Quick explorer. exe restart
### Requirements
### Windows 10/11
.NET 6.0 or later
Run as Administrator for full functionality
Notes
Registry changes (Win32PrioritySeparation, InterruptSteeringFlags) require a system restart to take effect
Static IP functionality auto-detects your current IPv4 configuration and tests DNS latency before applying
