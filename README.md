# Frogger

Cílem projektu je vytvořit 2D hru. Hráč bude ovládat postavu žaby a jeho úkolem bude doskákat s žabákem na druhou stranu a získat co nejvíce bodů. Ve hře je využit: 
plně dotykové ovládání, 
Zvuky, 
Canvas, 
SurfaceView, 
SharedPreferences, 
Vlákna

Za každý skok dopředu získá hráč 2 body, za úspěšné přejítí trati dostane 50 bodů. Při každém přejítí se zvyšuje level-rychlost klád a aut se zvyšuje a postupně ubývají klády(ubyde max 6 klád) a přibývají auta(přibydou max 4 auta).
Pokud bude sražen autem, nebo spadne do vody, bude odečten jeden z pěti životů. Jakmile hráč nebude mít životy, hra končí
