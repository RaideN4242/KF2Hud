# KF2Hud For Killing Floor 1
KF2Hud for ServerPerks 7.5

For Server [Dead Zone]: 109.195.103.47:9507

RUS:
В ServerPerksMut.uc поменять худ в строке SRHudType=class'KF2HUD'

Изменить название пакета ServerPerksDZ на свой!!!

Если есть кастомный босс, не унаследованный от ZombieBoss, то необходимо прописать его в KF2HUD.uc по аналогии в функции "function DrawBossBar(Canvas Canvas)" .

Исправил баг, когда в чате дублировался ник игрока. И баг с некорректным отображением полоски с бронёй Спасибо Essence.

Добавил рус локализацию. Спасибо HekuT.

Худ был адаптирован для совместимости с мутатором AreYouVip: https://github.com/Bleeding-Action-Man/AreYouVIP

Если нет ника в чате, то возьми код из message.txt и замени эту функцию в KF2HUD.uc

ENG: 
In ServerPerksMut.uc, change the hud in the line SRHudType=class'KF2HUD'

Replace package name ServerPerksDZ!!!

If there is a custom boss that is not extends from ZombieBoss, then you need to add him in KF2HUD.uc by analogy in the function "function DrawBossBar(Canvas Canvas)"
I fixed chat playernames. old code have a bug - double playername

Original code by https://github.com/XpecV52/XpecKFMuts Special thanks, bro!

Textures and sounds by https://github.com/InsultingPros/KF2HUD
