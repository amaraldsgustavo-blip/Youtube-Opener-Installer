# Youtube-Opener-Installer

# YouTube Opener. Deployment Project

This place has the code for a Windows installer that makes it easy to get to YouTube using Microsoft Edge.

## Project Overview

The YouTube Opener is a tool that helps people get to YouTube quickly. It was made using Inno Setup. It puts a shortcut on the Windows operating system. This shortcut opens YouTube in Microsoft Edge so it always works the way and is compatible with the system.

## Technical Specifications

- **Compiler:** Inno Setup 6+

- **Scripting Languages:** Pascal Script and VBScript.

- **Deployment Target:** Windows 10. Windows 11.

- **Protocol:** It uses the 'microsoft-edge:' URI scheme so it opens in the browser.

## Key Features

- **Automated Installation:** It has a setup wizard that puts files and shortcuts where they need to go.

- **Taskbar Compatibility:** The shortcut can be pinned to the Windows Taskbar.

- **System Integration:** It has an uninstaller that can be used from the Windows Control Panel.

- **Minimal Footprint:** It runs using Windows scripts. Does not use a lot of memory.

## Implementation Details

The installer does these things:

1. It makes a folder in the Program Files area.

2. It makes a VBScript file that helps open YouTube in the browser.

3. It puts an icon on the shortcut.

4. It sets up a shortcut that opens the Windows Script Host.

## Security and Transparency

You can see all the code in this repository. The YouTube Opener does not store any information about you it does not look at your browser history. It only talks to the official YouTube website using your browser.

## Instructions for Use

1. Get the `Installer.exe`, from the Releases section.

2. Run the installer. Do what it says.

3. Use the shortcut on your desktop to get to YouTube.

---

The YouTube Opener was made by [GusTAv] as a project to learn about deployment and automation.

This open code source is made for purely fun and ideas.
