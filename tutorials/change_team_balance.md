# Example - How to change ferrari team balance

First of all make backup of your game save.
There is a chance that using this may break your save.

The exported database can be edited in "DB Browser for SQLite", that you can download from [here](https://sqlitebrowser.org/dl/) (I've the ".zip (no installer) for 64-bit Windows")

Video you can follow if the text instruction isn't clear enough:

[VIDEO](https://streamable.com/pubd8l)

1. Open the cheat table
2. Attach to the game process (there may be two, so make sure you attach to the one in Binaries\Win64)
3. Activate script "Activate Me Before Load Your Game Save" (may take a few seconds, don't panic)
4. Load your game save
5. Activate "ExportDB", this will create "f1.db" file in <YOUR_GAME_INSTALL_DIR>\F1Manager2022\F1Manager22\Binaries\Win64
6. In SQLite Database Browser open the database that you just exported (f1.db)
7. In Browse Data Tab find "Finance_TeamBalance" table
8. You can figure out which team is yours by the current balance (should be the same as you see in game). Change the balance value for any value you want
9. Save Changes in SQLite Database Browser
10. CLOSE THE DATABASE in SQLite Database Browser! That's very important (additional after that you can close SQLite Database Browser just in case to be safer)
11. Go back to the cheat table and Activate "ImportDB_OnSave" script.
12. Go back to the game and save your game
13. Go back to the cheat table and Deactivate "ImportDB_OnSave" script.
14. Go Back to the game and Quit to main menu
15. Finally, load your saved game and enjoy your new budget