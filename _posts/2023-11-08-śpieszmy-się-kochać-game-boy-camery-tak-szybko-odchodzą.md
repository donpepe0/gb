---
layout: post
title: Śpieszmy się kochać Game Boy Camery, tak szybko odchodzą
categories:
- Game Boy Camera
tags:
- gameboy
- gameboycamera
img_path: "/202311/"
date: 2023-11-08 16:09 +0100
---
Tytuł to oczywiście parafraza księdza Twardowskiego, ale ma w sobie trochę prawdy, bo oryginalnych kompletnych kartridżów przecież ubywa, są niszczone, wyrzucane, lub rozmontowywane przez brać moderską. A to jest przecież kawałek całkiem fajnego sprzętu, który fan Nintendo powinien mieć w swojej kolekcji.

![Żółty Pocket i Camera](game-boy-camera-02.jpg){: width="421" height="316" }
_Żółty Game Boy Pocket i pasująca Game Boy Camera (wersja japońska)_
 
## Co to jest Game Boy Camera?
 
Game Boy Camera wydany w 1998 roku przez Nintendo, to kolorowy kartridż z aparatem cyfrowym, który można podłączyć do wszystkich Game Boyów (poza Game Boy Micro). W latach 90, kiedy cyfrowe aparaty były dość drogie (i przy tym sporych gabarytów), Game Boy Camera był tani i poręczny. Na premierę kosztował niecałe 50 dolarów. Do jego użytkowania nie trzeba specjalnych umiejętności. Nic więc dziwnego, że zyskał sobie spore grono fanów. Popularny jest nawet dzisiaj, mimo że jego produkcja zakończyła się w 2002 roku.
 
Game Boy Camera, posiada sensor CMOS 128 x 128 pikseli, tworzący zdjęcia o rozmiarze 128 x 112 pikseli w czterech odcieniach szarości. "Główka" kartridża, w której znajduje się sensor i soczewka, obraca się o 180 stopni i pozwala zrobić popularnego "selfiaka". Powstało 5 podstawowych wersji kolorystycznych tego urządzenia: czerwona, żółta, zielona, niebieska, przeźroczysto-purpurowa (wydana tylko w Japonii), oraz jedna wersja specjalna w kolorze złotym, wydana w USA z okazji wypuszczenia Zeldy na N64.

![Game Boy Caamera - moja kolekcja](game-boy-camera-01.jpg){: width="421" height="316" }
_Czerwona to wersja EU, czarna to Camera+, żółta to wersja JAP_

> W 2020 roku, dzięki wyciekowi, światło dzienne ujrzała jeszcze jedna wersja Game Boy Camery, a mianowicie Hello Kitty. Ta wersja różni się dosyć mocno od reszty, między innymi całkiem przebudowanym menu. Oficjalnie nigdy nie została wydana i oznaczona jest jako prototyp.
{: .prompt-info }

## Funkcje
 
Aparat wyposażony jest w szereg funkcji do tworzenia i edycji zdjęć, w tym możliwość przycinania, obracania i dodawania obramowania. Użytkownicy mogą również dodawać tekst i naklejki do swoich zdjęć, lub po nich malować. Zdjęcia można zapisać na kartridżu (maksymalnie 30), wydrukować za pomocą drukarki Game Boy Printer, lub udostępnić swoim znajomym z Game Boyem. Do robienia zdjęć mamy sporo trybów do wyboru: magiczne soczewki z różnymi efektami jak lustrzane odbicie, poziome i pionowe panoramy, fotografia poklatkowa, samowyzwalacz. Oprogramowanie pozwala również na tworzenie animacji, a nawet tworzenie muzyki, dzięki sekwencerowi o nazwie Trippy-H.
 
![Game Boy Camera Mario](gbcamera-01.png){: w="160" h="144" .normal }
![Game Boy Camera Funkcje](gbcamera-02.png){: w="160" h="144" .normal }
![Game Boy Camera Funkcje](gbcamera-03.png){: w="160" h="144" .normal }
![Trippy-H](trippy-h.png){: w="160" h="144" .normal }
 
 
## Społeczność i ich projekty
 
