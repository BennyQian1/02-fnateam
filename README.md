# FIVE NIGHTS AT TEMPLE
This is a FNAF fan game.

You work as a security guard at Temple University, working the night shifts. On the campus, there exist 5 animatronic where each of them resembles mascot for each of the sports teams of Philadelphia. These "mascots" was a final project created by students from the art and engineering students. On first night of your shifts, the mascots malfunctioned due to unknown circumstance that causes them to become more violent and willing to kil anyone on site.

Objective:
1. Starting at your office, your task for beating the game is to survive 5 nights to get your paycheck.
2. There are 5 mascots and each starts in a specific rooms :
   - Hooter, Gritty and Philly Phanatic starting at the lounge
   - Phang starts in the utility room
   - Franklin starts in the BallCart
   
3. Each mascot will randomly move to adjacent rooms where eventually they will reach the office where you reside.
   - Your visibility to the room may be disrupted.
   
5. There is also a TU Alert, that will be sent to the player randomly, and depending on the type of message, certain mascot will be more aggressive and move more often.

6. To defend yourself, there are 2 methods:
   - In the office, there are 2 doors and 1 vent where you can use the flashlight to scare off the mascots at the door/vent
   - Each rooms you see on the camera have a seal door feature that prevents the mascot from entering or leaving the room.
   - All animatronic can be flashed but Hooter can only be stalled, as the flash from the light will cause it to attack.

7. Finally, there is a power system where the actions you do such as opening the camera, sealing the rooms, or flashing the doors/vent will take a certain percentage of the power.
   - When the power reaches 0, it will automatically go into a recharge state, where you are essentially a sitting duck.
  
Additional Features:

1. As the night progress, strange sound will be played.

2. On the home page, there is a custom setting that allows the player to create a custom night where the ai levels are set by the player.





#Project Board
https://trello.com/b/03hQVfXd/fnat-final-project

## 🕹️ How to Run

### Play the Built Game
1. Go to the [**Releases**](https://github.com/cis3296f25/02-fnateam/releases/) page.
2. Find the latest release (e.g. **“FNAT DEMO - 3”**).
3. Under the **Assets** section, download the ZIP file for your operating system:
   - 💻 **Windows:** `fnat-project.zip`  
   - 🍎 **macOS:** `fnat-project.dmg`
4. Once downloaded, **extract the entire ZIP file** to a folder.
5. Open the extracted folder and run the game executable.

> ⚠️ **Tip:** Do not move or rename files after extracting. The game may fail to load assets if the folder structure changes.

### On mac you need to follow these steps or the game will not open!

1. On your Mac, choose Apple menu  > System Settings, then click Privacy & Security  in the sidebar. (You may need to scroll down.)

2. Open Privacy & Security settings for me

3. Go to Security, then click Open.

4. Click Open Anyway.

5. This button is available for about an hour after you try to open the app.

6. Enter your login password, then click OK.

## For Developers

### Prerequisites
1. Download [**Godot Engine**](https://godotengine.org/download/).

2. Extract and run installer.

3. Run Godot Engine

### To Edit the Project
1. Download the source code ZIP. (**Do not extract it.**)

2. In Godot Engine Project Manager, Click the Import button.

3. Navigate to the directory where the ZIP was downloaded and click 'Select Folder'.

4. Import the project and update the project the latest version of Godot Engine if needed.

5. Run the project.