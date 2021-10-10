# Plan aplikacji - Spatula

## Opis aplikacji

### Szafka

- Użytkownik może wpisać stan swojej szafki kuchennej/lodówki/ogólnie jakie ma składniki w domu
- Ustawianie alertów
  - Data ważności
  - Jakiś składnik się kończy
- Automatyczne generowanie listy zakupów na podstawie ww. alertów oraz manualnych wpisów użytkownika
- Możliwość dodawania innych użytkowników do tej samej szafki
- Możliwość posiadania kilku szafek
- Skaner kodów kreskowych

### Kuchnia

- Możliwość dodawania i wyświetlania przepisów w aplikacji
- Możliwość dodania czasu aktywnego i pasywnego (aktywny: przygotowywanie, gotowanie i smażenie, tego typu rzeczy; pasywny: czekanie na składniki, np. wyrastanie ciasta)
- Możliwość filtrowania na podstawie:
  - składników, które są wpisane w Szafce
  - składników, które Użytkownik podaje
  - tagów, które użytkownik wpisuje
  - częściowo na podstawie składników (np. jeśli jest większość składników, to generuje listę zakupów brakujących składników)
  - czasu przygotowania

#### Część społecznościowa aplikacji

- Możliwość udostępniania przepisów innym użytkownikom aplikacji, bezpośrednio oraz do globalnej listy przepisów
- Możliwość dodawania komentarzy
  - Komentarze są w formie drzew
  - Do komentarzy można dodawać zdjęcia
- Możliwość dodawania ocen
  - Oceny mogą oceniać określone części przepisu, n.p.: jakość przygotowanego dania, jakość samego przepisu
- Możliwość filtrowania "globalnych" przepisów (patrz: filtrowanie w Kuchnii)
- Możliwość sortowania przepisów na podstawie:
  - popularności
  - ocen
- Możliwość tagowania przepisów, m.in. czy jest zdrowe, etc.
- Konto premium dla użytkowników - daje użytkownikom jakieś dodatkowe funkcje, a pieniądze idą na opłacenie Jeffa Bezosa
- Możliwość nagradzania użytkowników za pieniądze (nagrody dają konto premium)
- Forum (dla rzeczy, które nie są przepisami)
- Wyszukiwarka przepisów i osób
- Weryfikacja "sławnych" osób

## Mocne i słabe strony

Mocne:

- Zniwelowanie kryzysu wyboru ("o mój boże nie wiem co zjeść")
- Automatyzacja uzupełnienia zapasów
  - Możliwa integracja z firmami dostarczającymi składniki, n.p.: Auchan, Intermarche, Careffour
- Mniejsze marnotrawstwo jedzenia
- Skrócony czas zakupów dzięki automatycznym listom zakupów
- Szansa poznania nowych przepisów
- Przepisy zweryfikowane przez innych użytkowników
- Możliwość sprawdzenia stanu kuchni bez potrzeby przebywania w niej

Słabe:

- Słaba monetyzacja
- Żmudne dodawanie składników do Szafki
- Utrudnione używanie przez osoby starsze
- Duża zależność na społeczności (kwestia ilości przepisów "globalnych")

## Plany na przyszłość (za żadne skarby nie będziemy robić do tego designu)

Dodatkowy wariant aplikacji dla restauracji: plan na przyszłość z rozszerzoną Szafką i wyciętą częścią społecznościową Kuchni

## Uwagi

- Wpisywanie, ile czego zuzyłeś jest uciązliwe (niedokładne miary, zmudny proces)
- Jakie dodatkowe funkcje dla premium?
- "Nawyki" - dodawanie częstych czynności i automatyczne usuwanie określonej ilości składników
- Automatyczne usuwanie składników na podstawie przepisu
  - Mozna manualnie zmienić co wziąłeś
- Opcję dodawania kalorii (premium?)
- Premium: liczenie kalorii i przypominanie o posiłkach
- Premium: OCR do etykiet
- Porównywarka cen produktów w kilku sklepach
- Dostosowanie ilości składników do wybranej liczby osób
- Integracja z asystentami
- Integracja z lodówką Samsunga
- Aplikacja na smart lodówki
- Nagrody za aktywność
- Premium: integracja z aplikacjami fitnessowymi
- Premium: dostęp do API

