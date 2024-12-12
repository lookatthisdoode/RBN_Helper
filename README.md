# RBN Helper Plugin
Enables live online racing functionality for Richard Burns Rally (RSF version).
Link to the source: https://www.rbrlover.cn/

## How to Install  
1. Move Plugins folder into the root folder of your Richard Burns Rally game.

## How to Uninstall  
1. Delete the `rbnhelper.dll` file located in the game's `Plugins` folder.  
2. Alternatively, disable the plugin directly via the RSF launcher.  

## Features  
- **Fully Automated Workflow:** Players simply select a car, adjust the setup, and start playing.  
- **Randomized Track Selection:** Automatically picks the track and weather conditions, with races starting every three minutes.  
- **Voice Notifications:** Prompts for joining, leaving, getting ready, loading, and starting races.  
- **Countdown Timers:** Notifications for upcoming race preparation and start times.  
- **Scoring System:**  
  - Points are logged after each race.  
  - Last place earns a minimum of 3 points, but dropping out results in a -5 penalty.  
- **Real-Time Ghosting:** Displays a ghost car of the player ahead for real-time competition.  
- **Map Exclusions:** Excludes maps with mazes, poor road conditions, or excessive length for better gameplay.  

## Custom Configuration  
You can customize the plugin via the `RBNHelper.ini` file located in the `Plugins\RBNHelper` folder. After making changes, restart the game.  
Configuration options include:  
- Enabling or disabling features in the `Setting` section.  
- Adjusting the position of the online leaderboard and progress bar with x/y offsets.  
- Customizing the color style of the leaderboard and progress bar.  

## How to Play Against Others  
1. Launch the game and log in to the RSF main menu as usual.  
2. Notifications will appear at the top-center of the screen, showing the number of players online and the time until the next race.  
3. Enter `Hotlap` or `Practice` mode to join the match queue.  
   - If the race has already started, you’ll be added to the next one. Simply stay on this menu page.  
4. When the next match begins, there’s a 30-second setup period before the race starts.  
5. Once all players have loaded, the server will engage the handbrakes and count down from 5 before the race begins.  
6. During the race:  
   - Drive carefully.  
   - Monitor other players' progress on the left side of the screen.  
   - A leaderboard is displayed in the top-left corner.  
7. After the race ends:  
   - If you finish first, remain on the results page to view the final leaderboard and score changes once all players have completed the race.  
8. Return to the `Hotlap` or `Practice` menu and wait for the next race to begin.  


## Author
   Steven Lee
   https://github.com/geekerlw

## Licence 
   MIT