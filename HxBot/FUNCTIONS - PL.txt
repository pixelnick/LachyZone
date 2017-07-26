HxBot 1.0+ opis funkcji:

#LECZENIE:

1. Hi, Mi, Lo: kolejno leczenie lekkie, średnie, ciężkie. Wstawiamy po kolei procent życia, wartość punktową many oraz czar, ID przedmiotu lub skrót: 
HP - health potion
SHP - strong health potion
GHP - great health potion
UHP - ultimate health potion
SUHP - supreme health potion
MP - mana potion
SMP - strong mana potion
GMP - great mana potion
UMP - ultimate mana potion
GSP - great spirit potion
USP - ultimate spirit potion
UH - hltimate healing rune
IH - intense healing rune
SIO - exura sio "moj nick

2. Pot HP & Pot MP: picie vialek. Wstawiamy procent many/życia. Typ: ID przedmiotu lub skrót jak wyżej.

#LECZENIE PRZYJACIÓŁ

1. Sio: aktywuje leczenie przyjaciół przy pomocy czaru exura sio "nick gracza    
2. Item: Leczenie przy użyciu przedmiotu np UH lub UHP (ultimate health potion). Wstawiamy ID przedmiotu lub skrót.
3. MyHP: Procent mojego życia poniżej której nie będziemy leczyć innych.
4. FriendHP: Procent życia przyjaciół poniżej którego będziemy ich leczyć.
5. Team: Leczenie członków party, gildi oraz zielone blachy na wojnie.
6. List: Leczenie graczy z listy Friends.txt (jeden nick na linijke)
7. Colors: Ustawienie alternatywne kolorów przyjaznych graczy na niebiesko.

#KONDYCJE

1. Haste: Trzymanie pozycji przyśpiesznia. Wstawiamy Czar i minimalna wartość many do jego użycia.
2. Para: Lecznie z paraliżu. Użycie jak wyżej.
3. ManaShield: Utrzymywanie tarczy many.
4. UtanaVid: Utrzymywanie niewidzialności.
5. Fire: Leczenie z ognia "exana flam"
6. Utura: Trzymanie buffa leczącego życie. Użycie jak w przypadku haste.
7. Pox: Leczenie z trucizny "exana pox"
8. Blood: Leczenie z krwawienia "exana kor"
9. Energy: Lecznie z porażenia "exana vis"
10. Death: Leczenie z opętania: "exana mort"
11. Dont cast in protection zone: Nie będzie używał wkększości funkcji w bezpiecznym miejscu (depot, temple).

#MANA TRAIN

1. Train: Aktywuje spalanie many. Wstawiamy czar oraz procent many poniżej którego ma używać czar.
2. Anti-Idle: Zapobiega wylogowaniu się postaci z gry zmieniając look-direction losowo.
3. EatFood: Jedzenie pożywienia w losowych odstępach czasowych.
4. LookIDs: Kiedy spojrzymy na jakiś przedmiot (Lewy+Prawy przycisk myszy) w Panelu bota\Inforamtion Box pojawi się ID przedmiotu.

#TIMERS	

Wszystkie czasu muszą być podane w milisekudnach: 1s = 1000ms
1. Spell: Ustala czas między powtarzalności używania czarów. Alternatywnie 100ms
2. Boost: Ustala czas między powtarzalności używania klawiszy oraz Dasha. Alternatywnie 40ms
3. Equip: Ustala czas między powtarzalności zakładania/zdejmowania przedmiotów oraz wyrzucania ich z plecaka. Alternatywnie 150ms
4. Pot: Ustala czas między powtarzalności używania run oraz potionów. Alternatywnie 500ms
5. Fire: Ustala czas między powtarzalności używania czarów oraz run atakujących. Alternatywnie 250ms
6. Hots: Ustala czas między powtarzalności używania wszystkich Shortkeys. Alternatywnie 100ms

#TOOLS

