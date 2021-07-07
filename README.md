# MC ARM Downloader

This tool allows you to download several versions of Minecraft: Windows 10 Edition (Bedrock) as an ARM Appx file.
This is useful if you want to install older versions of Minecraft on Windows ARM devices, including ARMv7 devices such as the Surface and Surface 2 with Windows 10 Build 15035.

## Disclaimer
This tool will **not** help you to pirate the game; it requires that you have a Microsoft account which can be used to download Minecraft from the Store.

## Prerequisites
- A PC that runs Windows 10 x86 or x64
- A Microsoft account connected to Microsoft Store which **owns Minecraft for Windows 10** both on the downloading PC and on the target device
- **Administrator permissions** on your user account (or access to an account that has)
- If you want to be able to download beta versions, you'll additionally need to **subscribe to the Minecraft Beta program using Xbox Insider Hub**.
- [Microsoft Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x64.exe) installed.

## Setup
- Download the latest release from the [Releases](https://github.com/etlam5123/mc-w10-arm-downloader/releases) section. Unzip it somewhere.
- Run `MCARMDownloader.exe` to start the downloader.
- Download the version you'd like to play and copy it to your ARM device.
- Double click the Appx-File and follow the installation steps. Alternatively the Powershell command `Add-AppxPackage filename.appx` can be used

## Compiling the launcher yourself
You'll need Visual Studio with Windows 10 SDK version 10.0.17763 and .NET Framework 4.7.2 SDK installed. You can find these in the Visual Studio Installer if you don't have them out of the box.
The project should build out of the box with VS as long as you haven't done anything bizarre.

## Frequently Asked Questions
**What is the newest version of Minecraft that runs on ARMv7 devices with Windows 10 Build 15035?**

Answer coming soon!
