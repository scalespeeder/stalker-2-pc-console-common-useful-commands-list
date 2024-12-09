Stalker 2 PC Console Commands Reference Notes

NOT COMPREHENSIVE! WILL BE UPDATED AS I TEST AND USE NEW COMMANDS!

USE AT YOUR OWN RISK!

CREATE A NEW SAVE BEFORE USING ANY COMMANDS!

YOU MAY BREAK YOUR SAVE GAME BY USING CONSOLE COMMANDS!

USE WITH UETOOLS MOD: https://www.nexusmods.com/stalker2heartofchornobyl/mods/64

---SPAWN ITEMS IN

XCreateItemInInventoryByID

(followed by a space then your item ID) eg:

XCreateItemInInventoryByID Jacket_Bandit_Armor 0 1 1

USE THIS WEBSITE FOR ITEM ID'S: https://www.gamerguides.com/stalker-2-heart-of-chornobyl/database/

---ADD MONEY / COUPONS

XAddMoneyToPlayer Value               (Value is the amount of coupons)

---FREECAM / FLYING

UETools_God true                    (Invincibility on / off)

UETools_God false

XSetNoClipGSC true 2000   (You can change value to speed up and slow down movement)

XSetNoClipGSC false

UETools_Fly						(Clipping freecam)

UETools_Ghost               (No clipping freecam)

UETools_Walk				(Turns freecam off)

UETools_BindToggle F "UETools_Ghost" "UETools_Walk"         (This binds freecam on/off to your F key)


---TELEPORTING

XTeleportTo XCoord YCoord ZCoord


X18 LAB:                      XTeleportTo 0, 0, 0 (Out of bounds developer location?)
Zalissya:                     XTeleportTo 404030.00, 546800.00, 650.00
Slag Heap:                    XTeleportTo 421200.00, 411620.00, 2150.00
Wild Island:                  XTeleportTo 488370.00, 517500.00, 380.00
Cement Factory:               XTeleportTo 492050.00, 372900.00, 2200.00
Rookie Village:               XTeleportTo 447000.00, 653350.00, -2700.00
Icarus:                      XTeleportTo 608150.00, 599650.00, 3180.00
Shevchenko:                  XTeleportTo 644090.00, 646230.00, 700.00
Sultansk:                     XTeleportTo 662880.00, 619000.00, 580.00
Rostok:                       XTeleportTo 317400.00, 415600.00, 350.00
Chemical plant:               XTeleportTo 307090.00, 515580.00, 750.00
Malachite:                    XTeleportTo 107550.00, 473500.00, 700.00
Yaniv Station:                XTeleportTo 214900.00, 270650.00, 950.00
Enerhetyk Palace of Culture:  XTeleportTo 231200.00, 159350.00, 1150.00

Shelter / Lodochka's Lab - 		XTeleportTo 498030.00, 527800.00, 850.00

Poppy Field - 					XTeleportTo 334030.00, 517800.00, 350.00

Cooling Towers - 				XTeleportTo 542200.00, 334520.00, 650.00

Dugan area Journalist Stash - 	XTeleportTo 182000.00, 635350.00, 700.00


---CHANGING WEATHER

UETools_God true

UETools_God false

XForceWeather			(Fast change, use commands below)

XSwitchToWeather		(Slow change, use values below)

XForceWeather Clearly
XForceWeather Cloudy
XForceWeather Fogy             
XForceWeather Stormy
XForceWeather LightRainy
XForceWeather Rainy
XForceWeather Thundery
XForceWeather CalmBeforeEmission
XForceWeather Emission
XForceWeather //Emission

XStopEmission
 
XStartEmission

---CHANGE TIME

XSetWeatherTime Hour Minute Second

---FREECAM FOR SCREENSHOTS

UETools_God true

UETools_God false

UETools_BindToggle F "UETools_Ghost" "UETools_Walk"

XSetNoClipGSC true 2000

XSetNoClipGSC false

UETools_PromoScreenshot 3			(Might be too dark)

XShowAllWidget

XHideAllWidget


Thanks, Rob.

Got some cool console commands for Stalker 2? Send them to scalespeeder@gmail.com 