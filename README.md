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

server_trader.sqf: add all new trader to: serverTraders =[  <br />
"HouseWife5",   // Food and such <br />
"Citizen2_EP1", Building supply <br />
"GUE_Woodlander1", Ammo  <br />
"US_Soldier_TL_EP1",  Weapons <br />
"CZ_Special_Forces_MG_DES_EP1", Cars   <br />
"GUE_Soldier_Sab", Helicopter Unarmed  <br />
"GUE_Soldier_Medic", Medic <Br />
"Soldier_GL_M16A2_PMC", Black Market  <br />
"TK_CIV_Woman01_EP1", Bankier (Gold and Gems)  <br />
