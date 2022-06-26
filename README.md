# Core.IO
Harmony Core.IO to replace RustEdits IO.Core Oxide Extention.
<br><br>
Chat Commands:<br>
/showiowires   -   Will show the IO wires to admins.<br>
/reloaddoors   -   Will respawn and repaire to door manipulators any doors that are missing compared to the map file.<Br>
<br>
Permissions:<br>
If your admin with god and no clip enabled.<br>It will let you bypass the block outs on IO entitys.<br>
Such as change the wiring, pick up entitys, auth/loot turrets.
<br>
<br>
Turrets:<br>
On Turret spawn it will give them 1 clip of ammo.<Br>
Once they run out of ammo it will give another clip of ammo after 60 seconds.<br>
If unlimited ammo mode is enabled then it replaces the bullet as its shot so it never runs out.<br>
Turrets wont attack if player is admin, has godmode and noclip enabled.<br>
<br>
Elevators:<br>
Elevators placed in the map are recreated on each startup. Then destroyed on shut down.<br>
Using a clean shutdown method such as "quit" or "restart". will allow this process to happen properly.<br>
If your server has a crash and misses the destroy phase. Then it will detect there already a elevator in that spot.<br>
It will destroy it and restart the server so it can restart correctly with out having a elevator blocked up with lifts.<br><br>
  # Installing
Copy Core.IO.dll to your "HarmonyMods" folder in the root of your rust servers install directory.
