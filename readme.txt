
Žaidas-Y, a Doom II - like shooter for MS-DOS by Aras Pranckevičius.
Made in 1998-1999. See https://aras-p.info/projZaidasY.html

I have lost the source code during all the computer moves. 

It works on DosBox these days.

Default controls are:
- W, A, S, D: forward, backward, strafe left/right
- Mouse Left: fire
- Mouse Right: forward
- Alt: jump
- Space: use (door etc.)
- Tab: show stats
- ~: open console
- F10: quit

Weapons:
- 1: club
- 3: shotgun
- 4: minigun
- 5: grenade launcher
  - T: grenade that explodes into 4 more grenades
- 6: rocket launcher
  - Y: launches two rockets, each with slightly random movement
  - H: launches three rockets
- U: flame thrower
- 7: plasma
- 8: "bfg11000" that looks like a vacuum cleaner

Console cheat commands "give_weapons" and "give_ammo" might be useful.

Available maps are (open console via ~, type "map <mapname>" e.g. "map genie"):
- zaidas_y: default level. No idea what that is based on, or what is it similar
  to.
- genie: very similar to Doom II "genocide.wad"
- hifrag: very similar to Doom II "hipafrag.wad"
- lievas: square-shaped map with "wind" feature (pushes players constantly,
  affects rockets, grenades etc.)
- zyquad: no idea what that is based on. Maybe there was some Quake level
  that was similar?
- ice: kinda useless, was for testing "ice" floor material which has very
  low friction.


Below is original readme in Lithuanian, as it was written in 1999 or so.

-----------------------------------------------------------------------------

 taigi apie  R E A D M E , o ne ne apie readme.
             ===========

garbusis turinys:

i.    prakalba i malonuji skaitytoja
ii.   apie autoriu
iii.  kas yra zhaidas-y, pagr. featurai (t.y. bugai)
iv.   reikalavimai kompui
v.    kaip zhaisti
vi.   kas turi buti
vii.  padeeka
viii. citata

I. PRAKALBA

  taigi imkite mane ir zhaiskite...

II. AUTORIUS

  zhaido-y kodo ir grafikos autorius yra Aras Pranckevichius, tikrasis
    vardas yra arukas.arukas@usa.net .
  naudingus ir nenaudingus patarimus dave: Viktoras Jucikas, Paulius Liekis,
    Laurynas Stanchikas ir dar daug kitu zhmoniu.
  grafikos eskizus paishe: tie patys.
  garsui ir muzikai panaudojau Watcom'ui nuportinta Allegro bibliotekos,
    kurios autorius yra Shawn Hargreaves, dalii.

III. KAS TAI YRA ?

  dar viena shaudykle. skirta daugiausiai zhaidimui tinkle.
  featurai:
    * zhaidimas IPX protokolu iki 8 zhaideju.
    * galima zhaisti su botais (iki 7 botu). botuu AI naudoja pachia
      geriausia ir greichiausia algoritma - random.
    * grafika: 320x200 256 spalvos.
    * komandine konsole zhaidimo parametrams keisti ir dar daug kam.
    * valdymas klaviatura arba pele. galinga ir bugova ivykiu sistema
      (bindai kaip kveike).
    * lygtai 11 skirtingo veikimo ginklu (kai kurie atrodo taip pat :))
    * efektai: shviesos mirgejimai, vejas, vandens tekme, shiaip vanduo.
    * visokie dalykai: sharvai, vaistineles, t.t.
    * pusiau trimatis pasaulis (iki kveiko nedatraukia, uzh dooma shiek
      tiek advancedesnis).
    * galimybe atjungti sienu arba grindu teksturavima - letiems kompams
      arba jeigu taip patogiau.
    * daugiakanalis (iki 16 kanalu) garsas. palaiko SB 1.0, SB 1.5, SB 2.0,
      SB Pro ir SB 16
    * programa nesukelia scintiliaciju, nenukrypsta nei magnetiniam, nei
      elektriniam lauke; nevartoti alergishkiems shokoladui; neblukina
      bromo vandens; 100g yra 6,66g riebalu, 13g baltymu, 5g angliavandeniu
      ir tik 2 kalorijos!

IV. KOKS KOMPAS ?

  ram: apie 2 MB
  hdd: kolkas apie 1.5 MB
  os:  dos, win3.x, win9x, gal veikia po dosemu. winnt neleidzhia pergauti
       taimerio, taigi viskas vyksta apie 2 sykius lechiau. po dr-dos
       paleisti man nepavyko.
  video: bet koks vga.
  kontrolai: ms pele, klaviatura.
  garsas: jei nieko nera, tai ir nereikia. jei yra bele koks SB (1.0, 1.5,
       2.0, Pro, 16, 666, SB-neSB, bobute ir kt.), tai groja.
  procas:
       su visomis teksturomis:
         ant p100 jau beveik bet kokiom salygom padaro maksimuma kadru per
         sekunde (35). ant 486-66 vidutinishkai padaro apie 25 fps, taigi
         zhaisti irgi galima.
       be teksturu:
         ant 468-66 irgi veik visada padaro 35 fps, tik jei l.sudetingas
         lygis arba l.daug daiktu tai nukrinta iki apie 28 fps.
       minimum:
         386.
  dar butinai reikia:
       33.6kbps modemo, billo g. pro langus zhiurinchio, cd-rw,
       power mygtuko, groodo, zovieso ir garastavoklio.

V. TAI KAIP DABAR ZHAISTI ?

  jei nori zhaisti tinkle, tai visi turi leisti ipxrun.exe su parametru
  -nodes ???, kur ???-zhaideju skaichius (pvz. ipxrun.exe -nodes 3).
  jei nori zhaisti vienas arba su botais, tai leisti main.exe .
  leidzhiant jis visa setupa nuskaito ish default.cfg ir autoexec.cfg .
  plachiau apie juos zr. 'konsole.txt' . va. tai jau galima ir zhaisti.
  isheiti ish zhaidimo - F10 arba konsoles komanda 'quit'. kitkas gal
  aishku... apie lygiu keitimus irgi zhiureti 'konsole.txt', apie visa
  kita - ten pat.

VI. KAS TURI BUTI ZHAIDO-Y PAKETE ?

  turi buti shie failai:

    main.exe     - pagrindinis egzekas
    ipxrun.exe   - paleidimo programa ipx tinklui
    aras         - shitas nebutinai turi buti. chia mano zhaido-y konfigas.
    autoexec.cfg - klavishu ir dar ko nori konfiguracijos byla
    default.cfg  - konoles kintamuju ishsaugojimo byla
    bugai.txt    - zhinomu bugu sarashas
    konsole.txt  - apie konsole ir shiaip viska
    readme.txt   - shitas failas
    relyzai.txt  - kurimo dienorashtis - nuo shiu dienu istorija iki
                   amzhiu amzhinuju.
    zaidas-y.zdf - ish visu zdf'u shitas butinai turi buti. jame yra visa
                   grafika, shiaip data bei kveiko dm6 lygio portas.
    ir dar keli *.zdf failai su lygiais

VII. PADEKOS

  dekoju tiems, kurie to nusipelne. nedekoju tiems, kurie to nenusipelne.

VIII. CITATA, ISH TIKRUJU ATPASAKOJIMAS

  - what are you doing?
  - installing windows (sux)
  - and why are you smashing your computer?
  - it keeps asking me where do i want to go today. i don't want to go
    anywhere!
