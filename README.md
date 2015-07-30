# Cherno-Bridge-Trader
A trader city in outskirt of Chernogorsk. <Br /> 
First just the files, I will add in install instruction soon. <Br />
All files and trader location in files, just add in mission.sqf and server_trader.sqf. <Br />
Change TID on traders, we probably dont have same. <Br />

cherno.sqf goes in dayz_server.pbo (un-PBO and place it in for excample: custom_building)<br />

Open dayz_server\system\server_monitor.sqf <br />
place end of file under: 	publicVariable "sm_done"; <br />
}; <br />
//Cherno Trader City <br />
execVM  "\z\addons\dayz_server\CustomBuildings\cherno_trader.sqf";   <br />
Repack PBO <br />
Done. <br />
