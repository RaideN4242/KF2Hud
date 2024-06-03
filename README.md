# KF2Hud For Killing Floor 1
KF2Hud for ServerPerks 7.5

RUS:
В ServerPerksMut.uc поменять худ в строке SRHudType=class'KF2HUD'.

Если есть кастомный босс не унаследованный от ZombieBoss, то необходимо его прописать его в KF2HUD.uc по аналогии в функции "function DrawBossBar(Canvas Canvas)" .

Исправил баг, когда в чате дублировался ник игрока. Спасибо Essense.

Добавил рус локализацию.

ENG: 
In ServerPerksMut.uc, change the hud in the line SRHudType=class'KF2HUD'

If there is a custom boss that is not extends from ZombieBoss, then you need to add him in KF2HUD.uc by analogy in the function "function DrawBossBar(Canvas Canvas)"
I fixed chat playernames. old code have a bug - double playername

Original code by https://github.com/XpecV52/XpecKFMuts

Textures and sounds by https://github.com/InsultingPros/KF2HUD