Już od dawna wiadomo, że Game Boy moderami stoi: podświetlane ekrany, współczesne gniazda ładowania, dodatkowe wyjścia audio. Nie inaczej jest w przypadku Game Boy Camery. To jest coś, co twórcom tego sprzęciku się chyba raczej nie śniło. Mianowicie społeczność założona dookoła tego małego aparatu jest niesamowita! Ilość projektów, która powstała i powstaje jest całkiem spora. Pokrótce postaram się opisać kilka z nich, a w kolejnych postach mam zamiar przyjrzeć się poszczególnym pomysłom szerzej.
 
### Game Boy Printer Emulator
 
Metod zrzucania zdjęć z Game Boy Camera na współczesny sprzęt jest kilka. Arduino Game Boy Printer Emulator to jeden z najtańszych i najprostszych sposobów. Do jego wykonania potrzebne jest Arduino Nano, lub jego klon, Link Cable do Game Boya (może być zamiennik z aliexpress) oraz odrobina lutowania. Na płytkę Arduino wgrywane jest oprogramowanie, które udaje gameboyową drukarę i przekazuje zdjęcie z konsoli do PC. Projekt jest open source.

![Game Boy Printer Emulator](game-boy-printer-emulator.jpg){: width="421" height="316" }
_Game Boy Printer Emulator zamknięty w pudełku po tabletkach_
 
