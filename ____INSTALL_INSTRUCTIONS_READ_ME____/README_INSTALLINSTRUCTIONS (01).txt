Fortbonnitar's Admin Menu (WIP):

Currently, the menu will spawn offline and spawn items to player, but haven't fixed the replication probelm that is causing it not to spawn onlne. Will update as soon as its fixed.


Installation Instructions:

--Open this project 

--Find the "CustomMaps/AdminMenu/" folder

--Right click on the folder

-Click migrate

--Navigate to your project's content folder and click select

--Once its migrated to your project, check that none of the migrated assets have any errors by opening them and compiling

--If anything has errors, delete the migrated assets and start over

--If no errors then move the AdminMenu folder into your SVR_ folder

-After the folder is moved, right click your main content folder and select "Fix up redirectors in folder"

--if your project already has a gamelogic, player proxy, global info, or player info, you'll need to parent each to the Admin_ that corrisponds       E.x.  MyPlayerProxy needs to be reparented to Admin_PlayerProxy (This should not break anything but to be sure, it is HIGHLY advised to make a duplicate of your assets before attempting to reparent just in case something breaks) 





Adding Custom Items/Skins/Vehicles:

--To add any extras to the selection lists, find the datatable of the type asset you want to add in the SpawnList folder
  
--Add your items to the row name in the datatable  in this folder.  Also if adding an item make sure to add the custom item to the custom items table provided by pavlov

-Same with process above for skins except you need to use the custom skins table and the skin selection datatable






***If you have any trouble with installation, have any suggestions, or would like to help in the development of this menu please DM on discord  

  FORTBONNITAR#6584

(discord name is all caps)

