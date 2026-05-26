# BrickHouse- windows simulation sandbox engine
🛠️ Iron Sheet Silicon (BrickHouse Core)
v1.6.0-STABLE_SOUL — Standalone Sandbox Shell
A fast, lightweight terminal wrapper designed to run custom scripts and commands cleanly without slowing down your computer. It checks your system hardware, protects your workspace, and runs with zero background lag.

# ✨ Key Features
Zero Lag: Designed to use almost 0% of your computer's CPU power when sitting open.

Smart Performance Modes: It checks if Virtualization is turned on in your computer settings. If it is active, it runs scripts in an isolated window (VIRTUAL_ISOLATED). If it is off, it safely uses basic processing threads (STANDARD_THREADED).

Morale Anchor System: Requires a blank, empty file named bbo.ps1 to be in the same folder before it boots up to ensure the system is ready.

# 📁 Folder Layout
This app is 100% portable and runs entirely on its own. There is no need to install Python or look at raw scripts. Just make sure these files sit together in the same folder:

📁 Your_Project_Folder/

-IronSheetCore.exe # The standalone application (Double-click to run)

 -bbo.ps1 # Empty file (Must be here to boot!)
 
 -your_script.py   # Put any scripts you want to run right here

# 🕹️ Shell Commands
Once you open IronSheetCore.exe and see the IRON_SHEET_SH > prompt, you can use these commands:

run [script.py] – Launches a custom Python script safely. (Example: run game.py)

sys [command] – Runs any normal Windows command directly through the app. (Example: sys dir or sys ipconfig)

cls – Clears all old text off the terminal screen.

exit – Closes the application completely.

#  🚨 Quick Fixes
🛑 Error: "Cores are Crying / Abort Halt"
The Problem: The app cannot find the bbo.ps1 file.

The Fix: Right-click inside your folder, select New > Text Document. Rename the file exactly to bbo.ps1 (make sure to erase the .txt at the end so it isn't named bbo.ps1.txt). Leave the file completely empty, save it, and open the app again.

⚠️ Virtualization Status Shows [FAILED]
The Problem: Virtualization is turned off in your computer's motherboard settings (BIOS).

The Fix: Restart your computer. Immediately keep tapping F2 or Delete to enter your BIOS setup. Find the setting named Intel Virtualization Technology (or VT-x), change it to Enabled, press F10 to save and exit, and let your PC boot up normally.
