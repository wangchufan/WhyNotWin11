[![Build Status](https://img.shields.io/github/workflow/status/rcmaehl/WhyNotWin11/wnw11)](https://github.com/rcmaehl/WhyNotWin11/actions?query=workflow%3AWNW11)
[![Download](https://img.shields.io/github/v/release/rcmaehl/WhyNotWin11)](https://github.com/rcmaehl/WhyNotWin11/releases/latest/)
[![Download count)](https://img.shields.io/github/downloads/rcmaehl/whynotwin11/total?label=Downloads)](https://github.com/rcmaehl/WhyNotWin11/releases/latest/)
[![Ko-fi](https://img.shields.io/badge/Support%20me%20on-Ko--fi-FF5E5B.svg?logo=ko-fi)](https://ko-fi.com/rcmaehl)
[![PayPal](https://img.shields.io/badge/Donate%20on-PayPal-00457C.svg?logo=paypal)](https://paypal.me/rhsky)
[![Join the Discord chat](https://img.shields.io/badge/Discord-chat-7289da.svg?&logo=discord)](https://discord.gg/uBnBcBx)

# WhyNotWin11
Detection Script to help identify why your PC isn't Windows 11 ready

![image](https://user-images.githubusercontent.com/716581/123536739-25d7cd80-d6fa-11eb-8b9e-3e23b2546ae9.png)

----

## Download

[Download here](https://github.com/rcmaehl/WhyNotWin11/releases/latest/download/WhyNotWin11.exe)

[Download DEV BUILDS here](https://github.com/rcmaehl/WhyNotWin11/actions?query=workflow%3AWNW11)\
/!\ Dev builds will not be able to automatically check for updates

## To-Do

- [x] Hard Floor Checks:
    - [x] Cores >= 2
    - [x] CPU Freq >= 1 GHZ
    - [X] CPU Arch = 64
    - [x] RAM >= 4 GB
    - [x] Storage >= 64 GB
    - [x] ~~TPM >= 1.2~~ (Removed with recent changes from Microsoft)
    - [x] SecureBoot
    - [x] ~~SMode~~ (WhyNotWin11 is not compatible with S Mode Devices)
- [x] Soft Floor Checks:
    - [x] TPM >= 2.0
    - [x] CPU Compatibility list
- [ ] Other Checks:
    - [x] DirectX 12
    - [x] WDDM 2
    - [ ] Screen Resolution
- [x] A fancier GUI

## How to build from source code

1. Download and run "AutoIt Full Installation" from [official website](https://www.autoitscript.com/site/autoit/downloads). 
1. Get the source code either by [downloading zip](https://github.com/rcmaehl/WhyNotWin11/archive/master.zip) or do `git clone https://github.com/rcmaehl/WhyNotWin11`.
1. Right click on `WhyNotWin11.au3` in the WhyNotWin11 directory and select "Compile Script (x64) (or x86 if you have 32 bit Windows install).
1. This will create WhyNotWin11.exe in the same directory.

This program is free and open source. Feel free to download and modify. Please do not sell exact copies.
