# 1. Introduktion och 3D ritning med OpenSCAD

I den här kapittel lära vis oss basen av
OpenSCAD. Vi följel kapittel 1 av boken
'Programming with OpenSCAD' av Justin Gohde
och Marius Kintel.

![Programming with OpenSCAD](programming_with_openscad_cover.png)

## 1.1. Att läsa Engelska

Boken är på Engelska.
Om du behöver översätta ord till svenska,
är Google Translate en bra webbsida:

I en webläsare (t.ex. Firefox, Chrome, Chromium, Edge, Opera)
surf till `https://translate.google.com` (det räcker
med att skriva `translate.google.com`).

Väljer den rätta språkor och dina meningar blir översätta:

![Dina meningar blir översätta](google_translate.png)

## 1.2. Att öppna OpenSCAD

Om du använder våra kursdatorer,
kann du hitta OpenSCAD ikonen
på vänstrasida av skrivbordet:

![OpenSCAD ikonen på skrivbordet](openscad_on_desktop_annotated.png)

Klicka på ikonen och OpenSCAD startar.

Om det finns ingen OpenSCAD ikon:

- Tryck på Windows tangenten

![Tryck på Windows tangenten](windows_key.jpg)

- Klicka på 'Type to search'

[Klicka på 'Type to search'](ubuntu_search.png)

- Skriv ner `openscad` och klick på OpenSCAD ikonen

![Skriv ner `openscad` och klick på OpenSCAD ikonen](ubuntu_seach_openscad.png)

## 1.3. Att start an ny ritning i OpenSCAD

Om du får den 'Welcome to OpenSCAD' föster,
klicka på 'New':

![Klicka på 'New'](openscad_welcome_screen_click_new.png)

Nu kann du skapa 3D modeller i OpenSCAD:

![Nu kann du skapa 3D modeller i OpenSCAD](openscad_on_ubuntu.png)

## 1.3. Vad är OpenSCAD?

Av kapittel 'Introduction' i boken, läs början och paragraf
'What is OpenSCAD?', på sidorna `xv` (Romerska 15)  och `xvi` (Romerska 16).

Hur uttalar man 'OpenSCAD'?

### 1.3. Svar

På Engelska: 'Open-S-CAD', på svenska: 'åpen-äs-kät'.

## 1.4. Vad är 3D punktar?

Om du har aldrig hör om koordinater,
av kapittel 'Introduction' i boken,
läs hela paragrafen 'A brief introduction to 3D design with OpenSCAD',
på sidorna `xxii` (Romerska 22)  och `xviii` (Romerska 23).

1. Vilken koordinat har ursprunget ('origin')?
1. Hur uttalar man koordinatet av ursprunget ('origin')?
1. Varför har koordinater tre siffror?
1. Vilket koordinat har punkt P?
1. Hur läser man koordinatet P på svenska? Envänder ord som 'åt höger',
  'åt vänster', 'uppåt', neråt', usw.
1. Vilket koordinat är 5 vänster av P?

### 1.4. Svar

1. Koordinatet är `(0,0,0)`
1. Det är uttalat som 'noll komma noll komma noll'
1. För att 3D har tre rikningar: åt höger, åt djupet, och åt uppåt
1. Koordinatet av P är `(3,0,5)`
1. `(3,0,5)` uttalar man på svenska som: '3 åt höger, noll i djupet
  och 5 uppåt'.
1. Koordinatet 5 vänster av P är `(-2,0,5)`

## 1.5. Att rita en kub

Av kapittel 1 '3D drawing with OpenSCAD', läs sidor 1 till 3,
till (och inklusive) 'Drawing Cuboids with `cube`.
Kör koden i OpenSCAD.

1. Hur läser man på svenska `cube([5, 10, 20]);`?
1. Vad betyder den semicolonen (`;`)? Tips: vilken tecken använder människor
  i skift istället?
1. Vad betyder den hakparenteser (`[` och `]`)? Tips: vad heter stället där
  en av hörnar av kuben?
1. Ändra koden till `cube(5);`. Hur uttalar man på svenska vad koden gör?

### 1.5. Svar

1. På svenska läser man `cube([5, 10, 20]);` som: 'Kära dator,
  gjärna rita ut en kub som är 5 bredd, 10 djupt och 20 högt'
1. Den OpenSCAD semicolonen (`;`) är den svenka period (`.`) i skift
1. Hakparenteserna betyder att detta är ett koordinat. En av hörnarna av kuben
  har koordinatet `(5, 10, 20)`
1. På svenska uttalar man `cube(5);` som 'Kara dator, rita ut en kub med
  storlek 5'

```text
TODO: more stuff, ask AtomBjörn first
```
  
## 1.99. Slutuppgift

Rita varje figur på sida 22 'Design time: 3D shapes'
i samma ordning. Visa varje en till en lärare eller visar all 6 samtidigt.

