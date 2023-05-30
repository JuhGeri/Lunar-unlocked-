![Github all releases](https://img.shields.io/github/downloads/Nilsen84/lunar-client-qt/total)
![GPLv3](https://img.shields.io/github/license/Nilsen84/lunar-client-qt)
![Stars](https://img.shields.io/github/stars/Nilsen84/lunar-client-qt)
![Forks](https://img.shields.io/github/forks/Nilsen84/lunar-client-qt)
![CI](https://img.shields.io/github/workflow/status/Nilsen84/lunar-client-qt/Build%20and%20Release)

# Lunar Client Unlocked
Lunar Client Unlocked is a lightweight, cross-platform and open sourced launcher for Lunar Client written in C++ using the Qt framework.  
  
![Lunar Client Qt](https://i.imgur.com/owcLWNV.png)

## Extra Information [Addons]
One of the primary features of this launcher is the ability to easily attach Java premain agents to your game, 
this allows you to modify the game on launch, which lets you write modifications that won't break when Lunar Client recieves an update. 
   
  
If you're familiar with Java bytecode, feel free to write your own!

## Usuage Information
Make sure you have python installed. 
```
Download latest release from "Realeases Tab"

Run "lunarclientunlocked-qt.exe" as adminstrator.
```

**NOTE**  
If you're on MacOS, you wanna start off by installing Qt using [Brew](https://brew.sh/): ```brew install qt@5```  
You also want to replace the `cmake ..` command with ``cmake -DCMAKE_PREFIX_PATH=`brew --prefix qt5` ..``  
Besides that, follow the same instructions above.