[Arduino Game Boy Printer Emulator ](https://github.com/mofosyne/arduino-gameboy-printer-emulator)
 
### Game Boy Camera Gallery
 
Świetny kawałek oprogramowania, dobrze współpracujący z wymienionym powyżej emulatorem drukarki. Możemy w nim zaimportować nasze zdjęcia, tworzyć galerię, tagować, zmieniać paletę kolorów czy dodawać obramowania. Dodane zdjęcia można później eksportować w wybranej skali i formacie graficznym. Działa również z plikami *.sav. Dane przechowywane są po stronie przeglądarki i nie są wysyłane w świat. Projekt open source.
 
[Game Boy Camera Gallery](https://herrzatacke.github.io/gb-printer-web/)
 
### 2BitToy Camera +
 
Jak wspomniałem wcześniej, Game Boy Camera nie grzeszy rozdzielczością, wynosi ona 0.014 megapixela. Nic więc dziwnego że współcześni fani chcą z niego wycisnąć jak najwięcej, tworząc różnego rodzaju adaptery do komercyjnych soczewek [np. do Canona](https://youtu.be/Bpizq3mVY20?si=zczUunFWzf1BBQZ0). 2BitToy podszedł do tematu trochę inaczej, bo stworzył kompletnie nową obudowę kartridża, zawierającą gniazdo na soczewkę CS. Przełożenie bebechów z oryginalnego kartridża jest proste i nie wymaga dodatkowych części. Projekt nie jest open source, a pliki STL kosztują 10 funtów, ale zdecydowanie warto. Pasujące soczewki, można dokupić np. na aliexpress. A obudowę wydrukować na [JLCPCB.com](https://JLCPCB.com)

![Game Boy Camera+](game-boy-camera-plus-01.jpg){: width="421" height="316" }
_Game Boy Camera+ z zdemontowaną soczewką_
![Game Boy Camera+ z boku](game-boy-camera-plus-02.jpg){: width="421" height="316" }
_Game Boy Camera+ z boku_
 
[2BitToy Camera +](https://2bittoy.carrd.co/)
 
### Photo!
 
Photo! To tzw. oprogramowanie homebrew czyli nieoficjalne oprogramowanie wydane na zamknięty system. Na stronie projektu przeczytać możemy "To projekt homebew zwiększający możliwości Game Boy Camery poprzez umożliwienie dostępu do wszystkich możliwych parametrów sensora oraz poprawę szybkości drukowania i ogólnej ergonomii aparatu". Photo! do pracy wymaga flashowalnego kartridża Game Boy Camery, który należy samemu zbudować, poświęcając przy tym części z oryginalnego kartridża - jest to projekt zaawansowany, wymagający lutowania mikroukładów [(patrz tutaj)](https://github.com/HDR/Gameboy-Camera-Flashcart/). Photo! współpracuje z emulatorami Game Boy np. PizzaBoy na Android, gdzie możemy przetestować jego możliwości, używając do tego wbudowanej kamery telefonu.

![Photo! Ekran początkowy](photo-01.png){: w="160" h="144" .normal }
![Photo! Tryb fotografowania](photo-02.png){: w="160" h="144" .normal }
![Photo! Galeria](photo-03.png){: w="160" h="144" .normal }
 
[Photo!](https://github.com/untoxa/gb-photo)
 
## Konkluzja
 
Game Boy Camera przypomina o czasach, gdy fotografia cyfrowa była na wczesnym etapie rozwoju. Jest to ograniczone urządzenie, ale dzięki temu, także potężne narzędzie twórcze. Aparat zainspirował pokolenie artystów cyfrowych i nadal jest źródłem kreatywności. Wciąż istnieje aktywna społeczność, która używa Game Boy Camery do robienia i udostępniania zdjęć. Sam do nich należę. Ty również możesz dołączyć do tego klubu, zobacz Game Boy Camera Club na [discordzie](https://discord.com/invite/C7WFJHG). 

Jeśli chodzi zakupy, to ceny samych kartridży wahają się 150-200 zł w zależności czy wersja japońska czy angielska. W pudełku to kwota ~250 zł. Jeżeli interesuje cię wersja limitowana Zeldy, to trzeba dać około 800 dolarów: [ebay](https://www.ebay.com/itm/225832619558?hash=item3494ac4e26:g:fyoAAOSw7R1lNsno&amdata=enc%3AAQAIAAAA4MTM6XGFBORBGnHF1cYM0%2BTy4B%2Big08n3%2BY1c3gj5V3G2vz423RBM%2BPw2CKrKOtvXd6%2B%2BFYqhXcTRvJe%2FMBCFTB8LTl4jpWWpUg65laszjHnaJYrUkU4GGYui5ZtfSZUE1mov73xkMpW9bn8mVJF6M9gpioqEkwNlwIew4xaAYoJs4NwYloXQRKh%2B0mlX%2FwuJnWoT3%2FYrfHYS3G%2F2pJaFLjNvtmxNCG7DBiG4cuMZkyoOIc6WdZ9vUPzOT1zCsS8FOEP1womWc78hYlbxQos%2B2nzLpiwpzRuDXYZ4Zye8ufq%7Ctkp%3ABk9SR5C5z4TvYg)


Źródła:
- [Artykuł na Wikipedii](https://en.wikipedia.org/wiki/Game_Boy_Camera)
- [Shooting the Nintendo Game Boy Camera 24 Years Later by Casual Photophile](https://casualphotophile.com/2021/12/19/game-boy-camera-review/)
- [Hello Kitty Pocket Camera na tcrf.net](https://tcrf.net/Hello_Kitty_Pocket_Camera)
- [Game boy Camera Club na Discordzie](https://discord.com/invite/C7WFJHG) 


![Hello Kitty](hellokitty-02.png){: w="160" h="144" .normal }
![Hello Kitty Error Page](hellokitty-01.png){: w="160" h="144" .normal }
![Game Boy Camera Funkcje](gbcamera-04.png){: w="160" h="144" .normal }
![Game Boy Camera Funkcje](gbcamera-05.png){: w="160" h="144" .normal }
![Game Boy Camera Funkcje](gbcamera-06.png){: w="160" h="144" .normal }
![Game Boy Camera Funkcje](gbcamera-07.png){: w="160" h="144" .normal }
![Game Boy Camera Funkcje](gbcamera-08.png){: w="160" h="144" .normal }
![Game Boy Camera Funkcje](gbcamera-09.png){: w="160" h="144" .normal }
![Game Boy Camera Funkcje](gbcamera-10.png){: w="160" h="144" .normal }
![Game Boy Camera Funkcje](gbcamera-11.png){: w="160" h="144" .normal }