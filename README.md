# Fängelsejobb
Ett script för att kunna jobba när man sitter inne.

### KRAV

 - [pNotify](https://github.com/Nick78111/pNotify)
 
 - [fivem-ipl](https://github.com/ESX-PUBLIC/fivem-ipl)
 
 - [Fängelse map mod](https://www.gta5-mods.com/maps/jail-stuart688)

### Config

 - ```Config.Payment = 10``` hur mycket pengar man får för att packa en låda
 - ```Config.TimeToPackBox = 20``` hur lång tid det tar att packa en låda i sekunder

### Installation

 - Ladda ner alla scripts under krav
 
 - Lägg in alla scripten i din resources mapp
 
 - Gå in i server.cfg och skriv ``` start esx_fangelsejobb ```
 
 - För att änra ställe man tpar till, gå in i esx_fangelsejobb/client/main.lua och ändra rad 120 & 125 
 
 ``` SetEntityCoords(GetPlayerPed(-1), 1798.39, 2482.91, -123.54) ``` X = 1798.39 Y = 2482.91 Z = -123.54 ```