## Persony

### Persona 3 - Typowy student

![](./sminem.png)

### Dane

Imię i nazwisko: Stahu Tadeusz Udenciak

Cytat:

> Zapijam oblaną sesję zamiast uczyć się na poprawkową

Wiek: 23

Zarobki: 2200 - z czego 250 zł na pożywienie

Wykształcenie: Studia

Zawód: student

Stanowisko: student filozofii

Lokalizacja: UAM

Introwertyk/Ekstrawertyk: 90% I 10% E

Analityczny/Kreatywny: 80% A 20% K

Konserwatywny/Liberalny: 1% K 99% L

Pasywny/Aktywny: 70% P 30% A

### Historia

| Cele                          | Frustracje                            | Bio                                                                                                                                                                         |
| ----------------------------- | ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| marzy o karierze akademickiej | sesja                                 | chciałby napisać wielkie dzieło filozoficzne które wejdzie do bibliografii jakiegoś kierunku, wtedy zacznie sprzedawać tę książkę za napompowaną cenę żeby orżnąć studentów |
| chce oszczędzić na wszystkim  | wydaje dużo na zupki chińskie i dowóż |                                                                                                                                                                             |

#### Cechy charakterystyczne:

- czyta książki dla fałszywego poczucia pożyteczności
- piwo
- za mało gotuje
- skąpy
- nie oszczędza (bo nie ma z czego)

### Szczegóły

#### Motywacje

Determinacja: 3/10

Obawa: 8/10

Osiąganie: 6/10

Rozwój: 8/10

Decyzyjność: 3/10

Socjalność: 0/10

#### Kanały komunikacji

Tradycyjna reklama/Internet i social media: 0% T 100% I

Polecenie/PR oraz marketing szeptany: 10% P 90% PR

#### Ulubione marki:

- Amarena
- Vifon
- Oyakata
- Harnaś
- Specjal
- Kustosz
- Snajper
- Sztern
- Biedronka
  - Pastani

### Empathy map

- Co myśli i czuje
  - głód bo wydał budżet na piwo bo oblał przedmiot
- Co słyszy
  - że nie jest wystarczający (od rodziców)
- Co widzi
  - przepłaconą kawalerkę
- Co mówi i robi
  - dużo planów, daleko do realizacji
- Bolączki
  - chce zacząć żyć zdrowiej ale nigdy tego nie robi
- Korzyści
  - będzie papier

### Projekt

#### Scenariusz

Najważniejszą funkcją dla Staha jest porównywarka cen, żeby jak najbardziej zaoszczędzić na jedzeniu.
Nie będzie korzystał z funkcji premium, ponieważ nie ma pieniędzy.

| Etapy                 | Potrzeby i aktywności                | Kanały   | Dobre doświadczenia UX                                                          | Złe doświadczenia UX                                           | Usprawnienia                                                       |
| --------------------- | ------------------------------------ | -------- | ------------------------------------------------------------------------------- | -------------------------------------------------------------- | ------------------------------------------------------------------ |
| Login                 | utworzenie konta lub zalogowania się | mobilnie | Rejestracja jest bardzo prosta (tylko nickname, hasło i email)                  | brak możliwości logowania się Google/Facebookiem               | Dodanie OAuth                                                      |
| Szafka                | dodanie przedmiotów do szafki        | mobilnie | Call to action zachęcający do dodania pierwszego produktu                       | żmudny proces dodawania produktów                              | Propozycja dodania produktów, które często są w kuchniach, np. sól |
| Kuchnia               | wyszukanie prostego przepisu         | mobilnie |                                                                                 | Brak preloadowanych przepisów                                  | Sugestia najpopularniejszych przepisów od społeczności             |
| Część społecznościowa | dodanie przepisu do Kuchnii          | mobilnie | Wyraźnie widoczny przycisk dodania przepisu do Kuchnii                          | Jeżeli nie doda przepisu od razu, trudniej do niego się dostać | Dodać historię ostatnio przeglądanych przepisów                    |
| Widok przepisu        | gotowanie danego przepisu            | mobilnie | podany czas pasywny i aktywny; wyróżnienie, które produkty posiada, a które nie |                                                                |                                                                    |
