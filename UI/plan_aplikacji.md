# Plan aplikacji - Spatula

~~za żadne skarby nie w PHP~~

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