1. NumKeys: Po włączeniu klawisza NumLock na klawiaturze numerycznej możemy poruszać sie przy użyciu Numpadów.
2. HoldTarget: Utrzymywanie ostatnio atakowego ID. W celu zatrzymania atakowania wystarczy wcisnąć klawisz Esc.
3. NoMana: Używania przedmiotu kiedy wartość życia jest poniżej wartości Hi,Mi lub Lo i brak many by użyć czar. Wstawiamy przedmiot ID lub skrót.
4. ReUse: Ciągłe używanie przedmiotu z krzyżyka.
5. Xray: Podgląd pięter poniżej/powyżej. Klawisze:
	a. Num +	do góry
	b. Num -	w dół
	c. Num *	powrót do normalnego widoku
6. Lighthack: Zwiększenie intensywności kolorów w grze oraz ograniczanie ciemnych pól.
7. HoldPosition: Utrzymywanie ostatniej pozycji.
8. Advert: Ogłaszanie swoich ofert handlowych na kanale Advertising/Trade. Wybieramy kanal na którym będziemy nadawać, klikamy guzik [message] i wpisujemy treść wiadomości. Czasami niektóre serwery wymagają aby wiadomość zaczynała się od "Sell" lub "Buy"

#MISC

1. MountsOFF: Wyłącza potworki innych graczy.
2. OutfitColorVariation: Zmienia kolory naszego addonu na losowe co 2s
3. FakeAddon: Ustawia widziałny tylko dla ciebie addon. Wstawiamy ID od 2-160, Nr addonu 0-3
4. StandHasteOFF: Nie używa haste z kondycji kiedy nasza postać sie nie porusza.
5. McHotkeys: Aktywuje klawisza od F1 do CTRL+F12 dla wszystkich procesów Tibia.exe. Gdy chcemy aktywować również Shorkeye, wymagane jest uruchomienie bota dla każdego klienta gry i zaznaczene tej opcji.
6. ShopBuy: Kupowanie przedmiotu u NPC. ID przedmiotu do kupienia oraz jego ilość. Funkcja nie została wyposarzona w element sprawdzania czy dany przedmiot został kupiony.

#SETTINGS

1. Save: Zapisuje nasze ustawienia w panelu głównym.
2. Load: Wczytuje ustawienia.

#ALARMS

1. PlayerAttack: Wywołuje jednorazowy alarm w przypadku ataku gracza.
2. Dead: Alarm w przypadku śmierci postaci.
3. LowMana: Alarm kiedy nasza wartośc many będzie poniżej 10%
4. LowHP: Alarm kiedy wartośc naszego życia jest poniżej 50%

#PVP SECTION

1. ReAmulet: Zakłada ostatnio używany amulet gdy slot jest pusty.
2. Mring: Automatyczne zakladanie Might Ringa gdy slot jest pusty.
3. Ering: Automatycznie zakłada Energy Ringa gdy procent życia postaci spadnie poniżej podanej wartości. OFF: wrzuca pierścionek z powrotem do plecaka gdy % życia powyżej wartości.
4. Paralysed: Wykonuję akcje w momencie gdy nasza postać została spowolniona. 
	a. Tring 		Zakłada Time Ring;
	b. SAA 		Zakłada Stone Skin Amulet;
	c. SleepCure 	Czeka określoną wartość czasu w milisekundach zanim wyleczy paraliż np. za pomocą "utani gran hur". Przydatne zwłaszcza na Hexera.net gdzie wprowadzona jest 1s blokada na wyleczenie parala.
5. AutoSSA: Zakłada automatycznie Stone Skin Amulet gdy nasz procent życia bądź many będzie poniżej ustalonej wartości.
	a. hp 		sprawdzane będzie poziom życia;
	b. mp 		sprawdzana będzie poziom many;
6. ExivaAim: Automatyczne używanie czaru exiva "nick ostatnio atakowanego gracza" co określoną ilość sekund.
7. SpellMax: Spamownie wcześniej ustalonego czaru z częstotliwością FireTimer.
8. IDMax: Spamowanie ID przedmiotu w atakowany cel.
9. SdMax: Automatyczne atakowanie celu z runy Sudden Death (częstotliwość: FireTimer)
10. ParaMax: Spam runy paraliżu w target.
11. ComboSd: Automatyczne użycie Runy Sudden Death w ostatnio atakowany cel gdy procent jego życia będzie mniejsza bądź równa ustalonej wartości.
12. ComboSpell: Tak samo jak w przypadku ComboSd tylko ustalamy atakujący czar.
13. NumPush: Po naciśnięciu klawisza NumLock klawiatura przekształca się w konsole do pushowania graczy a klawisze od 1-9 stają się kierunkami pusha. Ustawiamy również ID runy jaka będzie używana przed wykonaniem pusha np. Fire Field. oraz sposób jej użycia:
	a. t 		prosto na target np. desintegrate
	b. s 		pod siebie np. fire bomb
