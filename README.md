# CS16Client_vgui_menu_classic
classic menu for cs16client

Для работы нужны прописанные сквары
_vgui_menus 1
_extended_menu 1

Вызов меню радио... через тач управление командой showvguimenu 38

enum vguimenutype_t
{
MENU_TEAM = 2,
MENU_MAPBRIEFING = 4,
MENU_CLASS_T = 26,
MENU_CLASS_CT, 27
MENU_BUY, 28
MENU_BUY_PISTOL, 29
MENU_BUY_SHOTGUN, 30
MENU_BUY_RIFLE, 31
MENU_BUY_SUBMACHINEGUN, 32
MENU_BUY_MACHINEGUN, 33
MENU_BUY_ITEM, 34
};
showvguimenu
ПО РАДИО 
showvguimenu 38 // radioselector
showvguimenu 35 36 37 - A B C
A — 1. Cover Me
B — 1. Go.
C — 1. Affirmative
