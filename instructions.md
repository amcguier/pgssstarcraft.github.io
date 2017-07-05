# Bot Setup Instructions

1. Download the broodwar zip and extract it to your personal drive (mine is W:/)
3. Open powershell
4. Type:
   `Set-ExecutionPolicy -Scope CurrentUser Unrestricted`

    *Note: For the curious, this sets your permissions to run the script in the next steps*
5. Type:
   `cd "W:/Starcraft/cybw/"` 
   
    assuming you extracted starcraft to the top level of your shared drive
6.  Type:
    `.\venv\cybw\Scripts\activate.ps1`
7.  At this point you should see (cybw) at the begining of the command prompt, if not, ask for help
8. Type:
    `python  .\example_ai\example.py`
    

# Starcraft First Time Setup

1. Open the folder where you unzipped Starcraft in file explorer
2. Go to the ChaosLauncher folder
3. Run ChaosLauncher
4. Navigate to the settings tab ![Chaos Launcher](./images/ChaosLauncherPath.png)
5. Change the installpath to wherever you have starcraft
   
    By default this will be *W:/Starcraft/Brood War/*
6. Click `OK`
7. You should be prompted to restart the Chaos Launcher, in either case, restart it.
8. Go to the plugin tab
9. Enable 

    ```
    BWAPI 4.2.0 Injector [Release]
    W-Mode 1.0.2
    ```
   
   The former will setup the game to allow your bot to run, the latter will run the game 
   in a window so you don't have to live with the glories of 800x600 resolution
   ![Chaos Launcher Plugins](./images/ChaosLauncherPlugins.png)
10. Click `Start`

# Running the game
1. Go to the ChaosLauncher folder
2. Run ChaosLauncher
3. Click `Start`
4. The game is scripted to start automatically against a random opponent


# Pybrood documentation

<https://pybrood.readthedocs.io/en/latest/index.html>