14. ForceLog: Wylogowanie się z gry najszybciej jak to możliwe.

#SHORTKEYS

Jednorazowe akcje wykonywane w chwili naciśnięcia ustalonego klawisza wykonywane z częstotliwością Hots Timer(alternatywnie 100ms)

say exura 		- Wypowiada tekst na zwykłym kanale.
exivat			- Exivuje ostatnio atakowanego gracza.
wear 3081		- Zakłąda/ściąga przedmiot ID.
tuse 3155		- Używa przedmiotu ID na atakowany cel.
meuse 238		- Używa przedmiotu ID na twoją postać. 
use 3725		- Używa przedmiotu. Np jedzenie, otwieranie plecaków.
turn 0			- Obraca twoją postać w wybraną strone: [0=N, 1=E, 2=S, 3=W, 4=NE, 5=SE, 6=SW, 7=NW].
step 0			- Poruszą postać w wybraną stronę [zobacz wyżej].
pot Ben, 238		- Używa przedmiotu ID na graczu o nicku Ben
pusht 0, 3197		- Używa runy ID na ostatnio atakowanym graczu i pusha go pod określony kierunek [zobacz w turn]
pushm 0, 3192		- Jak wyżej tylko tym razem używa runy pod sobą np. fire bomb.
ssa			- Zakłada pojedyńczy Stone Skin Amulet.
mring			- Zakłada pojedyńczy Might Ring.
ering			- Zakłada pojedyńczy Energy Ring.
tring			- Zakłada pojedyńczy Time Ring.
sdlast			- Używa Runy Sudden Death na ostatni cel.
paralast		- Paraliżuje ostatnio atakowanego gracza.
mwtarget		- Trzyma magic walla w pozycje celu, gdy poruszy się on rzuca w to miejscie mw.
fbomb			- Używa runy Fire Bomb po twoją postacią.
simulate 112		- Symuluje wciśniecie klawisza w kliencie gry jak XMouseButton. Klawisz podajemy w decymalnych wartościach np 112 to F1. Lista klawisze dostępna tutaj:  http://cherrytree.at/misc/vk.htm
antipush 3031, 3492	- Trashowanie siebie, wyrzuca dwa itemki.
mousedrop 3031, 3492 - Jak antipush tylko przedmiot rzucony będzie na kratkę pod kursorem naszej myszy.
mousepush 3197, t	- Tak jak pusht czy pushm tylko pozycję docelową wyznacza kursor myszy.
fastssa			- W chwili przytrzymania klawisza z tą funkcją bot założy wszystkie Stone Skin Amulety z otwartego plecaka.
utoris			- Podpalanie celu z czarów: "utori mort", "utori vis", "utori flam".

#ALL IN SECTION

1. SD Enemies: Atakownia przeciwników z runy Sudden Death uwzględniając ich stan życia.
	a. War: atakujemy czerwone blachy;
	b. List: atakujemy osoby z Enemies.txt
2. AutoMring: Wstawiamy wartość życia poniżej którego będzie automatycznie ładowany Might Ring.
3. Change:
	a. Gold: Zamiana 100 sztuk złota w platynkę.
	b. Platinum: Zamiana 100 sztuk platynek w krystalkę (crystal coin)
4. RefillAmmo: Odnawianie amunicji, wstawiam ID np 3447 - arrow.
	a. toArrow: wrzucanie strzał czy boltów to slotu z amunicją.
	b. toHand: wrzucanie gwiazdek, włoczni czy noży do slotu z bronią (lewa ręka)
5. AutoAttackMonsters: Automatyczne atakownie potworów.

